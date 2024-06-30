# OpenHAB example files for Leaf2MQTT

To use this example config:
    - copy `items`, `things` and `transform` directories to `openhab` directory (under Linux it is located under `/etc/)
    - edit `.things` file so `mqtt:broker:mosquitto` Bridge points to your MQTT server or change Thing to point to your previously defined MQTT bridge

Leaf Statistics should appear under `Cars` devices.
