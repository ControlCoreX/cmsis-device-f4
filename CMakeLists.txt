# Date  : 2024-12-03
# Author: tuwenbo

include($ENV{PW_ROOT}/pw_build/pigweed.cmake)

pw_add_library(cmsis_device_f4 STATIC
    PUBLIC_INCLUDES
        Include
    SOURCES
        Source/Templates/system_stm32f4xx.c
)
