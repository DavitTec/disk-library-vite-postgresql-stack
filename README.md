# Disk library vite postgresql stack

<image-card alt="TypeScript" src="https://img.shields.io/badge/TypeScript-007ACC?style=flat&logo=typescript&logoColor=white" ></image-card>
<image-card alt="PostgreSQL" src="https://img.shields.io/badge/PostgreSQL-316192?style=flat&logo=postgresql&logoColor=white" ></image-card>
<image-card alt="Vite" src="https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white" ></image-card>

**v0.0.2** — A clean, production-ready starter boilerplate for complex relational applications using **Vite + React + TypeScript** frontend and a lightweight **Hono + PostgreSQL** backend.

Built specifically for projects that need strong table relationships (disks, locations, health monitoring, ownership history, deduplication, snapshots, etc.). Perfect base for inventory systems, asset management, disaster-recovery tools, or any multi-table PostgreSQL app.

> created as the foundation for a larger "Disaster Recovery Plan" project. Now open-sourced as a reusable starter.

![Dashboard](https://raw.githubusercontent.com/DavitTec/disk-library-vite-postgresql-stack/main/images/Dashboard.png)
![Dashboard-mobile](https://raw.githubusercontent.com/DavitTec/disk-library-vite-postgresql-stack/main/assets/preview/Dashboard-Mobile.png)
![Dashboard-mobile](https://raw.githubusercontent.com/DavitTec/disk-library-vite-postgresql-stack/main/assets/preview/Disks-Mobile.png)
![Dashboard-mobile](https://raw.githubusercontent.com/DavitTec/disk-library-vite-postgresql-stack/main/assets/preview/Locations-Mobile.png)
![Dashboard-mobile](https://raw.githubusercontent.com/DavitTec/disk-library-vite-postgresql-stack/main/assets/preview/Health-Monitoring-Mobile.png)

---

---_(add a more screenshots later)_

---

## ✨ Features

- Modern Vite + React + TypeScript frontend
- Lightweight Hono + `pg` proxy backend (no heavy Express/Next.js)
- Full CRUD for core entities (Locations, Disks, Health Logs)
- Live Dashboard with real-time stats
- Clean separation: `src/lib/*-queries.ts` for all API calls
- Ready for schema expansion (deduplication, snapshots, backups, tasks)
- CORS, error handling, and loading states included
- Easy local development with one command (`pnpm dev:all`)

---
