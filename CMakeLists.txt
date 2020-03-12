cmake_minimum_required(VERSION 2.8.6)

project(citest C)

include(CTest)

add_executable(citest citest.c)

if(BUILD_TESTING)
  enable_testing()
  add_test(citest citest)
endif()
