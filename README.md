# Server Monitoring, Logging & CI Pipeline

**Student Name:** [Your Name]  
**Batch:** DevOps Batch 14  
**Assignment Title:** Server Monitoring, Logging & CI Pipeline

## Project Overview

This project provisions a DevOps environment on an Ubuntu server, utilizing Prometheus for metric scraping, Node Exporter for system-level metrics, Grafana for visualization, Loki/Promtail for centralized logging, and a GitHub Actions self-hosted runner for CI.

## Architecture Diagram

_(Insert diagram image here)_

## Installation Steps & Configuration

_(Briefly summarize the commands and file paths you used above)_

## CI Pipeline Explanation

The CI pipeline runs on a self-hosted runner. It triggers on a push to `main`, checks out the code, simulates a build step, runs tests, and archives the resulting `/dist` folder using `actions/upload-artifact`.

## Screenshots

### 1. Prometheus

_(Insert Target UP screenshot)_
_(Insert metrics page screenshot)_

### 2. Node Exporter

_(Insert /metrics browser screenshot)_

### 3. Grafana

_(Insert Prometheus Datasource connected screenshot)_
_(Insert Dashboard screenshot)_

### 4. Loki

_(Insert Loki Datasource connected screenshot)_
_(Insert Explore page logs screenshot)_

### 5. GitHub Actions

_(Insert Self-hosted runner Online screenshot)_
_(Insert Workflow successful screenshot)_
_(Insert Artifact generated screenshot)_

## Result/Conclusion

Successfully implemented an end-to-end monitoring and logging stack without using Docker, and configured an automated CI pipeline attached to local infrastructure.
