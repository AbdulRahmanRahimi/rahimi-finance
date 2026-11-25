# Rahimi Finance

> **Internal tool** for [Rahimi Tech Solution](https://github.com/rahimiabdulrahmanab) · The source code is private.

A web-based financial management system for Rahimi Tech Solution. It replaced two Excel workbooks, **Project Finance** (the profit split for each project) and the **Cash Book** (a running cash balance), with a real-time, cloud-synced app that can be installed on any device.

## Features

- Project finance with automatic profit-split calculations
- Cash book with a running balance
- Live and shared: every admin sees the same data, and edits appear on all devices in real time
- Installable as a PWA on desktop, Android and iOS

## Engineering highlights

- **The database computes the money, never the browser.** Profit splits and the running balance come from PostgreSQL generated columns and views, so the figures can't drift.
- Row Level Security and Supabase Auth

## Tech stack

| Layer | Tools |
|---|---|
| Frontend | Next.js 16 (App Router, TypeScript), Tailwind CSS, shadcn/ui, Recharts, TanStack Table |
| Backend | Supabase: PostgreSQL, Auth, Row Level Security, Realtime |
| Hosting | Vercel · PWA |

---

Designed and built by **Abdul Rahman Rahimi**.
