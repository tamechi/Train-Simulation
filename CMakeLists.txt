cmake_minimum_required(VERSION 3.2)
project(marta-sim)

set(CMAKE_CXX_STANDARD 11)

add_executable(marta-sim main.cpp Event.h SimulatorDriver.h MakeEvent.h Objects.cpp Objects.h)