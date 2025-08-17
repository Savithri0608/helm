# 🛒 Best-Commerce Helm Project  

A **Kubernetes Helm-based deployment** for a sample **e-commerce platform**, built using two microservices:  
- **Payments Service** 💳  
- **Shipping Service** 🚚  

This project demonstrates **Helm templating, environment-specific configs, and scalable microservice deployments** on Kubernetes.  

---

## ⚡ Tech Stack  
- **Kubernetes** (EKS/Minikube)  
- **Helm** (Charts & templating)  
- **Docker** (Containerization)  

---

## 🚀 Deployment (Quick Start)  

```bash
# Clone the repo
git clone https://github.com/<your-username>/best-commerce-helm.git
cd best-commerce-helm

# Deploy Payments
helm install payments ./charts/payments -f charts/payments/values.yaml  

# Deploy Shipping
helm install shipping ./charts/shipping -f charts/shipping/values.yaml  
