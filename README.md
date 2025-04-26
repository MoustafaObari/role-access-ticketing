![HTML5](https://img.shields.io/badge/Frontend-HTML5-orange)
![CSS3](https://img.shields.io/badge/Frontend-CSS3-blue)
![Bootstrap](https://img.shields.io/badge/UI-Bootstrap4-purple)
![Node.js](https://img.shields.io/badge/Backend-Node.js-green)
![Express](https://img.shields.io/badge/Framework-Express.js-lightgrey)
![MongoDB](https://img.shields.io/badge/Database-MongoDB-yellow)
![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)

# 🔐 Role Access Ticketing System
A full-stack application that enables multi-level ticket approvals for enterprise role-based access control. Built using **Node.js**, **Express**, and **MongoDB**, this project simulates how employees request feature access and how managers and approvers review and approve/reject those requests.

## 💡 Features
- 📝 Submit access request tickets via user-friendly forms
- 🔄 Multi-level approvals: Reviewer → Approver 1 → Approver 2
- 📋 Role-based overview of all ticket requests (by status and priority)
- 🌐 Clean, responsive UI powered by Bootstrap 4
- 📦 MongoDB Atlas integration for persistent data handling

## ⚙️ Tech Stack
| Layer         | Technology                     |
|--------------|---------------------------------|
| **Frontend**  | HTML5, CSS3, Bootstrap 4        |
| **Backend**   | Node.js, Express.js             |
| **Database**  | MongoDB (via Atlas)             |
| **DevOps**    | Localhost / Optional Render     |

## 🚀 Getting Started
### 1. Clone the Repo
```bash
git clone https://github.com/MoustafaObari/role-access-ticketing.git
cd role-access-ticketing
npm install
node server.js
```
### 2. Open in Browser

Visit the app: [http://localhost:3000](http://localhost:3000)

---

## 🧭 Key Pages

| URL Path      | Description                             |
|---------------|-----------------------------------------|
| `/`           | Home Page                               |
| `/roles`      | Submit a new role access request        |
| `/review`     | View pending tickets (Reviewer)         |
| `/approver1`  | First-level approver interface          |
| `/approver2`  | Second-level approver interface         |
| `/overview`   | Ticket summary & status dashboard       |

---

## 📌 Planned Enhancements

- 🔐 JWT-based user authentication and role session handling  
- 📱 Mobile responsiveness + optional React Native companion app  
- 📊 Admin dashboard with ticket analytics and logs  
- 🌍 CI/CD deployment via Render or Railway  

---

## 👨‍💻 Developer

**Moustafa Obari**  
Software Engineer | Full-Stack Developer | Cloud & Database Enthusiast  
📫 [moustafaobari@gmail.com](mailto:moustafaobari@gmail.com)  
🔗 [GitHub](https://github.com/MoustafaObari) • [LinkedIn](https://www.linkedin.com)

> _“Streamlining access workflows through clean architecture and scalable approval logic.”_ 🚀


