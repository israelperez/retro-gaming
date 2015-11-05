# Retropie/EmulationStation Overlays
This setup is for a screen size of 1920 x 1080. To add these overlays to your retropie/emulationstation you will need to 

 1. create a folder called **1080p** in the folder **/opt/retropie/emulators/retroarch/overlays/**
 2. copy all the overlay pngs and their cfg files to this new folder
 3. locate the retroarch.cfg for each of the systems and add the following lines to the top

##Gameboy
/opt/retropie/configs/gb/retroarch.cfg

    video_fullscreen_x = 1920
    video_fullscreen_y = 1080
    custom_viewport_width = 640
    custom_viewport_height = 576
    custom_viewport_x = 640
    custom_viewport_y = 257
    aspect_ratio_index = 22
    input_overlay = /opt/retropie/emulators/retroarch/overlays/1080p/Gameboy_1080p.cfg
    input_overlay_enable = true
    input_overlay_opacity = 1.000000
    input_overlay_scale = 1.000000

##Gameboy Color
/opt/retropie/configs/gbc/retroarch.cfg

    video_fullscreen_x = 1920
    video_fullscreen_y = 1080
    custom_viewport_width = 640
    custom_viewport_height = 576
    custom_viewport_x = 640
    custom_viewport_y = 191
    aspect_ratio_index = 22
    input_overlay = /opt/retropie/emulators/retroarch/overlays/1080p/GameboyColor_1080p.cfg
    input_overlay_enable = "true"
    input_overlay_opacity = 1.000000
    input_overlay_scale = 1.000000

##Gameboy Advanced
/opt/retropie/configs/gbc/retroarch.cfg

    video_smooth = false
    video_fullscreen_x = 1920
    video_fullscreen_y = 1080
    custom_viewport_width = 960
    custom_viewport_height = 640
    custom_viewport_x = 480
    custom_viewport_y = 220
    aspect_ratio_index = 22
    input_overlay = /opt/retropie/emulators/retroarch/overlays/1080p/GameboyAdvance_1080p.cfg
    input_overlay_enable = true
    input_overlay_opacity = 1.000000
    input_overlay_scale = 1.000000

##GameGear
/opt/retropie/configs/gamegear/retroarch.cfg

    video_smooth = false
    video_fullscreen_x = 1920
    video_fullscreen_y = 1080
    custom_viewport_width = 640
    custom_viewport_height = 576
    custom_viewport_x = 639
    custom_viewport_y = 253
    aspect_ratio_index = 22
    input_overlay = /opt/retropie/emulators/retroarch/overlays/1080p/GameGear_1080p.cfg
    input_overlay_enable = true
    input_overlay_opacity = 1.000000
    input_overlay_scale = 1.000000

##NeoGeo Pocket
/opt/retropie/configs/ngp/retroarch.cfg

    video_fullscreen_x = 1920
    video_fullscreen_y = 1080
    custom_viewport_width = 800
    custom_viewport_height = 760
    custom_viewport_x = 563
    custom_viewport_y = 161
    aspect_ratio_index = 22
    input_overlay = /opt/retropie/emulators/retroarch/overlays/1080p/NeoGeoPocket_1080p.cfg
    input_overlay_enable = "true"
    input_overlay_opacity = 1.000000
    input_overlay_scale = 1.000000

##WonderSwan
/opt/retropie/configs/wonderswan/retroarch.cfg

    video_fullscreen_x = 1920
    video_fullscreen_y = 1080
    custom_viewport_width = 1120
    custom_viewport_height = 720
    custom_viewport_x = 401
    custom_viewport_y = 180
    aspect_ratio_index = 22
    input_overlay = /opt/retropie/emulators/retroarch/overlays/1080p/WonderSwan_1080p.cfg
    input_overlay_enable = "true"
    input_overlay_opacity = 1.000000
    input_overlay_scale = 1.000000