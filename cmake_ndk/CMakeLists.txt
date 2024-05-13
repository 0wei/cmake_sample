cmake_minimum_required(VERSION 3.0)

project(hello)

add_executable(${PROJECT_NAME} ./main.c)

# install(TARGETS ${PROJECT_NAME} RUNTIME DESTINATION ${PROJECT_SOURCE_DIR})