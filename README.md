\# Smart Campus MQTT Pub-Sub System



\## Description

This project implements a publish-subscribe system using Node-RED and Mosquitto MQTT broker (Docker).



\## Architecture

Publishers → Mosquitto Broker → Wildcard Subscriber → Dashboard



\## Topics Used

\- campus/lab1/temperature

\- campus/lab1/humidity

\- campus/status



\## QoS Levels Demonstrated

\- QoS 0 (No guarantee)

\- QoS 1 (At least once)

\- QoS 2 (Exactly once)



\## Retained Message

The status topic uses retained messages to store the last system state.



\## Tools Used

\- Node-RED (Docker)

\- Eclipse Mosquitto (Docker)

\- MQTT Protocol

