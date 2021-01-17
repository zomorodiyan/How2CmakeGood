cmake_minimum_required(VERSION "3.16.3")

project(MyProject VERSION 1.0.0)

add_subdirectory(say-hello) #library
add_subdirectory(hello-exe) #executable (library must be before executable)

#install(TARGETS "$(PROJECT_NAME)" DESTINATION bin)  #$(CMAKE_INSTALL_PREFIX)/bin
#install(FILES "Main.cpp" DESTINATION src)           #$(CMAKE_INSTALL_PREFIX)/src
 
