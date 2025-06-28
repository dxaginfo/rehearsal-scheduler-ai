# Rehearsal Scheduler

Automated rehearsal scheduling web app for bands, studios, orchestras.

## Features
- Efficient scheduling with group availability
- Attendance tracking
- Automated reminders/notifications
- Resource booking (rooms/equipment)
- Calendar integration (Google/Outlook)
- Analytics dashboard
- Mobile responsive
- Secure OAuth authentication

## Tech Stack
- Front-end: React.js
- Back-end: Node.js/Express
- Database: PostgreSQL
- Deployment: Docker, GitHub Actions, AWS/Vercel

## Setup
1. Clone the repo
2. See `/frontend` and `/backend` folders for codebase
3. Configure `.env` for each service
4. Use Docker Compose for dev/test run

## Deployment
- Push to main for CI/CD deploy
- Requires API keys for calendar/email (see docs)

## Security
- OAuth2 login required
- HTTPS only

---
For detailed design, see the Google Docs project plan: https://docs.google.com/document/d/1z_SGCZ0RnXPOpzxcPtRvUiFAeTA6P8yML3kAXvo98_k/edit