**Project Name: End-to-End CI/CD Pipeline for Java Application**

**Description:**
Designed and implemented a CI/CD pipeline to automate the software delivery process for a Java application. Configured Jenkins to manage builds, testing, and deployments. Integrated SonarQube for code quality analysis and security scanning. Packaged and deployed the application using Docker and Kubernetes. Established GitOps-based deployment with Argo CD to ensure seamless production releases. Enabled automated testing and monitoring to enhance reliability and maintainability.

**Tech Stack & Tools Used:**

Version Control & CI/CD: Git, Jenkins, Webhooks
Build & Code Quality: Maven, SonarQube
Testing & Containerization: JUnit, Docker
Artifact Management: DockerHub
Deployment & Monitoring: Kubernetes, Argo CD, 
**Pipeline Workflow:**

Code Push & Webhook Trigger → Developers push code to Git, triggering Jenkins.
Build & Analysis → Maven compiles the code, and SonarQube performs static code analysis.
Testing & Image Creation → If tests pass, a Docker image is built and pushed to DockerHub.
Automated Deployment → ArgoCD detects image updates in the manifest repo and deploys to Kubernetes.
This pipeline ensures continuous integration, continuous delivery (CI/CD), and GitOps-based deployments to enhance software reliability and efficiency.

![Project - Architecture](https://github.com/user-attachments/assets/7db647b7-0524-4af0-ba5b-155b5a1fe38d)
"C:\Users\rajachenthil\Pictures\Screenshots\Screenshot 2025-02-20 131616.png"
"C:\Users\rajachenthil\Pictures\Screenshots\Screenshot 2025-02-20 131505.png"
"C:\Users\rajachenthil\Pictures\Screenshots\Screenshot 2025-02-20 131321.png"
