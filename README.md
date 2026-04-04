<img src="header.svg" width="100%" alt="wydvoy"/>

<br/>

software engineer. i build automation tools, mobile apps, and backend systems—mostly in TypeScript and Python. currently focused on local-first AI pipelines and multi-platform mobile.

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
<summary><strong>rember</strong> — habit + debt tracker (React Native)</summary>

<br/>

Personal iOS app for tracking daily habits and informal debts between friends. Built for private, reflective use—no streaks, no gamification, no dashboard theater.

| Component | Tech |
|---|---|
| Framework | Expo SDK + Expo Router |
| Styling | Newsreader (serif) + Manrope (sans) |
| State | Zustand |
| Animations | React Native Reanimated 3 |
| Distribution | EAS Build + TestFlight |

**Aesthetic:** Warm dark, typographic-first. Inspired by Bear / Obsidian.

</details>

<details>
<summary><strong>the-irreverent</strong> — social expense splitting (iOS)</summary>

<br/>

Group debt management and bill-splitting app with NativeWind styling and Supabase backend. Gen-Z aesthetic—debt tracking that doesn't feel like accounting.

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
<summary><strong>Chat</strong> — multi-LLM chat platform (public)</summary>

<br/>

Enhanced GPT-clone supporting model switching across Anthropic, OpenAI, DeepSeek, Groq, Gemini, Azure, Mistral, and more. Includes Agents, MCP, code interpreter, DALL-E-3, and secure multi-user auth.

**Repo:** [wydvoy/Chat](https://github.com/wydvoy/Chat)

</details>

---

## stack

<table>
<tr>
<td valign="top" width="25%">

**Languages**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

</td>
<td valign="top" width="25%">

**Mobile / Frontend**

![React Native](https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-433e38?style=flat-square)
![Tauri](https://img.shields.io/badge/Tauri-24C8D8?style=flat-square&logo=tauri&logoColor=white)

</td>
<td valign="top" width="25%">

**Backend / AI**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic-191919?style=flat-square)

</td>
<td valign="top" width="25%">

**Infrastructure**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![mise](https://img.shields.io/badge/mise-21262d?style=flat-square)

</td>
</tr>
</table>

---

## stats

<table align="center">
<tr>
<td>
<img src="https://github-readme-stats.vercel.app/api?username=wydvoy&show_icons=true&hide_border=true&include_all_commits=true&count_private=true&bg_color=0d1117&title_color=e6edf3&text_color=848d97&icon_color=484f58&ring_color=30363d" alt="GitHub Stats"/>
</td>
<td>
<img src="https://github-readme-streak-stats.herokuapp.com/?user=wydvoy&hide_border=true&background=0d1117&stroke=30363d&ring=848d97&fire=e6edf3&currStreakNum=e6edf3&sideNums=848d97&currStreakLabel=3d444d&sideLabels=3d444d&dates=3d444d" alt="Streak Stats"/>
</td>
</tr>
</table>

<p align="center">
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=wydvoy&hide_border=true&layout=compact&langs_count=8&bg_color=0d1117&title_color=e6edf3&text_color=848d97&hide=html,css" alt="Top Languages"/>
</p>

---

<p align="center">
<sub><code>wydvoy</code> · github.com/wydvoy</sub>
</p>
