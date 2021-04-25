add_subdirectory(common)
add_subdirectory(server)
add_subdirectory(service)


add_executable(demo_http_server Main.cpp)

target_include_directories(demo_http_server PUBLIC
        ${EXTRA_INCLUDES}
        )

target_link_libraries(demo_http_server PUBLIC ${EXTRA_LIBS})