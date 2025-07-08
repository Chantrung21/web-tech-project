# Job Management System – Client-Based Web Project

This project was developed in collaboration with **ShangYa Consultancy** as part of the Web Technology unit under the Swinburne University program (INTI International College Subang).

We were selected as the **Top 2 performing team** among all project groups.

## 🌐 Overview

This web application serves both **employers** and **job seekers**, providing a platform to post jobs, apply with resumes, and manage submissions through an admin interface. All data is stored in structured MySQL tables.

---

## 🚀 Features

### 🔹 Homepage
- Brief introduction about ShangYa Consultancy
- Simple and clean landing page

### 🔹 Services
- Description of the services provided by ShangYa

### 🔹 Post a Job (Employer Form)
- Employers can fill out job details
- Submitted data is stored in the `jobs` table

### 🔹 Upload Resume (Employee Form)
- Job seekers submit their personal info, job interest, and skills
- Stored in the `eoi` (Expression of Interest) table

### 🔹 Job Listings
- Automatically fetch and display all job postings from the `jobs` table
- Includes sorting by job type (Full-time / Part-time / Internship)

### 🔹 Inquiry Form
- Allows general users to submit questions or inquiries
- Saved in the `inquiry` table

### 🔹 Manage Page (Admin Only)
- Requires login to access
- Admin dashboard allows viewing, updating, and deleting records from:
  - `jobs`, `eoi`, and `inquiry` tables
- Includes secure login validation

---

## 💻 Technologies Used

- PHP (server-side scripting)
- MySQL (database)
- HTML / CSS / JavaScript
- Bootstrap (for layout and responsiveness)

---

## ⚠️ Important Notes

> This project was originally designed to run on a **university-hosted local server** using XAMPP.  
> It connects to a MySQL database specific to our development environment.  
> As such, the live demo is not publicly available, but source code and structure are provided here.

---
