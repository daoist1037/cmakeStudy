set(CMAKE_EXPORT_COMPILE_COMMANDS ON)
cmake_minimum_required(VERSION 3.4.1)

project(demo)


file(GLOB SRC_LIST "*.cpp" "source/*.cpp")

include_directories(
    include/
    )

add_executable(demo.out ${SRC_LIST})
# set(CMAKE_EXPORT_COMPILE_COMMANDS ON)
# cmake -DCMAKE_EXPORT_COMPILE_COMMANDS=1 ..
