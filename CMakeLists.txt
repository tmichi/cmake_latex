cmake_minimum_required(VERSION 3.2)
set(CMAKE_VERBOSE_MAKEFILE 1)
project(exmaple NONE)
include (miLATEX.cmake)

set(MI_LATEX_COMMAND  "pdflatex")
set(MI_BIBTEX_COMMAND "bibtex")
add_subdirectory(sample1)
add_subdirectory(sample2)
