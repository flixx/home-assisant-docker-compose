# home-assisant-docker-compose
My Docker Compose Stack for a Zigbee / Home Assistan Installation on a Raspberry Pi

This docker-compose setup is inspired from https://medium.com/swlh/using-docker-compose-to-build-zigbee-infrastructure-336983a6ad67 and known to run on a Raspberry Pi 3B with [LibreELEC](https://libreelec.tv/) on it.

It is running the following services:

* [Home Assistant](https://www.home-assistant.io/)
* [zigbee2mqtt](https://www.zigbee2mqtt.io/)
* [node-red](https://nodered.org/)
* [zigbee2mqttAssistant](https://github.com/yllibed/Zigbee2MqttAssistant)
* mosquitto
* postgresql

## Prerequisites
* Docker (for LibreELEC install the Docker Plugin)
* docker-compose (for libreELEC see https://github.com/docker/compose/issues/6831#issuecomment-683797087)
* A [Flashed Zigbee Adapter](https://www.zigbee2mqtt.io/information/supported_adapters.html)

## Run

    ./restart
