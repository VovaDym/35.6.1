# CMakeList.txt : CMake project for 35.6.1, include source and define
# project specific logic here.
#
cmake_minimum_required (VERSION 3.8)

project ("35.6.1")

# Add source to this project's executable.
add_executable (35.6.1 "35.6.1.cpp" )

if (CMAKE_VERSION VERSION_GREATER 3.12)
  set_property(TARGET 35.6.1 PROPERTY CXX_STANDARD 20)
endif()

# TODO: Add tests and install targets if needed.
