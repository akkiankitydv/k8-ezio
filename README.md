# K8-Ezio

This project contains a Flask backend and Express frontend with K8s deployment files.

## Structure

- **backend/**: Flask application
- **frontend/**: Express.js application
- **k8s/**: K8s manifests for deployment
- **Dockerfiles**: inside frontend and backend folders

## Usage

1. Build Docker images, tagged and push to Docker Hub
2. Deploy using:
   kubectl apply -f backend/k8s/
   kubectl apply -f frontend/k8s/


