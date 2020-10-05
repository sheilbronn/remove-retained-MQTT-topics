# Remove retained MQTT topics

Helper scripts to remove stale retained MQTT messages from a broker, e.g. autodiscovery leftovers for homie oder homeassistant

* rm-retained-mqtt-messages:  removes all messages below a given topic root
* rm-retained-messages-from-cmd-line: removes all messages with topics passed from stdin

These scripts are intended for mosquitto client versions **before** version 1.5.8:
Since 1.5.8 mosquitto_sub has an option ``--remove-retained´´ that fulfills a similar purpose. 