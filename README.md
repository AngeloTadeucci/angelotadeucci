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

## Selected Projects

### MapleStory 2 Server Emulator
Contributor and maintainer of a full server emulator, involving:
- Networking and protocol handling
- Game logic and data parsing
- Performance and scalability improvements

Repo: [Maple2](https://github.com/MS2Community/Maple2)

### Ereklo Bounty Board
A full-stack, realtime stream companion built solo for a MapleStory event:
- Three live surfaces from one reactive backend — a public bounty board, an operator control panel, and a transparent OBS stream widget — kept in sync in real time (an operator edits a goal → the site and on-stream overlay update with no reload)
- A scene-rotating animated stream widget that reacts to live Twitch chat: emote bursts, chat votes, gifted-sub celebrations, and a chat state, with priority-based takeovers
- A separate Dockerized Twitch chat bot (Node / tmi.js) that relays operator messages and acts as a backup chat listener, talking to the backend over guarded HTTP
- Realtime-first design: Convex reactive queries as the live contract; countdowns tick client-side from timestamps so a per-second clock never hits the database

**Stack:** Next.js (App Router), React, Tailwind v4, Convex, Convex Auth (Google), Twitch IRC, Docker

Live: [ereklo.tadeucci.dev](https://ereklo.tadeucci.dev/)

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