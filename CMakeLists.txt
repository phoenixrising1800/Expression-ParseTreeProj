cmake_minimum_required(VERSION 3.21)
project(expr-parse-trees C) 

find_package(igraph REQUIRED) 

add_executable(main main.c) 
target_link_libraries(main PUBLIC igraph::igraph)
