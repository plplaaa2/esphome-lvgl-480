# esphome-lvgl-480-KC
For Esphome-lvgl-480x480 (Guition 4" ESP32 S3 LVGL Display Switch)

I'm not a developer, so I don't really use annotations.

**Note, this is for reference, not for everyone.**

This is for esphome Korean users and does not fit the English language.

The weather included in the source has to use certain components in Korea, so you have to change the weather sensor to one that suits you.

Also, there's no image file here, which is a free image, but it's not included because it's copyrighted. 

You have to find and use this part on your own.

**Key Features**

1. Kitchen Device Control
2. Weather. Clockwork
3. Air conditioning control
4. Play the radio
5. Power consumption warning

**User's Guide**

```
substitutions:
  name: "esphome-480-kc"  # Only lowercase letters
  device_description: ESPhome Craft 480 Kitchen Version
  
  # Switch
  light_switch: your entity #HA Light Switch entity id
  induction_switch: your entity #HA Induction entity id
  rice_switch: your entity #HA Electric rice cooker entity id  
  fan_switch: your entity #HA HA Can entity id  
  
  # Sensors
  indoor_temp: your entity # HA indoor temperature sensor entity id
  indoor_hum: your entity # HA indoor humidity sensor entity id  
  energy_sensor: your entity # HA energy meter entity id  
  presence_sensor: your entity # HA KC presence or motion detecter entity id  

  #devices
  aircon_id: your entity #HA Air conditioner entity id
  media_player: media_player.entity #HA KC media player entity id
  
  #Radio channel, For Korea User,
  kbscool: "https://your_radio_address/radio?keys=ytn&token=homeassistant"
  itv: "https://your_radio_address/radio?keys=ytn&token=homeassistant"
  mbcfm4u: "https://your_radio_address/radio?keys=ytn&token=homeassistant"
  KBSClassic: "https://your_radio_address/radio?keys=ytn&token=homeassistant"
  CBSMusic: "https://your_radio_address/radio?keys=ytn&token=homeassistant"
  YTN: "https://your_radio_address/radio?keys=ytn&token=homeassistant"
  TBS: "https://your_radio_address/radio?keys=ytn&token=homeassistant"
  MBCFM: "https://your_radio_address/radio?keys=ytn&token=homeassistant"
  KBS1FM: "https://your_radio_address/radio?keys=ytn&token=homeassistant"
  CBSFM: "https://your_radio_address/radio?keys=ytn&token=homeassistant"
  TBN: "https://your_radio_address/radio?keys=ytn&token=homeassistant"
  SBSLoveFM: "https://your_radio_address/radio?keys=ytn&token=homeassistant"
  EBSFM: "https://your_radio_address/radio?keys=ytn&token=homeassistant"
  KBS3FM: "https://your_radio_address/radio?keys=ytn&token=homeassistant"
  KBSHappyFM: "https://your_radio_address/radio?keys=ytn&token=homeassistant"
  SBSPowerFM: "https://your_radio_address/radio?keys=ytn&token=homeassistant"

  # location
  latitude: "37" # your home latitude
  longitude: "126" # your home longitude  

```


 **Main Page**

![1000011548](https://github.com/user-attachments/assets/570fdb4c-a2e6-4d31-9287-bf9d1ef7c84f)

**Weather Page**

![1000011549 (1)](https://github.com/user-attachments/assets/0d29ec11-76e8-42fd-8909-c2c223f9237a)

**Menu Page**
![1000011550](https://github.com/user-attachments/assets/7c8ca264-15bd-4650-bcf9-f0ee383bbf14)

**Air Conditioner Page**
![1000011551](https://github.com/user-attachments/assets/918551b4-c10f-4428-bd87-f46f6940fc71)

**Radio Page**
![1000011552](https://github.com/user-attachments/assets/aa383f2f-268b-448e-b6a5-db4db3bc6706)

**Energy Page**
![1000011553](https://github.com/user-attachments/assets/506632d9-94cf-4228-bef2-9aad1051fa07)

**Setting Page**
![1000011554](https://github.com/user-attachments/assets/dd26e9dd-4942-4262-81b3-9e0c910f7a60)
