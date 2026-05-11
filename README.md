# Asem Abdou

Senior Full-Stack Engineer | Technical Founder of MentorSimply & OpenPlanr | Building AI-Powered SaaS Platforms | Istanbul, Türkiye

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/asemabdo)
[![Email](https://img.shields.io/badge/asem@techarc.io-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:asem@techarc.io)
[![Website](https://img.shields.io/badge/asemabdo.com-000000?style=flat-square&logo=vercel&logoColor=white)](https://asemabdo.com)

---

## OpenPlanr — Spec-Driven AI Software Factory

[![npm](https://img.shields.io/npm/v/openplanr?label=CLI&color=cb3837)](https://www.npmjs.com/package/openplanr)
[![pipeline](https://img.shields.io/github/v/release/openplanr/planr-pipeline?label=pipeline&color=14B8A6)](https://github.com/openplanr/planr-pipeline)
[![license](https://img.shields.io/badge/license-MIT-green)](https://github.com/openplanr/planr-pipeline/blob/main/LICENSE)

Open-source protocol and toolchain that takes a feature spec from planning to shipped code across multiple AI runtimes — Claude Code, Cursor, and Codex.

**How it works:** write a brief → the pipeline decomposes it into user stories and tasks → 9 specialized AI agents generate production code, run tests, verify quality, and produce docs. Human reviews gate every phase transition. A partially-shipped spec on Claude Code can resume on Cursor and vice versa — the protocol is runtime-agnostic.

| Repo | What it does |
|---|---|
| [`planr-pipeline`](https://github.com/openplanr/planr-pipeline) | Claude Code plugin — 9 subagents, manifest-enforced tool restrictions, two-phase orchestration |
| [`OpenPlanr`](https://github.com/openplanr/OpenPlanr) | CLI — AI-powered agile planning, task decomposition, Linear sync, rule generation for Cursor/Codex |
| [`skills`](https://github.com/openplanr/skills) | Claude Code skill — multi-runtime routing (which surface to use when) |
| [`marketplace`](https://github.com/openplanr/marketplace) | Plugin marketplace for Claude Code |

**Key engineering decisions:**

- Per-task dispatch mode on Cursor/Codex (architectural fix for cumulative-context bias in continuous sessions)
- Project memory (`.planr/memory.md`) — agents learn from past failures across runs instead of repeating mistakes
- Write-time artifact validation — AI-generated output is structurally verified before touching disk
- Full JSON Schema conformance suite with CI enforcement

→ [openplanr.dev](https://openplanr.dev)

---

## MentorSimply — Mentorship SaaS Platform

Production-grade booking, payment, and onboarding system for premium mentorship.
Role-based architecture (mentor/student/admin), Stripe commission engine, Zoom session orchestration, referral system, AI-enhanced onboarding.

**Stack:** Next.js · TypeScript · NestJS · Prisma · PostgreSQL · Stripe · Zoom

→ [mentorsimply.com](https://mentorsimply.com)

---

## Selected Work

| Project | What | Stack | Link |
|---|---|---|---|
| **Self-Hosted Enterprise RAG Platform** | Privacy-first retrieval system with intent classification, server-side response guards, hybrid search, multilingual policy management, classifier warm-up + paraphrase-invariant evaluation harness | Python · FastAPI · Qdrant · OpenRouter · Opik | [modul.ac.at](https://modul.ac.at) |
| **Zero-Framework Agent Orchestration Platform** | Custom TypeScript agent runtime with multi-LLM routing (OpenRouter/Ollama), MCP tool protocol, database-level RBAC, and an adaptive AI portal as a unified entry point for public/staff/student roles | TypeScript · Hono · MCP · OpenAI SDK · Ollama | [modul.ac.at](https://modul.ac.at) |
| **Multi-Channel Customer Support Suite** | Real-time chat widget + WhatsApp + email with cross-department ticket routing, canonical phone identity dedup, in-app notifications with quiet hours, and full admin self-service | Next.js · TypeScript · Prisma · Twilio · Pusher | [modul.ac.at](https://modul.ac.at) |
| **Self-Hosted Event Registration & Checkout Platform** | Third-party event-platform replacement — cart-shaped multi-pass checkout with merch, admin-managed discount codes with per-unit Stripe Coupon sync, Dynamics CRM webhooks, and Microsoft Entra ID SSO | Next.js · TypeScript · Prisma · Stripe · Dynamics CRM · Entra ID | [modul.ac.at](https://modul.ac.at) |
| **Config-Driven Application Portal** | Admissions portal with CRM-spec-aligned form generation, draft persistence, demo-data harness, and embedded AI chat support | Next.js · TypeScript · Dynamics CRM · Vite | [modul.ac.at](https://modul.ac.at) |
| **Enterprise CMS with Embedded AI Widget** | Sitefinity public-site platform with self-healing embedded chat widget, IIS GitHub Actions CI/CD, rollback-safe production deploys, and role-based landing pages | Sitefinity · .NET · IIS · GitHub Actions · PowerShell | [modul.ac.at](https://modul.ac.at) |
| **BookSimply.io** | Direct booking engine with calendar sync and secure API layer | Next.js · REST API | [booksimply.io](https://booksimply.io) |
| **TechArc.io** | AI project planning — converts briefs/PDFs into structured roadmaps with timeline and pricing | SaaS | [techarc.io](https://techarc.io) |
| **FunderPro** | High-performance global corporate platform with modular content architecture | WordPress · API | [funderpro.com](https://funderpro.com) |
| **ImRed Knowledge Base** | Enterprise multisite CMS serving multiple brands from a single core | WordPress · WPML | [support.funderpro.com](https://support.funderpro.com) |
| **WP TeamHire** | ATS integration — real-time sync, multi-company architecture, structured application workflows | WordPress · REST API | — |
| **Enterprise CMS** | Scalable systems on TYPO3 (Mapo.at), CraftCMS (Tixee), and advanced WordPress ecosystems | Various | — |

---

## Stack

TypeScript · JavaScript · PHP · React · Next.js · Node.js · NestJS · Prisma · PostgreSQL · MySQL · Docker · CI/CD · Stripe · REST APIs

---

## GitHub Activity

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=AsemDevs&theme=radical" />
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=AsemDevs&theme=radical" />
</p>

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=AsemDevs&theme=radical" />
</p>

---

## Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/asemabdo)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:asem@techarc.io)
[![Website](https://img.shields.io/badge/Website-000000?style=flat-square&logo=vercel&logoColor=white)](https://asemabdo.com)
[![MentorSimply](https://img.shields.io/badge/MentorSimply-2563EB?style=flat-square)](https://mentorsimply.com)
[![OpenPlanr](https://img.shields.io/badge/OpenPlanr-14B8A6?style=flat-square&logoColor=white)](https://openplanr.dev)

---

*I build systems, not pages. Every platform I ship is modular, API-driven, and designed for growth.*
