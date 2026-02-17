# DevOps Task 4 – Git Branching & Pull Request Workflow

## 📖 Objective
The objective of this task is to demonstrate a proper Git workflow using:
- `main` branch (production)
- `dev` branch (development)
- `feature-login` branch (feature development)

This task showcases structured branching, pull requests, and proper merge flow.

---

## 🛠 Steps Performed

### 1️⃣ Created Development Branch
- Created a `dev` branch from `main`.
- This branch is used for ongoing development work.

### 2️⃣ Created Feature Branch
- Created a `feature-login` branch from `dev`.
- Added login functionality section in `README.md`.

### 3️⃣ Pull Request: feature-login → dev
- Created a Pull Request from `feature-login` into `dev`.
- Reviewed changes.
- Successfully merged the Pull Request.
- Deleted the `feature-login` branch after merge.

### 4️⃣ Pull Request: dev → main
- Created a Pull Request from `dev` into `main`.
- Verified changes.
- Successfully merged the Pull Request.
- Deleted the `dev` branch after merge.

---

## 🔄 Workflow Diagram

main  
⬇  
dev  
⬇  
feature-login  

feature-login → dev → main  

---

## 📸 Screenshots

<img width="1875" height="834" alt="Screenshot 2026-02-17 202343" src="https://github.com/user-attachments/assets/04cc54e3-da35-4524-be25-9049dda72fe0" />
<img width="1887" height="944" alt="Screenshot 2026-02-17 202238" src="https://github.com/user-attachments/assets/e0e5fec8-d9af-46a3-92fa-7c0460350842" />
<img width="1902" height="951" alt="Screenshot 2026-02-17 202041" src="https://github.com/user-attachments/assets/888ecea5-6211-44dc-9858-fd81353355e1" />
<img width="1853" height="952" alt="Screenshot 2026-02-17 201941" src="https://github.com/user-attachments/assets/2205080f-c64f-4843-a321-02a89194cf4f" />

---

## ✅ Result

- Feature successfully developed in isolated branch.
- Code reviewed using Pull Requests.
- Changes merged in a structured workflow.
- Proper branch cleanup performed after merge.

---



## 👤 Author
Sujay
