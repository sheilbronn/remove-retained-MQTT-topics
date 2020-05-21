# Remove retained MQTT topics
Helper scripts to remove stale retained MQTT messages from a broker, e.g. autodiscovery leftovers for homie oder homeassistant

* rm-retained-mqtt-messages:  removes all messages below a given topic root
* rm-retained-messages-from-cmd-line: removes all messages with topics passed from stdin