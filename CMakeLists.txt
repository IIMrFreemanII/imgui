cmake_minimum_required(VERSION 3.17)
project(ImGui)

set(CMAKE_CXX_STANDARD 20)

set(SOURCE_FILES
        imconfig.h
        imgui.cpp
        imgui.h
        imgui_demo.cpp
        imgui_draw.cpp
        imgui_internal.h
        imgui_tables.cpp
        imgui_widgets.cpp
        imstb_rectpack.h
        imstb_textedit.h
        imstb_truetype.h
        )

add_library(${PROJECT_NAME} STATIC ${SOURCE_FILES})