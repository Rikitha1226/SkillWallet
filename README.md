# 🔐 SkillWallet  
### Blockchain-Verified Trust and Identity Profile System

SkillWallet is a full-stack web application that demonstrates how **blockchain principles** can be used to build **trusted digital identity profiles** for skills, projects, and certificates.  
The system is designed for **academic learning**, **viva demonstrations**, and **beginner-friendly understanding** of blockchain concepts.

---

## 📌 Problem Statement

In the digital era, students and professionals frequently list skills, projects, and certificates on resumes and online profiles. However, there is **no reliable mechanism** to verify the authenticity of these claims.  
Manual verification is time-consuming, centralized, and prone to manipulation.

There is a strong need for a **transparent, tamper-proof, and trustworthy system** that can verify and store user credentials securely.

---

## 💡 Proposed Solution

SkillWallet provides a **blockchain-inspired verification platform** where every skill, project, or certificate uploaded by a user is stored as a **block**.  
Each block is cryptographically linked to the previous one using **hashing**, ensuring immutability and trust.

Instead of using a real cryptocurrency blockchain, SkillWallet uses a **mock blockchain implementation** to clearly demonstrate blockchain fundamentals in a simple and educational manner.

---

## 🎯 Objectives

- Build a **trusted digital identity wallet**
- Demonstrate **blockchain concepts** such as hashing and immutability
- Provide **secure user authentication**
- Verify:
  - Skills  
  - Projects  
  - Certificates
- Introduce **gamification** using achievement badges
- Keep the system **framework-free and beginner-friendly**
- Ensure the project is **easy to explain in viva**

---

## 🔄 System Workflow (Pipeline)

1. **User Signup**
   - User enters personal details (name, email, role, username, password)
   - Account is created on the server

2. **User Login**
   - Credentials are validated
   - Session is maintained using browser localStorage

3. **Dashboard Access**
   - Authenticated users access their dashboard
   - Unauthorized access is blocked

4. **Upload Verification**
   - User uploads skills/projects/certificates with proof links
   - Each upload creates a new blockchain block

5. **Blockchain Storage**
   - Each block stores:
     - Index
     - Data
     - Timestamp
     - Previous Hash
     - Current Hash (SHA-256)
   - Data cannot be altered without breaking the chain

6. **Gamification**
   - 🥉 Beginner (1–2 items)
   - 🥈 Skilled (3–5 items)
   - 🥇 Expert (6+ items)

---

## 🧰 Technologies Used

### Frontend
- HTML5
- CSS3
- JavaScript (Vanilla)

### Backend
- Python 3
- Flask

### Blockchain Logic
- SHA-256 hashing (`hashlib`)
- Block chaining concept

### Tools
- Visual Studio Code
- Web Browser (Chrome / Edge)

