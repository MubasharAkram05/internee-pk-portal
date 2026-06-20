
## 📝 GitHub README.md — Virtual Internship Portal:

```markdown
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

- 👤 **Intern Profiles** — View all registered interns with 
  university, role, department, and status
- 📁 **Project Submissions** — Form-based project submission 
  system, stored directly in RDS
- 📊 **Performance Tracking** — Weekly performance reports with 
  ratings and remarks per intern



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
<img width="1408" height="768" alt="home" src="https://github.com/user-attachments/assets/3af218e4-e1a0-4d39-bf28-0ffeb57d32d9" />


### 2. Elastic Beanstalk — Environment Health Ok
![Beanstalk Health](4_health.png)

### 3. Intern Profiles Page
![Profiles](profile.png)

### 4. Project Submissions Page
![Submissions](submission.png)

### 5. Performance Tracking Page
![Tracking](tracking.png)
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
```
