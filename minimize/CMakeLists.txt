add_executable (minimize "minimize.cpp" "minimize.h")

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET minimize PROPERTY CXX_STANDARD 20)
endif()
