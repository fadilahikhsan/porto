# Labaku — Intelligent Financial Toolkit for Micro-Businesses

Labaku is a production-ready, full-stack Next.js application designed to empower micro, small, and medium enterprises (UMKM) with professional cashflow management, cost-of-goods sold (HPP) calculation, and role-based administration.

**Role & Contribution**
- Lead developer and architect: designed the data model, implemented secure auth flows, and built the admin & cashier dashboards.

**Highlights**
- Robust multi-tenant data model with UUID primary keys and strict Row-Level Security (RLS) for per-tenant isolation.
- End-to-end features: transactions, product cost breakdowns, configurable categories, and demo seed data for quick evaluation.
- Security-first: password hashing, RLS policies, and careful separation between global and tenant-scoped data.
- Developer-friendly: TypeScript, Next.js App Router, Tailwind CSS, and well-structured API routes for maintainability.

**Tech stack**
- Frontend: Next.js (App Router), React, Tailwind CSS
- Backend & DB: Node.js, PostgreSQL (UUID, RLS), SQL migration scripts
- Dev tooling: TypeScript, ESLint, Prettier

**Impact**
- Built for fast onboarding: includes seeded demo accounts and sensible defaults to showcase real use-cases.
- Production-ready architecture that’s easy to migrate to other Postgres hosts (pg_dump-compatible).

**Repository**
- Source: https://github.com/fadilahikhsan/Labaku

**Try it**
- Clone the repo and follow the `SETUP.md` for local development and database initialization.

For technical deep-dives or code walkthroughs, feel free to reach out — I can provide architecture diagrams, ERD, or a short demo session.
