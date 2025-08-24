🚀 DevSecOps Pipeline for Node.js Application

This repository demonstrates a DevSecOps implementation using GitHub Actions with:

SonarQube → Code quality & security analysis

Snyk → Open-source dependency vulnerability scanning

OWASP ZAP → Dynamic Application Security Testing (DAST)

GitHub Issues Integration → Automatic vulnerability reporting and job failure handling

📌 Pipeline Overview

The pipeline is designed to shift security left and integrate it seamlessly into the CI/CD process.

🔹 Workflow Steps:

Checkout Code – Pulls source code from the repository.

Build & Test – Installs dependencies and runs Node.js tests.

SonarQube Scan – Analyzes code for quality, bugs, and vulnerabilities.

Snyk Scan – Detects security issues in dependencies.

OWASP ZAP Scan – Performs DAST on running application.

Fail on Vulnerabilities – If issues are found, the job fails.

GitHub Issues Automation – A detailed report is automatically created in GitHub Issues for tracking and remediation.

⚡ Architecture Diagram

<img width="1536" height="1024" alt="pipeline" src="https://github.com/user-attachments/assets/0a549e68-45a2-4a1b-8202-38087d184f62" />


🔐 Secrets Configuration

Before running the workflow, configure the following repository secrets in GitHub:

SONAR_TOKEN – Authentication token for SonarQube

SONAR_HOST_URL – SonarQube server URL

SNYK_TOKEN – Authentication token for Snyk

✅ Key Benefits

Automated code quality & security enforcement

Immediate feedback to developers via pipeline job failure

Seamless GitHub Issues tracking for vulnerabilities

Scalable and repeatable DevSecOps workflow

📢 Contributions

Feel free to fork this repo, raise PRs, or suggest improvements. Security is a journey – let’s build better pipelines together!

🔥 With this, you now have a production-ready DevSecOps pipeline that you can showcase directly in your GitHub repo.
