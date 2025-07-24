# 🧱 Contractor Attendance Management and Payment Tracker System

## 📌 Project Overview

The Contractor Attendance and Payment Management System is a full-stack web application designed to help contractors manage multiple construction or service-based projects. It simplifies the process of adding workers, tracking their daily attendance, and monitoring project payments in a centralized and organized manner.

## 📖 Project Explanation

Each contractor can log into the system and create projects that may involve either contract-based or daily-based workers. For every project, the contractor can:

- Add workers based on their work type (contract or daily)
- Mark attendance for each day, selecting workers and uploading image proof
- View attendance sheets for any date, including present workers and uploaded images
- Manage and update payments, with different logic for contract and daily projects

- **Contract-based Projects:** The contractor enters the total amount received; the system calculates the pending amount automatically.
- **Daily-based Projects:** The contractor manually enters both the total amount received and the pending amount.

All data—including users, projects, workers, attendance, and payments—is stored and managed using a MySQL database. The backend is built using Node.js with Express.js, while the frontend uses HTML, CSS, and JavaScript. This project demonstrates how a contractor’s day-to-day project tracking operations can be streamlined using a user-friendly and efficient digital system.
