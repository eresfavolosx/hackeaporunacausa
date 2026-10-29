# Hackea por una Causa — Youth Mentorship & Scheduling App

[![Live](https://img.shields.io/badge/site-hackea.novu.works-0f172a?style=flat-square)](https://hackea.novu.works)
![React](https://img.shields.io/badge/React%2015-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Redux](https://img.shields.io/badge/Redux-764ABC?style=flat-square&logo=redux&logoColor=white)
![Node.js](https://img.shields.io/badge/Express-339933?style=flat-square&logo=node.js&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)

*Read in Spanish below · [Versión en español](#-español)*

Built at the **Hackea por una Causa** social-impact hackathon in Puerto Rico (2017). The app **recruits professional mentors and schedules their sessions with at-risk youth** at Boys & Girls Clubs and community centers across the island.

> **▶ Project site:** **[hackea.novu.works](https://hackea.novu.works)** · Part of the [NovuWorks portfolio](https://novu.works)

---

## The Problem

Community centers serving at-risk youth struggle to **find, vet, and schedule** volunteer mentors. Coordination ran on phone calls and spreadsheets. Mentors didn't know where they were needed, and centers couldn't plan.

## The Solution

| Feature | Description |
| --- | --- |
| **Institutions directory** | Browse participating centers (Boys & Girls Clubs of Puerto Rico and others) |
| **Appointments** | Mentors book sessions; centers see who is coming and when |
| **Appointment details** | Session info, location, and mentor/institution context |
| **Mentor profiles** | Professional background and participation history |
| **REST API** | Express + Mongoose backend with models, controllers, and routes |

## Tech Stack

- **Frontend:** React 15, Redux (custom reducer factory and middleware), React Router 4, SCSS modules, Flow, ESLint/Stylelint
- **Backend:** Node.js, Express, Mongoose/MongoDB, body-parser, CORS
- **Tooling:** Babel, PostCSS, nodemon

## Running Locally

```bash
git clone https://github.com/eresfavolosx/hackeaporunacausa.git
cd hackeaporunacausa

# API
npm install
npm run server            # Express + MongoDB (set your Mongo URI)

# Client
cd app
cp .env.example .env
npm install
npm start
```

## Project Structure

```text
├── index.js            # Express server entry
├── models/             # Mongoose schemas
├── controllers/        # Request handlers
├── routes/             # API routes
└── app/                # React + Redux client
    └── src/
        ├── pages/      # App, Institutions, Appointments, AppointmentDetails, Profile
        ├── components/ # Shared UI (Footer, ...)
        └── helpers/    # Reducer factory, middleware, UI state
```

## Team

Built during the hackathon by:

- **Fabián Vélez Vicente** ([@eresfavolosx](https://github.com/eresfavolosx))
- Luis Betancourt
- Leonardo Calderón
- Ryan González
- Arturo Santiago

> Forked from the team repository [`leodrez/hackeaporunacausa`](https://github.com/leodrez/hackeaporunacausa).

---

## 🇵🇷 Español

**Proyecto:** App para reclutamiento y calendarización de mentores profesionales para jóvenes en riesgo, desarrollada durante el hackatón *Hackea por una Causa* en Puerto Rico.

**Miembros:** Fabián Vélez · Luis Betancourt · Leonardo Calderón · Ryan González · Arturo Santiago
