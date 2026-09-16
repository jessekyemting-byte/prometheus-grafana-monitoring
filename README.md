# Prometheus and Grafana Monitoring Setup

End-to-end monitoring solution configured on Ubuntu/WSL using Prometheus, Node Exporter, and Grafana.

## Architecture
- **Node Exporter:** Exposes host metrics on port `9100`
- **Prometheus:** Scrapes metrics on port `9090`
- **Grafana:** Visualizes metrics on port `3000`
