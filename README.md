<div align="center">

# 📓 Jupyter Notebook on Render

### A **premium, ready-to-deploy** Jupyter Notebook Docker image — one-click deploy on **Render.com**

<br/>

<img src="https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter&logoColor=white" />
<img src="https://img.shields.io/badge/Docker-Container-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
<img src="https://img.shields.io/badge/Render-Deploy-46E3B7?style=for-the-badge&logo=render&logoColor=white" />
<img src="https://img.shields.io/badge/Python-3.x-3776AB?style=for-the-badge&logo=python&logoColor=white" />

<br/><br/>

> ⚡ **Deploy a full Jupyter Notebook environment in under 2 minutes** — no local setup required.
> 🛡️ Token-protected • 🌐 Public URL • 🐳 Dockerized • 🆓 Free plan ready

<br/>

**👨‍💻 Developer:** [`@SHADOW_HEX_REAL`](https://t.me/SHADOW_HEX_REAL)

</div>

---

## 🌟 Overview

This repository contains a **production-grade Dockerfile** and **Render blueprint (`render.yaml`)** to spin up a secure, cloud-hosted **Jupyter Notebook** environment on [Render.com](https://render.com).

Built on top of the official **`quay.io/jupyter/base-notebook`** image, this setup gives you a powerful Python playground with all essential CLI tools pre-installed — perfect for **students, data scientists, developers, and tinkerers**.

---

## ✨ Features

| 🎯 Feature | 📝 Description |
|-----------|----------------|
| 📓 **Official Jupyter Base** | Uses the latest `jupyter/base-notebook` for maximum compatibility |
| 🔐 **Token-Protected Access** | Secured via `JUPYTER_TOKEN` environment variable |
| 🌐 **Public Remote Access** | Configured with `allow_remote_access=True` and `0.0.0.0` binding |
| 🐳 **Fully Dockerized** | Reproducible builds, zero-config deploy |
| ⚡ **One-Click Render Deploy** | `render.yaml` blueprint included |
| 🧰 **Pre-installed Toolkit** | `git`, `curl`, `wget`, `unzip`, `nano`, `zip`, `ca-certificates` |
| 💾 **Persistent Work Dir** | Notebooks stored in `/home/jovyan/work` |
| 🆓 **Free Plan Compatible** | Runs perfectly on Render's free tier |
| 🎨 **Premium UX** | Clean, minimal, focused — just open and code |

---

## 📂 Project Structure
