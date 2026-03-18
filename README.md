# Disk library vite postgresql stack

**v0.0.1** — A clean, production-ready starter boilerplate for complex relational applications using **Vite + React + TypeScript** frontend and a lightweight **Hono + PostgreSQL** backend.

Built specifically for projects that need strong table relationships (disks, locations, health monitoring, ownership history, deduplication, snapshots, etc.). Perfect base for inventory systems, asset management, disaster-recovery tools, or any multi-table PostgreSQL app.

> Originally created as the foundation for a larger "Disaster Recovery Plan" project. Now open-sourced as a reusable starter.

<img src="https://github.com/DavitTec/disk-library-vite-postgresql-stack/blob/main/assets/preview/Dashboard.png?raw=true" alt="Dashboard.png" style="zoom:33%;" /><img src="https://github.com/DavitTec/disk-library-vite-postgresql-stack/blob/main/assets/preview/Dashboard-mobile.png?raw=true" alt="Dashboard.png" style="zoom:33%;" />

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
