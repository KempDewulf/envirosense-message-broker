# RabbitMQ with MQTT Support

This repository contains a Docker-based setup for RabbitMQ with MQTT protocol enabled. This broker will be used for communication between server and Iot device.

---

## Features

- RabbitMQ with MQTT plugin enabled.
- Pre-configured default user and password.
- Easy setup using Docker Compose.

---

## Requirements

- [Docker](https://www.docker.com/) (v20.10 or higher recommended)
- [Docker Compose](https://docs.docker.com/compose/) (v2.0 or higher)

---

## Installation

1. **Clone the Repository**:
   ```bash
   git clone git@github.com:KempDewulf/envirosense-message-broker.git
   cd rabbitmq-broker
   ```
2. **Start the RabbitMQ Container**:
   ```bash
   docker-compose up -d
   ```
3. **Access the RabbitMQ Services:**
    - Management UI: http://localhost:15672
        - Default credentials:
            - Username: admin
            - Password: admin
    - MQTT Protocol: localhost:1883 using an MQTT client
4. **Optionally:**

   Make seperate Users in the Management UI for IoT and Server with required permissions
