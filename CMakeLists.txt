# Date  : 2024-12-03
# Author: tuwenbo

target_include_directories(${EXECUTABLE_NAME} PRIVATE
  "${CMAKE_CURRENT_LIST_DIR}/Include"
)

target_sources(${EXECUTABLE_NAME} PRIVATE
  "${CMAKE_CURRENT_LIST_DIR}/Source/Templates/system_stm32f4xx.c"
)
