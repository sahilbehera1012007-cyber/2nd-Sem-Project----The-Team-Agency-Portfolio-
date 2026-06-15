# The Team Agency Portfolio

A responsive **DOM & Layout** project that presents a fictional agency portfolio for a team of 5–6 members. The website is built as a data-driven landing page that highlights team profiles, technical skills, GitHub links, featured projects, a light/dark theme toggle, and a contact form with client-side validation.[page:1]

## Overview

The Team Agency Portfolio is designed to demonstrate core front-end development concepts using semantic HTML, modern CSS, and JavaScript DOM manipulation. The project focuses on layout structuring, reusable data rendering, theme persistence, and interactive form validation.[page:1]

## Features

- Data-driven rendering of 5–6 team member cards.
- Each member card includes avatar, name, role, skills, and GitHub profile link.
- Dedicated project showcase section for displaying agency work.
- Responsive landing page layout for desktop, tablet, and mobile screens.
- Light/Dark theme toggle for better user experience.
- Theme preference saved using `localStorage`.
- Contact form with client-side validation for fields like name, email, and message.
- Clean UI with semantic structure and accessible design practices.[page:1]

## Tech Stack

- **HTML5** for semantic page structure
- **CSS3** for styling, layout, and responsiveness
- **JavaScript (DOM)** for dynamic rendering, theme toggle, and form validation
- **localStorage** for saving theme preference[page:1]

## Learning Goals

This project was created to practice and demonstrate:

- DOM manipulation using JavaScript
- Data-driven UI rendering
- Responsive web layout design
- Light/Dark mode implementation
- Form validation on the client side
- Structuring a real-world landing page project[page:1]

## Project Structure

```bash
The-Team-Agency-Portfolio/
│── index.html
│── style.css
│── script.js
│── assets/
│   ├── avatars/
│   ├── icons/
│   └── images/
└── README.md
```

## Sections Included

### 1. Hero Section
Introduces the agency with a heading, short description, and call-to-action button.

### 2. Team Members Section
Displays 5–6 team members dynamically using JavaScript objects/arrays. Each card includes:

- Avatar
- Name
- Role
- Skills
- GitHub profile link

### 3. Projects Showcase
Highlights the projects completed by the team in a visually organized layout.

### 4. Theme Toggle
Allows users to switch between light and dark mode, with the selected theme stored in `localStorage`.

### 5. Contact Form
Includes client-side validation to ensure correct user input before submission.[page:1]

## How It Works

### Team Data Rendering
Team member information is stored in JavaScript as structured data and rendered dynamically into the DOM.

### Theme Persistence
The website checks saved theme settings from `localStorage` and applies the selected mode when the page loads.

### Form Validation
JavaScript validates user input for required fields, correct email format, and empty message handling before allowing submission.[page:1]
