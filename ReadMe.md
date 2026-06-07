# 🚀 Microsoft Fabric CI/CD Pipeline – Sales Project

## 📌 Project Overview
This project demonstrates an end-to-end implementation of Continuous Integration (CI) and Continuous Deployment (CD) using Microsoft Fabric and Azure DevOps. The solution is designed to manage and deploy data engineering components such as Lakehouse, PySpark Notebooks, and Semantic Models across multiple environments including Dev, Test, and Production.

## 🛠️ Technologies Used

- Microsoft Fabric
- Azure DevOps (Repos, Branching, Pull Requests)
- Git (Version Control)
- PySpark (Data Transformation)
- GitHub (Portfolio Showcase)

## 🏗️ Architecture Overview
Azure DevOps Repository acts as the central version control system connected to the Fabric workspace. Development happens in Dev workspace and changes are promoted step-by-step to Test and Production using Deployment Pipelines.

Flow:
Dev Workspace → Azure DevOps Repo → Pull Request → Test Workspace → Pull Request → Production Workspace

## 🔄 CI/CD Implementation

### ✅ Continuous Integration (CI)

- Created **Sales_Dev_WS workspace** in Microsoft Fabric
- Added:
  - Lakehouse
  - PySpark Notebook
  - Semantic Model
- Developed transformation logic using PySpark
- Connected Fabric workspace to Azure DevOps repository
- Committed and pushed changes to Git repository
- Used branching strategy for controlled development

### ✅ Continuous Deployment (CD)
- Created multiple environments:
  - Dev Workspace (Sales_Dev_WS)
  - Test Workspace
  - Production Workspace
- Implemented Deployment Pipeline in Microsoft Fabric
- Promoted changes across environments:
  - Dev → Test → Production
- Used Pull Requests (PR) to control and approve deployments
- Ensured only validated changes move forward

## ⚙️ Implementation Steps
1. Created Fabric workspace: Sales_Dev_WS
2. Added data engineering components (Lakehouse, Notebook, Semantic Model)
3. Wrote PySpark code for data processing
4. Connected workspace to Azure DevOps repo
5. Pushed all changes into Git repository
6. Created new branches for development control
7. Configured Deployment Pipeline for Dev, Test, and Production
8. Used Pull Requests to promote code between environments
9. Ensured version-controlled deployment
10. Cloned DevOps repository to local machine
11. Uploaded project to GitHub for HR and portfolio showcase

## 📂 Repository Structure
Items/
 ├── sales_LH4500.Lakehouse/
 ├── Sales_notebook.Notebook/
 ├── Sales_semantic4500.Semantic/
README.md

## 🔍 Key Features
- End-to-End CI/CD Implementation in Microsoft Fabric
- Integration with Azure DevOps for version control
- Multi-environment deployment (Dev, Test, Production)
- Pull Request based controlled releases
- Git-based change tracking and history management
- Scalable and production-ready design

## 🎯 Business Value
- Enables safe and controlled deployments
- Improves collaboration using Git
- Reduces manual deployment errors
- Provides structured release management
- Enhances data engineering lifecycle

## ✅ Outcome
Successfully implemented CI/CD pipeline in Microsoft Fabric using Azure DevOps. Achieved version control, structured deployment, and environment-based promotion of data engineering artifacts.

## 📸 Screenshots
(Add screenshots here for better visibility)
- Fabric Workspace
- Deployment Pipeline
- Azure DevOps Pull Requests
- Monitor Activities

## 👨‍💻 Author
Syed. 
Data Analyst | Microsoft Fabric | SQL | PySpark 

**Thank YOU 💐💐**
