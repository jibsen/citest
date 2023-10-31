cmake_minimum_required(VERSION 3.16)

project(citest C)

include(CTest)

add_executable(citest citest.c)

if(BUILD_TESTING)
  enable_testing()
  add_test(citest citest)
endif()
