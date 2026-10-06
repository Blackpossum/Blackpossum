<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d7d80,100:39c9cc&height=180&section=header&text=Yosaphat%20Harwindra&fontSize=42&fontColor=ffffff&fontAlignY=34&desc=Fullstack%20engineer%20%C2%B7%20Surakarta,%20Indonesia&descSize=16&descAlignY=54" alt="" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/React-149ECA?style=flat-square&logo=react&logoColor=white" alt="React" />
  <img src="https://img.shields.io/badge/Redux_Toolkit-764ABC?style=flat-square&logo=redux&logoColor=white" alt="Redux Toolkit" />
  <img src="https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Fastify-000000?style=flat-square&logo=fastify&logoColor=white" alt="Fastify" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white" alt=".NET" />
  <img src="https://img.shields.io/badge/Storybook-FF4785?style=flat-square&logo=storybook&logoColor=white" alt="Storybook" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
</p>

Frontend engineer in Surakarta. Two years on laboratory-automation software — the
interfaces people use to configure and watch machines that physically move.

Most weeks looked the same: a configuration form whose values end up on a robot
arm, a SignalR connection that drops mid-shift and has to recover without lying
to the operator about machine state, a component that eight product teams import
and therefore nobody can casually change. One week was 158 revisions to a
translation file because a button got renamed. That is the job. Less interesting
than the conference talks make it sound, and I like it anyway.

Currently on the other half of the stack — Fastify and PostgreSQL on a production
monorepo — because two years of consuming API contracts made me want to find out
what it costs to write one.

## What I work with

* **Core** TypeScript and React. Redux Toolkit and RTK Query wherever the server
  owns the truth and the cache has to be honest about it.
* **Real-time** SignalR and WebSocket. Connection managers, device event
  handling, and the mocks that let any of it be tested without the hardware
  plugged in.
* **Design systems** MUI, Storybook, Figma tokens. Component APIs other teams can
  adopt without reading the source, which turns out to be most of the work.
* **Testing** Jest and React Testing Library. Tests go in with the component, not
  in a cleanup sprint nobody schedules.
* **Backend** Node, Fastify, Objection and Knex, zod. C# and ASP.NET Core when
  the product already lives there.
* **Around it** PostgreSQL, Docker, Jenkins, pnpm workspaces.
* **Editor** Neovim on good days, VS Code on the days I want to ship something.

## A few things here

[**Project-Artemis**](https://github.com/Blackpossum/Project-Artemis) — A modular
component system in a pnpm monorepo, documented with Storybook 10 and Vite. The
same problem I spent a year on at work, rebuilt somewhere I am allowed to show it.

[**bsa-2026-promtomat**](https://github.com/Blackpossum/bsa-2026-promtomat) —
Binary Studio Academy 2026. Fastify, Objection/Knex and PostgreSQL behind React 19
and RTK Query, with the zod schemas shared between both halves so neither side can
drift. My commits are mostly auth: password reset, token handling, rate limiting.

[**Backend-Machine_Task_Orchestratin**](https://github.com/Blackpossum/Backend-Machine_Task_Orchestratin)
— Python server for managing tasks across multiple nodes. The typo in the repo
name has outlived several better-named projects.

[**React-app-3D-Design**](https://github.com/Blackpossum/React-app-3D-Design) — A
3D t-shirt configurator, React Three Fiber and Drei. Built to find out what
happens between a scene graph and a frame. Learning project, and I will say so.

None of these are frameworks. Most of what I have shipped lives in company
repositories, so what is public here is deliberately small.

## How I work

* Read the existing component before proposing a new one. Most of them are not
  badly designed, they are undocumented.
* A prop that two teams consistently misuse is a bug in the API, not in the
  teams. I have removed one for exactly this reason.
* If the UI shows something the server has not confirmed, the UI should say so.
  Optimistic is fine. Silent is not.
* I would rather delete a component than add a fifth boolean to it.

## 📊 Activity

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Blackpossum&theme=github" alt="Profile summary" />
</p>

<p align="center">
  <img height="180" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Blackpossum&theme=github" alt="Repos per language" />
  <img height="180" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Blackpossum&theme=github" alt="Most committed language" />
</p>

<p align="center">
  <img src="https://ghchart.rshah.org/0d7d80/Blackpossum" alt="Contribution chart" width="800" />
</p>

## Notes

Trained in mechanical engineering before I wrote any code, which is probably how
I ended up writing software for machines. Three years of lathes and tolerances
turns out to be reasonable preparation for arguing about state management.

Written in English here, Indonesian everywhere else.

## Contact

Open an issue or a discussion on anything above — that is the channel I actually
read. Otherwise yosaphatharwindra@gmail.com.

Surakarta, Indonesia. WIB, which is UTC+7 and inconvenient for roughly everyone.
