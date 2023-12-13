project(shm)

add_executable(${PROJECT_NAME} main2.c)

target_link_libraries(${PROJECT_NAME} rt)
