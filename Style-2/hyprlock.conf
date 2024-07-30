# BACKGROUND
background {
    monitor =
    path = ~/.config/hypr/hypr.png
    blur_passes = 0
    contrast = 0.8916
    brightness = 0.8172
    vibrancy = 0.1696
    vibrancy_darkness = 0.0
}

# GENERAL
general {
    no_fade_in = false
    grace = 0
    disable_loading_bar = false
}

# Time
label {
    monitor =
    text = cmd[update:1000] echo "<span>$(date +"%I:%M")</span>"
    color = rgba(216, 222, 233, .7)
    font_size = 160
    font_family = steelfish outline regular
    position = 0, 370
    halign = center
    valign = center
}

# Day-Month-Date
label {
    monitor =
    text = cmd[update:1000] echo -e "$(date +"%A, %B %d")"
    color = rgba(216, 222, 233, .7)
    font_size = 28
    font_family = SF Pro Display Bold
    position = 0, 490
    halign = center
    valign = center
}

# Foreground
image {
    monitor =
    path = ~/.config/hypr/foreground.png
    size = 700
    border_size = 0
    rounding = 0
    rotate = 0
    reload_time = 0
    reload_cmd = 
    position = 0, -66
    halign = center
    valign = center
}

# USER
label {
    monitor =
    text =     $USER
    color = rgba(216, 222, 233, 0.80)
    outline_thickness = 2
    dots_size = 0.2 # Scale of input-field height, 0.2 - 0.8
    dots_spacing = 0.2 # Scale of dots' absolute size, 0.0 - 1.0
    dots_center = true
    font_size = 18
    font_family = SF Pro Display Bold
    position = 0, -180
    halign = center
    valign = center
}

# INPUT FIELD
input-field {
    monitor =
    size = 300, 60
    outline_thickness = 2
    dots_size = 0.2 # Scale of input-field height, 0.2 - 0.8
    dots_spacing = 0.2 # Scale of dots' absolute size, 0.0 - 1.0
    dots_center = true
    outer_color = rgba(255, 255, 255, 0)
    inner_color = rgba(255, 255, 255, 0.1)
    font_color = rgb(200, 200, 200)
    fade_on_empty = false
    font_family = SF Pro Display Bold
    placeholder_text = <i><span foreground="##ffffff99">🔒 Enter Pass</span></i>
    hide_input = false
    position = 0, -250
    halign = center
    valign = center
}