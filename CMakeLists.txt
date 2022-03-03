cmake_minimum_required(VERSION 3.17)
project(SampleLayer)

set(CMAKE_CXX_STANDARD 20)

add_library(SampleLayer SHARED sample_layer.cpp vk_layer.h vk_platform.h vulkan.h)

