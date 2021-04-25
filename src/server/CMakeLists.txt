add_library(demo_server Server.cpp)


#set (POCO_INCLUDE_DIR "${PROJECT_SOURCE_DIR}/contrib/poco/Foundation/include")
#message(${POCO_INCLUDE_DIR})


target_link_libraries(demo_server Poco::Net)

target_include_directories(demo_server PUBLIC .)

message(${CMAKE_CURRENT_SOURCE_DIR})
#target_include_directories(demo_server SYSTEM BEFORE PUBLIC ${POCO_INCLUDE_DIR})