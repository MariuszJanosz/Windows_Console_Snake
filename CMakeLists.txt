cmake_minimum_required(VERSION 3.30)

project(Windows_Console_Snake)

add_executable(snake main.c)

set_directory_properties(PROPERTIES VS_STARTUP_PROJECT snake)
