# Generated from differentSlotParamType.pro.

#####################################################################
## differentSlotParamType Binary:
#####################################################################

qt_add_executable(differentSlotParamType
    OUTPUT_DIRECTORY "${CMAKE_CURRENT_BINARY_DIR}/"
    SOURCES
        ../mismatch.cpp
    INCLUDE_DIRECTORIES
        ..
    PUBLIC_LIBRARIES
        Qt::RemoteObjects
        Qt::Test
)
qt6_add_repc_replica(differentSlotParamType
    mismatch.rep
)
