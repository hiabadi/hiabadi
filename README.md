<div align="center">

# 👋 Hi, I'm Haris Ihsan Abadi

### Full-Stack Engineer · AI Product Builder

_I ship production web products that fuse **full-stack architecture**, **guardrailed AI**, and **editorial-grade UX** — across EdTech, FinTech, AgriTech/GIS, marketplaces, and knowledge systems._

<br>

[![Email](https://img.shields.io/badge/Email-haris.emailtugas@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:haris.emailtugas@gmail.com)
[![Stack](https://img.shields.io/badge/Focus-Full--Stack%20%2B%20AI-7B61FF?style=flat-square)]()
[![Region](https://img.shields.io/badge/Region-Indonesia%20🇮🇩-FF4B4B?style=flat-square)]()
[![Approach](https://img.shields.io/badge/Approach-Ship%20Products-2EA043?style=flat-square)]()

</div>

---

## 🧠 Engineering Philosophy

> **Ship products, not boilerplate.** Every repository below is a real, production-shaped system. I optimize for **architecture that makes sense**, **AI with guardrails** (RAG grounding + multi-provider fallback, never raw hallucination), and **interfaces that don't feel auto-generated**.

```
domain modeling → AI augmentation → production hardening → editorial polish
```

---

## 🛠️ Tech Stack

**Languages**
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)

**Frontend**
![React](https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite_6-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_v4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![GSAP](https://img.shields.io/badge/GSAP_3-88CE02?style=flat-square&logo=greensock&logoColor=black)
![Framer Motion](https://img.shields.io/badge/Motion-0055FF?style=flat-square&logo=framer&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white)
![Leaflet](https://img.shields.io/badge/Leaflet-199900?style=flat-square&logo=leaflet&logoColor=white)
![Recharts](https://img.shields.io/badge/Recharts-FF6384?style=flat-square&logo=chartdotjs&logoColor=white)

**Backend & Realtime**
![Node.js](https://img.shields.io/badge/Node.js_20-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express_4-000000?style=flat-square&logo=express&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma_5%2F6-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io_4-010101?style=flat-square&logo=socketdotio&logoColor=white)
![Zod](https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)

**Data & Infrastructure**
![PostgreSQL](https://img.shields.io/badge/PostgreSQL_16-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=flat-square&logo=supabase&logoColor=white)
![Firebase](https://img.shields.io/badge/Firestore-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=flat-square&logo=pinecone&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

**AI / LLM**
![Anthropic](https://img.shields.io/badge/Claude-D4A373?style=flat-square&logo=anthropic&logoColor=white)
![OpenAI](https://img.shields.io/badge/GPT--5.5-412991?style=flat-square&logo=openai&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-4285F4?style=flat-square&logo=googlegemini&logoColor=white)
![Groq](https://img.shields.io/badge/Groq-F55036?style=flat-square&logo=lightning&logoColor=white)
![OpenRouter](https://img.shields.io/badge/OpenRouter-6566F1?style=flat-square)

---

## 📦 Featured Work

### 🎓 ExamHub — Secure, AI-Assisted Online Exams
`EdTech · Online Assessment`
> Full-stack exam platform with AI question generation, real-time anti-cheat telemetry, and multi-role portals — delivered as one deploy-friendly monolith.
- **Stack:** React 19 · TypeScript · Express 4 · Prisma 5 · PostgreSQL 16 · Socket.IO 4 · Google Gemini
- **Highlights:** monolith (Express serves the Vite build, HMR middleware in dev) · AI MCQ generator + grammar/distractor polish · live monitoring with **9 configurable anti-cheat signals** · JWT + httpOnly auth · auto-grading + audit logs · DOCX/PDF ingestion · **9 Prisma models**

### 📚 PerpusAI — AI-Powered Digital Library
`AI Knowledge · RAG`
> A research assistant, digital reading room, and library-management system in one — RAG-grounded so the AI cites real holdings, not hallucinations.
- **Stack:** React 19 · Express 4 · Prisma 5 · PostgreSQL/Supabase · Pinecone · Midtrans · node-cron
- **Highlights:** **5-provider LLM fallback chain** (Groq → Claude/GPT/Gemini/DeepSeek) · keyword + Pinecone RAG · slash commands (`/rangkum`, `/sitasi`, `/kuis`…) · integrated chapter + PDF reader with highlights & "Ask AI" · citation engine (APA/IEEE/BibTeX/RIS/CSV) · report generator → DOCX/PDF · signature-verified Midtrans webhooks · cron-driven overdue/fine/reminder jobs · **18 Prisma models**

### 🎫 TemuJasa — Technical & Creative Services Marketplace
`Marketplace · Escrow · AI`
> Connects clients with IoT, software, data/AI, and creative experts — AI drafts the brief, escrow protects the funds, progress streams live.
- **Stack:** React 19 · Express 4 (TS) · Prisma 6 · PostgreSQL 16 · Socket.IO 4 · Groq + OpenRouter
- **Highlights:** ledger-backed **escrow state machine** (`UNPAID → PAID_ESCROW → RELEASED/REFUNDED`) · AI consultation → brief + milestones · real-time queue/progress/chat · RBAC (Client/Provider/Admin) · **AES-256-GCM PII encryption** + audit logs (UU PDP-aligned) · dispute arbitration · Helmet + rate-limit + Zod · gateway-ready (Midtrans/Xendit) · **14 Prisma models**

### 🌾 SawahScan AI — Web GIS for Rice-Field Health
`AgriTech · Web GIS`
> Turns complex multispectral drone analytics (RGB / YOLO / NDVI) into a clean dashboard, interactive map, and actionable field diagnostics.
- **Stack:** React 19 · Express 4 (TS) · Prisma 5 · PostgreSQL 16 · Leaflet + OpenStreetMap · Docker Compose
- **Highlights:** **3-service Docker Compose** (db/backend/frontend) with persistent volumes + auto-migrate · Leaflet sector mapping · per-scan multispectral galleries · Zustand + TanStack Query · Gemini insight layer · JWT + bcrypt · GSAP + Lenis smooth-scroll UI

### 💰 Saku — Smart Personal Finance
`FinTech · Personal Finance`
> Master your money from one minimalist dashboard — accounts, transactions, budgets, savings goals, and an AI advisor grounded in your real data.
- **Stack:** React 19 · TypeScript · Vite 6 · Tailwind v4 · TanStack Query · Supabase (Postgres + RLS) · Edge Functions
- **Highlights:** **atomic** internal transfers · budget & savings tracking · Recharts analytics · Saku AI advisor via OpenRouter gateway · Row-Level Security + AES-256 · **unit-tested** finance aggregation · dark mode, fully responsive

### 📲 UniPortal — Smart Campus Attendance
`Campus SaaS · Attendance`
> Replaces paper roll-call with time-limited QR check-ins, real-time tracking, and live analytics keeping students, lecturers, and admins in sync.
- **Stack:** React 18 · TypeScript · Vite 6 · Tailwind v4 · Firebase (Auth + Firestore + Cloud Functions) · Recharts
- **Highlights:** time-bound **QR sessions** (no student accounts needed) · Firestore real-time listeners · **4-role RBAC** (Admin/Lecturer/Student/Public) · bulk CSV/Excel import (Papa Parse, SheetJS) · calendar heatmap + KPI cards · PDF/Excel export (jsPDF, html2canvas) · ⌘K command palette · WebGL landing (OGL)

### 🎨 Dark Portfolio — Cinematic, CMS-Driven Landing
`Creative · WebGL`
> A portfolio that reads like a magazine and animates like a product launch — fully editable from a built-in back office with live preview.
- **Stack:** React 19 · TypeScript · Vite 6 · Tailwind v4 · Three.js (react-three-fiber) + OGL · GSAP · Framer Motion · Supabase Realtime
- **Highlights:** live **WebGL aurora** background · GSAP + Motion scroll choreography · glassmorphism + crossfaded ambient audio · built-in CMS at `/bts-porto` with live-preview iframe · Supabase Realtime instant re-render · HLS streaming · Vercel Analytics + Speed Insights

---

## 🏗️ How I Build

- 🔌 **Vendor-agnostic AI** — provider abstraction with a fallback chain (Groq → Claude → GPT → Gemini → DeepSeek), so no single outage or price change breaks the product.
- 🛡️ **Guardrail-first AI** — keyword/Pinecone RAG retrieval *before* hitting the LLM; answers stay grounded in real data.
- ⚡ **Real-time by default** — Socket.IO rooms (`exam:{id}`, `project:{id}`) and Firestore listeners for live monitoring, queues, and chat.
- 🔒 **Production hardening** — JWT httpOnly cookies, bcrypt, AES-256-GCM PII, Row-Level Security, Helmet, rate-limiting, Zod validation, audit logs, idempotent webhooks.
- 🧱 **Pragmatic deploys** — TypeScript monolith (Express + Vite middleware) for solo/small-team velocity; Docker Compose for reproducible/VPS; Vercel + Firebase serverless.
- 🎯 **Domain modeling** — ledgers and explicit state machines (escrow), strongly-typed schemas end-to-end with Prisma.

### Reference Architecture

```mermaid
flowchart TB
    subgraph C["🖥️ Client"]
        c1["React 19 / 18 · TypeScript · Vite 6 · Tailwind v4<br/>GSAP · Framer Motion · Three.js / OGL · Leaflet · Recharts"]
    end
    subgraph A["⚙️ API"]
        a1["Express 4 (TypeScript) · Firebase Cloud Functions<br/>Zod · JWT + httpOnly cookie · bcrypt · Helmet · rate-limit · node-cron"]
    end
    subgraph D["🗄️ Data"]
        d1["PostgreSQL 16 · Prisma 5 / 6 · Supabase · Firestore<br/>Row-Level Security · AES-256-GCM PII · audit logs · ledgers + state machines"]
    end
    subgraph L["🤖 AI Layer"]
        l1["Provider abstraction + fallback chain<br/>Groq · Claude · GPT-5.5 · Gemini · DeepSeek · Pinecone RAG"]
    end
    C -->|"REST + WebSocket · Socket.IO"| A
    A -->|"Prisma / Firebase SDK"| D
    A -->|"grounded prompts"| L
    L -.->|"streamed tokens"| C
```

### Multi-Provider AI Fallback (RAG-grounded)

```mermaid
flowchart LR
    Q(["🔎 User query"]) --> RAG["RAG grounding<br/>keyword · Pinecone"]
    RAG --> P["⚡ Groq · primary"]
    P -->|success| OUT(["✅ Grounded, streamed answer"])
    P -.->|on failure| F1["Claude"]
    F1 -.->|on failure| F2["GPT-5.5"]
    F2 -.->|on failure| F3["Gemini"]
    F3 -.->|on failure| F4["DeepSeek"]
    F1 --> OUT
    F2 --> OUT
    F3 --> OUT
    F4 --> OUT
```

---

## 📊 By the Numbers

<div align="center">

| Metric | Count |
| --- | --- |
| Production full-stack products | **7** across **7** domains |
| LLM providers integrated (with fallback) | **5** — Groq · Claude · GPT-4 · Gemini · DeepSeek |
| Primary data layers | PostgreSQL · Supabase · Firestore · Pinecone |
| Default language | **TypeScript**, end-to-end |

**Domains shipped:** EdTech · FinTech · AgriTech / GIS · Marketplace & Escrow · AI / RAG Knowledge · Campus SaaS · Creative / WebGL

</div>

---

## 📈 GitHub Stats

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=hiabadi&show_icons=true&hide_border=true&theme=tokyonight&count_private=true" alt="GitHub stats" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=hiabadi&layout=compact&hide_border=true&theme=tokyonight&langs_count=8" alt="Top languages" />

</div>

---

<div align="center">

### 📬 Let's Build Something

Have a product idea that needs **grounded AI**, **solid full-stack architecture**, or **editorial UX**?

**[haris.emailtugas@gmail.com](mailto:haris.emailtugas@gmail.com)**

<sub><i>Every project above is a real implementation — not a demo or template.</i></sub>

</div>
