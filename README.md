# Network Monitoring System Using Prometheus and Grafana

## Overview

This project was developed during my internship as a NOC & Network Field Support Intern at PT Semen Padang.

The project aims to build a container-based network monitoring system using Prometheus, Grafana, and SNMP Exporter to monitor network devices in real time. The system provides network visibility through an interactive dashboard, helping administrators monitor device conditions and network traffic efficiently.

> Note: All IP addresses, device names, SNMP communities, and internal network information have been modified or anonymized for security and confidentiality purposes.

## Technologies Used

* Docker
* Docker Compose
* Prometheus
* Grafana
* SNMP Exporter
* Ubuntu Server

## Features

* Device Uptime Monitoring
* Interface Status Monitoring
* Traffic In Monitoring
* Traffic Out Monitoring
* Total Traffic Monitoring
* Real-Time Dashboard Visualization

## System Architecture

<img width="761" height="471" alt="Diagram Tanpa Judul drawio (7)" src="https://github.com/user-attachments/assets/1d9947c3-6617-4e54-82de-11fe19f25e8f" />


## Monitoring Parameters

The implemented monitoring system collects and visualizes the following metrics:

* Device Uptime
* Interface Status
* Traffic In
* Traffic Out
* Total Network Traffic

## Screenshots

### Main Dashboard

<img width="1920" height="2003" alt="screencapture-10-28-119-218-3000-d-addlbpk-monitoring-switch-2026-06-17-12_42_24" src="https://github.com/user-attachments/assets/ff2bc2b7-a402-49a2-9e3d-565f0ee43ca1" />


### Device Dashboard

<img width="1920" height="1766" alt="screencapture-10-28-119-218-3000-d-7qKD6I1Wk-snmp-stats-2026-06-17-12_43_05" src="https://github.com/user-attachments/assets/88b5a2b1-c313-46cb-86f4-2b51e11c0694" />


## Project Structure

```text
monitoring-jaringan/
├── docker-compose.yml
├── prometheus/
├── grafana/
├── snmp_exporter/
└── README.md
```

## Learning Outcomes

Through this project, I gained practical experience in:

* Network Monitoring Implementation
* Docker Containerization
* SNMP-Based Data Collection
* Time-Series Data Monitoring
* Grafana Dashboard Development
* Network Infrastructure Observability

## Author

Sangkot Wahyu Pulungan

Computer Network Engineering Technology Student

Universitas Bung Hatta
