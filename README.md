# Cloud Resume Challenge (Azure Edition)

This project is my implementation of the **Cloud Resume Challenge** on Microsoft Azure.  
It demonstrates cloud, DevOps, and automation skills by deploying a static resume website with a serverless backend, database, CI/CD pipeline, and monitoring.

---

## 📌 Architecture (initial plan)
User → Azure Static Web App → Azure Function → Cosmos DB
↑
GitHub Actions CI/CD + Terraform

yaml
Copy code

---

## 📂 Project Structure
- `/frontend` → Resume website (HTML/CSS/JS)
- `/backend` → Azure Function (visitor counter)
- `/infra` → Terraform IaC for Azure resources
- `/.github/workflows` → GitHub Actions pipelines
- `README.md` → Documentation

---

## 🚀 Features
- Personal resume site hosted in Azure.
- Live visitor counter with Cosmos DB.
- Automated deployments with GitHub Actions.
- Infrastructure defined using Terraform.
- Monitoring and alerts via Azure Monitor.

---

## 🛠️ Skills Demonstrated
- Azure (Functions, Static Web Apps, Cosmos DB, Monitor)
- Terraform (Infrastructure as Code)
- GitHub Actions (CI/CD)
- Monitoring & Logging
