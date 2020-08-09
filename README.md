# MQTT-with-TLS
Guides and code examples for configuring MQTT on IoT with TLS, and other security features.

For further notes and links, see my [Dust-Notes](https://github.com/Dustpancake/Dust-Notes) repository.

## What this repository covers
I've been working on creating secure IoT devices, with the Arduino Nano 33 IoT micro-control unit. My aim is to

- spawn VerneMQTT brokers to handle and deliver messages
- use NGiNX as a load balancer for the brokers
- configure NGiNX for TLS TCP streams
- use the IoT device to send MQTT packets via TLS over WiFi

This repository will act as an overview, and eventually a guide, as to a possible implementation of this goal, first on a privately owned server, and later over AWS.

## Organisation
As this project is a work in progress, I am unsure how I will organise the final overview. Most of my notes will be included in my [Dust-Notes/mq-mqtt](https://github.com/Dustpancake/Dust-Notes/tree/master/mq-mqtt) and [Dust-Notes/arduino](https://github.com/Dustpancake/Dust-Notes/tree/master/arduino) repository, however I will include explicit code examples both in this repository, and in my own Ego and the [Id-IoT](https://github.com/Dustpancake/Id-IoT) project. 

For relevant notes, see here:

- minimal MQTT protocol overview [here](https://github.com/Dustpancake/Dust-Notes/blob/master/mq-mqtt/mqtt-specs.md)
- NGiNX as a load balancer (with Docker) [here](https://github.com/Dustpancake/Dust-Notes/blob/master/mq-mqtt/nginx-load-balancing.md)
- VerneMQ cluster (with Docker) (TODO)
- Configuring SSL/TLS on NGiNX (TODO)
- Uploading CA certificates and encryption keys onto Arduino firmware [here](https://github.com/Dustpancake/Dust-Notes/blob/master/arduino/ca-certs-nano.md)
- Testing the communication system is secure (TODO)


### Useful links

The [Arduino Nano 33 IoT Ultimate Guide](https://github.com/ostaquet/Arduino-Nano-33-IoT-Ultimate-Guide)