# 🚀 K8s Kind Voting App

A comprehensive guide for setting up a **Kubernetes cluster using Kind on an AWS EC2 instance**, installing and configuring **Argo CD**, and deploying the **Kubernetes Voting Application** using the **GitOps** workflow.

---

## 📖 Overview

This project demonstrates how to:

- ☁️ Launch an AWS EC2 instance
- 🐳 Install Docker and Kind
- ☸️ Create a Kubernetes cluster using Kind
- ⚙️ Install and configure kubectl
- 📊 Deploy the Kubernetes Dashboard
- 🚀 Install and configure Argo CD
- 🔄 Connect and manage the Kubernetes cluster using Argo CD
- 📦 Deploy the Voting Application using GitOps

---

## 🛠️ Tech Stack

- AWS EC2
- Ubuntu Linux
- Docker
- Kubernetes (Kind)
- kubectl
- Argo CD
- Git & GitHub
- YAML

---

## 📂 Project Structure

```text
.
├── commands.md
├── config.yml
├── dashboard.yml
├── install_kind.sh
├── kubectl_install.sh
├── k8s-specifications/
├── vote/
├── result/
├── worker/
├── seed-data/
├── Screenshot/
└── README.md
```

---

## 🏗️ Architecture Diagram

![Architecture Diagram](https://github.com/rushikeshsatwadhar/k8s-kind-voting-app/blob/main/Screenshot/Architecture%20Diagram.png?raw=true)

---

## 🚀 Argo CD Dashboard

![Argo CD Dashboard](https://github.com/rushikeshsatwadhar/k8s-kind-voting-app/blob/main/Screenshot/Argo%20CD%20Dashboard.png?raw=true)

---

## 🗳️ Voting Application

![Voting Application](https://github.com/rushikeshsatwadhar/k8s-kind-voting-app/blob/main/Screenshot/Voting%20Application.png?raw=true)

---

## 📊 Result Application

![Result Application](https://github.com/rushikeshsatwadhar/k8s-kind-voting-app/blob/main/Screenshot/Result%20Application.png?raw=true)

---

## 📁 Kubernetes Components

- Vote Application
- Result Application
- Worker Service
- Redis
- PostgreSQL
- Kubernetes Deployments
- Kubernetes Services
- Persistent Storage

---

## 🚀 Deployment Workflow

```text
Developer
      │
      ▼
 GitHub Repository
      │
      ▼
    Argo CD
      │
      ▼
 Kubernetes Cluster (Kind)
      │
      ├── Vote App
      ├── Result App
      ├── Worker
      ├── Redis
      └── PostgreSQL
      │
      ▼
 Docker Engine
      │
      ▼
 AWS EC2 Instance
```

---

## ⭐ Features

- Kubernetes cluster using Kind
- GitOps deployment with Argo CD
- Automated synchronization
- Kubernetes Dashboard
- Voting application deployment
- Multi-container application
- Easy to reproduce
- Beginner-friendly DevOps project

---

⭐ **If you found this project helpful, please consider giving it a star!**
