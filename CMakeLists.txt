cmake_minimum_required(VERSION 3.10)

project(LintToAnnotate)

find_package(fmt CONFIG REQUIRED)

add_executable(LintToAnnotate LintToAnnotate.cpp)

target_link_libraries(LintToAnnotate PRIVATE fmt::fmt)