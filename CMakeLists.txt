# cmake_minimum_required(VERSION <specify CMake version here>)
project(cpp_pr1)

set(CMAKE_CXX_STANDARD 14)

include_directories(.)

add_executable(cpp_pr1
        .idea/cpp_pr1.iml
        .idea/encodings.xml
        .idea/misc.xml
        .idea/modules.xml
        .idea/untitled.iml
        .idea/vcs.xml
        .idea/workspace.xml
        CMakeLists.txt
        main.cpp)
