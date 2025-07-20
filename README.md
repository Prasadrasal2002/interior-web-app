# 🏠 InteriorDesignPro

# 📌 Project Overview

This is a modern web application built primarily to showcase **end-to-end DevOps practices**. It includes both frontend and backend components, integrated with a complete **DevOps workflow for CI/CD, monitoring, and cloud-native infrastructure management**.


---

### 🛠️ Tech Stack Used

#### 🧑‍💻 Frontend & Backend
- **Frontend**: HTML, CSS, JavaScript  
- **Backend**: Node.js 
- **Version Control**: Git, GitHub  

#### ⚙️ CI/CD & DevOps
- **CI/CD**: GitHub Actions  
- **EC2 as a Self-hosted Runner** for pipeline execution  
- **Containerization**: Docker  
- **Infrastructure as Code**: Terraform 

#### ☁️ AWS Cloud Services
- **EC2** – For self-hosted GitHub runner  
- **S3** – Hosting static files/images  
- **DynamoDB** – NoSQL data storage  
- **VPC** – Isolated networking setup  
- **CloudWatch** – Monitoring and alerting  
- **ALB Ingress Controller** – Managing external access to Kubernetes services via AWS Application Load Balancer

#### 🧵 Kubernetes & Orchestration
- **Kubernetes** – Application orchestration  
- **Helm & Helm Charts** – For packaging and deploying Kubernetes resources  
- **ALB Ingress Controller** – For scalable, production-grade routing with AWS ALB  

#### 🔍 Monitoring & Security
- **Loki** – Centralized log aggregation
- **Promtail** – Log shipping agent used with Loki to collect logs from Kubernetes pods
- **CloudWatch** – AWS-native monitoring and alerting
- **Prometheus & Grafana** – Metrics collection and dashboard visualization
- **SonarQube** – Code quality and static analysis
- **Trivy** – Container vulnerability scanning
- **Docker Scout** – Security insights and image analysis


---

## ⚙️ Setup Instructions

1. **Clone the repository**

   ```bash
   git clone https://github.com/sparknet-innovations/interior-web-app.git
   cd interior-web-app
   ```

2. **Create a virtual environment**

   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use venv\Scripts\activate
   ```

3. **Install dependencies**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Flask app**

   ```bash
   python app.py
   ```

5. **Open your browser**
   Visit `http://127.0.0.1:5000` to see the app in action.

---


## 👨‍💻 Author

This project is maintained by [Prasad Rasal](https://github.com/rasalprasad2002).  
Feel free to check out my other work or get in touch!
