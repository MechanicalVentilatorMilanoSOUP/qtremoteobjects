# Generated from client.pro.

#####################################################################
## restart_client Binary:
#####################################################################

qt_add_executable(restart_client
    OUTPUT_DIRECTORY "${CMAKE_CURRENT_BINARY_DIR}/"
    SOURCES
        main.cpp
    INCLUDE_DIRECTORIES
        ${CMAKE_CURRENT_SOURCE_DIR}
    PUBLIC_LIBRARIES
        Qt::RemoteObjects
        Qt::Test
)
qt6_add_repc_replica(restart_client
    ../subclass.rep
)

#### Keys ignored in scope 1:.:.:client.pro:<TRUE>:
# TEMPLATE = "app"
