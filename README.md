# esphome-lvgl-480
For Esphome-lvgl-480x480 (Guition 4" ESP32 S3 LVGL Display Switch)

I'm not a developer, so I don't really use annotations.

**Note, this is for reference, not for everyone.**

This is for esphome Korean users and does not fit the English language.

The weather included in the source has to use certain components in Korea, so you have to change the weather sensor to one that suits you.

Also, there's no image file here, which is a free image, but it's not included because it's copyrighted. 

You have to find and use this part on your own.

**Key Features**

1. Light Switch Control
2. Weather. Clockwork
3. Air conditioning control


**User's Guide**

```
substitutions:
  name: "your-device-name"  # Only lowercase letters
  device_description: Your device description
  light_1_name: "서재등"   # Device Light Switch entity name
  light_1_room: "서  재"   # Device Light Switch entity room name
  light_2_name: "전체 전등" # #HA Light Switch entity name
  light_2_room: "조  명"  # #HA Light Switch entity room name
  light_switch_2: switch.light_switch_lb_right  #HA Switch entity id
  indoor_temp: sensor.smartmi_air_purifier_temperature  # HA 실내 온도 센서 entity id
  indoor_hum: sensor.smartmi_air_purifier_humidity  # HA 실내 습도 센서 entity id
  aircon_id: climate.eeokeon  #HA air conditionor entity id
  latitude: "37"    # your latitude
  longitude: "126"   # your longitude

```
