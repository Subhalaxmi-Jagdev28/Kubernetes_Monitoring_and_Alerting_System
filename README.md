# Kubernetes Monitoring & Alerting System

## Tools
- Kubernetes (Minikube)
- Prometheus
- Grafana
- Alertmanager
- Helm

## Features
- CPU Monitoring
- Memory Monitoring
- Pod Crash Detection
- Node Health Monitoring
- Email & Slack Alerts

## We can demonstrate

✅ Kubernetes Administration
✅ Observability Engineering
✅ DevOps Monitoring
✅ Production Alerting
✅ Helm Deployment
✅ GitHub DevOps Workflow

## Architecture
                        ┌────────────────────────┐
                        │        Users           │
                        │  (Admin / DevOps)      │
                        └──────────┬─────────────┘
                                   │
                                   ▼
                          ┌────────────────┐
                          │     Grafana    │
                          │ Visualization  │
                          └───────┬────────┘
                                  │ Queries
                                  ▼
                    ┌─────────────────────────┐
                    │       Prometheus        │
                    │   Metrics Collection    │
                    └───────┬────────┬────────┘
                            │        │
            Metrics Scrape  │        │ Alert Rules
                            │        ▼
        ┌────────────────┐  │   ┌───────────────┐
        │ Node Exporter  │  │   │ Alertmanager  │
        │ kube-state     │  │   │ Alert Routing │
        │ metrics        │  │   └──────┬────────┘
        └───────┬────────┘  │          │
                │           │          │
                ▼           │          ▼
        ┌────────────────────────┐   ┌──────────┐
        │   Kubernetes Cluster   │   │ Email/Slack│
        │  Pods | Nodes | Apps   │   │ Notifications

## Figure: Architecture of Kubernetes Monitoring and Alerting System using Prometheus, Grafana, and Alertmanager.

## Setup Steps
-  To check the installations:
- docker --version
- kubectl version --client
- minikube version
- helm version
- git --version

## To push into the GitHub
-  git init
- git add .
- git commit 
- git push
