# Hi, I'm Segun 👋

I'm a senior frontend engineer moving into AI product engineering.

For about 7 years I've built production software at fintech scale, mostly in React and TypeScript. These days I split my time between shipping banking interfaces and working on the AI side: evaluating coding agents and LLMs, and building small AI-powered products. I'm doing that transition in public, so this profile is where you can watch it happen.

### What I work on

- **Production fintech frontends.** Senior frontend engineer at a payments company. Compliance onboarding (KYB/CDD), transfers, savings, offline-first flows, and card lifecycle, built in React, TypeScript and Next.js.
- **AI evaluation.** I design benchmarks and evals for AI coding agents and run pairwise model comparisons, working with several frontier AI labs under NDA. This is the part I'm leaning into hardest.
- **Backend when the problem needs it.** Node, TypeScript and Postgres, with a bias toward correctness under concurrency.

### Building in public

I'm documenting the move from frontend engineer to AI product engineer: the projects, the evals, and the things that break along the way. If that's interesting to you, follow along on [X](https://x.com/techwithsegun) or [LinkedIn](https://www.linkedin.com/in/olusegun-olayinka).

### Selected work

**[wallet-system](https://github.com/olayis/wallet-system)** — A money-correct wallet and ledger API in TypeScript (Fastify, Postgres, Objection).
Balances are derived from an append-only double-entry ledger, never a cached column. Concurrent transfers take row locks on both wallets in a stable order to avoid deadlocks, writes are idempotent at two layers, and database CHECK constraints enforce the invariants. Full test suite and CI. This is the repo I point to when someone asks how I think about correctness.

*More AI-focused projects are landing here over the coming weeks as I build them in public.*

### Stack

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Redux](https://img.shields.io/badge/Redux-764ABC?style=flat&logo=redux&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat&logo=tailwindcss&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

### Reach me

- X: [@techwithsegun](https://x.com/techwithsegun)
- LinkedIn: [olusegun-olayinka](https://www.linkedin.com/in/olusegun-olayinka)
- Email: olayinkasegunsolo@gmail.com

<br/>

![Segun's GitHub stats](https://github-readme-stats.vercel.app/api?username=olayis&show_icons=true&hide_border=true)
