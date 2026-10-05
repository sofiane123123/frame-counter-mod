cmake_minimum_required(VERSION 3.24)
project(frame-counter-mod)
find_package(Geode REQUIRED)
add_geode_mod(
    sofianegg.frame_counter
    main.cpp
)
