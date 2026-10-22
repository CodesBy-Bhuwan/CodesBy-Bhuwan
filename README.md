<div align="center">
  
# **Hi there** 👋      
  
# BACKEND && DEVOPS ENGINEER   

**Java Backend Developer · CI/CD · Cloud · Automation**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)

[About Me](#-about-me) ·  [Projects](#-featured-projects) · [Workflow](#-my-workflow) · [Contact](#-connect-with-me)

## Welcome to My GitHub!

![Behind Emoji](https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExNnc2Zm84bXB1Zmg5OWFjajVvZGNqeWFwd3M3bWxpbjR4dDRpMGM1ciZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/f8X0VZ33mAsreX9ZHB/giphy.gif)

## Repo Down Here 👇👇👇  

</div>

---

## 👨‍💻 About Me

I'm a **DevOps Engineer and Java Backend Developer** passionate about building robust applications and reliable infrastructure.

- ☕ **Backend Development:** Java, Spring Boot, REST APIs, business logic, and database integration.
- 🔧 **DevOps & Automation:** Docker, Kubernetes, Jenkins, Terraform, Ansible, and CI/CD pipelines.
- ☁️ **Cloud & Infrastructure:** Cloud technologies, infrastructure automation, and reliable application deployments.
- 📊 **Monitoring & Reliability:** Application monitoring, logging, troubleshooting, and performance optimization.
- 🔄 **End-to-End Delivery:** Bridging development and operations—from writing backend code to deploying, monitoring, and scaling applications.

---

## 🚀 Featured Projects

<!-- PROJECT 1: Replace the image URL and repository link with your actual project details. -->

### 🌍 Wanderlust

<div align="center">

[![Wanderlust Project Preview](images/wanderlust-preview.gif)](YOUR_WANDERLUST_REPOSITORY_URL)

**Full-Stack Application · Containerization · CI/CD**

</div>

A full-stack project focused on containerization and deployment automation.

**Technologies:** Docker · Jenkins · Nginx · CI/CD

- 🐳 Containerized application components.
- 🔄 Worked on CI/CD pipeline configuration.
- 🌐 Configured Nginx reverse proxy for application routing.
- 🛠️ Troubleshot deployment and infrastructure issues.

**[📂 View Repository](https://github.com/CodesBy-Bhuwan/wanderlust-DevOps)**

---

### ☁️ DevOps Infrastructure Project

<div align="center">

[![Infrastructure Project Preview](images/devops-preview.gif)](https://github.com/CodesBy-Bhuwan/DevOps-Architecture)

**Infrastructure Automation · Cloud · Monitoring**

</div>

Infrastructure automation and deployment workflows using DevOps tools.

**Technologies:** AWS · Terraform · Ansible · Docker · Prometheus · Grafana

- 🏗️ Infrastructure provisioning and configuration automation.
- 🔄 CI/CD workflow implementation.
- 📊 System metrics monitoring and visualization.

**[📂 View Repository](https://github.com/CodesBy-Bhuwan/DevOps-Architecture)**

---

## 🔄 My Workflow

<div align="center">

## 🚀 DevOps CI/CD Pipeline

```mermaid
flowchart TD
    DEV["👨‍💻 DEVELOPER"]
    GIT["🔀 🐙 GIT / GITHUB"]
    JENKINS["👨‍🔧 JENKINS"]
    BUILD["⚙️ BUILD & TEST"]
    SONAR["🔍 SONARQUBE"]
    NEXUS["📦 NEXUS"]
    DOCKER["🐳 DOCKER / KUBERNETES"]
    AWS["☁️ AWS / SERVERS"]
    APP["⚛️ FRONTEND + 🍃 BACKEND<br/>APPLICATION"]
    MYSQL[("🐬 SQL DATABASE")]
    SQLITE[("🗄️ No-SQL DATABASE")]

    TF["🏗️ TERRAFORM"]
    VAGRANT["🖥️ VAGRANT"]
    INFRA["☁️ AWS / INFRASTRUCTURE"]
    ANSIBLE["🔧 ANSIBLE"]

    PROM["🔥 PROMETHEUS"]
    GRAFANA["📊 GRAFANA"]
    PROMTAIL["📜 PROMTAIL"]
    LOKI["📋 LOKI"]

    DEV --> GIT --> JENKINS
    JENKINS --> BUILD --> SONAR --> NEXUS --> DOCKER --> AWS --> APP
    APP --> MYSQL
    APP --> SQLITE

    JENKINS -.-> TF
    JENKINS -.-> VAGRANT
    TF <--> VAGRANT
    TF --> INFRA
    VAGRANT -.-> INFRA
    INFRA --> ANSIBLE
    ANSIBLE --> AWS

    JENKINS -.-> PROM
    AWS --> PROM
    PROM --> GRAFANA

    AWS --> PROMTAIL
    PROMTAIL --> LOKI
    LOKI --> GRAFANA

    classDef main fill:transparent,stroke:#58a6ff,color:#c9d1d9,stroke-width:2px
    classDef ci fill:transparent,stroke:#f0ad4e,color:#f0ad4e,stroke-width:2px
    classDef infra fill:transparent,stroke:#a371f7,color:#d2a8ff,stroke-width:2px
    classDef monitoring fill:transparent,stroke:#00c896,color:#7ee787,stroke-width:2px
    classDef logging fill:transparent,stroke:#ff4d9d,color:#ff8ac2,stroke-width:2px
    classDef database fill:transparent,stroke:#39c5cf,color:#79e6ef,stroke-width:2px

    class DEV,GIT,APP,DOCKER main
    class JENKINS,BUILD,SONAR,NEXUS ci
    class TF,VAGRANT,INFRA,ANSIBLE,AWS infra
    class PROM,GRAFANA monitoring
    class PROMTAIL,LOKI logging
    class MYSQL,SQLITE database

    linkStyle 0,1,2,3,4,5,6,7,8 stroke:#58a6ff,stroke-width:2px
    linkStyle 9,10,11,12,13,14,15,16 stroke:#a371f7,stroke-width:2px
    linkStyle 17,18,19 stroke:#00c896,stroke-width:2px
    linkStyle 20,21,22 stroke:#ff4d9d,stroke-width:2px
```

</div>

### 🛠️ Technology Stack

- **Application:** Java, Spring Boot, React.js, REST APIs
- **Databases:** MySQL, SQLite
- **CI/CD:** Git, GitHub, Jenkins
- **Quality & Artifacts:** SonarQube, Nexus
- **Infrastructure:** Terraform, Ansible, Vagrant, AWS
- **Deployment:** Docker, Kubernetes
- **Monitoring:** Prometheus, Grafana
- **Logging:** Promtail, Loki



---

## 📅 Currently

- 🔨 **Working on:** CI/CD, containerization, and infrastructure projects.
- 📚 **Learning:** Kubernetes, Terraform, and cloud infrastructure.
- 🎯 **Goal:** Build reliable, secure, and scalable deployment workflows.

---


## 🤝 Connect With Me

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](YOUR_LINKEDIN_URL)
[![Email](https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:YOUR_EMAIL)

</div>

<div align="center">

*Building · Automating · Deploying*

</div>
 
