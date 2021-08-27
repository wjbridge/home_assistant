| :exclamation:  Work in progress         |
|-----------------------------------------|

# Home Assistant Configuration

[Home Assistant Container](https://www.home-assistant.io/installation/#compare-installation-methods) ([Docker](https://hub.docker.com/r/homeassistant/home-assistant)) on a Ubuntu 20.04. I **LOT** of the source code and inspiration came from ([Matt](https://github.com/matt8707/hass-config)) 

![screenshot](https://raw.githubusercontent.com/wjbridge/home_assistant/master/www/img/screenshot.png)

---

## Features

* A different take on designing a [Lovelace UI](https://www.home-assistant.io/lovelace/) using <s>picture elements card</s> [custom:layout-card](https://github.com/thomasloven/lovelace-layout-card)
* Achieving a less cluttered interface by displaying [more information](https://github.com/thomasloven/hass-browser_mod#popup) on a [long press](https://www.home-assistant.io/lovelace/picture-elements/#hold_action)
* Loading wheel for slow responding entities.
* [CSS Animations](https://www.w3schools.com/css/css3_animations.asp) based on state

### The sidebar

[Markdown Card](https://www.home-assistant.io/lovelace/markdown/) to create dynamic [templates](https://www.home-assistant.io/docs/configuration/templating/).

* Time and date
* Temperature with emoji based on weather conditions
* Weather alert information
* Other conditional alerts

### Sidebar footer

The three icons at the bottom in order:

* Conditional card to list missing entities
* Monitor [Home Assistant](https://home-assistant.io/), batteries, and docker containers
* Lists available HACS updates and release notes for Home Assistant

![info](https://raw.githubusercontent.com/wjbridge/home_assistant/master/www/img/info.png)

### Media

Poster of last downloaded episodes is shown [Sonarr](https://github.com/Sonarr/Sonarr)). Swipe to reveal other downloaded episodes.

### Climate

* Dynamic icon changing depending on mode (i.e. heat, cool, fan)
* Graphs of all temperature data

![climate](https://raw.githubusercontent.com/wjbridge/home_assistant/master/www/img/climate.png)

### Garage

* Dynamic icon changing depending on mode (i.e. heat, cool, fan)
* List garage door status and history
* Live view of the garage updated at 2 Hz

![garage](https://raw.githubusercontent.com/wjbridge/home_assistant/master/www/img/garage.png)

### Misc
![person](https://raw.githubusercontent.com/wjbridge/home_assistant/master/www/img/person.png)

***

**Home Assistant Community Topic**  
[https://community.home-assistant.io/t/a-different-take-on-designing-a-lovelace-ui/162594](https://community.home-assistant.io/t/a-different-take-on-designing-a-lovelace-ui/162594)