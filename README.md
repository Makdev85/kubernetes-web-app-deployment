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
📋 Challenge

The challenge required:

Creating a web application and placing the application files inside a web-app directory.
Creating a Docker image using a Dockerfile.
Pushing the Docker image to DockerHub.
Deploying the application on a Kubernetes cluster provided through KillerKoda.
Challenge Brief

The original challenge instructions provided during the KillerKoda DevOps Challenge.

🐳 Docker
Build the Docker Image
docker build -t <dockerhub-username>/<image-name>:latest .
Login to DockerHub
docker login
Push the Image
docker push <dockerhub-username>/<image-name>:latest
☸️ Kubernetes
Deploy the Application
kubectl apply -f k8s/deployment.yaml
kubectl apply -f k8s/service.yaml
Check the Deployment
kubectl get pods
kubectl get deployments
kubectl get services
🧪 KillerKoda Deployment

The application was deployed and tested on the Kubernetes cluster provided through the KillerKoda environment.

The Kubernetes deployment was successfully created, and the application was exposed using a NodePort service.

The deployment was verified using Kubernetes commands such as:

kubectl get pods
kubectl get deployments
kubectl get services

This confirmed that the application pod was running successfully and that the Kubernetes service was correctly exposing the application.

📁 Project Structure
kubernetes-web-app-deployment/
│
├── web-app/
│   ├── index.html
│   ├── style.css
│   └── ...
│
├── screenshots/
│   ├── application-running.png
│   ├── challenge.png
│   ├── kubernetes-deployment.png
│   └── result.png
│
├── Dockerfile
│
├── k8s/
│   ├── deployment.yaml
│   └── service.yaml
│
└── README.md
🌐 Application Running

After building the Docker image, pushing it to DockerHub, and deploying it to Kubernetes, the web application was successfully accessed through the exposed Kubernetes service.

The successful deployment demonstrates the complete workflow from application development to containerization and Kubernetes deployment.

💡 What I Learned

This challenge provided hands-on experience with:

Containerizing web applications with Docker
Building and tagging Docker images
Publishing images to DockerHub
Writing Kubernetes deployment and service configurations
Deploying applications to a Kubernetes cluster
Exposing applications using Kubernetes Services
Managing applications through the Linux command line
🏆 Achievement

🥉 3rd Position — KillerKoda DevOps Challenge at SD HUB

⏱️ Completed in 34 minutes

The challenge was completed within 34 minutes, resulting in a 3rd-place finish.

🏅 Final Result

The final result announced at the end of the challenge.
