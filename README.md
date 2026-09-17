# Hi, I'm Tarik

I build full-stack web applications and, more recently, LLM-powered tools. Everything below is
deployed and clickable — schema and auth through to a live URL.

**TypeScript · Next.js · React · Prisma · PostgreSQL · Python · FastAPI**
Sarajevo, BiH · Open to junior software / AI engineering roles · tarikfilipovic1234@gmail.com

---

## What I've built

### [GenLeadAI](https://github.com/tarikfilipovic1234-maker/genleadai) — Lead research agent · [Live demo](https://genleadai.vercel.app)
An agent that researches local businesses as sales leads: it calls tools (OpenStreetMap, site
crawls with robots.txt respected, page extraction), records where each fact came from, and refuses
to save anything it could not verify. Scoring is deterministic YAML rules rather than a model
opinion, and a claim checker rejects outreach drafts containing facts the research never found.
Two runtimes — a hand-written Claude Messages API loop with prompt caching and a cost ledger, and
an Agent SDK runtime — plus SSE streaming with reconnect. **339 backend tests.**
`Python · FastAPI · SQLAlchemy · Alembic · PostgreSQL · Claude API · Next.js`

### [Darceflow](https://github.com/tarikfilipovic1234-maker/darceflow) — Multi-tenant SaaS · [Live demo](https://darceflow.vercel.app)
Management platform for Brazilian Jiu-Jitsu gyms: memberships, class booking with waitlists,
attendance, belt progression and Stripe subscription billing. Every query goes through a
gym-scoped Prisma client so one gym cannot read another's data; booking runs in serializable
transactions with retry so the last mat space cannot be double-booked; Stripe webhooks are
idempotent. Unit, integration and end-to-end tests.
`Next.js 16 · Prisma 7 · PostgreSQL · Auth.js · Stripe · Playwright · Vitest`

### [USA2BIH](https://github.com/tarikfilipovic1234-maker/usa2bih) — Vehicle import platform · [Live demo](https://usa2bih.vercel.app)
Importing cars from US auctions to Bosnia: browse listings, then a landed-cost calculator that
works out customs duty and VAT on the duty-inclusive value and converts to BAM, so a buyer knows
the real cost before bidding. Plus import tracking, document uploads and an admin panel.
Calculator covered by unit tests running in GitHub Actions.
`Next.js 16 · Prisma 7 · Neon PostgreSQL · Neon Auth · Vercel Blob · Vitest · GitHub Actions`

### [Voltra](https://github.com/tarikfilipovic1234-maker/voltra) — E-commerce storefront · [Live demo](https://voltra-gold.vercel.app)
Store for a fictional electronics brand: Stripe checkout, inventory holds that check stock against
existing reservations in a single atomic UPDATE, a tiered loyalty system, six-language i18n and an
admin console for products, orders and content.
`Next.js 16 · Prisma · PostgreSQL · Auth.js v5 · Stripe · i18n`

### [Enamel](https://github.com/tarikfilipovic1234-maker/enamel) — Booking system · [Live demo](https://enamel-pi.vercel.app)
Bilingual (Bosnian/English) site for a fictional dental clinic, built around a real availability
engine: working hours minus staff time-off minus existing appointments, with a transactional
overlap guard and a staff dashboard for approving and rescheduling.
`Next.js 16 · Prisma 7 · Neon Auth · Resend · i18n`

### [DevVault](https://github.com/tarikfilipovic1234-maker/devvault) — Portfolio · [Live](https://devvault-three.vercel.app)
My portfolio site: content-driven project pages, filterable gallery, working contact form.
`Next.js 16 · React 19 · Tailwind CSS v4 · Framer Motion · Resend · Zod`

---

## Tech I work with

| | |
| --- | --- |
| **Languages** | TypeScript, JavaScript, Python, C#, SQL |
| **Front end** | React, Next.js (App Router), Tailwind CSS, Framer Motion |
| **Back end** | Node.js, Next.js server actions, FastAPI, REST APIs, SSE |
| **Data** | PostgreSQL, Prisma, SQLAlchemy, Neon |
| **AI** | Claude API, tool calling, structured outputs, prompt caching, agent loops |
| **Auth & services** | Auth.js, Neon Auth, Stripe, Resend, Vercel Blob |
| **Testing & tooling** | Vitest, pytest, Playwright, Git, ESLint, GitHub Actions, Vercel, Render |

---

## What I bring

- **End-to-end ownership** — schema design and auth through to a deployed production URL.
- **Real-world domains** — payments, bookings, multi-tenancy, internationalization, customs and
  tax arithmetic, role-based admin tools.
- **Correctness where it matters** — tenant isolation, transaction isolation for double-booking and
  oversell, idempotent webhooks, tests on the logic that would cost money if it were wrong.
- **Honest AI work** — I care more about what an LLM should not be trusted to do than about
  wiring one up. GenLeadAI is built so the model cannot invent a phone number.

---

## Also here

- [Reactivity](https://github.com/tarikfilipovic1234-maker/Reactivity) — .NET + React app built
  while following a guided course, kept as a record of learning C# and layered architecture.

---

## Let's talk

- **Email:** tarikfilipovic1234@gmail.com
- **LinkedIn:** https://www.linkedin.com/in/tarik-filipovic-b41487333/
- **Portfolio:** https://devvault-three.vercel.app
