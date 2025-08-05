# 🐳 Custom Dockerfile – Hello NGINX

This task builds a custom Docker image using a simple `Dockerfile` and serves a custom HTML page using NGINX.

## 📁 Files

- `index.html` – Custom homepage

- `Dockerfile` – Uses NGINX base image and replaces the default index

## 🏗️ Build

```bash

docker build -t my-nginx-custom .
