# Analytics Infrastructure

This repository contains the local data and messaging infrastructure for the Payment Analytics platform.

## Included Services

- **TimescaleDB (Port 5432):** Primary relational and Time-Series database.
- **ClickHouse (Ports 8123 / 9000):** Columnar OLAP database for high-performance analytical queries.
- **RabbitMQ (Ports 5672 / 15672):** Message Broker for asynchronous communication between microservices.
- **MinIO (Ports 9000 / 9001):** S3-compatible Object Storage for saving generated reports.

## How to Run

Ensure you have Docker and Docker Compose installed on your machine.

1. Clone this repository.
2. Run the following command to start all services in the background:

```bash
docker compose up -d
```

To stop the services, run:

```bash
docker compose down
```
