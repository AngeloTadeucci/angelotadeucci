# Hi, I'm Ângelo Tadeucci <img src="https://raw.githubusercontent.com/jadilson12/jadilson12/master/assets/hi.gif" width="16">

Senior Software Engineer focused on backend systems, distributed services, and reverse engineering of client-server architectures.

I have strong experience with C#, .NET, TypeScript, and low-level protocol analysis, and I actively contribute to complex open-source projects involving game servers, binary formats, and tooling.

---

## What I work on

- Backend development with **C# / .NET**
- Distributed systems and service communication
- Reverse engineering of proprietary protocols and file formats
- Game server emulation and tooling
- Full-stack realtime web apps and Twitch/streaming integrations
- Technical leadership in open-source projects

---

## Cool Projects

### MapleStory 2 Server Emulator
Lead contributor to a full, from-scratch emulator of a shut-down MMORPG:
- **Distributed architecture** — separate Login, World (gRPC coordinator), multi-channel Game, and Web servers communicating over gRPC
- **Client data pipeline** ingesting game files into MySQL via EF Core, powering items, maps, NPCs, and quests
- **Live game systems** — NPC AI, navmesh pathfinding, Lua-scripted map triggers, combat, and player progression
- Backed by automated tests, BenchmarkDotNet suites, and a session stress-testing tool

**Stack:** C#, .NET 10, gRPC, Entity Framework Core, MySQL, Docker, DotRecast

Repo: [Maple2](https://github.com/MS2Community/Maple2)

### Streamer Bounty Board
A full-stack, realtime stream companion built solo for a MapleStory event:
- Three surfaces from one reactive backend — public bounty board, operator control panel, and a transparent OBS overlay — kept in sync live with no reloads
- An animated, scene-rotating stream widget driven by Twitch chat: emote bursts, votes, and gifted-sub celebrations with priority-based takeovers
- A separate Dockerized Twitch chat bot (Node / tmi.js) relaying operator messages over guarded HTTP
- Realtime-first: Convex reactive queries as the live contract; countdowns tick client-side so a per-second clock never hits the database

**Stack:** Next.js (App Router), React, Tailwind v4, Convex, Convex Auth (Google), Twitch IRC, Docker

Live: [ereklo.tadeucci.dev](https://ereklo.tadeucci.dev/)

### MapleStory 2 Handbook
A searchable database of MapleStory 2 items and NPCs, built and maintained solo:
- Full-text search over items and NPCs with stats, drop locations, and other in-game metadata
- In-browser 3D model viewer for game assets
- Svelte front-end backed by a separate C# data pipeline ([backend repo](https://github.com/AngeloTadeucci/MapleStory2-Handbook-BackEnd)) that imports game files into MySQL

**Stack:** SvelteKit, Node.js, MySQL, C# (data import)

Live: [handbook.tadeucci.dev](https://handbook.tadeucci.dev) · Repo: [MapleStory2-Handbook](https://github.com/AngeloTadeucci/MapleStory2-Handbook)

---

## Other Projects

| Project | Description | Links |
|---|---|---|
| **StarForce Simulator** | Interactive MapleStory enhancement-cost simulator | [Live](https://starforce.tadeucci.dev/) · [Repo](https://github.com/AngeloTadeucci/starforcing-test) |
| **Maple2-PacketLib-TS** | TypeScript library + CLI to read and parse MS2 packet sniffs | [npm](https://www.npmjs.com/package/maple2-packetlib-ts) · [Repo](https://github.com/AngeloTadeucci/Maple2-PacketLib-TS) |
| **PacketToSQL** | Generates SQL shop-seeding data from captured MS2 game packets | [Repo](https://github.com/AngeloTadeucci/PacketToSQL) |

---

## Tech Stack

- **Languages:** C#, TypeScript, JavaScript, Python, Lua
- **Backend:** .NET, gRPC, REST APIs
- **Full-stack / Web:** React, Next.js, Tailwind, Convex (realtime)
- **Databases:** PostgreSQL, MySQL, SQLite
- **Dev Tools:** Git, Docker
- **Other:** Reverse engineering, binary parsing, protocol analysis

---

## Contact

- **Email**: angelo_tadeucci@hotmail.com.br