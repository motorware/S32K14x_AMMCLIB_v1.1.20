The SWLIBS_DEFAULT_IMPLEMENTATION macro should be defined in the SWLIBS_Config.h file located in $project_name/include directory.
Please add to main.c file:
#include "SWLIBS_Config.h" 
The following options were set for the project:
S32 Design Studio for Arm based MCUs 6.3.1
    -mfloat-abi=hard -mfpu=fpv4-sp-d16 \
    -std=c99 \
    -mthumb \
    -O3 \

Green Hills MULTI v2017.1.4
    -fpu=vfpv4_d16 \
    -fsingle \
    -O3 -Otime \
    -ansi \
    -preprocess_assembly_files \
    --no_exceptions \
    -Wundef \
    -Wimplicit-int \
    -Wshadow \
    -Wtrigraphs \
    --no_commons \
    --gnu_asm

IAR ANSI C/C++ Compiler for ARM V8.11.2.13589
    --fpu=VFPv4_sp \
    -Ohs --use_c++_inline \

