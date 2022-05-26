cmake_minimum_required(VERSION 3.21)
project(MVS_HugeNumberCalculator C)

set(CMAKE_C_STANDARD 99)

add_executable(MVS_HugeNumberCalculator main.c ScanHugeNumber.c ScanHugeNumber.h ShowHugeNumber.c ShowHugeNumber.h)
add_executable(MVS_HugeNumberCalculator main.c HugeFloatOperator.c HugeFloatOperator.h HugeIntOperator.c HugeIntOperator.h HugeUnsignedIntOperator.c HugeUnsignedIntOperator.h)
add_executable(MVS_HugeNumberCalculator main.c HugeFloat.c HugeFloat.h HugeInt.c HugeInt.h HugeUnsignedInt.c HugeUnsignedInt.h)
