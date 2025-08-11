# Task 5 - Minikube Kubernetes Deployment

This repo contains YAMLs and screenshots for Task 5: Build a Kubernetes cluster locally with Minikube.

## How I ran it
1. minikube start --driver=docker
2. kubectl apply -f deployment.yaml
3. kubectl apply -f service.yaml
4. minikube service abc --url

## Deliverables
- deployment.yaml
- service.yaml
- screenshots showing pods, service, describe and logs.
