# This file was automatically generated for projects
# without default 'CMakeLists.txt' file.

# FILE(GLOB_RECURSE app_sources ${CMAKE_SOURCE_DIR}/src/*.*)

# idf_component_register(SRCS ${app_sources})

idf_component_register(SRCS 
    "main.c"
    "data_timer.c"
    "imu_read.c"
    "imu_setup.c"
    "imu_spi.c"
    "uart.c"
)
