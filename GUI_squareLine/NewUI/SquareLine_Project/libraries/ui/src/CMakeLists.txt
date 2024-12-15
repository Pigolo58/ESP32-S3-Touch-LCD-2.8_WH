SET(SOURCES screens/ui_MainPage.c
    screens/ui_WorckingPage1.c
    ui.c
    components/ui_comp_hook.c
    ui_helpers.c
    ui_events.c
    images/ui_img_image_wifi_notconnect_png_png.c
    images/ui_img_image_warning_icon_png_png.c
    images/ui_img_image_mqtt_connect_png.c
    images/ui_img_image_mqtt_notconnect_png_png.c
    images/ui_img_image_wifi_isconect_png_png.c
    images/ui_img_image_admin_png.c
    images/ui_img_image_logo_wipay_png.c
    images/ui_img_image_baht_png_png.c
    images/ui_img_image_thai_qr_payment_png.c
    images/ui_img_image_imageworning_1_png.c
    images/ui_img_image_imageworning_1_copy_png.c
    images/ui_img_image_rectangle_png.c
    images/ui_img_image_tank__png.c
    fonts/ui_font_Font1.c
    fonts/ui_font_Font20.c
    fonts/ui_font_Font30.c
    fonts/ui_font_Font30item.c
    fonts/ui_font_Font36item.c
    fonts/ui_font_Font40item.c
    fonts/ui_font_Font50.c
    fonts/ui_font_Font60.c
    fonts/ui_font_Font60b.c
    fonts/ui_font_Thaifont50.c
    fonts/ui_font_ThaifontNoto20.c)

add_library(ui ${SOURCES})
