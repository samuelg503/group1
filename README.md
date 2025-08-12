# TELSAL | Google Cloud Tech Pre-Training Capstone Project

This repository contains the final deliverables for the TELSAL capstone project, designed to demonstrate the skills acquired during the Google Cloud Tech Pre-Training program. The objective was to launch a scalable, reliable, and globally accessible static website for our client, **Travel Europe LLC**.

---

## 🚀 Project Scope & Objective

The primary goal was to take a 'green field' approach to deploy a new teaser website on Google Cloud Platform (GCP). The solution needed to be highly scalable to attract potential customers from the Americas and leverage containerized applications for automated lifecycle management.

The key requirements were:
* Containerize the existing static website build using **Docker**.
* Store the container image in **Google Artifact Registry**.
* Deploy the container to a managed orchestration service. We chose **Google Kubernetes Engine (GKE)** for its power and scalability.
* Expose the website to the public internet through a **Google Cloud Global External HTTPS Load Balancer** to ensure low latency and high availability for users worldwide.

---

## 🛠️ Technology Stack

* **Cloud Platform**: Google Cloud Platform (GCP)
* **Containerization**: Docker
* **Container Registry**: Google Artifact Registry
* **Orchestration**: Google Kubernetes Engine (GKE)
* **Networking**: Google Cloud Load Balancing
* **Version Control**: Git & GitHub



---

##  Sprint-Based Execution

The project was executed over three, one-hour sprints following a trunk-based development model.

### Sprint 1: Containerization & Registry
* **Goal**: Create a portable Docker image of the website and store it in a centralized, secure location.
* **Outcome**: A `Dockerfile` was created, the website was successfully containerized, tested locally, and the final image was pushed to a dedicated repository in Google Artifact Registry.

### Sprint 2: Deployment & Public Access
* **Goal**: Deploy the container on GCP and make the website publicly accessible.
* **Outcome**: A GKE cluster was provisioned. Kubernetes `Deployment` and `Service` manifests were created to run the container. The application was exposed securely using a Google Cloud Load Balancer, making the website available via a public IP address.

### Sprint 3: Finalization & Documentation
* **Goal**: Complete project documentation and ensure the final code is available.
* **Outcome**: This public GitHub repository was created. All infrastructure code, Kubernetes manifests, and documentation were pushed to the `main` branch. This `README.md` file and the `git.log` were finalized and committed.

---

## acknowledgment

The base static website code used for this project was provided by **GNiruthian**.
* **Original Repository**: [https://github.com/GNiruthian/Europe-Travel-Website-html-css-js](https://github.com/GNiruthian/Europe-Travel-Website-html-css-js)
