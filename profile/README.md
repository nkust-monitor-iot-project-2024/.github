# NKUST Monitor IoT project

This repository contains the code implementation of the paper, “**Intruder Monitoring: Building Highly Scalable Monitoring Services with Machine Learning, Microservices, and IoT**”.

Code here are somewhat incompleted, and I prefer to leave it as it is.

## Repositories

- [Central System](https://github.com/nkust-monitor-iot-project-2024/central): Event Aggregator, Recognition Façade, Public Event Façade, MQTT Forwarder and some Protobuf and GraphQL definitions.
- [Recognition Service](https://github.com/nkust-monitor-iot-project-2024/recognition): Recognize the entities of a picture with YOLOv10.
- [Edge System (Rust, deprecated)](https://github.com/nkust-monitor-iot-project-2024/edge-system-rs): The code that can be run on Raspberry Pi 3B. I decide to rewrite it in Python for better ecosystem support, so I archive this.

### Drafts

This drafts act like an PoC of our sensors. It is not well-written, but it mostly works.

- [Sensor examples](https://github.com/nkust-monitor-iot-project-2024/sensor-examples): PoC of the sensors.
- [Notification examples](https://github.com/nkust-monitor-iot-project-2024/notification-examples): PoC of LINE Notify and Discord (Webhook)

## Unimplemented

- [ ] Notification System - For sending the events to LINE Notify and Discord.
- [ ] The front-end of Public Event Façade. We can only call it with the built-in GraphiQL currently.
- [ ] The organized edge system.
