# Monitoring Dashboard Project

This project sets up a monitoring solution using Prometheus, Loki, and Grafana.

## Project Description

Monitors system metrics and logs, visualized in Grafana.

## Getting Started

1.  Make sure you have Docker and Docker Compose installed on your system.
2.  Clone this repository.
4.  Run: `docker-compose up -d`.
5.  Access Grafana at `http://localhost:3000` (default login: `admin`/`your_strong_password`).
6.  Add Prometheus data source (`http://prometheus:9090`).
7.  Add Loki data source (`http://loki:3100`).
8.  Import the Grafana dashboard JSON file.
9.  Explore the "Monitoring Dashboard".

## Repository Contents

* `docker-compose.yml`: Docker services definition.
* `prometheus.yml`: Prometheus configuration.
* `loki-config.yml`: Loki configuration.
* `promtail-config.yml`: Promtail configuration.
* `dashboard.json`: Grafana dashboard JSON.
* `README.md`: This file.
