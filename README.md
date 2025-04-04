# 💼 Job Portal Application

A full-stack Job Portal web application that allows **Job Seekers** to find and apply for jobs and **Employers** to post job listings. The application features user authentication, role-based access, and automated email notifications for job applications.

---

## 🚀 Features

### 👥 User Roles
- **Job Seeker**:
  - Register/Login
  - Browse and filter job listings
  - Apply to jobs with resume upload
  - Receive confirmation emails after applying

- **Employer**:
  - Register/Login
  - Post new job opportunities
  - View applications received
  - Receive emails when someone applies

### 📦 Core Functionalities
- 🔐 Authentication (JWT + Cookies)
- 🧠 Role-based Authorization (Seeker vs Employer)
- 📃 Job Posting and Management
- 🔍 Search & Filter by City, Niche, and Keywords
- 📩 Email Notifications on Applications
- 📁 File Uploads (resumes, cover letters)
- 📊 Dashboard for both roles

---

## 🛠 Tech Stack

### Frontend:
- React
- Redux Toolkit
- React Router
- TailwindCSS / CSS Modules
- Toastify for notifications

### Backend:
- Node.js
- Express.js
- MongoDB with Mongoose
- Multer for file uploads
- Nodemailer for emails
- JWT for authentication

---

## 📬 Email Functionality

When a **Job Seeker applies** for a job:
- An email is sent to the **Employer** with the applicant's details and resume (if uploaded).
- A confirmation email is sent to the **Job Seeker**.

> 💡 Make sure to configure your SMTP credentials (e.g., Gmail, Mailtrap) in the `.env` file.

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/job-portal.git
cd job-portal
