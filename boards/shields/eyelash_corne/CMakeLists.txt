# Eyelash Corne Shield CMakeLists
if(CONFIG_ZMK_DISPLAY AND CONFIG_ZMK_DISPLAY_STATUS_SCREEN_CUSTOM)
    zephyr_library()
    zephyr_library_sources(${ZEPHYR_BASE}/misc/empty_file.c)
endif()
