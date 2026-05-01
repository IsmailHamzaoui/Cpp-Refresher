cmake_minimum_required(VERSION 3.20)

project(01_CPP_REFRESHER LANGUAGES C CXX)

add_executable(01_CPP_REFRESHER 
    main.cpp)

target_compile_features(01_CPP_REFRESHER PRIVATE cxx_std_23)