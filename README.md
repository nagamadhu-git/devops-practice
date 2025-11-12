# 🚀 DevOps Practice Repository

Welcome to my **DevOps Learning & Practice Repository** 👨‍💻  
This repo contains my **daily practical exercises, commands, outputs, and notes** from my complete **DevOps journey — from Linux to Jenkins (including Terraform)**.  
Each folder contains real-time **commands, outputs, and explanations** recorded during hands-on practice.

---

## 🧩 Repository Structure


devops-practice/
├── linux/ → Linux basics, permissions, processes, networking, scripting
├── git/ → Git & GitHub workflows, branching, merging, SSH setup
├── aws/ → EC2, S3, IAM, CLI, EBS, VPC basics
├── docker/ → Docker installation, images, containers, networking
├── kubernetes/ → Pods, Deployments, Services, Namespaces, EKS
├── terraform/ → IaC, Providers, Variables, Modules, AWS infrastructure setup
├── jenkins/ → Jenkins installation, CI/CD pipelines, automation
├── scripts/ → Shell & automation scripts
└── mini-projects/ → End-to-end DevOps automation projects

---

## 🐧 **Linux**
- File system structure and navigation  
- File & directory management (`ls`, `cd`, `pwd`, `mkdir`, `rm`)  
- File permissions and ownership (`chmod`, `chown`, `umask`)  
- User and group management (`useradd`, `groupadd`, `passwd`)  
- Process management (`ps`, `top`, `kill`, `nice`, `jobs`)  
- System monitoring and logging  
- Networking commands (`ping`, `netstat`, `ss`, `scp`, `ssh`)  
- Bash scripting (variables, loops, conditionals, functions)  
- Automation using cron jobs and scripts  

---

## 🪣 **Git & GitHub**
- Git installation and global config (`git config --global`)  
- Commands: `init`, `clone`, `add`, `commit`, `push`, `pull`, `merge`  
- Branching and merging  
- Working with GitHub repositories  
- Setting up SSH keys for GitHub authentication  
- Daily commit and push routine for practice logs  
- README.md creation for project documentation  

---

## ☁️ **AWS (Amazon Web Services)**
- Launch and connect to EC2 instances  
- Configure security groups and key pairs  
- Manage EBS volumes and snapshots  
- Create and configure S3 buckets  
- Manage IAM users, groups, and roles  
- Install AWS CLI and configure credentials  
- Static website hosting using S3  
- Integrate AWS CLI with shell scripts  

---

## 🐳 **Docker**
- Docker architecture: client, daemon, registry  
- Docker installation and configuration on EC2  
- Commands: `docker run`, `ps`, `images`, `exec`, `logs`, `rm`, `rmi`  
- Building images using Dockerfile  
- Docker volumes and networking  
- Docker Compose setup for multi-container apps  
- Pushing/pulling images to Docker Hub  
- Integrating Docker with AWS (ECR + EC2 deployment)  

---

## ☸️ **Kubernetes (K8s)**
- Kubernetes architecture (Control Plane, Worker Nodes)  
- Cluster setup using Minikube / Amazon EKS  
- Creating and managing Pods, Deployments, ReplicaSets  
- Exposing services (ClusterIP, NodePort, LoadBalancer)  
- ConfigMaps, Secrets, and Environment Variables  
- Namespaces and resource limits  
- Deploying a multi-tier application  
- Monitoring Pods (`kubectl logs`, `describe`, `get events`)  
- Rolling updates and rollbacks  
- Integration with Docker and AWS  

---

## 🧱 **Terraform (Infrastructure as Code)**
- Introduction to IaC and Terraform basics  
- Installation and provider setup (AWS provider)  
- Writing Terraform configuration files (`main.tf`, `variables.tf`, `outputs.tf`)  
- Understanding state files and `.terraform.lock.hcl`  
- Commands: `terraform init`, `plan`, `apply`, `destroy`  
- Using input variables and output values  
- Creating reusable modules  
- Managing AWS resources (EC2, VPC, S3, IAM) using Terraform  
- Remote backend configuration with S3 and DynamoDB  
- Integrating Terraform with Jenkins for automated provisioning  

---

## ⚙️ **Jenkins (CI/CD)**
- Jenkins installation and setup on EC2  
- Creating and managing Jenkins jobs  
- Setting up Jenkins as a service  
- Configuring Git and GitHub integration  
- Setting up Webhooks for automated builds  
- Jenkins pipeline syntax (Declarative & Scripted)  
- Building CI/CD pipelines for Dockerized applications  
- Integration with AWS, Docker, Kubernetes, and Terraform  
- Scheduling jobs with cron  
- Securing Jenkins (credentials, roles, permissions)  

---

## 🧰 **Tools & Technologies Used**

| Category | Tools |
|-----------|-------|
| OS | Amazon Linux 2 / Ubuntu |
| Version Control | Git & GitHub |
| Cloud | AWS |
| Containers | Docker |
| Orchestration | Kubernetes (EKS) |
| IaC | Terraform |
| CI/CD | Jenkins |
| Scripting | Bash, YAML |

---
