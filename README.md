# 🌐 Nilesh Banik — Personal Portfolio Website

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Responsive Design](https://img.shields.io/badge/Design-Responsive-brightgreen?style=for-the-badge)]()

A clean, modern, and fully responsive personal portfolio website designed to showcase frontend development skills, projects, educational background, and technical proficiencies.

---

## 📑 Table of Contents

- [Overview](#-overview)
- [Key Features & Sections](#-key-features--sections)
- [Technologies & Tools](#-technologies--tools)
- [Directory Structure](#-directory-structure)
- [Responsive Breakpoints](#-responsive-breakpoints)
- [Getting Started](#-getting-started)
- [Deployment Guidelines](#-deployment-guidelines)
- [Author & Contact](#-author--contact)

---

## 🌟 Overview

This project is a personal portfolio created by **Nilesh Banik**, a 4th-year undergraduate student at **IIEST Shibpur** (B.Tech in Mechanical Engineering) pursuing software and frontend web development.

The website delivers a seamless browsing experience with smooth scrolling navigation, glassmorphism UI elements, dynamic mobile navigation, and interactive project cards.

---

## 📌 Key Features & Sections

- **Hero / Profile Section:**
  - Introduction with call-to-action buttons (*Download CV* and *Contact Info*).
  - Quick-access social links for GitHub and LinkedIn.
- **About Me Section:**
  - Summary cards highlighting experience level and educational background at IIEST Shibpur.
  - Academic bio and personal focus on frontend development.
- **Experience & Skills Matrix:**
  - **Frontend Development:** HTML, CSS, JavaScript, Bootstrap.
  - **Backend & Core Tools:** Python, C, MySQL, Git.
- **Projects Showcase:**
  - Card-based grid showcasing projects with thumbnail previews, GitHub repository buttons, and Live Demo links.
- **Contact Section:**
  - Direct Gmail compose integration and LinkedIn profile connection.
- **Header & Navigation:**
  - Desktop navbar with smooth scrolling anchor links.
  - Mobile hamburger drawer with animated transformation into a close button.

---

## 🛠️ Technologies & Tools

| Technology | Purpose |
| :--- | :--- |
| **HTML5** | Semantic layout structure and accessibility elements. |
| **CSS3** | Modern styling, Flexbox layout, CSS transitions, and glassmorphism effects (`backdrop-filter`). |
| **JavaScript (ES6)** | DOM manipulation for the responsive hamburger menu toggle. |
| **Google Fonts** | `Poppins` typeface (weights: 300, 400, 500, 600). |
| **Git & GitHub** | Version control and source code hosting. |

---

## 📁 Directory Structure

```text
portfolio/
├── assets/                  # Static media assets & icons
│   ├── about-pic1.png       # About section photo (optimized)
│   ├── arrow.png            # Navigation down-arrow icon
│   ├── checkmark.png        # Skill checkmark bullet icon
│   ├── education.png        # Education badge icon
│   ├── email.png            # Email contact icon
│   ├── experience.png       # Experience badge icon
│   ├── favicon.png          # High-resolution PNG favicon
│   ├── github.png           # GitHub brand icon
│   ├── linkedin.png         # LinkedIn brand icon
│   ├── profile-pic.png      # Hero profile photo (optimized)
│   ├── project-1.png        # Project 1 preview thumbnail
│   ├── project-2.png        # Project 2 preview thumbnail
│   └── resume-example.pdf   # Downloadable curriculum vitae (CV)
├── favicon.ico              # Browser tab icon
├── index.html               # Main website entry point & structure
├── style.css                # Base stylesheet, typography, and section layouts
├── mediaqueries.css         # Breakpoints for mobile, tablet, and widescreen devices
├── script.js                # Interactive logic (menu toggle)
├── .gitignore               # Ignored system and editor files
├── LICENSE                  # MIT open-source license
└── README.md                # Project documentation
```

---

## 📱 Responsive Breakpoints

The portfolio includes custom media query rules defined in `mediaqueries.css`:

* **Desktop / Large Screens (> 1400px):** Full multi-column Flexbox layout with expanded navigation and side-by-side section containers.
* **Laptops & Small Desktops (≤ 1400px):** Adjusted profile margins and flexible container wrapping.
* **Tablets (≤ 1200px):** Switched from top navigation bar to compact hamburger menu; converted multi-column grids to vertical flow.
* **Mobile Devices (≤ 600px):** Scaled down typography, stacked action buttons, optimized thumbnail heights, and full-width touch-friendly layouts.

---

## 🚀 Getting Started

### Local Setup

No compilation or external dependencies are required. You can run the website directly in any web browser:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/nilbanik/portfolio.git
   ```
2. **Navigate into the project folder:**
   ```bash
   cd portfolio
   ```
3. **Launch the site:**
   * Double-click `index.html` to open it in your default web browser, **or**
   * Use the VS Code **Live Server** extension (right-click `index.html` -> *Open with Live Server*), **or**
   * Run a local HTTP server with Python:
     ```bash
     python -m http.server 8000
     ```
     Then open `http://localhost:8000` in your browser.

---

## 🌐 Deployment Guidelines

When deploying this project to static hosting services (such as **GitHub Pages**, **Vercel**, **Netlify**, or **Cloudflare Pages**):

> **Note**: `index.html` serves as the standard root entry point and works out of the box with GitHub Pages and all major static web hosts.

---

## 📬 Author & Contact

**Nilesh Banik**
* 📧 **Email:** [baniknilesh2@gmail.com](mailto:baniknilesh2@gmail.com)
* 💼 **LinkedIn:** [linkedin.com/in/nilesh-banik-096183302](https://www.linkedin.com/in/nilesh-banik-096183302/)
* 🐙 **GitHub:** [github.com/nilbanik](https://github.com/nilbanik)
