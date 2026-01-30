# CYD Living Room

This project contains the code and resources for the CYD Living Room application. It is designed to provide an interactive and immersive experience for users in a living room setting.

## Features
- Control lights
- Arm Alarm
- View Battery Status
- Control TV

## Installation
Git clone the repo and create a new base yaml file like example.

```yaml
substitutions:
  text_font: roboto_20
  width: 240
  height: 320
  device_name: display
  nice_name: Cheap Yellow Display
  icon_font: mdi_icons_40
  text_color: white
  bg_color: black
  button_on_color: "ep_orange"
  button_off_color: "very_dark_gray"
  icon_on_color: "yellow"
  icon_off_color: "gray"
  label_on_color: "white"
  label_off_color: "gray"
  button_text_color: "white"
  touchscreen_idle_timeout: "60s"

packages:
  general: !include cyd_living_room/general.yaml
  fonts: !include cyd_living_room/fonts.yaml
  glyphs: !include cyd_living_room/glyphs.yaml
  color: !include cyd_living_room/color.yaml
  theme_style: !include cyd_living_room/theme_style.yaml
  sensors: !include cyd_living_room/sensors.yaml
  backlight: !include cyd_living_room/backlight_time.yaml
  hardware: !include cyd_living_room/hardware.yaml
  loading_page: !include cyd_living_room/pages/loading.yaml
  main_page: !include cyd_living_room/pages/main.yaml
  tv_page: !include cyd_living_room/pages/tv.yaml
```
