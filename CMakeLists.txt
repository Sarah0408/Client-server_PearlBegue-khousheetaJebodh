cmake_minimum_required(VERSION 3.10.2)

# set the project name
project(client)

include_directories(include)


set(SOURCES src/server.c
			)
add_executable(server
			   ${SOURCES})


set(SOURCES src/client.c
			)
add_executable(client
			   ${SOURCES})


