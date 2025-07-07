# VoteSync — Secure Online Voting Backend

VoteSync is a secure and scalable backend system for managing an online voting platform. Built with Node.js, Express, and MongoDB, it enables user registration, role-based access, vote casting, and candidate management. Each user can vote only once, and only admins can manage candidates.

---
Features
Aadhaar-Based User Authentication
Users can register and log in using their Aadhaar number and password, ensuring secure and unique identification.

JWT-Based Session Management
Uses JSON Web Tokens to handle user sessions in a secure and stateless manner.

One-Vote-Per-User Logic
Each registered user is allowed to vote only once, ensuring the integrity of the voting process.

Admin-Only Candidate Management
Only admin users have the ability to add, update, or delete candidates.

Real-Time Vote Count
Provides up-to-date vote counts for each candidate, sorted by number of votes.

 Installation & Setup

Clone the repository

```bash
git clone https://github.com/code0027-sid/votesync-backend.git
cd votesync-backend
