project(GD32H73x_75x_standard_peripheral LANGUAGES C CXX ASM)

# Comment-out unused source files.
add_library(GD32H73x_75x_standard_peripheral OBJECT
	${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_adc.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_can.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_cau.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_cau_aes.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_cau_des.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_cau_tdes.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_cmp.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_cpdm.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_crc.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_ctc.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_dac.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_dbg.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_dci.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_dma.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_edout.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_efuse.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_enet.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_exmc.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_exti.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_fac.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_fmc.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_fwdgt.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_gpio.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_hau.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_hau_sha_md5.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_hpdf.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_hwsem.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_i2c.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_ipa.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_lpdts.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_mdio.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_mdma.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_misc.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_ospi.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_ospim.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_pmu.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_rameccmu.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_rcu.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_rspdif.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_rtc.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_rtdec.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_sai.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_sdio.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_spi.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_syscfg.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_timer.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_tli.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_tmu.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_trigsel.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_trng.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_usart.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_vref.c
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Source/gd32h73x_75x_wwdgt.c
    )

target_include_directories(GD32H73x_75x_standard_peripheral PUBLIC
    ${DRIVERS_DIR}/GD32H73x_75x_standard_peripheral/Include
    )

# CMSIS header only library is linked.
target_link_libraries(GD32H73x_75x_standard_peripheral PUBLIC CMSIS)
