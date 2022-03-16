cmake_minimum_required(VERSION 3.20)
project(imguizmo CXX C)

include_directories(${CMAKE_CURRENT_SOURCE_DIR}/include)

set(CMAKE_LIBRARY_OUTPUT_DIRECTORY  "${CMAKE_BINARY_DIR}/lib")

add_library(imguizmo STATIC
        ImGuizmo.h
        ImGuizmo.cpp
        ImGradient.h
        ImGradient.cpp
        ImSequencer.h
        ImSequencer.cpp
        ImZoomSlider.h
        ImCurveEdit.h
        ImCurveEdit.cpp
        GraphEditor.h
        GraphEditor.cpp
        )