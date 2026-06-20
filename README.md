# 🎓 Internee.pk Virtual Internship Portal (Major Project)

## 📌 Project Overview
A cloud-hosted internship management portal built with Node.js, 
connected to AWS RDS (MySQL), and deployed on AWS Elastic Beanstalk. 
The portal manages intern profiles, project submissions, and 
performance tracking — designed for scalability to support 
thousands of users.

> **Objective:** Create a cloud-hosted portal for managing 
> internships with intern profiles, project submissions, and 
> performance tracking.

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Node.js + Express | Backend application framework |
| EJS | Server-side templating |
| AWS RDS (MySQL) | Cloud database |
| AWS Elastic Beanstalk | Application hosting & auto-scaling |
| AWS Auto Scaling | Handles traffic scalability |

---

## ⚙️ Features

- 👤 **Intern Profiles** — View all registered interns with university, role, department, and status
- 📁 **Project Submissions** — Form-based project submission system, stored directly in RDS
- 📊 **Performance Tracking** — Weekly performance reports with ratings and remarks per intern

---

## 🗄️ Database Schema
internee_portal/

├── interns        (id, full_name, email, university, role, department, joining_date, status)

├── submissions    (id, intern_id, project_title, description, submission_date, file_link)

└── performance    (id, intern_id, week_number, task_completed, rating, remarks)

---

## 🚀 Deployment Steps

1. ✅ Built Node.js + Express app with EJS views
2. ✅ Created AWS RDS MySQL instance (`internee-portal-db`)
3. ✅ Designed schema with 3 relational tables
4. ✅ Connected app to RDS using `mysql2` driver
5. ✅ Tested locally on `http://localhost:8080`
6. ✅ Packaged app as ZIP (excluding `node_modules`)
7. ✅ Deployed to AWS Elastic Beanstalk (Node.js platform)
8. ✅ Verified environment health status: **Ok**
9. ✅ Confirmed all pages working on live Beanstalk URL

---

## 📸 Screenshots

### 1. Homepage
<img width="1408" height="768" alt="home" src="https://github.com/user-attachments/assets/67c3a56c-b85c-46fb-900c-099a146bea94" />


### 2. Elastic Beanstalk — Environment Health Ok
<img width="1408" height="768" alt="4_health" src="https://github.com/user-attachments/assets/cf08025b-38c8-41b4-9758-245eb790cba5" />


### 3. Intern Profiles Page
<img width="1408" height="768" alt="profile" src="https://github.com/user-attachments/assets/1ca0672d-c382-48a3-b196-65ea13e886f3" />


### 4. Project Submissions Page
<img width="1408" height="768" alt="submission" src="https://github.com/user-attachments/assets/b33f7d7b-e0e0-4517-a487-9994d015af8c" />


### 5. Performance Tracking Page
<img width="1408" height="768" alt="tracking" src="https://github.com/user-attachments/assets/bf735cc2-4c84-4d2f-a4b7-6d4aca9840ff" />


---

## 📈 Scalability Notes

Elastic Beanstalk automatically handles load balancing and can be 
configured with Auto Scaling Groups to add/remove EC2 instances 
based on traffic — enabling the portal to scale for thousands of 
concurrent users without manual infrastructure management.

---

## 👨‍💻 Author

**Mubashar Akram**  
Internee @ Internee.pk  
GitHub: [@MubasharAkram05](https://github.com/MubasharAkram05)

