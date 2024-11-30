# RabbitMQ with MQTT Support

This repository contains a Docker-based setup for RabbitMQ with MQTT protocol enabled. This setup is suitable for local development and testing IoT applications using RabbitMQ as a message broker.

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
   git clone git@gitlab.ti.howest.be:ti/2024-2025/s5/ccett/projects/group-14/rabbitmq-broker.git
   cd git@gitlab.ti.howest.be:ti/2024-2025/s5/ccett/projects/group-14/rabbitmq-broker.git
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
