# Hi there 👋

Independent SWE — Fullstack & Backend
Building AI-native tools to modernise enterprise SaaS (ERP / SCM / HCM)
Exploring: LLM agents for legacy workflow automation

---

**TypeScript** · **Node.js** · **PostgreSQL** · **LangChain** · **Docker** · **Next.js** · **Python**

---

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=IcannAI&show_icons=true&hide_border=true&count_private=true&theme=default" height="150"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=IcannAI&layout=compact&hide_border=true&theme=default" height="150"/>
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=IcannAI&hide_border=true"/>
</div>

---

## 📌 Pinned Projects

### [erpnext-ai-research](https://github.com/IcannAI/erpnext-ai-research)
> LLM agent layer for SAP/Oracle workflows — natural language → ERP actions

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![CI](https://img.shields.io/badge/CI-passing-brightgreen?style=flat-square)
![Stars](https://img.shields.io/github/stars/IcannAI/erpnext-ai-research?style=flat-square)

**Benchmark**

| Task | Manual / Baseline | This Agent |
|------|-------------------|------------|
| PO creation | 4.2 s (GPT-4 raw) | 1.8 s |
| GL reconciliation | 20 min manual | 43 s automated |

---

### [my-next-beauty-project — GlowSocial](https://github.com/IcannAI/my-next-beauty-project)
> Production-ready KOL live-streaming e-commerce platform engineered for high concurrency, real-time engagement, and robust financial settlement

![Next.js](https://img.shields.io/badge/Next.js-15.x-black?style=flat-square&logo=next.js)
![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?style=flat-square&logo=typescript)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-15-336791?style=flat-square&logo=postgresql&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-E2E_120_tests-45ba4b?style=flat-square&logo=playwright&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-17%2F17_passing-C21325?style=flat-square&logo=jest)

**Highlights**
- Atomic checkout (`prisma.$transaction` + `SELECT FOR UPDATE`) — race condition protection against overselling
- Commission clawback — automatic `kolEarnings` decrement on refund approval
- Real-time chat & order notifications via Pusher Channels
- Datadog RUM + APM with custom business KPI dashboard
- Three-role RBAC: `USER` / `KOL` / `ADMIN`

**Stack:** Next.js 15 · Prisma · Neon Serverless PostgreSQL · Pusher · Cloudflare R2 · Zustand · shadcn/ui · Vercel Cron

---

### [taskflow-board](https://github.com/IcannAI/taskflow-board)
> Keyboard-first task OS for developers — AI-powered task breakdown + Git workflow visualisation

[![CI](https://github.com/IcannAI/taskflow-board/actions/workflows/ci.yml/badge.svg)](https://github.com/IcannAI/taskflow-board/actions/workflows/ci.yml)
![React](https://img.shields.io/badge/React-19-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-5.8-3178C6?style=flat-square&logo=typescript)
![License: ISC](https://img.shields.io/badge/License-ISC-blue?style=flat-square)

**Highlights**
- Zero prop-drilling architecture via Zustand
- Gemini API proxied through Vercel Edge Function — API key never bundled into client JS
- Command palette (⌘K) with Fuse.js fuzzy search + full keyboard navigation
- AI task breakdown: subtasks, branch name suggestion, time estimate in one call

**Stack:** React 19 · Vite 6 · Zustand · Tailwind CSS · Recharts · Fuse.js · Vercel Edge Functions

---

### [mitaya-restaurant](https://github.com/IcannAI/mitaya-restaurant)
> Production-quality restaurant SPA — accessibility-first, i18n, full Zod schema validation

![React](https://img.shields.io/badge/React-19-61DAFB?style=flat-square&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-5.8-3178C6?style=flat-square&logo=typescript)
![Vite](https://img.shields.io/badge/Vite-6.5-646CFF?style=flat-square&logo=vite)
![License: ISC](https://img.shields.io/badge/License-ISC-blue?style=flat-square)

**Highlights**
- `reservationSchema` (Zod v4) is the single source of truth — drives form validation, TypeScript types, and future API contracts
- Full keyboard navigation (Tab / Arrow / Enter / Esc) + ARIA roles
- English / Traditional Chinese i18n toggle (zero-dependency custom implementation)
- Domain-modelled around three bounded contexts: Menu · Order · Booking

**Stack:** React 19 · Vite · react-hook-form + Zod v4 · framer-motion · Tailwind CSS

---

## 🔬 Currently Researching

Research: where LLM agents plug into open-source ERP — procurement & inventory for hardware companies

Focused on ERP (procurement, GL, inventory) and the interface layer between natural language and structured workflows.

`agentic-workflows` · `enterprise-ai` · `erp-modernisation` · `llm-tool-use`

---

<div align="center">
  <sub>Open to interesting problems at the intersection of AI and enterprise software.</sub>
</div>
