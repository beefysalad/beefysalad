<div align="center">

<a href="https://github.com/beefysalad">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=24&pause=1200&color=36BCF7&center=true&vCenter=true&width=600&lines=Hey%2C+I'm+Patrick;I+build+full-stack+products+end+to+end;Currently+shipping+Wanderly" alt="Typing SVG" />
</a>

Next.js/TypeScript on the web, with the occasional detour into hardware when the problem wants a sensor or a lock instead of a button.

</div>

## Start here

- **[Wanderly](https://github.com/beefysalad/Wanderly)** — live product, real-time group trip planning
- **[Penni](https://github.com/beefysalad/Penni)** ([web](https://github.com/beefysalad/penni-web) · [API](https://github.com/beefysalad/Penni-API)) — personal finance, one backend serving web and mobile
- **[Tempo](https://github.com/beefysalad/pomodoro)** — gamified Pomodoro study planner
- Everything else is smaller experiments and boilerplates — poke around if you're curious, no promises on polish

## What I've shipped

### Wanderly — live at [wanderly.quest](https://wanderly.quest)

Groups planning a trip need one shared source of truth for the itinerary, activities, and who-owes-who on expenses — instead of a group chat and five different spreadsheets. Next.js 15 App Router, service/repository-layered API, Prisma/Postgres, Firebase auth plus a signed guest-token flow so non-account members can still view and edit their group, and Socket.IO for live updates when someone adds an activity or logs an expense.

### Penni — personal finance, web + mobile on one API

Split into three repos (mobile, web, API) so the same Clerk-authenticated backend serves an Expo/React Native app and a Next.js 16 web client without duplicating business logic. Web side runs TanStack Query, Radix/shadcn, and Zod-validated forms; mobile runs Nativewind and Expo Router.

### Tempo — gamified Pomodoro planner, live at [tempo.qpon](https://tempo.qpon)

A study timer that actually gets used: three focus/break intervals (Blitz/Focus/Deep), XP and levels per session, and streaks tracked in the user's local timezone so they don't break from a timezone bug instead of an actual missed day. Next.js 16, Prisma/Postgres, Clerk.

## Stack

<p align="left">
  <img src="https://skillicons.dev/icons?i=ts,js,py,cpp,nextjs,react,tailwind,nodejs,nestjs,express,fastapi,postgres,mysql,mongodb,prisma,redis,firebase,git,github,vercel,arduino&theme=dark" alt="Stack" />
</p>

AI tooling day to day: Claude, Codex — not just for show.

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com/?user=beefysalad&theme=tokyonight&hide_border=true" alt="GitHub streak" height="165" />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/beefysalad/beefysalad/output/github-contribution-grid-snake-dark.svg" />
  <img alt="contribution snake" src="https://raw.githubusercontent.com/beefysalad/beefysalad/output/github-contribution-grid-snake.svg" />
</picture>

</div>

## Elsewhere

[patr1ck.dev](https://www.patr1ck.dev) · Cebu, PH
