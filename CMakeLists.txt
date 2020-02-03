cmake_minimum_required(VERSION 3.10)

# set project name
project(discordpp)

set(EXEC discordpp)

include_directories(includes)

file(GLOB SOURCES src/*.cpp)

# add executable
add_executable(${EXEC} ${SOURCES})