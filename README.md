# Stepwise
>  — a step-by-step event/workflow tracker.

[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)]
[![Node.js](https://img.shields.io/badge/node-%3E%3D14-brightgreen.svg)]


## About
**Stepwise**  is a lightweight app for listing and tracking upcoming events with role-based access (Admin / Super Admin / Normal User). Users can view, like, filter and export events. Admins can add/edit/delete events, and Super Admin can approve/deny special requests.

---

## Features
- Role-based access: Admin, Super Admin, Normal User
- Add / Edit / Delete events (Admin)
- Like events and view liked events (User)
- Filter, sort, export event lists (User)
- Super Admin approval workflow for special events
- Email OTP signup flow
- Simple REST backend + React frontend

---

## Tech Stack
- Node.js (backend & frontend tooling)
- Express.js (backend)
- MongoDB (database)
- Mongoose (ODM)
- React (frontend)

---

## Prerequisites
- Node.js (LTS recommended) — https://nodejs.org/en/download/  
- MongoDB Community Server — https://www.mongodb.com/try/download/community  
- Git

---

Project structure (expected / example)
Stepwise/
 ┣ backend/
 ┃ ┣ index.js
 ┃ ┣ package.json
 ┃ ┣ routes/
 ┃ ┣ controllers/
 ┃ ┣ models/
 ┃ ┗ config/
 ┣ client/ (or frontend/)
 ┃ ┣ package.json
 ┃ ┣ src/
 ┃ ┃ ┣ components/
 ┃ ┃ ┣ pages/
 ┃ ┃ ┗ App.jsx
 ┣ SRS.pdf
 ┣ Design_doc.pdf
 ┣ Test_Document.pdf
 ┣ README.md
 ┗ .gitignore

User Roles & Functionality Summary

Admin

Login (admins added directly to DB)

Add / Edit / Delete events

See events created by admin and liked events

View clash warnings while adding events

Normal User

Signup via email OTP

Login

View events (table & details)

Like/Unlike events, filter & sort, export events

Dashboard with liked events

Super Admin

Access via protected URL 

Approve/Deny pending event requests

---
Contact

Created / maintained by Ridhi Jolly — GitHub: https://github.com/jollyridhi
