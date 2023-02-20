cmake_minimum_required(VERSION 3.10)

project(termx)

set(CMAKE_CXX_STANDARD 17)

find_package(ftxui REQUIRED)

add_executable(termx main.cpp)
target_link_libraries(termx ftxui::screen ftxui::dom)
