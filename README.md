PROJ03: System Monitoring with Prometheus & Grafana

Overview

This project sets up a comprehensive system monitoring solution using Prometheus, Node Exporter, and Grafana. It involves manual and automated deployment using Ansible, real-time metric collection, custom PromQL queries, and visualization with Grafana dashboards.

Features

Automated Installation of Prometheus and Node Exporter using Ansible

Custom PromQL Queries for system performance analysis

Real-time Monitoring of disk usage, memory, CPU, network traffic, and uptime

Grafana Dashboard for data visualization

Security Hardening using UFW firewall rules and systemd service management

Project Breakdown

PROJ03-1: Setup & Preparation

Configured VM environment for hosting Prometheus and Node Exporter.

Ensured the availability of necessary packages and dependencies.

PROJ03-2: Manual Installation of Prometheus

Created a dedicated Prometheus system user.

Installed and configured Prometheus manually.

Opened necessary firewall ports (9090/tcp).

Set up systemd service for process management.

PROJ03-3: Automated Deployment with Ansible

Created Ansible playbooks for:

Prometheus installation and configuration.

Node Exporter deployment across multiple VMs.

Firewall rule enforcement (UFW) to allow monitoring traffic.

Implemented templated configuration management with Jinja.

Configured Prometheus targets to dynamically track VMs.

Wrote PromQL queries to monitor:

Disk Usage (%)

RAM Utilization (%)

System Uptime

PROJ03-4: Data Visualization with Grafana

Designed a Grafana dashboard displaying:

Disk Space Usage

Memory Consumption

Swap Utilization

CPU Load

Network Traffic

System Uptime

Ensured that the dashboard meets the three key principles:

Looks Good (clear, structured, visually appealing)

Is Good (accurate, actionable data)

Is Not Wrong (validated metrics, proper interpretation)

Exported queries and justifications into a PDF report.

