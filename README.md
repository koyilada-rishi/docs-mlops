# MLOps Architecture — Complete Guide

A complete, production-grade MLOps architecture reference. Every component, every connection, every tool. Built for engineers targeting senior MLOps/ML engineering roles.

## Pages

| Page | Description |
|------|-------------|
| [index.html](index.html) | Main hub — architecture overview, pipeline strip, glossary preview |
| [01-data.html](01-data.html) | Data sources → MinIO → DVC versioning |
| [02-features.html](02-features.html) | Feature engineering — numeric, categorical, temporal, text |
| [03-training.html](03-training.html) | MLflow experiment tracking, eval gates, model registry |
| [04-serving.html](04-serving.html) | FastAPI gateway, KServe InferenceService, canary rollout |
| [05-observability.html](05-observability.html) | Prometheus, Grafana, Evidently drift monitoring |
| [06-cicd.html](06-cicd.html) | GitHub Actions CI/CD, Docker, K3s deploy, retraining loop |
| [07-glossary.html](07-glossary.html) | 50+ term searchable/filterable MLOps glossary |

## Hosting on GitHub Pages

1. Create a new GitHub repo (e.g. `mlops-architecture`)
2. Copy all files from this folder into the repo root
3. Go to Settings → Pages → Source: Deploy from branch → `main` → `/ (root)`
4. Your site will be live at `https://<username>.github.io/mlops-architecture/`

## Home Lab Configuration

All code examples reference:
- **MinIO**: `192.168.1.15:30900` (credentials: minioadmin/minioadmin)
- **MLflow**: `192.168.1.15:30500`
- **K3s cluster**: Proxmox-hosted
- **GitHub repo**: `koyilada-rishi/MLops-prep` branch `mlops-prep-nayak-main`
