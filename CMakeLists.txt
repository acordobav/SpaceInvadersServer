cmake_minimum_required(VERSION 3.9)
project(SpaceInvadersServer C)

set(CMAKE_C_STANDARD 99)

add_executable(SpaceInvadersServer Server.c Socket.h Socket_Servidor.h)