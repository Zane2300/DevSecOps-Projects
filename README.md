# 🛡️ DevSecOps & Cloud Engineering Labs

[![CI/CD](https://img.shields.io/badge/CI%2FCD-GitHub%20Actions-2088FF)]()
[![Security](https://img.shields.io/badge/Security-Trivy-orange)]()
[![Containers](https://img.shields.io/badge/Containers-Docker-blue)]()
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

> A collection of hands-on laboratories and projects focused on **DevSecOps**, **Automation**, **Infrastructure as Code**, and **Cloud Security**.

This repository documents my journey implementing security-first practices in modern DevOps pipelines. Each folder represents a standalone project designed to solve real-world infrastructure and security challenges.

---

## 🗂️ Project Directory

| Project | Description | Tech Stack |
|:---|:---|:---|
| **[📂 1. The Shield Pipeline](./1.-The_Shield_Pipeline)** | **Shift-Left Security:** A CI/CD pipeline that builds Docker images and automatically blocks deployment if Critical CVEs are detected using **Trivy**. | `GitHub Actions` `Docker` `Trivy` `Python` |
| 🚧 *Project 2* | *Coming soon: GitOps / Infrastructure as Code...* | *Pending* |

---

## 🛠️ Global Tech Stack

The projects in this repository utilize a variety of modern tools and technologies:

* **CI/CD & Orchestration:** GitHub Actions
* **Security & Compliance:** Aqua Security Trivy
* **Containerization:** Docker, Docker Compose
* **Scripting & Backend:** Python, Bash
* **Infrastructure:** *Coming soon (Terraform/K8s)*

---

## 🚀 How to Navigate

Each project is **self-contained**. To explore a specific lab:

1. Click on the project name in the [Directory](#-project-directory) table above.
2. Read the project-specific `README.md` for detailed architecture, installation steps, and evidence of execution.
3. Check the `.github/workflows` folder (in the root) to see the automation logic for that specific path.

---

## 🤝 Contribution & Feedback

These projects are created for educational and portfolio purposes. Feedback, pull requests, or suggestions to improve security practices are always welcome!

---

## 📄 License

This repository is published under the **MIT License**. See the [`LICENSE`](LICENSE) file for details.

---

### ✍️ Author

**Alex Rosell**
*DevSecOps and Cibersecurity*