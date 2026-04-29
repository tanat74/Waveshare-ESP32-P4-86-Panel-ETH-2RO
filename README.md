### English

I would like to express my sincere gratitude to the original author for providing the foundation for this project.

This version has been refined and adapted by AI specifically for **ESPHome 2026.4.3**. The following enhancements have been implemented:
* Integrated **i2s_audio_duplex** for advanced audio communication.
* Added **timer** functionality.
* Implemented a **"stop"** word feature to interrupt active processes.

This work was inspired by the Home Assistant Voice PE project and the Respeaker Lite ESPHome integration.

---

### Русский

Выражаю искреннюю благодарность автору оригинального репозитория за основу для данного проекта.

Эта версия была доработана с помощью ИИ специально для сборки на **ESPHome 2026.4.3**. Были внесены следующие изменения:
* Интегрирован компонент **i2s_audio_duplex** для реализации дуплексной связи.
* Добавлены функции **таймера**.
* Реализована возможность остановки процессов голосовой командой **«stop»**.

Данная работа вдохновлена проектами Home Assistant Voice PE и интеграцией Respeaker Lite для ESPHome.

---

### Links / Ссылки

* **Original Base / Основа:** [alaltitov/Waveshare-ESP32-P4-86-Panel-ETH-2RO](https://github.com/alaltitov/Waveshare-ESP32-P4-86-Panel-ETH-2RO)
* **Audio Integration / Интеграция аудио:** [n-IA-hane/esphome-intercom](https://github.com/n-IA-hane/esphome-intercom)
* **Inspiration / Вдохновение 1:** [Home Assistant Voice YAML](https://github.com/esphome/home-assistant-voice-pe/blob/dev/home-assistant-voice.yaml)
* **Inspiration / Вдохновение 2:** [Respeaker Lite ESPHome Integration](https://github.com/formatBCE/Respeaker-Lite-ESPHome-integration/blob/main/config/common/respeaker-satellite-base.yaml)

# LVGL ESPhome Waveshare-ESP32-P4-86-Panel-ETH-2RO custom firmware

<p align="center">
 <img width="200px" src="/docs/images/loading.png">
 <img width="200px" src="/docs/images/home.png">
 <img width="200px" src="/docs/images/forecasts.png">
 <img width="200px" src="/docs/images/info.png">
 <img width="200px" src="/docs/images/settings.png">
 <img width="200px" src="/docs/images/light0.png">
 <img width="200px" src="/docs/images/light1.png">
 <img width="200px" src="/docs/images/climate0.png">
 <img width="200px" src="/docs/images/climate1.png">
 <img width="200px" src="/docs/images/climate2.png">
 <img width="200px" src="/docs/images/climate3.png">
 <img width="200px" src="/docs/images/media_player.png">
 <img width="200px" src="/docs/images/vacuum.png">
</p>

<p align="center">
    <img alt="Static Badge" src="https://img.shields.io/badge/made%20by-alaltitov-blue">
    <img alt="Static Badge" src="https://img.shields.io/badge/version-v1.0%20Dev-green">
    <img alt="Static Badge" src="https://img.shields.io/badge/esphome min version-2025.11.0-red">
    <img alt="Static Badge" src="https://img.shields.io/badge/license-MIT-orange">
</p>

## Support the Project

<img src="/docs/images/donate.png" alt="QR Code" width="150" align="left" hspace="10"/>

<div style="padding-top: 40px;">
  <b>Support me on</b>
  <div style="height: 30px;"></div>
  <a href="https://boosty.to/altitov/donate">
    <img src="/docs/images/boosty.png" alt="Boosty" width="160"/>
  </a>
</div>

<br clear="all"/>

## Questions, Discussions, Ideas

<div style="padding-top: 40px;">
  <a href="https://t.me/esphome_lvgl_chats">
    <img src="/docs/images/t_me_chats.jpg" alt="QR Code" width="150" align="left" hspace="10"/>
  </a>
</div>

<br clear="all"/>

## ✨ Features

- Status indicators for Wi-Fi, Home Assistant API, thermostat, air conditioner, touchscreen lock, alarm panel
- Weather icons with current conditions and temperature
- Weather Forecasts daily and hourly
- Date and time
- Sensor readings from Home Assistant
- Voice Assistant (testing...)
- Lights control
- Alarm Panels control
- Climate control
- Covers control
- Fans control
- Media Player control
- Radio control (testing...)
- Vacuum control
- Settings:
  * Backlight adjustment
  * Screen timeout settings
  * Language selection:
    - ru (from [alaltitov](https://github.com/alaltitov))
    - en (from [alaltitov](https://github.com/alaltitov))
    - pl (from [reaper7](https://github.com/reaper7))
    - fr (from [lboue](https://github.com/lboue))
    - es (from Antonio)
    - nl (from [zjean](https://github.com/zjean))
    - si (from [Protoncek](https://github.com/Protoncek))
    - it (from [echopage1964](https://github.com/echopage1964))
    - de (from [MATZE-MAN](https://github.com/MATZE-MAN))

## 📦 Installation
> 📹 **Video [instruction](https://youtu.be/HYN_2hvcbes?si=JfYQH4vCuFlr8Q9r)**

<img width="400px" src="/docs/images/ha_options.png">

- You must enable the "Allow the device to perform Home Assistant actions." option in the ESPHome integration to Home Assistant to control devices.
- Install custom component for forecasts and covers for media player from [here](https://github.com/alaltitov/homeassistant-display-tools).
- Copy repository to vscode or to esphome folder of your Home Assistant. Change substitutions.yaml and config.yaml your entities in all widgets (only in substitution, in code everything will be substituted automatically).

## 📖 Documentation
- [ESPHome LVGL 8.4](https://esphome.io/components/lvgl/)

## 🤝 Thanks for your help
- Thanks to [ZHNovell](https://github.com/ZHNovell) for financial support of the project, as well as for help with testing and ideas.
- Thanks, [сlydebarrow](https://github.com/clydebarrow), [jesserockz](https://github.com/jesserockz), [ssieb](https://github.com/ssieb) for helping me with the project!

