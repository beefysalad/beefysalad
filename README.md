# Patrick

I build full-stack products end to end — Next.js/TypeScript on the web, with the occasional detour into hardware when the problem wants a sensor or a lock instead of a button.

```txt
currently: building Wanderly, a group trip planner (wanderly.quest)
```

## Start here

- **[Wanderly](https://github.com/beefysalad/Wanderly)** — live product, real-time group trip planning
- **[Penni](https://github.com/beefysalad/Penni)** ([web](https://github.com/beefysalad/penni-web) · [API](https://github.com/beefysalad/Penni-API)) — personal finance, one backend serving web and mobile
- **[Tempo](https://github.com/beefysalad/pomodoro)** — gamified Pomodoro study planner
- Everything else is smaller experiments and boilerplates — poke around if you're curious, no promises on polish

## What I've shipped

### Wanderly — group trip planning, live at [wanderly.quest](https://wanderly.quest)
Groups planning a trip need one shared source of truth for the itinerary, activities, and who-owes-who on expenses — instead of a group chat and five different spreadsheets. Built on Next.js 15 App Router with a service/repository-layered API, Prisma/Postgres, Firebase auth plus a signed guest-token flow so non-account members can still view and edit their group, and Socket.IO for live updates when someone adds an activity or logs an expense. Currently mid-refactor toward stricter Zod validation and a cleaner service/repo split across the older routes.

### Penni — personal finance, web + mobile on one API
Split into three repos ([mobile](https://github.com/beefysalad/Penni), [web](https://github.com/beefysalad/penni-web), [API](https://github.com/beefysalad/Penni-API)) so the same Clerk-authenticated backend serves an Expo/React Native app and a Next.js 16 web client without duplicating business logic. Web side uses TanStack Query, Radix/shadcn, and Zod-validated forms; mobile uses Nativewind and Expo Router.

### Tempo — gamified Pomodoro planner, live at [tempo.qpon](https://tempo.qpon)
A study timer that actually gets used: three focus/break intervals (Blitz/Focus/Deep), XP and levels per session, and streaks tracked in the user's local timezone so they don't break from a timezone bug instead of an actual missed day. Next.js 16, Prisma/Postgres, Clerk.

## Stack

**Frontend** — TypeScript, React, Next.js, React Native, Tailwind, shadcn/ui
**Backend** — Node.js, NestJS, Express, Fastify, Python/FastAPI
**Data** — PostgreSQL, MySQL, MongoDB, Prisma, Redis
**Infra** — Firebase, Vercel, Git/GitHub
**Hardware** — Arduino, C++
**AI tooling** — Claude, Codex — day to day, not just for show

## Elsewhere

[patr1ck.dev](https://www.patr1ck.dev) · Cebu, PH
