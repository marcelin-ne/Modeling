cmake_minimum_required(VERSION 3.0.0)
project(C3_Exercise_16_Load3DModel_Task1 VERSION 0.1.0)

include(CTest)
enable_testing()

add_library(C3_Exercise_16_Load3DModel_Task1 C3_Exercise_16_Load3DModel_Task1.cpp)

set(CPACK_PROJECT_NAME ${PROJECT_NAME})
set(CPACK_PROJECT_VERSION ${PROJECT_VERSION})
include(CPack)
