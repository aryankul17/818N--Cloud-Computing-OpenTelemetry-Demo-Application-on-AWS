# Phase 2: Helm-Based Deployment & Rollback

## Objective
Transition to a scalable, modular deployment using Helm charts. Improve deployment consistency, introduce version control, and validate rollback capabilities.

## Key Tasks
- **Helm Chart Usage:** Installed and validated `helm`, added OpenTelemetry Helm repo, and installed the application with custom values in the `otel-helm-demo` namespace.
- **Application Deployment via Helm:** Confirmed that all microservices were up and running, services exposed, and Grafana/Jaeger dashboards loaded correctly.
- **Upgrade & Rollback:** Demonstrated upgrade via `helm upgrade` and rollback using `helm rollback` for reliability testing.

## Tools Used
- Helm v3
- OpenTelemetry Helm Charts
- kubectl
- Amazon EKS

## Outcome
Helm streamlined our deployment process, resolved ConfigMap size limitations, and made future upgrades and rollbacks seamless. The structured deployment improved observability tool loading and allowed efficient namespace management.
