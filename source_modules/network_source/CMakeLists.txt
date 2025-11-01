cmake_minimum_required(VERSION 3.10)
project(network_source)

file(GLOB SRC "src/*.cpp")

include(${SDRPP_MODULE_CMAKE})