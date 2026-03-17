cmake_minimum_required(VERSION 3.16)

project(TD1 LANGUAGES C)

add_executable(TD1 main.c)

include(GNUInstallDirs)
install(TARGETS TD1
    LIBRARY DESTINATION ${CMAKE_INSTALL_LIBDIR}
    RUNTIME DESTINATION ${CMAKE_INSTALL_BINDIR}
)
