# k8s training

This repository was created for kubernetes practice only. 

## App

App included: 
- php:7.4-fpm container with simple script
- nginx server

## Structure

Directors: 
- app-deployment (approach with all container in the one deployment)
- pods (approach with container separated by pods)
- k8s-app (dev proper approach with skaffold. It needs skaffold and minikube)

## Useful command
- `Skaffold init` initializes skaffold project  (in this project should be use from k8s-app dir)
- `Skaffold dev` starts skaffold project (as above)
- `eval $(minikube docker-env)` use minikube docker daemon
