# SACERT Website Portal

A GitHub-ready React/Vite website prototype for the **San Andres Community Emergency Response Team (SACERT)**.

## Features

- Public homepage
- About page
- Administrator login portal
- Member login portal
- Admin can create, edit, and remove member accounts
- Admin can issue digital IDs
- Admin can issue certificates
- QR verification page for ID/certificate validation
- Member dashboard with digital ID and certificate preview

## Demo Login

**Administrator**
```txt
Username: admin
Password: admin123
```

**Sample Member**
```txt
Username: juan
Password: 1234
```

## Installation

```bash
npm install
npm run dev
```

Then open the local URL shown in your terminal.

## Build for Production

```bash
npm run build
```

## Important Note

This is a front-end prototype. For real production use, connect it to a backend database and authentication system such as:

- Firebase
- Supabase
- Laravel API
- Node.js + Express + MySQL
- Django + PostgreSQL

Do not use plain text passwords in production.
