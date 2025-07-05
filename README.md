
## **Ansible AWS EC2 Jenkins Deployment**

### 🔧 Overview

This project automates the deployment of a **Jenkins CI/CD server** on an **AWS EC2 instance** using **Ansible**, with a dynamic inventory powered by the `aws_ec2` plugin. It follows Infrastructure as Code (IaC) principles, ensuring repeatability, modularity, and scalability.



---

### 🔑 Features

* ✅ **Dynamic AWS EC2 inventory** using the `aws_ec2` Ansible plugin.
* 🐳 **Docker-based Jenkins deployment**.
* 🔐 Automatically retrieves and displays **Jenkins initial admin password**.
* ♻️ Uses **Ansible roles** for modular, maintainable code.
* 🚀 Quick setup: Jenkins is ready to use via a browser on port `8080`.

---

### 🚀 How to Run



1. **Install required Ansible collections:**

   ```bash
   ansible-galaxy collection install amazon.aws community.docker
   ```

2. **Run the playbook:**

   ```bash
   ansible-playbook  deploy-jenkins.yaml
   ```

3. **Access Jenkins:**
   Open your browser and navigate to `http://<EC2-Public-IP>:8080`



---

### 🛠 Technologies Used

* **Ansible**
* **AWS EC2**
* **Docker**
* **Jenkins**
* **Bash / YAML**

---

