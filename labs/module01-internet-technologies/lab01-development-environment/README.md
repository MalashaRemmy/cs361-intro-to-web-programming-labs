# Lab 01 — Local Web Development Environment Setup

## Introduction

This lab focused on preparing a complete local web development environment for modern web application development.

Before building websites and full-stack applications, it is important to configure the tools, editors, runtime environments, and workflows used throughout the development process.

The goal of this lab was to create a stable and productive workspace for future practical work throughout the CS361 course.

---

## Objectives

The objectives of this lab were to:

- Install and configure Visual Studio Code
- Install Git for version control
- Create and configure a GitHub account and repository
- Install and configure XAMPP
- Explore browser developer tools
- Understand the purpose of local development environments
- Prepare the system for frontend and backend web development

---

## Tools Installed

### Visual Studio Code
Used as the primary code editor for writing and managing web development projects.

### Git & GitHub
Used for version control, repository management, and project tracking.

### XAMPP
Used to provide:
- Apache web server
- PHP runtime environment
- MySQL database server

### Chrome DevTools
Used for:
- inspecting HTML and CSS
- monitoring network requests
- debugging JavaScript
- analysing HTTP headers

---

## Activities Completed

### 1. VS Code Setup
Installed VS Code and configured essential extensions:
- Live Server
- Prettier
- PHP Intelephense
- GitLens

### 2. Git Configuration

Configured Git locally using:

```bash
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
```

### 3. GitHub Repository Creation

Created the course repository:

```text
cs361-intro-to-web-programming-labs
```

The repository is intended to serve as:
- a laboratory archive,
- a technical learning resource,
- and a long-term documentation portfolio.

### 4. XAMPP Installation

Installed and tested:
- Apache server
- MySQL server
- PHP environment

Verified successful setup by running localhost in the browser.

### 5. Browser Developer Tools

Explored:
- Elements panel
- Network tab
- Console
- Sources tab
- HTTP request headers

---

## Folder Structure

```text
cs361-intro-to-web-programming-labs/
│
├── docs/
├── labs/
├── assets/
└── references/
```

---

## Key Concepts Learned

### Local Development Environment
A local development environment allows developers to build and test applications on their own machine before deployment to production servers.

### Client-Server Architecture
Browsers act as clients that send requests to web servers, which respond with web resources such as HTML, CSS, JavaScript, and data.

### Version Control
Git allows tracking project changes over time, while GitHub enables remote collaboration and repository hosting.

### Web Servers
Apache serves web files locally and processes server-side scripts such as PHP.

---

## Challenges Encountered

Some initial challenges included:
- understanding Git workflow concepts,
- configuring environment variables,
- and understanding how local servers differ from static file execution.

These challenges highlighted the importance of development environment configuration in professional web development workflows.

---

## Lessons Learned

This lab demonstrated that web development involves much more than writing code. Professional development requires:
- proper tooling,
- structured workflows,
- debugging skills,
- version control,
- and environment management.

Setting up a reliable foundation early simplifies future development work significantly.

---

## Screenshots

Screenshots documenting the setup process are stored in the `screenshots/` directory.

---

## References

- MDN Web Docs
- W3Schools
- The Odin Project
- PHP Manual
- Git Documentation