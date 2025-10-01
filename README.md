# Spring Boot on Kubernetes with Docker and Minikube

This project demonstrates how to **containerize a Spring Boot application** using Docker and deploy it on a **local Kubernetes cluster** using Minikube for learning purposes

Original guide: [Deploy Spring Boot on Kubernetes](https://bell-sw.com/blog/how-to-deploy-spring-boot-application-on-kubernetes/#mcetoc_1he7nfcuc6c)

---

## Workflow Overview

Below is the workflow of building, containerizing, and deploying your application:

| Concept                | What it means                                                                 |
|------------------------|-------------------------------------------------------------------------------|
| **Docker image**       | A template containing your app and runtime.                                    |
| **Docker container**   | A running instance of the image.                                              |
| **Push to Docker Hub** | Allows Kubernetes to pull your image from a public/private registry.         |
| **Minikube**           | Local single-node Kubernetes cluster for development/testing.                 |
| **Kubernetes Deployment** | Defines how many replicas of your app to run and which image to use.       |
| **Kubernetes Service** | Exposes your app to the network and routes traffic to Pods.                   |

---