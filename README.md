# 📊 Grafana & Prometheus Monitoring Stack for Homelab

This project outlines the setup of a robust monitoring stack using **Prometheus** and **Grafana** to visualize and monitor system and container metrics across a Proxmox-based homelab environment.

🔗 **Full Guide:** [Grafana and Prometheus Setup](https://homelab.sanjuprojects.uk/grafana-and-prometheus/)

---

## 🧰 Stack Components

- **Prometheus**: Time-series database for collecting and querying metrics.
- **Grafana**: Visualization tool for creating interactive dashboards.
- **Node Exporter**: Exposes hardware and OS metrics from *nix systems.
- **cAdvisor**: Provides container resource usage and performance metrics.
- **Docker Compose**: Simplifies the deployment and management of services.

---

## 📁 Project Structure
Prometheus-
.
├── config
│   └── prometheus.yml
├── docker-compose.yaml
└── prometheus_data

Grafana
.
├── docker-compose.yaml
└── grafana-storage
    ├── grafana.db
    ├── plugins/
    │   ├── grafana-clock-panel/
    │   │   ├── plugin.json
    │   │   └── README.md
    │   ├── grafana-exploretraces-app/
    │   │   ├── plugin.json
    │   │   └── README.md
    │   ├── grafana-lokiexplore-app/
    │   │   ├── plugin.json
    │   │   └── README.md
    │   ├── grafana-metricsdrilldown-app/
    │   │   ├── plugin.json
    │   │   └── README.md
    │   ├── grafana-pyroscope-app/
    │   │   ├── plugin.json
    │   │   └── README.md
    │   └── grafana-simple-json-datasource/
    │       ├── plugin.json
    │       └── README.md
---

## 🚀 Deployment Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/homelab-monitoring.git
cd homelab-monitoring

📚 Learn More
📘 Read the full setup guide and context on my website:
👉 Grafana and Prometheus Homelab Monitoring Guide

Feel free to fork and adapt this project to suit your homelab or self-hosted monitoring needs!