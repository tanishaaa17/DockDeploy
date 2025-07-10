# DockDeploy 🐳

A simple yet effective project to demonstrate modern CI/CD workflows using **Docker** and **GitHub Actions**.

This repository contains a minimal portfolio website that is containerized and automatically deployed to the cloud on every push to `main`.

---

## 🚀 Features

- 🐳 Docker-based containerization
- 🔁 GitHub Actions for continuous integration
- ☁️ One-click deploy to Railway / Render / GCP
- 💡 Great starting point for DevOps learners

---

## 💻 Tech Stack

- HTML / CSS / JS (Frontend)
- Node.js (API server - optional)
- Docker
- GitHub Actions
- Railway / Render / GCP

---

## 🧑‍🔧 Setup Instructions

```bash
# Clone the repo
git clone https://github.com/yourusername/DockDeploy.git
cd DockDeploy

# Build the Docker image
docker build -t dockdeploy .

# Run locally
docker run -p 3000:3000 dockdeploy

```

## 🛠 CI/CD Pipeline
GitHub Actions workflow:

```yaml
Builds the container

Runs simple lint/test steps

Deploys to your preferred cloud provider

on: push
jobs:
  build-deploy:
    ...
```
---
## 🌐 Live Demo

```yaml
🔗 https://dockdeploy.onrender.com (example)
```

