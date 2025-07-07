# VoteSync — Secure Online Voting Backend

**VoteSync** is a secure and scalable backend system for managing an online voting platform. Built with Node.js, Express, and MongoDB, it enables user registration, role-based access, vote casting, and candidate management. Each user can vote only once, and only admins can manage candidates.

---

## 🔧 Features

- 👤 Aadhaar-based user registration & login
- 🔐 JWT-based authentication for session handling
- 🗳️ One-vote-per-user logic for fair elections
- 🧑‍💼 Admin-only access to add, update, or delete candidates
- 📊 Real-time vote count tracking per candidate
- 🔐 Role-based access (admin vs user)

---

## 🛠️ Technologies Used

- **Node.js** + **Express.js** — Backend Framework
- **MongoDB** + **Mongoose** — Database & ODM
- **JWT (JSON Web Tokens)** — Secure user authentication
- **dotenv** — Manage environment variables
- **bcrypt.js** — Secure password hashing

---

## 📦 Installation & Setup

### 1. Clone the repository

```bash
git clone https://github.com/code0027-sid/votesync-backend.git
cd votesync-backend
