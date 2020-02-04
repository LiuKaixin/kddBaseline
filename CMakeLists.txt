cmake_minimum_required(VERSION 2.8)

# 项目信息
project(anchoredKcore)

# 指定生成目标
add_executable(kcore anchoredKcore.cpp)
set(EXECUTABLE_OUTPUT_PATH ${PROJECT_SOURCE_DIR})
set(CMAKE_CXX_FLAGS "-O3")