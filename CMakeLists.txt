cmake_minimum_required(VERSION 2.8.11)

if(COMMAND CMAKE_POLICY)
    CMAKE_POLICY(SET CMP0003 NEW)
endif()

project(dcm2niix)

set(CMAKE_BUILD_TYPE,"Release")

include(${CMAKE_SOURCE_DIR}/SuperBuild/SuperBuild.cmake)
