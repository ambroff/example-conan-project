cmake_minimum_version(3.5)

project(testproj)

# If conan is being used, configure CMake to use conan for dependencies.
include(${CMAKE_BINARY_DIR}/conan-paths.cmake OPTIONAL)

add_subdirectory(src)
