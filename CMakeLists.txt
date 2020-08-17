cmake_minimum_required(VERSION 2.8.9)
project(myworld)
add_executable(myworld helloworld.cpp)
install(TARGETS myworld DESTINATION bin)
