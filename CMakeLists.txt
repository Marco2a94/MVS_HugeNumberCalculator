cmake_minimum_required(VERSION 3.21)
project(MVS_HugeNumberCalculator C)

set(CMAKE_C_STANDARD 99)

add_executable(MVS_HugeNumberCalculator main.c HugeFloatOperator.c HugeFloatOperator.h HugeIntOperator.c HugeIntOperator.h HugeUnsignedIntOperator.c HugeUnsignedIntOperator.h)
