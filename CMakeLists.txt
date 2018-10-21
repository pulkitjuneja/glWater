cmake_minimum_required(VERSION 3.10)
set(CMAKE_CXX_STANDARD 11)
project(glWater)

add_subdirectory(ext/GlCore)

add_executable(
  glWater
  src/main.cpp
)

target_link_libraries(
  glWater
  GlCore
)
