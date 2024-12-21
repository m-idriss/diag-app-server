# Diag App Server

## Overview

This project sets up a Kafka server and a Kafka UI using Docker Compose. It includes services for Kafka and Kafka UI,
configured to run in a Docker network.

## Services

### Kafka

- **Image**: `bitnami/kafka:latest`
- **Ports**: `9092:9092`

### Kafka UI

- **Image**: `provectuslabs/kafka-ui:latest`
- **Ports**: `8090:8080`

## Getting Started

### Prerequisites

- Docker
- Docker Compose

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/m-idriss/diag-app-server.git
   cd diag-app-server