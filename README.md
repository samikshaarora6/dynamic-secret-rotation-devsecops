# 🚀 Dynamic Secret Rotation for DevSecOps Pipelines

Welcome to the **Dynamic Secret Rotation** project!  
This project demonstrates how to securely **store**, **rotate**, and **inject secrets** into DevOps pipelines using **HashiCorp Vault**, **CI/CD pipelines** (like GitHub Actions / Jenkins), and modern security best practices.


---

## 📚 Project Overview

🔒 **Problem**:  
Hardcoding secrets in code or CI/CD pipelines can lead to security breaches.

⚙️ **Solution**:  
Use **Vault** to dynamically generate and rotate secrets, inject them securely into pipelines, and avoid exposing sensitive credentials.

---

## 🛠️ Tech Stack

- **HashiCorp Vault** (Secrets Management)
- **Docker** (for local Vault setup)
- **Python / Bash** (for automation scripts)
- **GitHub Actions / Jenkins** (CI/CD)
- **Kubernetes** (optional - future enhancement)

---

## 🏗️ Project Structure

```bash
dynamic-secret-rotation-devsecops/
├── vault-setup/          # Vault setup scripts and instructions
├── scripts/              # Scripts to create/rotate secrets
├── cicd-pipeline/        # CI/CD pipelines for dynamic secret injection
├── kubernetes/           # K8s manifests (optional for K8s secrets injection)
├── architecture-diagram/ # Architecture and flow diagrams
├── README.md             # Project documentation
└── .gitignore            # Ignored files
