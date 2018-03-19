[![Build Status](https://travis-ci.org/mnigbur/homeassistant-config.svg?branch=master)](https://travis-ci.org/mnigbur/homeassistant-config)
# Home-Assistant Config

# Current state
* I broke the main SD Card.. redoing the system right now.
* FireTV is currently not working, I removed Python2 completely.
* Automations and specifically automatic lights are currently a bit messy, need to redo this asap.

# Planned things
* Refactor all appdaemon automations (with upgrade to 3.0)
* Move all automations to appdaemon
* RGB Led Cube for the living room
* Building the amplifier case and document the process.
* Full documentation on my current setup
* Blog series about getting started with home automation

# If time permits, someday
* Get some machine learning going on the entity states and see if we can get prediction on user "interactions"

# Random stuff to remember
* View HASS realtime logs `sudo journalctl -f -u home-assistant`
* View mosquitto realtime messages `mosquitto_sub -u {user} -P {password} -v -t '#'`

# Restore from git
```
sudo su - homeassistant
cd /home/homeassistant
git clone git@github.com:mnigbur/homeassistant-config.git .homeassistant
```
