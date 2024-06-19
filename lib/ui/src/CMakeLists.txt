SET(SOURCES screens/ui_Main.c
    screens/ui_LEDs.c
    screens/ui_Cast.c
    ui.c
    components/ui_comp_hook.c
    ui_helpers.c
    ui_events.cpp
    images/ui_img_hstlogo_png.c)

add_library(ui ${SOURCES})
