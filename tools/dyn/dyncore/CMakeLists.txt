set(LLVM_LINK_COMPONENTS
  )

set(SOURCES
  dyncore.cpp
  )

add_llvm_library(LLVMDYNCore ${SOURCES})
add_dependencies(LLVMDYNCore intrinsics_gen)
