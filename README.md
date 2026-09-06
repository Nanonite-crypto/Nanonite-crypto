<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=22&duration=2800&pause=900&color=00E07A&center=true&vCenter=true&width=620&lines=Data+Engineer;Local+LLMs+%C2%B7+MCP+servers+%C2%B7+fullstack+tools;Voice+interfaces+%2B+Tauri+desktop+apps;Open+to+junior+dev+roles+%26+OSS+collabs)](https://github.com/Nanonite-crypto)

</div>

---

```bash
$ whoami --verbose
──────────────────────────────────────────────────────────
  role          Data Engineer
  langs         Python · TypeScript · React · Next.js · Rust · Lua
  loves         Local LLMs · MCP · voice interfaces · PWAs
  speaks        Norwegian / English / Spanish
  shell         PowerShell + bash
  editor        VS Code + Claude Code
  uptime        19 years
──────────────────────────────────────────────────────────
```

Self-taught developer building voice-controlled AI assistants, MCP servers, and the occasional retired SaaS experiment. Currently focused on running fine-tuned LLMs locally and building tools on top of the Model Context Protocol.

Open to **junior developer roles**, **freelance work**, and **open-source contributions**.

## Stack

![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/-JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![React](https://img.shields.io/badge/-React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/-Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![Tauri](https://img.shields.io/badge/-Tauri-FFC131?style=flat-square&logo=tauri&logoColor=black)
![Rust](https://img.shields.io/badge/-Rust-000000?style=flat-square&logo=rust&logoColor=white)
![Lua](https://img.shields.io/badge/-Lua-2C2D72?style=flat-square&logo=lua&logoColor=white)
![FastAPI](https://img.shields.io/badge/-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Nginx](https://img.shields.io/badge/-Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Stripe](https://img.shields.io/badge/-Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white)
![Ollama](https://img.shields.io/badge/-Ollama-000000?style=flat-square&logo=ollama&logoColor=white)
![Claude](https://img.shields.io/badge/-Claude-D97757?style=flat-square&logo=anthropic&logoColor=white)

## Projects

<details>
<summary><b>JARVIS</b> — voice-controlled AI assistant living on my PC <i>(click to expand)</i></summary>

<br>

Dual-brain architecture: a fine-tuned local **Qwen3** model handles everyday conversation, with **Groq** cloud fallback for harder questions. Voice in, voice out, long-term memory engine that distills conversations into facts and preferences, optional Tauri desktop UI, and a bridge to **Claude Code** so JARVIS can modify its own source when asked.

```text
┌─ Tauri Desktop UI ─────────────────────────────────────┐
│   ↕ WebSocket :8765                                    │
│ ┌─ Python backend (server.py) ──────────────────┐      │
│ │  • JarvisBrain      → Ollama + Groq fallback  │      │
│ │  • Voice I/O        → Whisper STT + Edge TTS  │      │
│ │  • Memory engine    → JSON-backed long-term   │      │
│ │  • Tool registry    → 30+ PC + web tools      │      │
│ │  • Claude bridge    → self-modification       │      │
│ └───────────────────────────────────────────────┘      │
└────────────────────────────────────────────────────────┘
```

**Stack:** Python · Ollama · Groq · Whisper · Edge TTS · FastAPI · httpx · pyautogui · Tauri · React · Rust
**Repo:** [Nanonite-crypto/jarvis](https://github.com/Nanonite-crypto/jarvis)

</details>

<details>
<summary><b>pc-control-mcp</b> — 30+ MCP tools that give Claude full Windows control</summary>

<br>

Model Context Protocol server. Mouse, keyboard, screenshots, window management, Playwright browser automation (multi-session), markdown notes, clipboard, shell commands. Plugs straight into Claude Desktop via stdio.

**Stack:** Python · FastMCP · pyautogui · pygetwindow · Playwright · Pillow
**Repo:** [Nanonite-crypto/pc-control-mcp](https://github.com/Nanonite-crypto/pc-control-mcp)

</details>

<details>
<summary><b>glowup-tracker</b> — RPG-style PWA for fitness, food, and skincare</summary>

<br>

Vanilla HTML/CSS/JS. localStorage for persistence, service worker for offline use, installable on iPhone home screen. Built it for myself and use it daily — XP bars, streak counters, the whole gamification kit.

**Stack:** HTML · CSS · vanilla JS · PWA · localStorage
**Repo:** [Nanonite-crypto/glowup-tracker](https://github.com/Nanonite-crypto/glowup-tracker)

</details>

<details>
<summary><b>Forge</b> — AI app-generator I built, deployed, and retired</summary>

<br>

Generated full-stack Next.js apps from a single prompt. Deployed on my own Hetzner server — set up Ubuntu, Nginx reverse proxy, PM2 process manager, Let's Encrypt SSL, PostgreSQL, Stripe billing across four subscription tiers, all from scratch. Ran it for a while, then took it down when server costs outgrew the value it returned as an experiment. Learned more about production deployment and Linux operations from running and breaking it than any tutorial would have taught me.

**Stack:** Next.js · Claude Agent SDK · Stripe · PostgreSQL · Hetzner · Nginx · PM2 · Let's Encrypt
**Status:** Retired — code stays private

</details>

