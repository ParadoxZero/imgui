cmake_minimum_required (VERSION 3.8)

set(SOURCE_FILES
    imgui.cpp
    imgui_widgets.cpp
    imgui_draw.cpp
    imgui_tables.cpp
)

add_library(imgui STATIC ${SOURCE_FILES})
