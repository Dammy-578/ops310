# Azure PaaS Automation – OPS310 Project 2

**Course:** OPS310 – Cloud Platform Management  
**Date:** December 2024  
**Institution:** Seneca Polytechnic

---

## ☁️ Overview
This project simulates a real-world Azure Platform-as-a-Service (PaaS) deployment. A Logic App monitors an Azure Storage container for new files, processes them automatically, and sends out notification emails. Optionally, a static front-end was added using Azure Static Web Apps and GitHub integration.

---

## 🧠 Key Components
- **Azure Storage Account:**  
  Two containers: `incoming-files` and `processed-files`

- **Azure Logic App:**  
  - Triggered on new blob upload  
  - Adds `processed-` prefix to file name  
  - Moves file to `processed-files`  
  - Sends email notification to user

- **Optional Static Web App:**  
  - Basic front-end UI for users to upload files  
  - Connected via GitHub and auto-deploys changes

---

## 🔐 Features Implemented
- Automated file detection and handling in Logic App  
- Email automation using personal Microsoft 365 account  
- Dynamic file renaming using built-in Azure expressions  
- GitHub-connected static site (optional)  
- Azure Storage CORS configuration (bonus)

---

## 🧠 Skills Demonstrated
- Azure Logic Apps  
- Azure Storage Automation  
- GitHub + Azure Integration  

---

## 📂 Notes
This project was submitted in video format and validated using test runs. All automation steps were demonstrated live. Screenshots and sample files may be added later.

---

## ✅ Project Status
- ✔️ Logic App automation tested and complete  
- ✔️ Notification emails received  
- ✔️ GitHub-integrated WebApp deployed (optional)
