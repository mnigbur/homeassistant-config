# [![Build Status](https://travis-ci.org/mnigbur/homeassistant-config.svg?branch=master)](https://travis-ci.org/mnigbur/homeassistant-config) Home-Assistant Config

# Current state

# Planned things

# Random stuff to remember
View HASS realtime logs `sudo journalctl -f -u home-assistant`
View mosquitto realtime messages `mosquitto_sub -u {user} -P {password} -v -t '#'`

# Restore from git
```
sudo su - homeassistant
cd /home/homeassistant
git clone git@github.com:mnigbur/homeassistant-config.git .homeassistant
```
