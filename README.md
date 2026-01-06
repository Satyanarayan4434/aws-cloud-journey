# 🚀 My AWS Cloud Journey

This repository documents my daily AWS learning journey
from basics to advanced with hands-on practice.

📅 Started On: January 2026
🎯 Goal: Cloud / DevOps Engineer

**From Zero → Cloud & DevOps Engineer (Daily Learning Log)**

Welcome to my **AWS Cloud learning journey**.  
This repository documents my **step-by-step progress**, concepts, hands-on practice, and real-world understanding of **Amazon Web Services (AWS)**.

📅 **Started:** January 2026  
🎯 **Goal:** Cloud / DevOps Engineer  
📍 **Learning Mode:** Daily consistency + Hands-on + Notes (PDF based)

---

## 👨‍💻 About Me

I am **Satyanarayan Sen**, a Computer Science graduate and Cloud & DevOps trainee.  
This repo is my **public learning proof**, not just notes.

- 🔗 **GitHub:** https://github.com/Satyanarayan4434  
- 🔗 **LinkedIn:** https://www.linkedin.com/in/satyanarayan-sen-a3a57b1b5/  
- 🔗 **Portfolio:** https://satyanarayansen.vercel.app/  
- 🏅 **Credly (AWS Badges):** https://www.credly.com/users/satyanarayan-sen/badges#credly  

---

## 🧭 Learning Philosophy

> *"Cloud is not about servers — it's about **abstraction, scalability, and responsibility**."*

I follow this pattern:
- 📘 **Concept first**
- 🧠 **Why it exists**
- 🌍 **Real-life analogy**
- 🔧 **Hands-on**
- 📝 **Daily update**

---

## 📂 Repository Structure

📌 **Note:**  
Each folder contains **only PDF notes & project documents**.  
All explanations, progress, and updates live here in **one README**.

---

## ☁️ Phase 1: Cloud Computing Fundamentals

### 🔹 What is Cloud?
Cloud allows us to **access data and applications anytime, anywhere** using the internet.

🌍 **Real-life example:**  
Google Drive → even if your laptop breaks, your files are safe.

---

### 🔹 Why Cloud?
Traditional systems depend on **physical devices**:
- Laptop
- Hard disk
- Pen drive

If hardware fails → **data loss** ❌

Cloud solves this by storing data **securely in remote data centers**.

---

### 🔹 Cloud Computing Definition
Cloud Computing is the **delivery of computing services** like:
- Servers
- Storage
- Databases
- Networking
- Software

…over the **internet**, on a **pay-as-you-go** model.

---

### 🔹 Service Models

| Model | Meaning | Real-Life Example |
|----|----|----|
| **IaaS** | You manage OS & apps | AWS EC2 |
| **PaaS** | Platform managed | Hosting services |
| **SaaS** | Software ready to use | Gmail |

🧠 Key idea:  
👉 **More abstraction = less responsibility**

---

### 🔹 Deployment Models
- **Public Cloud** – Shared, cost-effective (AWS)
- **Private Cloud** – High security, internal
- **Hybrid Cloud** – Best of both
- **Community Cloud** – Shared by orgs (e.g. banks)

---

## 🔐 Phase 2: AWS IAM (Identity & Access Management)

IAM is the **security backbone of AWS**.

### Core Components:
- 👤 **Users** – Individual identities
- 👥 **Groups** – Collection of users
- 🎭 **Roles** – Temporary permissions (no credentials)
- 📜 **Policies** – JSON rules (Allow / Deny)

🌍 **Real-life analogy:**  
Office building access cards:
- Employee → User
- Department → Group
- Visitor pass → Role
- Office rules → Policy

🔐 **Best Practices I Follow**
- Never use root account
- Enable MFA
- Least privilege access
- Use roles instead of access keys

---

## 🗄️ Phase 3: Amazon S3 (Simple Storage Service)

S3 is **object storage**, not a file system.

### Key Concepts:
- **Bucket** → Container (like a cupboard)
- **Object** → File
- **Key** → Object name/path

🌍 **Analogy:**  
S3 = Google Drive  
EBS = Hard disk

---

### 🔹 S3 Storage Classes
- Standard
- Intelligent-Tiering
- Standard-IA
- One Zone-IA
- Glacier / Deep Archive

💰 Used based on **access frequency & cost**

---

### 🔹 S3 Features I Practiced
- Versioning
- Lifecycle rules
- Encryption
- Static website hosting
- Bucket policies
- Pre-signed URLs

---

## 🌍 Phase 4: S3 Cross Region Replication (CRR)

CRR automatically copies data between **different AWS regions**.

🎯 **Why CRR?**
- Disaster recovery
- Compliance
- High availability

### Project Summary:
- Source bucket (Region A)
- Destination bucket (Region B)
- Versioning enabled
- IAM role for replication

🧠 **Real-life analogy:**  
Primary office + backup office in another city.

---

## 🖥️ Phase 5: Amazon EC2 (Elastic Compute Cloud)

EC2 is **more than a VM**.

It allows you to:
- Choose OS
- Select CPU/RAM
- Attach storage
- Configure networking & security

### Key EC2 Components:
- AMI
- Instance type
- EBS
- Security Groups
- Key Pair
- IAM Role

🌍 **Real-life analogy:**  
Renting a fully managed flat instead of building a house.

---

### 🔐 EC2 Security
- Security Groups = Virtual firewall
- No passwords inside instance
- Use IAM Roles + AWS services

---

## 🌐 Phase 6: VPC (Virtual Private Cloud)

VPC provides **network isolation**.

### Core Concepts:
- CIDR blocks
- Subnets (Public / Private)
- Internet Gateway
- Routing
- Security boundaries

🌍 **Analogy:**  
VPC = Apartment building  
Subnets = Floors  
IGW = Main gate

---

## 📊 Phase 7: Amazon CloudWatch

CloudWatch is AWS's **monitoring and observability service**.

### What CloudWatch Does:
- **Monitors** AWS resources and applications
- **Collects** metrics, logs, and events
- **Visualizes** data through dashboards
- **Alerts** you when thresholds are breached
- **Automates** responses to changes

### Key Components:
- 📈 **Metrics** – Numerical data (CPU usage, disk I/O)
- 📝 **Logs** – Application and system logs
- ⏰ **Alarms** – Trigger notifications or actions
- 📊 **Dashboards** – Visual representation of metrics
- 🎯 **Events** – Respond to state changes

🌍 **Real-life analogy:**  
CloudWatch = Security camera system in a building  
- Cameras = Metrics
- Recording = Logs
- Alert system = Alarms
- Control room monitors = Dashboards

### Common Use Cases I Practiced:
- Monitor EC2 CPU utilization
- Track S3 bucket requests
- Set billing alarms
- Collect application logs
- Create custom dashboards
- Auto-scaling based on metrics

🧠 **Key Understanding:**  
CloudWatch tells you **"what is happening"** in your AWS environment in real-time.

---

## 📧 Phase 8: Amazon SNS (Simple Notification Service)

SNS is AWS's **fully managed pub/sub messaging service**.

### What SNS Does:
- **Sends notifications** to multiple subscribers
- **Decouples** microservices and distributed systems
- **Delivers messages** via multiple protocols
- **Fans out** messages to multiple endpoints

### Core Concepts:
- 📢 **Topics** – Communication channels
- 👥 **Subscriptions** – Endpoints that receive messages
- 📨 **Publishers** – Services that send messages
- 🎯 **Protocols** – Email, SMS, HTTP, Lambda, SQS

🌍 **Real-life analogy:**  
SNS = News broadcasting station  
- Topic = TV Channel
- Subscription = Your TV tuned to that channel
- Publisher = News anchor
- Message = Breaking news

### SNS Protocols I Used:
- Email
- Email-JSON
- SMS
- HTTP/HTTPS
- AWS Lambda
- Amazon SQS

### Integration with CloudWatch:
CloudWatch Alarms → SNS Topics → Notifications

🎯 **Example Flow:**
1. EC2 CPU > 80%
2. CloudWatch Alarm triggers
3. SNS sends notification
4. Email/SMS received

🧠 **Key Understanding:**  
SNS enables **"one message to many destinations"** instantly.

---

## 🔗 CloudWatch + SNS Integration

This powerful combination enables **proactive monitoring and alerting**.

### Real-World Scenario:
1. **Monitor:** CloudWatch tracks EC2 instance metrics
2. **Detect:** Alarm triggers when CPU > 80% for 5 minutes
3. **Notify:** SNS sends alert to on-call team via email/SMS
4. **Act:** Team investigates or auto-scaling kicks in

### My Hands-On Project:
- Created CloudWatch alarm for EC2 instance
- Set CPU threshold at 70%
- Configured SNS topic
- Subscribed my email
- Simulated high CPU load
- Received notification successfully

💡 **Benefits:**
- Reduced downtime
- Faster incident response
- Automated alerting
- Cost optimization through monitoring

---

## 📅 Daily Update Log (Template)

I update this section **daily** 👇

### ✅ Day X – _(Topic Name)_
- 📘 Learned:
- 🔧 Practiced:
- 🧠 Understood well:
- ❓ Doubts:
- 🔁 Revision needed:

---

## 🎯 Final Goal

This repository will evolve into:
- ✅ Proof of consistency
- ✅ Hands-on AWS knowledge
- ✅ Interview-ready explanation
- ✅ Recruiter-friendly learning trail
- ✅ Real-world monitoring and alerting skills

---

> ⭐ If you are a recruiter or fellow learner, feel free to explore, fork, or connect with me.

**Learning. Building. Improving. Daily. 🚀**