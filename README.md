# ESPHome Smart Button (Multi-Click Event)
Beschreibung: Dieses Projekt verwandelt einen ESP8266 (z.B. Wemos D1 Mini) oder ESP32 in einen leistungsfähigen Smart Button für Home Assistant. Im Gegensatz zu einfachen binären Sensoren nutzt dieses Projekt native Home Assistant Events, um Klicks extrem schnell und zuverlässig zu verarbeiten.

Es unterscheidet zwischen Einfach-, Doppel-, Dreifachklick und langem Tastendruck.

Features:

🚀 Event-Basiert: Nutzt esphome.button_action Events statt träger Status-Änderungen.

🎛 4 Aktionen: Single, Double, Triple & Long Press.

📦 Blueprint Ready: Inklusive Home Assistant Blueprint zur kinderleichten Automatisierung.

👀 Dashboard Feedback: Ein Text-Sensor zeigt den letzten Klickstatus im Dashboard an.

🔧 Remote Packages: Der ESPHome-Code ist modular aufgebaut und kann einfach in bestehende Configs importiert werden.

Voraussetzungen:

Home Assistant

ESPHome (Add-on oder Standalone)

Ein ESP8266 oder ESP32 Board mit einem Taster (zwischen GPIO und GND).

Installation:

Importiere den Blueprint über den Button oben.

Flashe deinen ESP mit dem Code aus smartbutton.yaml.

Erstelle eine Automatisierung in Home Assistant mit dem Blueprint.

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint URL pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fedethio%2Fsmartbutton%2Fblob%2Fmain%2Fblueprint_smartbutton.yaml)
