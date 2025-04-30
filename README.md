# 🧠 ML Model Deployment with Kubernetes

This project demonstrates how to containerize and deploy a simple machine learning model using Docker, Kubernetes (Minikube), and FastAPI. The model is a Random Forest classifier trained on the Iris dataset.

---

## 📦 Project Structure
k8s-ml-app/ ├── model_service/ │ ├── model.pkl │ ├── main.py │ ├── Dockerfile │ └── requirements.txt ├── k8s/ │ ├── deployment.yaml │ └── service.yaml ├── .gitignore └── README.md
