# pipelines
## Azure Pipeline v1

An Azure DevOps multi-stage YAML pipeline for deploying infrastructure across **Test**, **QA**, and **Production** environments using Infrastructure-as-Code (IaC) practices.
---
## 📌 Key Features

- 🧪 **Test Stage**: Deploys from any branch *except* `main`
- 🔎 **QA Stage**: Deploys from the `main` branch
- 🚀 **Production Stage**: Deploys *only after* successful QA deployment on the `main` branch
- 📄 Environment-specific variable templates
- 🔁 Reusable job template for infrastructure deployment
- 🐧 Runs on `ubuntu-latest` agent
