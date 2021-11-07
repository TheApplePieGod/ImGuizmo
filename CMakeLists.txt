cmake_minimum_required(VERSION 3.14)

project(ImGuizmo)

include_directories(".")

add_library(imguizmo STATIC 
    "GraphEditor.cpp"
    "GraphEditor.h"
    "ImCurveEdit.cpp"
    "ImCurveEdit.h"
    "ImGradient.cpp"
    "ImGradient.h"
    "ImGuizmo.cpp"
    "ImGuizmo.h"
    "ImSequencer.cpp"
    "ImSequencer.h"
    "ImZoomSlider.h"
)