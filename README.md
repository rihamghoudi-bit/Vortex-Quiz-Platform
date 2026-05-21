# 🌌 Vortex — Modern Quiz Management Platform

**Vortex** is a professional, web-based quiz management platform designed with a modern, responsive user interface. It features distinct workflows and dashboards for students, teachers, and administrators to seamlessly create, manage, and take quizzes.

---

## ✨ Features

* **Role-Based Access Control (RBAC):** Separate interfaces and privileges for Admins, Teachers, and Students.
* **Dynamic Quiz Engine:** Track user attempts, scores, and manage categories effortlessly.
* **Modern UI/UX:** Built with a clean aesthetic, optimized layouts, and smooth navigation.
* **Secure Authentication:** Secure registration, login, and session management.

---

## 📂 Project Structure

Here is the directory layout of the repository based on the core architecture:

```text
quiz-platform1/
├── assets/             # CSS stylesheets, JS scripts, and media files
├── config/             # Database connection and environment configurations
├── dashboard/          # Role-specific dashboard layouts (Admin, Teacher, Student)
├── includes/           # Reusable components (Header, Footer, Navbar, Functions)
├── quiz/               # Quiz execution logic and question processors
├── index.php           # Landing page / Portal entryway
├── login.php           # User authentication page
├── logout.php          # Session termination script
├── register.php        # User registration portal
└── update_db.php       # Database migration / Setup script
