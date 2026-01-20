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
- ✍️ **Medium Blog:** https://medium.com/@satyanarayan74sen  
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

## 🗃️ Phase 9: Amazon RDS (Relational Database Service)

RDS is AWS's **managed relational database service** that eliminates the complexity of database administration.

### What RDS Does:
- **Manages** database infrastructure (hardware, OS, patching)
- **Automates** backups, snapshots, and recovery
- **Scales** compute and storage independently
- **Provides** high availability through Multi-AZ deployments
- **Handles** routine maintenance and updates

### Supported Database Engines:
- 🐘 **PostgreSQL** – Open-source, advanced features
- 🐬 **MySQL** – Popular, widely used
- 🔷 **MariaDB** – MySQL fork with enhancements
- 🟦 **Oracle** – Enterprise-grade commercial
- 🟪 **SQL Server** – Microsoft's relational database
- 🚀 **Amazon Aurora** – AWS-optimized, MySQL/PostgreSQL compatible

🌍 **Real-life analogy:**  
RDS = Managed apartment with maintenance staff  
Self-managed DB on EC2 = Owning a house (you handle everything)

### Core Concepts:

#### 📦 **DB Instance**
- Virtual database server in the cloud
- Choose instance class (CPU, RAM)
- Select storage type (SSD, Provisioned IOPS)

#### 🔄 **Multi-AZ Deployment**
- **Primary** instance in one Availability Zone
- **Standby** replica in another AZ
- Automatic failover (60-120 seconds)
- Used for **high availability**, not read scaling

🎯 **Why Multi-AZ?**
- Protects against AZ failure
- Automatic failover during maintenance
- No manual intervention needed

#### 📖 **Read Replicas**
- Asynchronous replication from primary
- Up to 15 read replicas
- Offload read traffic from primary
- Can be in different regions
- Used for **read scaling**, not disaster recovery

🎯 **Multi-AZ vs Read Replicas:**

| Feature | Multi-AZ | Read Replicas |
|---------|----------|---------------|
| **Purpose** | High Availability | Read Scaling |
| **Replication** | Synchronous | Asynchronous |
| **Readable** | No (standby) | Yes |
| **Failover** | Automatic | Manual promotion |
| **Use Case** | Disaster recovery | Performance |

#### 💾 **Automated Backups**
- Daily full backup of DB instance
- Transaction logs backed up every 5 minutes
- Point-in-time recovery (up to 35 days)
- Stored in S3 (no extra charge)

#### 📸 **DB Snapshots**
- Manual, user-initiated backups
- Stored until explicitly deleted
- Can copy across regions
- Used for long-term retention

### RDS Security:

#### 🔒 **Encryption**
- **At Rest:** Uses AWS KMS
- **In Transit:** SSL/TLS connections
- Must enable during creation (can't add later)

#### 🛡️ **Network Isolation**
- Deploy in VPC for network isolation
- Security Groups control access
- Private subnets for extra security
- No public access by default

#### 👤 **Access Control**
- IAM database authentication (no passwords)
- Master user credentials
- Database-level permissions

### What I Practiced:

✅ **Created MySQL RDS instance**
- Selected db.t3.micro (Free Tier eligible)
- Enabled automated backups (7 days retention)
- Configured security group (allow port 3306)

✅ **Connected from EC2**
- Used MySQL client
- Tested CRUD operations
- Verified connection security

✅ **Configured Multi-AZ**
- Enabled for high availability
- Simulated failover scenario
- Observed automatic recovery

✅ **Created Read Replica**
- Deployed in same region
- Tested read queries
- Monitored replication lag

✅ **Performed Backup & Restore**
- Created manual snapshot
- Restored to new instance
- Verified data integrity

### 🧠 Key Learnings:

💡 **RDS vs EC2 Database:**
- RDS = Managed (less control, less responsibility)
- EC2 = Self-managed (full control, full responsibility)

💡 **When to Use RDS:**
- You want AWS to handle patching, backups, scaling
- High availability is critical
- You need read replicas for scaling
- Compliance requires automated backups

💡 **When NOT to Use RDS:**
- Need root access to OS
- Custom database engine
- Require specific database configurations
- NoSQL requirements (use DynamoDB instead)

### 🎯 Real-World Use Case:

**E-commerce Application:**
1. **Primary RDS** in us-east-1a (writes)
2. **Multi-AZ Standby** in us-east-1b (failover)
3. **Read Replicas** in multiple AZs (product catalog reads)
4. **Daily Snapshots** for compliance
5. **CloudWatch Alarms** for CPU, connections, storage

---

## ⚖️ Phase 10: Elastic Load Balancer (ELB)

ELB is AWS's **managed load balancing service** that automatically distributes incoming traffic across multiple targets.

### What is Load Balancing?

Load balancing distributes network traffic across multiple servers to ensure:
- **No single server is overwhelmed**
- **High availability** (if one server fails, traffic goes to others)
- **Better performance** (distribute workload efficiently)
- **Scalability** (add/remove servers based on demand)

🌍 **Real-life analogy:**  
ELB = Traffic police at an intersection  
- Multiple lanes (servers) handle traffic (requests)
- Police (load balancer) directs cars (users) to available lanes
- If one lane is blocked (server down), traffic goes to other lanes

---

### 🔹 Types of Load Balancers

AWS offers **4 types** of load balancers, each for different use cases:

#### 1️⃣ **Application Load Balancer (ALB)**
- **Layer:** OSI Layer 7 (Application Layer)
- **Protocol:** HTTP, HTTPS, WebSocket
- **Best for:** Web applications, microservices, containers

**Key Features:**
- Content-based routing (path, host, headers)
- Support for multiple domains (Host-based routing)
- WebSocket and HTTP/2 support
- Integration with AWS WAF (Web Application Firewall)
- Advanced request routing

**Example Use Cases:**
- Route `/api/*` to API servers
- Route `/images/*` to image servers
- Route based on domain (app1.example.com vs app2.example.com)

🌍 **Analogy:**  
ALB = Smart receptionist who reads your request and directs you to the right department

---

#### 2️⃣ **Network Load Balancer (NLB)**
- **Layer:** OSI Layer 4 (Transport Layer)
- **Protocol:** TCP, UDP, TLS
- **Best for:** Extreme performance, low latency, static IP requirements

**Key Features:**
- Ultra-low latency (millions of requests/second)
- Static IP address support
- Preserves source IP address
- Handles volatile workloads
- PrivateLink support

**Example Use Cases:**
- Gaming applications (low latency critical)
- IoT applications
- Financial trading platforms
- Static IP needed for firewall whitelisting

🌍 **Analogy:**  
NLB = Express elevator that doesn't stop to read your request, just moves you fast

---

#### 3️⃣ **Gateway Load Balancer (GWLB)**
- **Layer:** OSI Layer 3 (Network Layer)
- **Protocol:** IP packets
- **Best for:** Third-party virtual appliances (firewalls, intrusion detection)

**Key Features:**
- Deploy, scale, and manage third-party appliances
- Transparent to source and destination
- Single entry/exit point
- Integrates with security vendors

**Example Use Cases:**
- Firewall inspection
- Intrusion detection/prevention
- Deep packet inspection
- Network monitoring

---

#### 4️⃣ **Classic Load Balancer (CLB)**
- **Layer:** Both Layer 4 and Layer 7 (limited)
- **Status:** Legacy (not recommended for new applications)
- **Best for:** Existing EC2-Classic applications

🚫 **Note:** AWS recommends using ALB or NLB instead of CLB for new deployments.

---

### 🎯 **ALB vs NLB Comparison**

| Feature | Application LB (ALB) | Network LB (NLB) |
|---------|---------------------|------------------|
| **OSI Layer** | Layer 7 (Application) | Layer 4 (Transport) |
| **Protocols** | HTTP, HTTPS, WebSocket | TCP, UDP, TLS |
| **Routing** | Content-based (path, host) | Connection-based |
| **Performance** | Good | Extremely high |
| **Latency** | Higher | Ultra-low |
| **Static IP** | No | Yes |
| **Use Case** | Web apps, APIs | Gaming, IoT, high throughput |
| **Price** | Moderate | Lower |

---

### 🔧 **Core Components of ELB**

#### 1️⃣ **Listeners**
- Rules that check for connection requests
- Define protocol and port (HTTP:80, HTTPS:443)
- Can have multiple listeners per load balancer

#### 2️⃣ **Target Groups**
- Collection of targets (EC2, IP, Lambda)
- Health checks configured per target group
- Routing rules direct traffic to target groups

#### 3️⃣ **Health Checks**
- ELB automatically checks target health
- Sends traffic only to healthy targets
- Configurable: interval, timeout, thresholds

**Health Check Parameters:**
- **Protocol:** HTTP, HTTPS, TCP
- **Path:** /health or /ping
- **Interval:** 30 seconds (default)
- **Timeout:** 5 seconds
- **Healthy threshold:** 2 consecutive successes
- **Unhealthy threshold:** 2 consecutive failures

#### 4️⃣ **Availability Zones**
- ELB must be enabled in at least 2 AZs
- Automatically distributes traffic across AZs
- Provides fault tolerance

---

### 🌐 **How ELB Works (Request Flow)**
```
User Request (www.example.com)
        ↓
    Route 53 (DNS)
        ↓
Elastic Load Balancer
        ↓
[Listener Rules]
        ↓
    Target Groups
        ↓
Health Check Filter
        ↓
Available Targets (EC2 instances)
   ↙     ↓     ↘
 EC2-1  EC2-2  EC2-3
(AZ-1) (AZ-2) (AZ-3)
```

---

### 🔒 **ELB Security Features**

#### **SSL/TLS Termination**
- Load balancer handles SSL/TLS encryption/decryption
- Reduces CPU load on backend servers
- Centralized certificate management

#### **Security Groups**
- Control inbound/outbound traffic
- Only allow traffic from load balancer to targets

#### **AWS Certificate Manager (ACM)**
- Free SSL/TLS certificates
- Automatic renewal
- Easy integration with ALB/NLB

---

### 🧪 **What I Practiced:**

✅ **Created Application Load Balancer**
- Configured 2 Availability Zones
- Created target group with EC2 instances
- Set up health checks (/health endpoint)
- Configured listeners (HTTP:80)

✅ **Implemented Path-Based Routing**
- `/app` → App Servers Target Group
- `/api` → API Servers Target Group
- Default → Landing Page

✅ **Configured Health Checks**
- Interval: 30 seconds
- Timeout: 5 seconds
- Healthy/Unhealthy threshold: 2

✅ **Tested High Availability**
- Stopped one EC2 instance
- Verified traffic automatically routed to healthy instances
- Monitored health check status in console

✅ **Added SSL/TLS Certificate**
- Used AWS Certificate Manager
- Configured HTTPS listener (443)
- Set up HTTP to HTTPS redirect

✅ **Monitored with CloudWatch**
- Tracked request count
- Monitored target response time
- Set alarms for unhealthy targets

---

### 💡 **Key Learnings:**

#### **Why Use Load Balancers?**
1. **High Availability** – If one server fails, traffic goes to others
2. **Scalability** – Easily add/remove servers
3. **Performance** – Distribute load across servers
4. **Fault Tolerance** – Automatically route around failures
5. **SSL Offloading** – Centralize certificate management

#### **Best Practices:**
- ✅ Always use at least 2 Availability Zones
- ✅ Enable Cross-Zone Load Balancing (for even distribution)
- ✅ Configure proper health checks
- ✅ Use target groups for logical grouping
- ✅ Monitor with CloudWatch metrics
- ✅ Enable access logs for debugging
- ✅ Use security groups to restrict access

#### **Common Mistakes to Avoid:**
- ❌ Not configuring health checks properly
- ❌ Using only one Availability Zone
- ❌ Incorrect security group rules
- ❌ Not monitoring target health
- ❌ Forgetting to enable access logs

---

### 🎯 **Real-World Architecture:**

**High-Availability Web Application:**
```
                    Internet
                       ↓
                   Route 53
                       ↓
            Application Load Balancer
               (Multi-AZ enabled)
                   ↓      ↓
        ┌──────────┴──────┴──────────┐
        ↓                              ↓
   Target Group 1              Target Group 2
  (Web Servers)                (API Servers)
        ↓                              ↓
  ┌─────┴─────┐              ┌────────┴────────┐
  ↓           ↓              ↓                  ↓
EC2 (AZ-1) EC2 (AZ-2)   EC2 (AZ-1)      EC2 (AZ-2)
  ↓           ↓              ↓                  ↓
      RDS Multi-AZ (Database)
```

**Benefits:**
- **No single point of failure**
- **Automatic failover**
- **Horizontal scaling**
- **Zero-downtime deployments**
- **Geographic redundancy**

---

### 🔗 **ELB + Auto Scaling Integration**

ELB works perfectly with Auto Scaling:

1. **Auto Scaling** creates/terminates EC2 instances based on demand
2. **ELB** automatically registers/deregisters instances
3. **Health Checks** ensure traffic only goes to healthy instances
4. **CloudWatch** triggers scaling based on metrics

**Example Flow:**
- Traffic increases → CPU > 70%
- Auto Scaling launches new EC2 instance
- ELB automatically adds instance to target group
- Health check passes → ELB sends traffic to new instance

---

### 📊 **ELB Metrics to Monitor (CloudWatch):**

**Key Metrics:**
- **RequestCount** – Total requests processed
- **TargetResponseTime** – How long targets take to respond
- **HealthyHostCount** – Number of healthy targets
- **UnHealthyHostCount** – Number of unhealthy targets
- **HTTPCode_Target_2XX_Count** – Successful responses
- **HTTPCode_Target_5XX_Count** – Server errors

**Alarms to Set:**
- UnHealthyHostCount > 0 (immediate alert)
- TargetResponseTime > 1 second
- HTTPCode_Target_5XX_Count > threshold

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
- ✅ Production-grade database management understanding
- ✅ High-availability architecture design expertise

---

> ⭐ If you are a recruiter or fellow learner, feel free to explore, fork, or connect with me.

**Learning. Building. Improving. Daily. 🚀**