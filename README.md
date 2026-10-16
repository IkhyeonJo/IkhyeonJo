# Ikhyeon Jo

Backend developer in Seoul. By day I work on mortgage loan origination software at **Calyx Software** (C#/.NET, with a US team). On my own time I build and **run** a production web app end to end — from DNS down to containers, backups, and cron.

### ⭐ [Maroik](https://github.com/IkhyeonJo/Maroik) · [maroik.com](https://www.maroik.com)
A self-hosted ASP.NET Core app (finance, calendar, boards, user management) — built & operated solo.

**.NET 10 · ASP.NET Core MVC · PostgreSQL/EF Core · Valkey · RabbitMQ · ClamAV · Docker · Cloudflare Tunnel**

- **No open inbound ports** — reachable only through an outbound Cloudflare Tunnel.
- **3 services** (Website · FileStorage · Worker) on Docker Compose, with hourly backups via cron.
- **Layered solution** (Domain · Repository · Service · Client), each project with its own test project — xUnit for units, Playwright for E2E.
- **Strict TypeScript front end** — `strict` plus `noUncheckedIndexedAccess` / `exactOptionalPropertyTypes`, tested with Vitest.

### Also
- **Compilers & low-level systems** — reading LCC and TinyCC on the way to my own C toolchain (compiler, assembler, linker).
- **Desktop** — WPF (MVVM) and TCP/IP tooling from earlier work.

📫 admin@maroik.com
