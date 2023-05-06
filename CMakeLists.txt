cmake_minimum_required(VERSION 3.24)
project(laba4)

set(CMAKE_C_STANDARD 99)

add_executable(laba4 4laba/main.c 4laba/lyb/check.c 4laba/lyb/memory.c 4laba/lyb/menu.c 4laba/lyb/chrono.c 4laba/lyb/query.c 4laba/tree.c)
