# Phase 3: Observability & Alerts

## Objective
Enable real-time monitoring, alerting, and visibility into system behavior using Prometheus, Grafana, and Jaeger.

## Key Tasks
- **Prometheus Setup:** Configured Prometheus to scrape metrics from Kubernetes pods and services.
- **Grafana Integration:** Used Helm to deploy Grafana and configured dashboards for CPU, memory, and pod health.
- **Alerting Rules & Email Notifications:** Defined alert rules in `pod-restart-alert.yaml` to monitor pod failures and sent alert emails through SMTP configuration.

## Tools Used
- Prometheus
- Grafana
- Jaeger
- Alertmanager

## Outcome
This phase provided detailed observability into cluster and application performance. Alerts enabled proactive issue detection and helped simulate real-world reliability practices.
