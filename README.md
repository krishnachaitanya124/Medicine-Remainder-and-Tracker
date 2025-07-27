# 💊 Medicine Reminder & Tracker

A full-stack web application that helps patients schedule and track their medication routine with reminders and dosage details. Built using **MySQL, Express.js, React.js, and Node.js** (MERN-like stack with MySQL).

## 🚀 Features

- 📅 Add and schedule medicines with dosage, time, and frequency.
- ⏰ Set personalized reminders for each medicine.
- 🧠 Track and manage upcoming medications with an intuitive interface.
- 📊 View and edit medicine logs/history.
- 🔒 User authentication and session management.
- 📬 Notification alerts to ensure timely intake (sms/email).

---

## 🛠️ Tech Stack

| Layer        | Technology         |
|--------------|--------------------|
| Frontend     | React.js,TailwindCSS (optional) |
| Backend      | Node.js, Express.js |
| Database     | MySQL (with Sequelize / custom queries) |
| Other Tools  | Nodemailer (if email reminders)

---

## 📂 Folder Structure
project-root/
├── client/ # React frontend
│ ├── public/
│ └── src/
│ ├── components/
│ ├── pages/
│ └── App.js
├── server/ # Express backend
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ └── server.js
├── database/ # MySQL setup and scripts
├── .env
└── README.md


---

## 🧪 Setup & Installation

### 🔧 Prerequisites

- Node.js & npm
- MySQL server running
- (Optional) Git & VSCode

---

### 🖥️ Backend Setup

```bash
cd server
npm install
# Create a `.env` file with your DB credentials
npm start

DB_HOST=localhost
DB_USER=root
DB_PASSWORD=yourpassword
DB_NAME=med_tracker
JWT_SECRET=your_secret_key

```
### 🌐 Frontend Setup
```bash

cd client
npm install
npm start

Frontend will run on http://localhost:3000/
```
✅ TODO / Enhancements
 Add calendar view to visualize schedules.

 Add progressive web app (PWA) support.

 SMS/email reminders.

 Mobile responsive UI improvements.

🙌 Authors
Krishna Chaitanya Uppada
Full Stack Developer | Feb 2025


