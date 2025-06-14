**Project Name: End-to-End CI/CD Pipeline for Java Application**

**Description:**
Designed and implemented a robust CI/CD pipeline to fully automate the software delivery process for a Java application. Configured Jenkins to orchestrate automated builds, comprehensive testing, and controlled deployments. Integrated SonarQube for continuous code quality analysis and proactive security scanning, embedding DevSecOps practices. The application was containerized with Docker and deployed onto a Kubernetes cluster, ensuring portability and scalability. Established GitOps-based deployment with Argo CD to enable seamless, auditable, and automated production releases, significantly enhancing system stability and rapid recovery capabilities. Enabled automated testing and integrated monitoring to rigorously enhance overall application reliability and maintainability.

**Tech Stack & Tools Used:**

Version Control & CI/CD: Git, Jenkins, Webhooks
Build & Code Quality: Maven, SonarQube
Testing & Containerization: JUnit, Docker
Artifact Management: DockerHub
Deployment & Monitoring: Kubernetes, Argo CD

**Pipeline Workflow:**

Code Push & Webhook Trigger → Code pushes to Git automatically trigger the Jenkins pipeline via webhooks.

Build & Analysis → Maven compiles the application code, and SonarQube performs static code analysis and security vulnerability checks, upholding code quality standards.

Testing & Image Creation → Upon successful test execution, a version-controlled Docker image is built and securely pushed to DockerHub, ensuring artifact integrity.

Automated Deployment → Argo CD detects new image updates in the Git-based manifest repository, automatically pulling and deploying the application to the Kubernetes cluster. 
This ensures desired state configuration and facilitates rollbacks.

This pipeline ensures continuous integration, continuous delivery (CI/CD), and GitOps-based deployments to enhance software reliability and efficiency.

***PROJECT ARCHITECTURE***
![Project - Architecture](https://github.com/user-attachments/assets/7db647b7-0524-4af0-ba5b-155b5a1fe38d)


**JENKINS - Continuous Integration Stage :-**
![Screenshot 2025-02-20 131616](https://github.com/user-attachments/assets/c4b35ad6-e740-4fe1-af84-09a23e731b4f)


**SONARQUBE - CODE QUALITY PASSED :-**
![Screenshot 2025-02-20 131505](https://github.com/user-attachments/assets/47b69e59-5306-4484-a7fb-235a69846693)


**ArgoCD - Continuous Deployment Stage :-**
![Screenshot 2025-02-20 134952](https://github.com/user-attachments/assets/dd2f1719-792d-444f-893a-0989a1431ceb)

