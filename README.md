<div align="center">

```
╔════════════════════════════════════════════════════════════╗
║                                                            ║
║    🔐  T E C H V A U L T                                  ║
║    ─────────────────────────────────────────────────────   ║
║    Your vault of developer mastery — one concept at        ║
║    a time.                                                 ║
║                                                            ║
╚════════════════════════════════════════════════════════════╝
```

**A self-contained developer knowledge dashboard — no servers, no npm, no build step.
Just open `index.html` in a browser and start learning.**

[![Vaults](https://img.shields.io/badge/Vaults-2_Active-4f8ef7?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik0xMiAxTDMgNXY2YzAgNS41NSAzLjg0IDEwLjc0IDkgMTIgNS4xNi0xLjI2IDktNi40NSA5LTEyVjVsLTktNHoiLz48L3N2Zz4=)](index.html)
[![Modules](https://img.shields.io/badge/Total_Modules-45-10d98e?style=flat-square)](index.html)
[![Pure HTML](https://img.shields.io/badge/Pure-HTML_%2F_CSS_%2F_JS-f59e0b?style=flat-square&logo=html5&logoColor=white)](index.html)
[![Theme](https://img.shields.io/badge/Theme-Dark_%26_Light-9b59b6?style=flat-square)](index.html)
[![No Dependencies](https://img.shields.io/badge/Dependencies-Zero-61DAFB?style=flat-square)](index.html)

</div>

---

## 🧠 The Idea

Most developers learn in scattered ways — a YouTube video here, a blog post there, a docs page somewhere else. **TechVault** is the antidote to that chaos.

It's a **single-file, offline-first mastery dashboard** where every technology gets its own self-contained vault — a structured, distraction-free environment with:

- Curated module content (not copy-pasted docs, but actually written explanations)
- Interactive exercises, flashcards, and code playgrounds
- Quizzes with instant feedback
- Real XP and progress tracking via `localStorage`
- A completion certificate at the end

No login. No cloud. No tracking. Everything lives **in your browser**.

---

## 🗂️ What's Inside

```
TechVault/
│
├── 🏠  index.html            ← Dashboard — start here
│
├── ⚛️  react-mastery.html    ← React & React Native vault
│   └── 29 modules · Hooks, Context, Router, TanStack Query,
│       React Native, Testing, Performance, Patterns
│
└── ☁️  aws-mastery.html      ← AWS Cloud vault
    └── 16 modules · EC2, S3, Lambda, RDS, IAM, VPC,
        CloudFront, SQS, DynamoDB + Final Certificate
```

**Coming soon:**

```
├── 🔷  TypeScript Mastery    ← Types, Generics, Decorators
├── 🐳  Docker & DevOps       ← Containers, CI/CD, Kubernetes
├── 🏗️  System Design         ← Scale, Caching, Microservices
└── 🟢  Node.js & APIs        ← REST, GraphQL, WebSockets
```

---

## ✨ Features

| Feature | Details |
|---|---|
| 🎯 **Structured modules** | Each topic broken into focused, digestible sections |
| 🧩 **Interactive exercises** | Drag-and-match, fill-in-blank, flashcards, state visualizers |
| 🖥️ **Live code playgrounds** | Write and run React code directly in the browser |
| 📊 **XP & progress tracking** | localStorage-based — survives refreshes, no account needed |
| 🌓 **Dark & light mode** | Synced across all pages, respects your OS preference |
| 📜 **Completion certificates** | Awarded on finishing all modules in a vault |
| 📱 **Responsive** | Works on desktop, tablet, and mobile |
| ⚡ **Zero dependencies** | No npm, no bundler, no internet required after first load |

---

## 🚀 Getting Started

**It couldn't be simpler:**

```bash
# Clone or download the repo
git clone <your-repo-url>

# Open the dashboard
open index.html       # macOS
start index.html      # Windows
xdg-open index.html   # Linux
```

> Or just double-click `index.html`. That's it. No setup, no install, no config.

---

## 🎨 Design System

TechVault uses a consistent design language across all pages:

```
Fonts       →  Syne 800 (headings) · JetBrains Mono (code) · Inter (body)

Dark mode   →  Background  #060810  ·  Cards  #111827  ·  Border  #1e2d44
Light mode  →  Background  #f8fafd  ·  Cards  #ffffff  ·  Border  #c6d6e8

Accent      →  React  #61DAFB  ·  AWS  #FF9900  ·  Blue  #4f8ef7
```

Each vault has its own **accent color** that flows through every element — progress bars, buttons, glows, badges — giving each technology its own distinct identity.

---

## 📈 Progress System

Progress is stored in `localStorage` under vault-specific keys:

| Vault | Key | Tracks |
|---|---|---|
| React Mastery | `react-mastery-pro-v3` | `completed{}` object + `xp` field |
| AWS Mastery | `aws_mastery_state` | `modules[]` array |

The dashboard (`index.html`) reads all keys and aggregates stats across vaults — total XP earned, modules completed, last vault visited.

---

## 🏗️ Philosophy

> *"The best learning tool is the one you actually open."*

TechVault is built around three beliefs:

**1. Frictionless beats feature-rich.**
A tool you can open in one click, with no login, no install, and no loading spinners, gets used. A sophisticated app with onboarding flows doesn't.

**2. Depth beats breadth.**
Each vault goes deep on one technology. No surface-level "intro" content. Every module assumes you want to actually understand, not just be familiar.

**3. Active beats passive.**
Reading is the weakest form of learning. Every vault includes exercises, quizzes, and playgrounds that force you to produce, not just consume.

---

## 🛠️ Tech Stack

```
HTML5      —  semantic structure, single-file architecture
CSS3       —  custom properties, grid, flexbox, animations
Vanilla JS —  no frameworks, no build step, localStorage API
Babel CDN  —  in-browser JSX transpilation for React playground
Google Fonts — Syne · JetBrains Mono · Inter (loaded once)
```

---

## 🤝 Contributing

Want to add a new vault or improve an existing one?

1. Each vault is a **single self-contained HTML file** — all CSS and JS inline
2. Follow the existing design tokens (see the `Design System` section above)
3. Add progress tracking using `localStorage` with a versioned key
4. Register the vault in `index.html` — add a card, hook up the progress reader
5. Open a PR with a short description of what the vault covers

---

<div align="center">

---

*Built for developers who believe mastery is a process, not a destination.*

**🔐 TechVault** — *Open. Learn. Master.*

</div>
