# IoT Alarm Blueprint

[![Open your Home Assistant instance and show the blueprint import dialog with a specific blueprint pre-filled.](https://my.home-assistant.io/badges/blueprint_import.svg)](https://my.home-assistant.io/redirect/blueprint_import/?blueprint_url=https%3A%2F%2Fgithub.com%2Fcbource%2Fiot-alarm-blueprint%2Fblob%2Fmain%2Fcustom_iot_alarm.yaml)

A powerful, highly customizable Home Assistant Blueprint for a DIY IoT Alarm System.

## Features
- **Easy Arm/Disarm**: Use a simple `input_boolean` switch to enable or disable your alarm.
- **Door/Window & Motion Sensors**: Automatically filter and select from your existing binary sensors to act as alarm triggers.
- **Geo-fencing / Away Mode**: Optionally select Device Trackers or Persons. The alarm will only trigger if everyone selected is marked as `not_home`.
- **Instant Sirens**: Trigger multiple sirens, lights, or switches immediately upon an intrusion.
- **Actionable Mobile Notifications**: Get an instant push notification via the Home Assistant mobile app with exactly what triggered the alarm, plus a built-in **Silence Alarms** button to verify and turn off the sirens directly from your lock screen.

## Installation

### Method 1: My Home Assistant (Recommended)
Click the badge at the top of this page to import the blueprint directly into your Home Assistant instance.

### Method 2: Manual URL
1. Go to **Settings** > **Automations & Blueprints** > **Blueprints** in Home Assistant.
2. Click **Import Blueprint** at the bottom right.
3. Paste the URL of the `custom_iot_alarm.yaml` file:
   `https://github.com/cbource/iot-alarm-blueprint/blob/main/custom_iot_alarm.yaml`

## License
MIT License
