# MenaCode

A full-stack competitive programming platform built with Next.js, Express, and a custom online judge.

Users can solve programming problems, submit code, compete in contests, and track their rankings in real time.

---

## Features

- **Online Judge** — C++17 compilation and execution with NSJail sandboxing and cgroup v2 resource control
- **Contest System** — Create and join contests with live standings and Codeforces-style rating
- **Problem Archive** — Browse, search, and solve problems with an in-browser Monaco code editor
- **Real-time Chat** — Private messaging powered by Socket.IO
- **Leaderboard & Rankings** — Persistent rating system across contests
- **Admin Dashboard** — Manage users, problems, contests, and submissions

---

## Tech Stack

| Layer | Technologies |
|-------|-------------|
| Frontend | Next.js 16, React 19, TypeScript, Tailwind CSS, shadcn/ui, Monaco Editor |
| Backend | Node.js, Express 5, Socket.IO, Prisma ORM, Zod |
| Database | PostgreSQL |
| Judge | C++17, g++, NSJail, cgroup v2 |
| Auth | JWT, Google OAuth, 42 OAuth |
| DevOps | Docker Compose, NGINX, GitHub Actions, Github Container Registry |

---

## My Contributions

**Role:** Technical Lead / Developer

- **Homepage & Navigation** — Designed and built the responsive homepage with contest countdown, leaderboard preview, and announcements section
- **Problems & Submissions** — Implemented problem browsing, code editor integration, and submission flow
- **Problem CRUD** — Built the full problem creation, editing, and deletion system for admins
- **Rating System** — Built the Codeforces-inspired rating algorithm for contest rankings
- **Code Quality** — Eliminated all TypeScript and ESLint errors across the frontend codebase (~20 files)
- **Docker & DevOps** — Configured multi-service Docker Compose, NGINX reverse proxy, and scalable judge workers
- **CI/CD** — Set up GitHub Actions workflows for linting, type checking, and Docker image publishing to GitHub Container Registry
- **AWS Deployment** — Containerized deployment pipeline to AWS (in progress)

---

## Contact & Updates

This repository is private and the platform is not yet publicly available. Follow the organization for future updates:

[MenaCode0x0 on GitHub](https://github.com/MenaCode0x0)
