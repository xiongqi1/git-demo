cmake_minimum_required(VERSION 2.6)
project(xq123)

add_executable(xq123 xq123.c)

INSTALL(TARGETS xq123 RUNTIME DESTINATION /usr/bin/)
