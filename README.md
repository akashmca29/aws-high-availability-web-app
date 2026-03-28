# 🚀 AWS Highly Available Web Application

![Architecture](architecture.png)

---

## 📌 Overview
This project demonstrates a highly available and fault-tolerant web application architecture using AWS services across multiple Availability Zones.

---

## 🏗 Architecture

User  
↓  
Application Load Balancer  
↓  
EC2 Instances (Multi-AZ)  
↓  
RDS Database (Multi-AZ)  

---

## 🧰 Services Used

- EC2 → Web servers  
- Application Load Balancer → Traffic distribution  
- RDS → Managed database  
- Auto Scaling → Dynamic scaling  
- CloudWatch → Monitoring  

---

## ⚙️ How It Works

1. User sends request  
2. Load Balancer distributes traffic  
3. Requests handled by EC2 instances  
4. Data stored in RDS database  
5. Response returned to user  

---

## 🔐 Security

- Security Groups control access  
- Private subnet for database  
- Load balancer handles public traffic  

---

## 💰 Cost Optimization

- Auto Scaling reduces idle cost  
- Right-sizing EC2 instances  
- Managed RDS reduces maintenance  

---

## 📈 High Availability

- Multi-AZ deployment  
- Load balancing ensures uptime  
- Failover support in RDS  

---

## ⚠️ Failure Scenario

- If one AZ fails → traffic shifts automatically  
- If EC2 fails → Auto Scaling replaces instance  
- If DB fails → RDS failover activated  

---

## 📂 Project Structure

aws-high-availability-webapp  
│  
├── architecture.png  
└── README.md  

---

## 🧠 Key Learnings

- High availability design  
- Fault tolerance  
- Load balancing  
- Auto scaling concepts  

---

## 👨‍💻 Author

Akash  
AWS Certified Solutions Architect – Associate  

GitHub: https://github.com/akashmca29  

---

## ⭐ Conclusion

This project demonstrates designing resilient, scalable, and highly available applications using AWS cloud architecture.
