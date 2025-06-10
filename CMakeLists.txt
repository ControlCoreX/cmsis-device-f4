# Date  : 2024-12-03
# Author: tuwenbo

pw_add_library_generic(cmsis_device_f4 STATIC
    PUBLIC_INCLUDES
        Include
    PUBLIC_DEPS
        cmsis_6
        cmsis_compiler
        ${target_device}.cmsis_device
    SOURCES
        Source/Templates/system_stm32f4xx.c
)
