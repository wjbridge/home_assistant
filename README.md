# Home Assistant Configuration
[Home Assistant Container](https://www.home-assistant.io/installation/#compare-installation-methods) ([Docker](https://hub.docker.com/r/homeassistant/home-assistant)) on a Ubuntu 20.04. I won't document the features of Mattias's repository but I will try to document the differences.

![screenshot](https://raw.githubusercontent.com/wjbridge/home_assistant/master/www/img/homescreen.png)

# Features
* Identify any missing or unavailable entities (including a filter list) and display a warning
* Swiping to show the last 3 captured TV Shows
* Shows weather alerts in the sidebar

## Credit
* I first want to give credit where credit is due. Most of the codebase was taken from [Mattias Persson](https://github.com/matt8707/hass-config) who is a genius when it comes to CSS and javascript layouts.
* The temperature icon came from [RoRoW](https://community.home-assistant.io/u/RoRoW).

## Docker Container Dependencies
* [swag](https://hub.docker.com/r/linuxserver/swag)
* [eufy-ha-mqtt-bridge](https://hub.docker.com/r/matijse/eufy-ha-mqtt-bridge)
* [eclipse-mosquitto](https://hub.docker.com/_/eclipse-mosquitto)
* [zigbee2mqtt](https://hub.docker.com/r/koenkk/zigbee2mqtt)
* [shinobidocker](https://hub.docker.com/r/migoller/shinobidocker)

# Sidebar

[Custom Button Card](https://github.com/custom-cards/button-card) to create dynamic [templates](https://www.home-assistant.io/docs/configuration/templating/).

* Time and date
* Temperature with emoji based on weather conditions
* Conditional weather alert information

![weather](https://raw.githubusercontent.com/wjbridge/home_assistant/master/www/img/weather_alert.png)

## Sidebar Footer

The three icons at the bottom in order:

* Monitor [Home Assistant](https://home-assistant.io/), batteries, and key docker containers 
* List any missing or unavailable entities
* Lists available HACS updates and release notes for Home Assistant

### Missing or Update Available Animation
![warning](https://raw.githubusercontent.com/wjbridge/home_assistant/master/www/img/missing_update.gif)

### Information Dialog Box
![info](https://raw.githubusercontent.com/wjbridge/home_assistant/master/www/img/info.png)

### Update Information Dialog Box
![info](https://raw.githubusercontent.com/wjbridge/home_assistant/master/www/img/update.png)

# Media
Poster of last downloaded episodes with swiping to reveal other downloaded episodes.
![toggle](https://raw.githubusercontent.com/wjbridge/home_assistant/master/www/img/media_swipe.gif)

## Added Animations
![toggle](https://raw.githubusercontent.com/wjbridge/home_assistant/master/www/img/toggle.gif)

# Climate

* Dynamic icon changing depending on mode (i.e. heat, cool, fan)
* Graphs of all temperature data
* Shows the amount of cool / heating time for the last 3 days

![climate](https://raw.githubusercontent.com/wjbridge/home_assistant/master/www/img/climate.png)

### Misc
![person](https://raw.githubusercontent.com/wjbridge/home_assistant/master/www/img/person.png)

![garage](https://raw.githubusercontent.com/wjbridge/home_assistant/master/www/img/garage.png)

![fan](https://raw.githubusercontent.com/wjbridge/home_assistant/master/www/img/fan.png)

***

**Home Assistant Community Topic**  
[https://community.home-assistant.io/t/a-different-take-on-designing-a-lovelace-ui/162594](https://community.home-assistant.io/t/a-different-take-on-designing-a-lovelace-ui/162594)