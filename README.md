<img src="header.svg" width="100%" alt="wydvoy"/>

<br/>

software engineer. i build across the full stack: mobile apps, web interfaces, automation bots, backend systems, scrapers, and AI pipelines. most things in TypeScript; occasionally Python when the problem demands it.

---

## projects

<details>
<summary><strong>captureflow</strong> — audio intelligence pipeline</summary>

<br/>

A local Python pipeline that continuously captures mic audio, filters speech in real-time using VAD, and produces structured project artifacts from planning sessions.

| Component | Tech |
|---|---|
| Voice Activity Detection | silero-vad (ONNX, runs entirely local) |
| Transcription | faster-whisper / OpenAI Whisper API |
| Relevance filtering | two-pass LLM scoring (Anthropic + sentence-transformers) |
| Artifact extraction | structured JSON via Claude |
| Backend | FastAPI + WebSockets (uvicorn) |
| Runtime | Python 3.11+, PyTorch, sounddevice, numpy |

**Status:** MVP pipeline validated. Tauri desktop shell in design.

</details>

<details>
<summary><strong>shopbot</strong> — Telegram e-commerce + admin platform</summary>

<br/>

pnpm monorepo: Telegram storefront bot (grammY), Fastify REST API with JWT auth, Radix UI admin dashboard, and a shared types package. Bitcoin payment support via bitcoinjs-lib.

| Package | Tech |
|---|---|
| Telegram bot | grammY + conversations plugin |
| Backend API | Fastify + @fastify/jwt + @fastify/rate-limit + zod |
| Admin UI | React + Radix UI primitives + shadcn/ui + Tailwind |
| Payments | bitcoinjs-lib + bip32 |
| Monorepo | pnpm workspaces + Turborepo |

</details>

<details>
<summary><strong>rember</strong> — habit + debt tracker (React Native)</summary>

<br/>

Personal iOS app for tracking daily habits and informal debts between friends. Built for private, reflective use—no streaks, no gamification, no dashboard theater.

| Component | Tech |
|---|---|
| Framework | Expo SDK + Expo Router |
| Typography | Newsreader (serif) + Manrope (sans) |
| State | Zustand |
| Animations | React Native Reanimated 3 |
| Distribution | EAS Build + TestFlight |

**Aesthetic:** Warm dark, typographic-first. Inspired by Bear / Obsidian.

</details>

<details>
<summary><strong>the-irreverent</strong> — social expense splitting (iOS)</summary>

<br/>

Group debt management and bill-splitting app. NativeWind styling, Supabase backend, full i18n support.

| Component | Tech |
|---|---|
| Framework | Expo SDK 52 + Expo Router |
| Styling | NativeWind v4 (Tailwind for React Native) |
| Backend | Supabase (Postgres + Auth + Realtime) |
| State | Zustand |
| i18n | i18next + react-i18next |

</details>

<details>
<summary><strong>polybot</strong> — Polymarket prediction market bot</summary>

<br/>

TypeScript bot that streams real-time order book data from Polymarket's CLOB API, executes conditional market strategies, and manages position sizing via ethers.js.

| Component | Tech |
|---|---|
| Market data | WebSocket streaming (Polymarket CLOB) |
| Execution | @polymarket/clob-client + ethers.js |
| Runtime | Node.js / tsx, Vitest |

</details>

<details>
<summary><strong>smoketable</strong> — Next.js web app</summary>

<br/>

Full-stack Next.js app with Supabase backend, shadcn/ui component system, and Framer Motion animations.

| Component | Tech |
|---|---|
| Framework | Next.js + React |
| UI | shadcn/ui + Tailwind CSS + Framer Motion |
| Backend | Supabase (Postgres + SSR auth) |

</details>

---

## stack

<table>
<tr>
<td valign="top" width="33%">

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)

**Web / UI**

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![shadcn/ui](https://img.shields.io/badge/shadcn%2Fui-18181b?style=flat-square)
![Framer Motion](https://img.shields.io/badge/Framer_Motion-0055FF?style=flat-square&logo=framer&logoColor=white)

</td>
<td valign="top" width="33%">

**Mobile**

![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white)
![NativeWind](https://img.shields.io/badge/NativeWind-06B6D4?style=flat-square)

**Backend**

![Fastify](https://img.shields.io/badge/Fastify-000000?style=flat-square&logo=fastify&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)

</td>
<td valign="top" width="33%">

**Bots & Automation**

![grammY](https://img.shields.io/badge/grammY-2CA5E0?style=flat-square)
![discord.py](https://img.shields.io/badge/discord.py-5865F2?style=flat-square&logo=discord&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logo=playwright&logoColor=white)

**Infra / Edge**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Cloudflare Workers](https://img.shields.io/badge/CF_Workers-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)

</td>
</tr>
</table>

---

## stats

<p align="center">
<img src="https://github-profile-trophy.vercel.app/?username=wydvoy&theme=darkhub&no-bg=true&no-frame=true&column=6&margin-w=6&margin-h=6" alt="Trophies"/>
</p>

<p align="center">
<img src="https://streak-stats.demolab.com/?user=wydvoy&hide_border=true&background=0d1117&stroke=30363d&ring=848d97&fire=e6edf3&currStreakNum=e6edf3&sideNums=848d97&currStreakLabel=3d444d&sideLabels=3d444d&dates=3d444d" alt="Streak Stats"/>
</p>

---

<p align="center">
<sub><code>wydvoy</code> · github.com/wydvoy</sub>
</p>
