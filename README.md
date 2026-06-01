# md.local — Developer & Founder

Building production SaaS products and AI-powered tools. Working with clients from US, EU, and CIS.

---

## Freelance & Consulting

Available for product and engineering work through Fiverr and direct contracts.

**Team capabilities:**
- Full-cycle product delivery — discovery, architecture, frontend, backend, deployment
- AI & automation — workflow automation, AI-powered features, integrations
- SaaS development — multi-tenant apps, payment flows, subscription management

**Clients served:** US, EU, CIS markets

---

## Projects

### [Metrix](https://metrixplatform.vercel.app) — Coworking & Office Booking Platform

> *In development*

Platform for booking coworking spaces, meeting rooms, and private offices. Covers the full booking lifecycle: slot selection, payments, calendar sync, and admin operations.

| Property | Details |
|---|---|
| **Status** | In development |
| **Type** | B2B SaaS / Platform |
| **Services** | `bot-gateway` · `booking-service` · `payment-service` · `calendar-service` · `analytics-service` · `admin-service` · `security-service` · `notification-service` · `worker-service` |
| **Shared packages** | `@metrix/audit-log` · `@metrix/auth` · `@metrix/rbac` · `@metrix/observability` · `@metrix/redis-bus` · `@metrix/contracts` · `@metrix/error-tracker` |
| **Events** | Redis Streams · BullMQ · DLQ replay · idempotency · slot locking |
| **Payments** | Invoice/hold/confirm/cancel saga · compensation flows |
| **Observability** | Prometheus · Grafana · OpenTelemetry tracing · structured JSON logs · GlitchTip |
| **Security** | HMAC service-to-service auth · JWT with key rotation · token blacklist · RBAC · audit log |
| **Contracts** | OpenAPI 3.1 · TypeScript contracts · CI validation |
| **Quality gates** | typecheck · unit · integration · e2e · contract · security audit |
| **Stack** | TypeScript · Next.js 16 · React 19 · Node.js · PostgreSQL · Prisma · Redis · Traefik · Docker Compose · MinIO |

---

### [Operon](https://github.com/Hqzdev/Operon) — Ad Campaign Decision Engine

Live SaaS tool for Shopify and DTC advertisers. Takes campaign metrics and outputs a structured decision: **SCALE / KILL / TEST AGAIN / FIX**.

| Property | Details |
|---|---|
| **Status** | Live |
| **Type** | SaaS · Freemium |
| **Core output** | Decision + confidence score · funnel breakdown · break-even CPA/ROAS · diagnosis · creative angle suggestions |
| **Input** | CTR · CPC · CPM · CPA · ROAS · funnel conversion rates · product margin |
| **Pro features** | Budget allocator across ad sets · scenario simulator |
| **Tiers** | Starter (free, 10/mo) · Basic · Pro |
| **Payments** | YooKassa (cards, SBP) |
| **Integrations** | Meta Marketing API · TikTok Marketing API · Shopify Admin API (read-only OAuth) |
| **AI** | GigaChat-2-Pro · rule-based fallback |
| **Stack** | Next.js 16 · React 19 · TypeScript · PostgreSQL · Prisma · Vercel |

---

### [BizStruct](https://github.com/Hqzdev/BizStruct-Web) — Business Control Center

Web app for small business owners. Connects Gmail via OAuth, classifies incoming work with AI, and surfaces tasks, projects, clients, and finances in one dashboard.

| Property | Details |
|---|---|
| **Status** | Live |
| **Type** | SaaS · Subscription |
| **Core flow** | Gmail OAuth → AI classification → structured task/project creation |
| **Workspaces** | Tasks · Projects · Clients · Finances |
| **AI** | OpenRouter — email classification and content refinement |
| **Auth** | Session-based · Google OAuth via Supabase |
| **Payments** | YooKassa · plan-gated feature access |
| **Stack** | Next.js 14 · React 18 · TypeScript · PostgreSQL · Vercel |

---

### [Opsys](https://github.com/Hqzdev/Opsys) — AI Ops Automation MVP

Demand-validation MVP for founder-led SaaS teams. One workflow: AI lead qualification producing structured output — time saved estimate, CRM draft, Slack update, approval boundaries.

| Property | Details |
|---|---|
| **Status** | Validation MVP |
| **Type** | B2B SaaS · Demand validation |
| **Scope** | Landing page · one AI workflow · lightweight persistence |
| **AI** | Claude via Anthropic Messages API · deterministic fallback |
| **Storage** | Supabase · local JSON fallback |
| **Auth** | Google OAuth via Supabase |
| **Stack** | Next.js · TypeScript · Tailwind CSS · Supabase · Vercel |

---

## Tech Stack

### Frontend
- Next.js 15/16 (App Router, Server Components, Server Actions)
- React 18/19 (Concurrent Features)
- TypeScript (strict)
- Tailwind CSS 4, Radix UI, shadcn/ui, Framer Motion

### Backend
- Node.js v18+ (microservices, APIs)
- Python 3.11+ (Flask, AI processing)
- PostgreSQL · Prisma · Drizzle ORM
- Redis · BullMQ · Redis Streams
- MongoDB Atlas (legacy projects)

### AI & Integrations
- Anthropic Claude · OpenAI GPT-4 · GigaChat · OpenRouter · DeepSeek · Gemini
- Meta Marketing API · TikTok Marketing API · Shopify Admin API · Google Calendar OAuth
- Payment: YooKassa, Telegram Stars

### Infrastructure
- Docker & Docker Compose
- Traefik v3
- Vercel (edge deployment)
- Prometheus · Grafana · GlitchTip (OpenTelemetry)
- MinIO / S3-compatible storage
- GitHub Actions CI/CD

---

## Contact

[GitHub](https://github.com/Hqzdev) · [Telegram](https://t.me/Osaslime) · [Discord](https://discord.com/users/1268562577080713282)
