<!-- Generated from the personal-portfolio repo (profile.json + CV data) by `npm run readme`. Do not edit by hand: changes here are overwritten. -->

# Ezequiel Olivero

**Full Stack AI Engineer** · TypeScript · React · Node.js · Claude API

📍 Argentina (UTC−3) · Open to remote roles worldwide · Relocating to Norway

[Portfolio](https://ezequielolivero.dev) · [Résumé (PDF)](https://ezequielolivero.dev/CV.pdf) · [LinkedIn](https://www.linkedin.com/in/ezequiel-olivero/) · [Email](mailto:eze.olivero96@gmail.com)

## About

Full stack engineer who ships LLM features end to end. On Sunnsteel, my training platform in production, I built two Claude-powered features with structured outputs, grounded answers, evals on every pull request and per-member cost limits. Before that, 4+ years at Trii Software: I moved an enterprise SaaS frontend to Single-SPA microfrontends (~10 modules) and built most of its real-time omnichannel chat.

## Tech stack

| Area | Tools |
| --- | --- |
| **AI engineering** | Claude API, structured outputs, validation and repair, grounding, evals, prompt-injection tests, cost control |
| **Agentic workflow** | Claude Code, Codex, CLAUDE.md / AGENTS.md project specs, agent-driven work with human review |
| **Frontend** | React, Next.js, TypeScript, Tailwind CSS, shadcn/ui, Material UI, TanStack Query, Redux Toolkit, Zustand |
| **Architecture** | Microfrontends (Single-SPA), component libraries, Storybook, IndexedDB, Web Workers |
| **Backend** | Node.js, NestJS, Express, PostgreSQL, Prisma, MongoDB, AWS Cognito, WebSockets, WebRTC |
| **Testing & Tooling** | Jest, Vitest, Playwright, GitHub Actions, Git, Azure DevOps |

## Experience

### Full Stack Developer (Frontend-focused) · Trii Software

*Jul 2022 – Oct 2026 · Remote* — Enterprise omnichannel SaaS for chat, ticketing and business operations.

- **Architecture:** Researched and introduced a Single-SPA microfrontend architecture, migrated ~10 modules to it and mentored two teammates on adoption.
- **Omnichannel chat:** Built ~90% of a real-time chat spanning WhatsApp, Facebook and Instagram (WebSockets, WebRTC, webhooks), then refactored it into a decoupled architecture.
- **Performance:** Cut load time of the data-heavy chat view from ~4–5 s to under 1 s with cache-first loading (IndexedDB + Web Workers) and list virtualization.
- **Shared code & APIs:** Built a shared chat module (Single-SPA parcels), an internal React component library (Storybook, npm) and Express/MongoDB APIs; designed auth on AWS Cognito.

## Featured project

### [Sunnsteel](https://sunnsteel-frontend.vercel.app/) · Training platform with paid AI features, built end to end

- **LLM features:** Claude-powered routine drafts and training reviews with structured outputs (JSON Schema), domain checks plus one automatic repair call, and server-side fallback when the model declines.
- **Grounding & evals:** Reviews cite only numbered facts computed from the member's own workouts. 15 recorded eval cases, including prompt injection, run on every pull request, plus live runs.
- **Cost control:** Per-model token pricing, a usage ledger, monthly quotas per plan and a global cost ceiling.
- **Stack & quality:** Next.js, NestJS + PostgreSQL, English and Spanish PWA. 569 frontend and 403 API tests, CI on GitHub Actions, Vercel and Railway.

## Education

- **Technical Degree in Software Development** · ITEC (2021 – 2024)

**Courses**

- Full Stack Web Development · University of Helsinki
- JavaScript Algorithms & Data Structures · freeCodeCamp
- Full Stack Development · The Odin Project

## Languages

Spanish Native · English C2 · Norwegian A1 (learning)

## GitHub stats

![GitHub stats](https://github-readme-stats.vercel.app/api?username=ezee969&show_icons=true&theme=default&hide_border=true)
![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=ezee969&layout=compact&theme=default&hide_border=true)
