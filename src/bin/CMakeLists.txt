option(build_sandbox "Build sandbox prototyping code" OFF)

if(build_sandbox)
  add_subdirectory(sandbox)
endif()
