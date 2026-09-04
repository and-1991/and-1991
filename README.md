<div align="center">

# Hi, I'm Jura

Software engineer building **[Eventra](https://eventra.dev)** after work - a feature-analytics platform for understanding which features people actually use.

[![Website](https://img.shields.io/badge/eventra.dev-visit-1E7F72?style=flat-square)](https://eventra.dev)
[![SDK npm](https://img.shields.io/npm/v/@eventra_dev/eventra-sdk?label=sdk&style=flat-square&color=blue&logo=npm&logoColor=white)](https://www.npmjs.com/package/@eventra_dev/eventra-sdk)
[![CLI npm](https://img.shields.io/npm/v/@eventra_dev/eventra-cli?label=cli&style=flat-square&color=blue&logo=npm&logoColor=white)](https://www.npmjs.com/package/@eventra_dev/eventra-cli)
[![CLI Vue plugin npm](https://img.shields.io/npm/v/@eventra_dev/cli-plugin-vue?label=cli-plugin-vue&style=flat-square&color=blue&logo=npm&logoColor=white)](https://www.npmjs.com/package/@eventra_dev/cli-plugin-vue)
[![CLI Svelte plugin npm](https://img.shields.io/npm/v/@eventra_dev/cli-plugin-svelte?label=cli-plugin-svelte&style=flat-square&color=blue&logo=npm&logoColor=white)](https://www.npmjs.com/package/@eventra_dev/cli-plugin-svelte)
[![CLI Astro plugin npm](https://img.shields.io/npm/v/@eventra_dev/cli-plugin-astro?label=cli-plugin-astro&style=flat-square&color=blue&logo=npm&logoColor=white)](https://www.npmjs.com/package/@eventra_dev/cli-plugin-astro)
[![CLI Angular plugin npm](https://img.shields.io/npm/v/@eventra_dev/cli-plugin-angular?label=cli-plugin-angular&style=flat-square&color=blue&logo=npm&logoColor=white)](https://www.npmjs.com/package/@eventra_dev/cli-plugin-angular)

</div>

---

## What is Eventra

Most products accumulate features nobody's sure are still used. Someone asks "can we kill this?" in a planning meeting, nobody has a real answer, and the feature survives another quarter out of pure uncertainty.

Eventra removes the guessing:

- **SDK** reports what actually **happened** - real usage, from inside your app.
- **CLI** statically scans your code for what **exists** - every place a tracked event is reachable, via real compiler-based analysis (TypeScript compiler API + a plugin per framework), not a regex.
- **Dashboard** cross-references the two and flags the gap: features that exist in code but haven't fired an event in N days. That's the dead-feature list.

No runtime magic. No monkey-patching. It reads source code, it reads events, and it tells you where those two things disagree.

---

## Ecosystem

| Package | What it does | Repo | npm |
|---|---|---|---|
| **SDK** | Track feature usage in your app (browser, Node, edge, serverless) | [repo](https://github.com/and-1991/eventra-sdk) | [![npm](https://img.shields.io/npm/v/@eventra_dev/eventra-sdk?style=flat-square&label=)](https://www.npmjs.com/package/@eventra_dev/eventra-sdk) |
| **CLI** | Statically scan your codebase for tracked events | [repo](https://github.com/and-1991/eventra-cli) | [![npm](https://img.shields.io/npm/v/@eventra_dev/eventra-cli?style=flat-square&label=)](https://www.npmjs.com/package/@eventra_dev/eventra-cli) |
| **CLI Plugin - Vue** | Vue/Nuxt SFC support for the CLI | [repo](https://github.com/and-1991/eventra-cli-plugin-vue) | [![npm](https://img.shields.io/npm/v/@eventra_dev/cli-plugin-vue?style=flat-square&label=)](https://www.npmjs.com/package/@eventra_dev/cli-plugin-vue) |
| **CLI Plugin - Svelte** | Svelte/SvelteKit support for the CLI | [repo](https://github.com/and-1991/eventra-cli-plugin-svelte) | [![npm](https://img.shields.io/npm/v/@eventra_dev/cli-plugin-svelte?style=flat-square&label=)](https://www.npmjs.com/package/@eventra_dev/cli-plugin-svelte) |
| **CLI Plugin - Astro** | Astro support for the CLI | [repo](https://github.com/and-1991/eventra-cli-plugin-astro) | [![npm](https://img.shields.io/npm/v/@eventra_dev/cli-plugin-astro?style=flat-square&label=)](https://www.npmjs.com/package/@eventra_dev/cli-plugin-astro) |
| **CLI Plugin - Angular** | Angular for the CLI | [repo](https://github.com/and-1991/eventra-cli-plugin-angular) | [![npm](https://img.shields.io/npm/v/@eventra_dev/cli-plugin-angular?style=flat-square&label=)](https://www.npmjs.com/package/@eventra_dev/cli-plugin-angular) |
| **Dashboard** | The analytics platform itself | - | [eventra.dev](https://eventra.dev) |
| **Examples** | Full working example projects - frontend, backend, edge runtimes | [repo](https://github.com/and-1991/eventra-examples) | - |
| **Docs** | Code snippets for quick integration | [repo](https://github.com/and-1991/eventra-docs) | - |

---

## Status

| Component | Status |
|---|---|
| Dashboard | Production-ready |
| SDK | Stable - batching, retry + backoff, circuit breaker, idempotent delivery |
| CLI | Stable - semantic analysis, wrapper propagation, plugin ecosystem for Vue / Svelte / Astro / Angular |

---

## Tech stack

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![NestJS](https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

---

## Links

- **Website** - [eventra.dev](https://eventra.dev)
- **Docs** - [eventra.dev/docs](https://eventra.dev/docs)
- **Changelog** - [eventra.dev/changelog](https://eventra.dev/changelog)
- **Roadmap** - [eventra.dev/roadmap](https://eventra.dev/roadmap)
