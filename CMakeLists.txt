include(../tp_stub/krkrz.cmake)

krkrz_plugin(resourceRW
    SOURCES
        Main.cpp
        ${CMAKE_CURRENT_SOURCE_DIR}/../simplebinder/v2link.cpp
    INCLUDES
        ${CMAKE_CURRENT_SOURCE_DIR}/../simplebinder
)
