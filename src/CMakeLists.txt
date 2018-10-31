find_package(fmt CONFIG REQUIRED)

add_executable(testproj main.cpp)

target_link_libraries(testproj
  fmt::fmt
  )
