# Kubernetes Web Application Deployment

A web application containerized using **Docker** and deployed on a **Kubernetes cluster**. The project demonstrates the process of packaging an application into a Docker image, pushing the image to **DockerHub**, and deploying it to Kubernetes using deployment and service configurations.

## 🚀 Tech Stack

* HTML / CSS / JavaScript
* Docker
* DockerHub
* Kubernetes
* Linux / Ubuntu

## 🔄 Deployment Workflow

```text
Web Application
       ↓
   Dockerfile
       ↓
 Docker Image
       ↓
   DockerHub
       ↓
 Kubernetes Cluster
       ↓
 Deployed Application
```

## 📋 Challenge

The challenge required:

1. Creating a web application and placing the application files inside a `web-app` directory.
2. Creating a Docker image using a `Dockerfile`.
3. Pushing the Docker image to DockerHub.
4. Deploying the application on a Kubernetes cluster provided through KillerKoda.

## 🐳 Docker

### Build the Docker Image

```bash
docker build -t <dockerhub-username>/<image-name>:latest .
```

### Login to DockerHub

```bash
docker login
```

### Push the Image

```bash
docker push <dockerhub-username>/<image-name>:latest
```

## ☸️ Kubernetes

### Deploy the Application

```bash
kubectl apply -f k8s/deployment.yaml
kubectl apply -f k8s/service.yaml
```

### Check the Deployment

```bash
kubectl get pods
kubectl get deployments
kubectl get services
```

## 📁 Project Structure

```text
kubernetes-web-app-deployment/
│
├── web-app/
│   ├── index.html
│   ├── style.css
│   └── ...
│
├── Dockerfile
│
├── k8s/
│   ├── deployment.yaml
│   └── service.yaml
│
└── README.md
```

## 📸 Screenshots

Screenshots demonstrating the application, Docker image, and Kubernetes deployment can be added to the `screenshots/` directory.

## 💡 What I Learned

This challenge provided hands-on experience with:

* Containerizing web applications with Docker
* Building and tagging Docker images
* Publishing images to DockerHub
* Writing Kubernetes deployment and service configurations
* Deploying applications to a Kubernetes cluster
* Managing applications through the Linux command line

## 🏆 Achievement

🥉 **3rd Position — KillerKoda DevOps Challenge at SD HUB**
⏱️ **Completed in 34 minutes**

---

**Built as part of a KillerKoda DevOps Challenge 🚀**
