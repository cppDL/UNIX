project(pid)

find_package(json-c CONFIG)

add_executable(${PROJECT_NAME} main.c)

target_link_libraries(${PROJECT_NAME} PRIVATE json-c::json-c)
