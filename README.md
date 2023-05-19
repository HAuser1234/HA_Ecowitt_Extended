<a href="https://www.buymeacoffee.com/tobineidhaj" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="41" width="174"></a>


# HA_Ecowitt_Extended
this repository is trying to get the most out of your ecowitt weatherstation in homeassistant!
Very easy config and plug'n'play use with the local weather forecast repo!! https://github.com/HAuser1234/homeassistant-local-weather-forecast

# Features
- get all sensors of your weathersation as entities!
- Cloud cover estmation
- Current weather condions estimation
- Wind chill
- Head index
- Battery Info

and together with @ https://github.com/HAuser1234/homeassistant-local-weather-forecast
Get your own customized local weather forecast!!

# Card
![grafik](https://github.com/HAuser1234/HA_Ecowitt_Extended/assets/122117318/f04d1d63-8d75-4924-a3c5-25994ed332a4)

(English translation should be easy. Please Contribute that!!)

# Installation
please contribute ANY upgrades to the card or algorythm thia helps everybody!

> Step 1:
* connect with the WSview app to your weatherstation
* go to custom
* protocoll: ecowitt -> enable
* Server: Your.HA.IP.Adress
* Port: 8123
* Upload Intervall: 60
* Path: /api/webhook/pws

> Step 2:
* copy weatherstation.yaml into your custom yaml integrations folder
how to make a integrations folder:
1. add this to your configuration.yaml:

```
homeassistant:
  packages: !include_dir_named integrations
```
2. create a folder named integrations in your config directory
3. copy weather_forecast.yaml in this folder

> Step 3:
* copy the card as a manual yaml config into lovelace. !mushroom required, vertical-stack-in-card required, compass card required and rain-gauge-card required!

# ToDo
- translate Card


--------------------
sources:
This code os based on the work of:
```
https://github.com/Xorfor/HA-PWS
https://github.com/Xorfor/Domoticz-PWS-Plugin/blob/master/plugin.py
https://community.home-assistant.io/t/weather-station-recommendation/55353/23
https://www.home-assistant.io/integrations/template/
https://github.com/pnbruckner/ha-illuminance/blob/master/custom_components/illuminance/sensor.py
https://github.com/Xorfor/HA-PWS
```
--------------------
THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.


