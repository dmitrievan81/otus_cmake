cmake_minimum_required(VERSION 3.5)

project(01.fish)

add_executable(fish 
    main.cpp
)

set_target_properties(fish PROPERTIES
    CXX_STANDARD 17
    CXX_STANDARD_REQUIRED ON
)