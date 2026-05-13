# SkillSwap Frontend

A modern frontend for **SkillSwap**, a skill-exchange platform where users can learn, teach, and exchange services using credits instead of money.

---

## Overview

SkillSwap is designed to connect people who want to share their skills with others in their community.
The platform includes separate flows for users and providers, with clean dashboards, role-based navigation, service listings, bookings, wallet UI, and chat interface.

---

## Features

* User and provider authentication UI
* Role-based dashboard navigation
* User dashboard with nearby skills and upcoming exchanges
* Provider dashboard for managing services and bookings
* Service listing and service detail pages
* Booking flow UI
* Wallet and credit-based transaction interface
* Chat interface
* Responsive and clean Material UI design

---

## Tech Stack

| Technology   | Purpose                   |
| ------------ | ------------------------- |
| React        | Frontend development      |
| Material UI  | UI components and styling |
| React Router | Page routing              |
| Axios        | API communication         |
| CSS          | Custom styling            |

---

## Project Structure

```bash
src/
├── components/
│   ├── common/
│   ├── layout/
│   └── service/
├── context/
├── pages/
│   ├── user/
│   ├── provider/
│   └── admin/
├── routes/
└── App.jsx
```

---

## Installation

```bash
git clone https://github.com/shiwani2006/Frontend-Skillswap.git
cd Frontend-Skillswap
npm install
npm run dev
```

---

## Role Based Flow

| Role     | Redirect Path         |
| -------- | --------------------- |
| User     | `/user/dashboard`     |
| Provider | `/provider/dashboard` |
| Admin    | `/admin/dashboard`    |

---

## Main Pages

* Home
* Login
* Register
* User Dashboard
* Provider Dashboard
* Admin Dashboard
* Services
* Bookings
* Wallet
* Chat
* Profile

---

## Tagline

**Exchange skills. Build community. Grow together.**


---Home page---
<img width="1894" height="871" alt="image" src="https://github.com/user-attachments/assets/758dba8f-3c1e-446a-92c0-84646fc38f04" />




<img width="1888" height="852" alt="image" src="https://github.com/user-attachments/assets/524c97a4-ab57-46fe-a44f-cb46cbca8b3c" />

