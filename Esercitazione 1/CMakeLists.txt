cmake_minimum_required(VERSION 3.20)
project(lez22ottobre C)

set(CMAKE_C_STANDARD 99)

add_executable(lez22ottobre main.c
        esercizio_1.c esercizio_1.h
        esercizio_2.c esercizio_2.h esercizio_2_alt.c
        esercizio_3.c esercizio_3.h
        esercizio_4.h esercizio_4.c )
