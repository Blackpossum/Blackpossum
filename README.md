<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d7d80,100:39c9cc&height=180&section=header&text=Yosaphat%20Harwindra&fontSize=42&fontColor=ffffff&fontAlignY=34&desc=Fullstack%20engineer%20%C2%B7%20Surakarta,%20Indonesia&descSize=16&descAlignY=54" alt="Yosaphat Harwindra, fullstack engineer, Surakarta, Indonesia" />
</p>

<p align="center">
  <a href="https://software-engineer-portfolio-lovat.vercel.app"><img src="https://img.shields.io/badge/Portfolio-0d7d80?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
  <a href="https://linkedin.com/in/yosaphat-harwindra"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:yosaphatharwindra@gmail.com"><img src="https://img.shields.io/badge/Email-39c9cc?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

Fullstack engineer with two years shipping production React and TypeScript for
laboratory-automation software: interfaces that configure and watch machines
that physically move. Now writing the other half of the contract too, with
Fastify, NestJS and PostgreSQL.

## Proof

**Formulatrix** · Frontend Software Engineer · Jul 2024 to May 2026

- **Design system.** 417 commits to the company React/MUI component library,
  2nd of 40+ contributors. Storybook docs, OTP/TOTP components, 86% test
  coverage. Eight product teams imported it, so every API change had to be right
  the first time.
- **Real-time robotics UI.** Fleet visualisation in React, Three.js and SignalR,
  holding 60fps through telemetry bursts. Built its Jenkins CI/CD pipeline.
- **Employee portal.** JWT with refresh-token rotation and role-based access,
  against ASP.NET Core contracts.

**Binary Studio Academy 2026** · top contributor on the team monorepo (50 of 118
commits), mostly auth: password reset, token handling, rate limiting.

## Featured

| Project | What it is | Stack |
| --- | --- | --- |
| [**parish-booking-system**](https://github.com/Blackpossum/parish-booking-system) · [live](https://parish-booking-frontend.vercel.app) | Meeting-room booking for a real parish in Surakarta. Parishioners request, the secretariat approves, a wall monitor shows today's schedule live. Double-booking is blocked at the database. | NestJS, Prisma, PostgreSQL, React PWA |
| [**bsa-2026-promtomat**](https://github.com/Blackpossum/bsa-2026-promtomat) | Production-style monorepo from Binary Studio Academy. Zod schemas shared between API and client so neither side can drift. | Fastify, Objection/Knex, PostgreSQL, React 19, RTK Query |
| [**software-engineer-portfolio**](https://github.com/Blackpossum/software-engineer-portfolio) · [live](https://software-engineer-portfolio-lovat.vercel.app) | My portfolio, rebuilt in code. Static routes, schema-validated content, Playwright across three browsers on every PR. | Next.js 16, React 19, GSAP, Vitest, Playwright |
| [**Project-Artemis**](https://github.com/Blackpossum/Project-Artemis) | A modular component library: the problem I spent a year on at work, rebuilt where I can show it. | TypeScript, pnpm workspaces, Storybook 10, Vite |

Most of what I have shipped lives in company repositories, so what is public
here is deliberately small.

## Stack

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/React-149ECA?style=flat-square&logo=react&logoColor=white" alt="React" />
  <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/Redux_Toolkit-764ABC?style=flat-square&logo=redux&logoColor=white" alt="Redux Toolkit" />
  <img src="https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white" alt="Three.js" />
  <img src="https://img.shields.io/badge/Storybook-FF4785?style=flat-square&logo=storybook&logoColor=white" alt="Storybook" />
  <br />
  <img src="https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Fastify-000000?style=flat-square&logo=fastify&logoColor=white" alt="Fastify" />
  <img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white" alt="NestJS" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt=".NET" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white" alt="Jenkins" />
</p>

**Real-time:** SignalR and WebSocket, with connection managers that recover
without lying to the operator about machine state. **Testing:** Jest, Vitest,
React Testing Library, Playwright. Tests go in with the component.

## How I work

- If the UI shows something the server has not confirmed, the UI says so.
  Optimistic is fine. Silent is not.
- A prop that two teams keep misusing is a bug in the API, not in the teams.
- I would rather delete a component than add a fifth boolean to it.

---

<sub>Trained in mechanical engineering before I wrote any code, which is
probably how I ended up writing software for machines. Surakarta, Indonesia ·
UTC+7.</sub>
