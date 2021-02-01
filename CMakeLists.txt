cmake_minimum_required(VERSION "3.19.4")

project("HelloWorld")

add_executable("${PROJECT_NAME}" "Main.cpp")


install(TARGET "${PROJECT_NAME}" DESTINATION bin)
install (FILES "Main.cpp" DESTINATION src)