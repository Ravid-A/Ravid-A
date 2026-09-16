<h1 align="center">Ravid Atia</h1>

<p align="center">
  <b>Full-stack developer</b> · Israel<br>
  B.Sc Software Engineering student · certified Practical Software Engineer<br>
  React / Next.js on the front, Node and .NET on the back, SQL and Mongo underneath — deployed on my own k3s cluster.
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Ravid-A&style=flat-square&color=6e7681" alt="Profile views">
</p>

---

### What I do

- **Frontend** — React and Next.js with TypeScript, React Native / Expo for mobile. Component state with MobX or hooks, Vite or Next tooling.
- **Backend** — Node/Express REST APIs with Sequelize over MySQL/MariaDB, Mongoose over MongoDB, JWT + bcrypt auth, real-time over Socket.IO. C#/.NET when the problem calls for it.
- **Infrastructure** — I run what I build. My projects are deployed on a single-node k3s cluster I maintain myself, behind Cloudflare, Nginx Proxy Manager, Tailscale and Traefik, with every service declared in manifests. Docker, Linux, GitHub Actions.
- **On the side** — Counter-Strike 2 server plugins in C#/.NET on CounterStrikeSharp, and older CS:GO work in SourcePawn. It's where I learned to read someone else's engine and ship against it.

### Selected projects

| Project | What it is | Stack |
| --- | --- | --- |
| [2048Multiplayer](https://github.com/Ravid-A/2048Multiplayer) | **Practical engineering final project.** Real-time multiplayer 2048 — Next.js client, separate API server with accounts and live matches | Next.js · Express · Socket.IO · Sequelize · MariaDB · JWT |
| [TodoMate](https://github.com/Ravid-A/TodoMate) · [mobile client](https://github.com/Ravid-A/TodoMate-ReactNative) | Task app built twice — native Android, then cross-platform with a Firebase backend | Kotlin · React Native · Expo · Firebase |
| [ai-study-planner](https://github.com/Ravid-A/ai-study-planner) | Study-plan generator backed by the Gemini API | React 19 · TypeScript · Vite · @google/genai |
| [CompilationProject](https://github.com/Ravid-A/CompilationProject) | **Compilation course final project, B.Sc.** Compiler front end for a small language — lexer, LALR grammar, AST and semantic analysis over functions, control flow and typed expressions | Lex · Yacc · C |
| [cs2-retakes-weapon-allocator](https://github.com/Ravid-A/cs2-retakes-weapon-allocator) | Weapon allocator for CS2 retakes with a client-drawn Panorama loadout menu | C# · .NET 10 · CounterStrikeSharp |

### Open source

I help maintain plugins that other people run on their servers, and I send fixes upstream rather than forking around them.

- **[cs2-retakes-weapon-allocator](https://github.com/Ravid-A/cs2-retakes-weapon-allocator)** — 23 releases, currently `v3.2.5`, ~1k downloads. Released through a tagged pipeline with NuGet publishing.
- **Merged upstream** into the frameworks I build on: [CounterStrikeSharp](https://github.com/roflmuffin/CounterStrikeSharp/pull/1031) (plugin load ordering), [b3none/cs2-retakes](https://github.com/B3none/cs2-retakes/pull/293) (warmup death-cam bug), [PanoramaManager](https://github.com/Next-il/PanoramaManager/pull/1) (moved the HUD entity onto CounterStrikeSharp's `CCSCustomHudLayout` API), [SPCode](https://github.com/SPCodeOrg/SPCode/pull/131).
- Comfortable working in someone else's codebase: read the engine API, find the real cause, keep the diff small enough to review.

### Tech

**Languages**
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![Python](https://img.shields.io/badge/Python-3670A0?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)

**Frontend**
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-61DAFB?style=flat-square&logo=react&logoColor=black)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

**Backend**
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![.NET](https://img.shields.io/badge/.NET-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white)
![Sequelize](https://img.shields.io/badge/Sequelize-52B0E7?style=flat-square&logo=sequelize&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)

**Data & infra**
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-DD2C00?style=flat-square&logo=firebase&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![k3s](https://img.shields.io/badge/k3s-FFC61C?style=flat-square&logo=kubernetes&logoColor=black)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)

### Stats

<p align="left">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=Ravid-A&theme=github_dark&hide_border=true&include_all_commits=true&show_icons=true" alt="GitHub stats">
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Ravid-A&theme=github_dark&hide_border=true&layout=compact&langs_count=8&exclude_repo=cs2-retakes-weapon-allocator" alt="Top languages">
</p>

### Reach me

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Ravid-A)
