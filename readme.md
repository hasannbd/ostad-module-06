# Kubernetes Deployment of a Multi-Component Application

This repository contains kubernetes resources to deploy:

- **MongoDB** — A NoSQL database
- **MongoExpress** — A web-based admin interface for MongoDB
- **Ostadserver** — An Express.js backend server
- **OstadUI** — A React frontend application built with Vite

---


## A brief description of each resources

- **1. mongo-deployment.yaml** — Deployment resource for MongoDB
- **2. mongo-service.yaml** — Service resource for MongoDB
- **3. mongo-express-deployment.yaml** — Deployment resource for MongoDB admin UI
- **4. mongo-express-service.yaml** — Service resource for MongoDB admin UI
- **5. ostad-server-deployment.yaml** — Deployment resource for Express.js backend server
- **6. ostad-server-service.yaml** — Service resource for Express.js backend server
- **7. ostad-ui-deployment.yaml** — Deployment resource for React frontend application
- **8. ostad-ui-service.yaml** — Service resource for React frontend application
- **9. ostad-ingress.yaml** — Nginx ingress controller to expose application outside cluster

---


## How it works?

- Pull the repository
- Apply all the k8s resources
- Add necessary host entry (e.g. 127.0.0.1 ui.local, mongo.local)
- Browse ui.local for application fronend and mongo.local for MongoDB admin UI

---

