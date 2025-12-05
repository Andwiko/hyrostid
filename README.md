# Hyrost Community Platform

A full-stack community website inspired by Hytale.com, featuring:
- Admin & user login (Google/email)
- Membership system
- Forum (threaded discussion)
- Private & group chat
- User profiles
- Admin dashboard

## Tech Stack
- **Backend:** Node.js (Express)
- **Database:** PostgreSQL
- **Frontend:** React

## Folder Structure
```
/backend      # Express API (auth, forum, chat, membership, admin)
/frontend     # React app (UI, pages, components)
/database     # SQL migrations & seeds
/.github      # Copilot instructions & workflows
```

## Setup & Development
See each folder for setup instructions. Example `.env` files and further documentation will be provided.

---

## Saran & Best Practice
- Gunakan JWT untuk autentikasi user & admin
- Gunakan WebSocket (socket.io) untuk chat real-time
- Pisahkan role user & admin di database
- Gunakan ORM (Sequelize/Prisma) untuk integrasi PostgreSQL
- Siapkan sistem moderasi forum & chat
- Tambahkan verifikasi email & reset password
- Siapkan sistem notifikasi (in-app/email)
- Gunakan environment variable untuk data sensitif
- Dokumentasikan API & endpoint

---

> Untuk fitur lanjutan (payment, upload gambar, dsb) bisa ditambahkan sesuai kebutuhan.
