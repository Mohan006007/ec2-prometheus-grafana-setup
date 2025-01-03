# EC2 Prometheus & Grafana Setup

This repository contains a complete setup for monitoring EC2 instances using **Prometheus** and **Grafana**. The setup includes Prometheus scraping metrics from **Node Exporter** and visualizing the data with **Grafana dashboards**.

## Setup Overview

- **Prometheus** collects and stores metrics from the EC2 instance running **Node Exporter**.
- **Grafana** visualizes the metrics from Prometheus to monitor system performance.

## Screenshots

- **Prometheus Targets Health**:  
  Prometheus showing the status of its targets as up and running.  
  ![Prometheus Targets Health](screenshots/prometheus-targets.png)

- **Grafana Dashboard**:  
  Grafana dashboard visualizing Prometheus metrics for easy monitoring.  
  ![Grafana Dashboard](screenshots/grafana-dashboard.png)

- **Node Exporter Metrics**:  
  Node Exporter displaying system performance data.  
  ![Node Exporter Metrics](screenshots/node-exporter-metrics.png)

## Files Included

- `prometheus.yml`: Prometheus configuration file.
- `node_exporter.service`: Service file for Node Exporter.
- `prometheus.service`: Service file for Prometheus.

## Usage

1. Install **Prometheus** and **Node Exporter** on the EC2 instance.
2. Configure **Prometheus** to scrape metrics from **Node Exporter**.
3. Set up **Grafana** to visualize the metrics stored in Prometheus.
