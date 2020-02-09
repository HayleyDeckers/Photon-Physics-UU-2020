cmake_minimum_required(VERSION 3.14)
project(handins)

include(UseLATEX.cmake)
SET(LATEX_OUTPUT_PATH build)
ADD_LATEX_DOCUMENT(
    week_01.tex
    #IMAGE_DIRS homework/images
    #BIBFILES main.bib
    #USE_INDEX
    )
