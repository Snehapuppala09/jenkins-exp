# Web App For - Jenkins CI/CD Implementation

This project demonstrates a basic Continuous Integration (CI) pipeline using Jenkins for a simple static web application.

The purpose of this project is to understand how Jenkins automates the process of:
- Fetching code from GitHub
- Running pipeline stages
- Archiving build artifacts
- Executing CI workflow successfully
---
## 📁 Project Structure
jenkins-web-app/
├── index.html
├── style.css
├── script.js
└── Jenkinsfile
---
## About The Application
This is a simple static web application built using:
- HTML
- CSS
- JavaScript
When the user clicks a button, a success message is displayed indicating that the Jenkins CI/CD pipeline is working.
---
##  Jenkins Pipeline Overview
The Jenkins pipeline performs the following stages:
1. **Checkout Code**
   - Clones the project from GitHub repository.
2. **Build Stage**
   - Static website → No compilation required.
3. **Archive Artifacts**
   - Archives project files as Jenkins build artifacts.
4. **Post Actions**
   - Displays success or failure messages.
---
## Technologies Used
- Git & GitHub
- Jenkins
- HTML
- CSS
- JavaScript

