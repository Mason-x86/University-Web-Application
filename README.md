# Course Management System (Express + EJS)

A university project that demonstrates a fully functioning **course management platform** built using
**Node.js**, **Express**, and **EJS**. The application allows teachers to create and manage courses,
enroll students, track progress, and view course-related information.  

This project received a **final grade of 86%**, reflecting strong implementation quality, clean code,
and thoughtful UX design.

---

## Key Features

### Teacher-Focused Tools
- Create, update, and delete courses  
- Enroll and manage students per course  
- View course rosters and student details  
- Manage coursework and information pages

### Offline-Capable / Installable Web App
This project includes a lightweight app manifest and service-worker-based caching approach that
allows the system to:

- Be **installed as a web app** on mobile devices  
- Run **offline** with cached pages  
- Load quickly even on slow networks  

Users can add it to their homescreen and launch it like a native app.

### Clean Templating with EJS
- EJS templates for views  
- Partial components for header/footer  
- Clean separation of routes, views, and controllers

### Backend with Express
- Modular route structure  
- REST-style endpoints  
- Middleware for validation and routing  
- Robust error handling

---

## Tech Stack

**Backend:** Node.js, Express  
**Frontend:** EJS templates, vanilla JS, HTML/CSS  
**Database:** (Depending on your implementation — SQLite, MySQL, or in-memory data for demo)  
**Offline Capabilities:** Service Worker, Web App Manifest  
