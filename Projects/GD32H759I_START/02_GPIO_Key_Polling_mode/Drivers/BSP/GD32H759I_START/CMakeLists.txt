project(GD32H759I_START LANGUAGES C CXX ASM)

add_library(GD32H759I_START OBJECT
    ${DRIVERS_DIR}/BSP/GD32H759I_START/gd32h759i_start.c
    ${DRIVERS_DIR}/BSP/GD32H759I_START/LCD_Common/lcd_font.c
    )

target_include_directories(GD32H759I_START PUBLIC
    ${DRIVERS_DIR}/BSP/GD32H759I_START
    )

target_link_libraries(GD32H759I_START PUBLIC GD32H73x_75x_standard_peripheral)
