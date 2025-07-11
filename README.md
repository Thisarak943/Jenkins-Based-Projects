Jenkins-Based DevOps Projects
-----------------------------

This repository contains a series of projects centered around Jenkins — an open-source automation server widely used for continuous integration and continuous delivery (CI/CD). These projects showcase how Jenkins can be used to automate software build, test, and deployment pipelines using various integrations and tools.

Each project includes detailed documentation, pipeline scripts (both Freestyle and Declarative), and setup guides to demonstrate how Jenkins is used in real-world DevOps scenarios.

Project Highlights:
- Installing and configuring Jenkins on different environments (RHEL, Ubuntu, Docker)
- Creating Freestyle and Declarative Jenkins pipelines for CI/CD
- Integrating Jenkins with GitHub for automated build triggers on code push
- Docker integration to build and push container images from Jenkins
- Deploying applications to Kubernetes clusters directly from Jenkins
- Using Jenkins with AWS (e.g., deploying to EC2, EKS, S3)
- Creating multi-stage pipelines with stages for build, test, lint, deploy, and notifications
- Using Jenkins plugins for email notifications, Git integration, Docker, and pipeline visualization

What I Learned:
- Jenkins installation, configuration, and user management
- Writing and managing Jenkinsfiles using Declarative syntax
- Automating end-to-end CI/CD processes from GitHub to deployment
- Handling credentials and secure variables in Jenkins
- Triggering jobs via Git webhooks and polling mechanisms
- Monitoring Jenkins jobs and analyzing console output for debugging
- Best practices in structuring Jenkins pipelines for scalability and reusability

Tools & Technologies Used:
- Jenkins
- GitHub
- Docker & Docker Hub
- Kubernetes (Minikube, EKS)
- AWS (EC2, S3, EKS)
- Linux (Ubuntu, RHEL)
- Shell Scripting & YAML
- Jenkins Plugins (Docker, Git, Blue Ocean, Email, Credentials, etc.)

This repository reflects my hands-on experience with Jenkins and its role in automating software delivery pipelines. It also highlights how Jenkins fits into the broader DevOps toolchain when working with cloud platforms, containers, and Kubernetes.

Please refer to individual project folders for detailed steps, configurations, and Jenkinsfile scripts.
