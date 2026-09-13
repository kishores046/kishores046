<div align="center">

# Hey there, I'm Kishore S 👋☕

### Java-focused Backend Developer · Spring Boot · Cloud-Native Enthusiast

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/kishore-s-6b299b290)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/Kishore15092005/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/kishores046)
[![Email](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:kishore279k@gmail.com)

</div>

---

## 🧑‍💻 About Me

```bash
$ whoami
  Kishore S — Backend Developer

$ cat profile.txt
  📍 Erode, Tamil Nadu, India
  🎓 Velalar College of Engineering & Technology
  💼 Backend Developer Intern @ Infosys SpringBoard (Dec 2025 – Jan 2026)

$ skills --list
  Languages             : Java, C
  Frameworks            : Spring Boot, Spring Security, Spring Data JPA
  Auth                  : JWT, OAuth2, RBAC
  Databases             : MySQL, H2, PostgreSQL
  Server Side Rendering : Thymeleaf
  Tools                 : Git, Maven, Linux, Docker, Nginx , Postman, IntelliJ

$ echo $MOTTO
  "Projects over promises 🚀"
```

---

## 💼 Experience

### Full Stack Developer Intern (Backend Role) — Infosys SpringBoard
📅 Dec 2025 – Jan 2026

- Designed and architected the entire backend for the **Global IP Intelligence Platform** as the Backend Lead on a full-stack team project
- Designed a **modular monolith** architecture with clear domain separation across IP search, alerts, analytics, and admin modules
- Implemented **Caffeine caching**, async processing, and normalized API aggregation across USPTO, EPO, WIPO, and PatentsView — reducing external API latency by **~60%**
- Led all backend decisions: auth (JWT + OAuth2 + RBAC), deployment (Render + PostgreSQL), and third-party API integration strategy

---

## 🛠️ Tech Stack


### Languages
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)

### Backend
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![Spring MVC](https://img.shields.io/badge/Spring_MVC-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Spring Data JPA](https://img.shields.io/badge/Spring_Data_JPA-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=spring&logoColor=white)
![REST API](https://img.shields.io/badge/REST_API-FF6F00?style=for-the-badge&logo=fastapi&logoColor=white)
![Thymeleaf](https://img.shields.io/badge/Thymeleaf-005F0F?style=for-the-badge&logo=thymeleaf&logoColor=white)

### Security & Auth
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)
![OAuth2](https://img.shields.io/badge/OAuth2-EB5424?style=for-the-badge&logo=auth0&logoColor=white)

### Database
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![H2](https://img.shields.io/badge/H2_Database-0044B3?style=for-the-badge&logo=h2&logoColor=white)

### Build Tools
![Maven](https://img.shields.io/badge/Maven-C71A36?style=for-the-badge&logo=apache-maven&logoColor=white)

### DevOps & OS
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white)

### Development Tools
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ_IDEA-000000?style=for-the-badge&logo=intellij-idea&logoColor=white)

### Testing
![JUnit](https://img.shields.io/badge/JUnit5-25A162?style=for-the-badge&logo=junit5&logoColor=white)
![Mockito](https://img.shields.io/badge/Mockito-78CFF5?style=for-the-badge&logo=mockito&logoColor=white)

---

## 🚀 Featured Projects

### 🌐 [Global IP Intelligence Platform](https://github.com/kishores046/GLOBAL-IP)
> Full-stack IP monitoring & analytics platform — **Backend Lead** · *Infosys SpringBoard Internship Project*

- 🏗️ Designed the overall backend architecture as a **modular monolith** with domain-separated modules for search, alerts, analytics, and admin
- 🌍 Built IP monitoring features covering patent & trademark search, competitor tracking, legal status monitoring, and landscape visualization via **USPTO, EPO, WIPO, and PatentsView** APIs
- ⚡ Architected Spring Boot services with normalized API aggregation, async processing, pagination strategies, and **Caffeine caching** — reducing external API latency by **~60%**
- 🔐 Implemented secure **RBAC** using JWT + OAuth2 (Google/GitHub) with admin-approved role escalation and scoped API key access for third-party integrations
- 🔔 Developed subscription-based alert system for filing & legal status updates, along with admin dashboards for user activity monitoring, API health tracking, and usage analytics
- ☁️ Deployed production-ready backend on **Render** and frontend on **Vercel** with environment-based config and **PostgreSQL** persistence

---

## 🎮 Real-Time Hangman Game

**A concurrent multiplayer terminal-based Hangman game built entirely with Core Java.**

A TCP-based multiplayer game server supporting single-player and real-time 1v1 gameplay, with authentication, matchmaking, chat, persistent player statistics, leaderboards, match history, and movie plot hints.

### ⚡ Highlights

- Built a **custom text-based application protocol over TCP sockets** for client-server communication.
- Implemented **real-time 1v1 matchmaking** using a thread-safe `LinkedBlockingQueue` and dedicated matchmaking thread.
- Designed separate **ExecutorService thread pools** for client handling, game sessions, and Hangman engine execution.
- Used **CompletableFuture** to coordinate concurrent multiplayer game execution.
- Implemented a layered **DAO architecture using JDBC and MySQL** for authentication, player statistics, leaderboards, and match history.
- Added **HikariCP connection pooling** for efficient database connection reuse.
- Implemented **Caffeine caching** for movie plot hints, reducing repeated external API calls.
- Added **BCrypt password hashing** with automatic migration from legacy SHA-256 passwords.
- Implemented **real-time multiplayer chat over the existing TCP connection**.
- Added **UDP-based LAN server discovery** for automatic server discovery on local networks.
- Integrated the **OMDb API** to provide movie plot hints without directly revealing the word.
- Containerized the server and MySQL database using **Docker Compose**.
- Deployed the production game server on **AWS EC2** with a **static Elastic IP** for stable internet connectivity.
- Externalized database, server, and API configuration using **environment variables**.

### 🏗️ Architecture

```text
Client
   ↓
TCP Socket
   ↓
ClientHandler
   ↓
Authentication
   ↓
Matchmaking / Session
   ↓
Hangman Game Engine
   ↓
DAO Layer
   ↓
MySQL
```

---

## 📊 GitHub Stats

<div align="center">

<img height="180em" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=kishores046&theme=tokyonight" />

<table>
  <tr>
    <td>
      <img height="180em" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=kishores046&theme=tokyonight" />
    </td>
    <td>
      <img height="180em" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=kishores046&theme=tokyonight" />
    </td>
    <td>
      <img height="180em" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=kishores046&theme=tokyonight" />
    </td>
  </tr>
</table>

<img src="https://streak-stats.demolab.com?user=kishores046&theme=tokyonight&hide_border=true&date_format=M%20j%5B%2C%20Y%5D" />

</div>

---

## 🐍 My Contributions!

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/kishores046/kishores046/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/kishores046/kishores046/output/github-contribution-grid-snake.svg" />
  <img alt="Snake animation" src="https://raw.githubusercontent.com/kishores046/kishores046/output/github-contribution-grid-snake.svg" />
</picture>

</div>

---

<div align="center">

*"Projects over promises"* ☕

</div>
