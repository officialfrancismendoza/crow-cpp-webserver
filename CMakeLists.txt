cmake_minimum_required(VERSION 3.15)
project(crowsample)

set(INCLUDE_PATHS boost_1_84_0 crow/include)
# set(CMAKE_PREFIX_PATH "C:/Users/franc/OneDrive/Documents/vcpkg/installed/x64-windows/share")

add_executable(crowsample crowServer.cpp)

target_include_directories(crowsample PUBLIC ${INCLUDE_PATHS})