
cmake_minimum_required(VERSION 2.8.11)
project(test-collatz-conjecture-with-yarp-gabrielenava)

set(CMAKE_MODULE_PATH ${CMAKE_MODULE_PATH} ${CMAKE_CURRENT_SOURCE_DIR}/cmake)

set(test-collatz-conjecture-with-yarp-gabrielenava_SHARE_DIR "${CMAKE_INSTALL_PREFIX}/share/test-collatz-conjecture-with-yarp-gabrielenava")

install(CODE "MESSAGE(\"This repository simply acts as a container\")")
