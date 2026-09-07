# Greyson Denison-Fischer

Computer Science student at **Central Michigan University**, graduating **May 2027**.

I'm seeking full-time **software engineering opportunities after graduation**, with interests in backend, full-stack, and application development.

I enjoy building complete systems—from user-facing applications and APIs to databases, real-time data pipelines, automation, and self-hosted infrastructure.

## Featured Projects

### [Athlete Moves](https://github.com/dgreyson3/Athlete-Moves-Showcase)

A cross-platform workout application I built independently using **React Native, Expo, Supabase, and PostgreSQL**.

Athlete Moves guides users from an initial fitness assessment through level-matched workout discovery, interactive workout tracking, saved history, and history-informed progression.

**Highlights:**
- Built for iOS, Android, and web with React Native and Expo
- Implemented authentication, athlete assessment, and level-based workout discovery
- Built interactive set, rep, weight, timer, and workout-history systems
- Persisted exercise-level results with Supabase/PostgreSQL
- Implemented editable, history-informed weight recommendations and athlete progression

**Technologies:** JavaScript, React Native, Expo, Supabase, PostgreSQL, TanStack Query, NativeWind

---

### [Cross-Venue Prediction Market Arbitrage Engine](https://github.com/dgreyson3/prediction-market-arbitrage-showcase)

A Python system I built to normalize, match, and evaluate equivalent sports and esports prediction-market contracts across **Kalshi and Polymarket**.

The engine combines REST APIs and WebSocket market data with depth-aware pricing, persistence, risk checks, paper execution, and guarded live-execution capabilities.

**Highlights:**
- Built asynchronous Kalshi and Polymarket REST/WebSocket integrations
- Normalized venue-specific contracts into a shared internal model
- Developed deterministic cross-venue matching and depth-aware opportunity analysis
- Evaluated executable liquidity with fees, modeled slippage, freshness, and risk checks
- Built paper and guarded live-execution workflows with safety controls
- Added PostgreSQL persistence, operator tooling, Discord alerts, reports, and **225 passing tests**

**Technologies:** Python, asyncio, HTTPX, WebSockets, PostgreSQL, SQLAlchemy, Pydantic, Pytest, Docker

> Strategy logic, credentials, and execution parameters remain private. The public showcase uses synthetic data to demonstrate the system.

---

### [GTracker](https://gtracker-pi.vercel.app/)

A full-stack League of Legends performance and team analytics application I originally built in **late 2024–early 2025** for my semester's esports team.

At the time, reviewing team performance meant jumping between several separate OP.GG profiles. GTracker gave us one place to review recent matches, player statistics, goals, shared games, and team performance.

**Highlights:**
- Integrated Riot Account, Summoner, and Match APIs
- Built player profiles, match history, derived statistics, and performance charts
- Built measurable player goals with progress tracking and team visibility
- Implemented team creation, invite codes, membership, and authorization
- Detected matches played together by linked teammates
- Built team analytics with roster comparisons, shared-match records, champion frequency, and role distribution
- Created a synthetic public demo that requires no real Riot account or private player data

**Technologies:** JavaScript, React, Next.js, Node.js, MongoDB, Mongoose, Tailwind CSS, Recharts, Riot Games API, JWT, bcrypt

[**Live Demo →**](https://gtracker-pi.vercel.app/)

> GTracker is a completed project and is no longer in active development. One future direction I'm interested in is combining its player analytics with Esports Central's VOD workflow into a unified esports team platform.

---

### [Esports Central](https://github.com/dgreyson3/Esports-Central-Showcase)

A self-hosted esports VOD library I built for my college esports team after our scrim recordings were effectively trapped on the individual computers that recorded them in the esports lab.

Esports Central gave **6 players and 1 coach** a central place to upload, browse, and review those recordings remotely.

**Highlights:**
- Built authenticated team accounts and a shared VOD library
- Implemented direct browser-to-MinIO MP4 uploads using temporary presigned URLs
- Generated video thumbnails client-side and displayed real-time upload progress
- Stored VOD metadata and team/uploader relationships in PostgreSQL with Prisma
- Built uploader filtering and browser-based video playback
- Containerized Next.js, PostgreSQL, and MinIO with Docker Compose
- Deployed on an Ubuntu VM under Proxmox with NGINX and HTTPS

**Technologies:** Next.js, React, Node.js, PostgreSQL, Prisma, MinIO, Docker, Ubuntu, Proxmox, NGINX

---

## Technical Skills

**Languages:** Python, Java, C, C#, JavaScript, SQL  
**Frontend & Mobile:** React, React Native, Next.js, Expo, Tailwind CSS / NativeWind, Recharts  
**Backend & Data:** PostgreSQL, MongoDB, Mongoose, Prisma, Supabase, Node.js, Express.js, FastAPI, REST APIs, WebSockets  
**Systems & Infrastructure:** Linux, Docker, NGINX, MinIO, Proxmox  
**Testing & Tools:** Pytest, Ruff, MyPy, Git/GitHub, Postman, Arduino  
**Game & Simulation Development:** Unity, C#

## Currently Working On

### Cross-Venue Prediction Market Arbitrage Engine

Continuing development on my Python system for monitoring and evaluating equivalent prediction-market contracts across Kalshi and Polymarket.

**Current focus:** real-time market data, cross-venue normalization, order-book analysis, execution safety, reliability, and automated testing.

### Smash-and-Upgrade Incremental Game — Roblox

Building a progression-focused Roblox game where players clear junk from a town, collect and sell scrap, upgrade their capabilities, and unlock increasingly difficult areas.

A major part of the project is studying what makes progression feel rewarding and designing systems that give players reasons to return. I'm iterating on pacing, rewards, difficulty, economy balance, and event structure to keep the core loop satisfying rather than repetitive.

**Current focus:** player progression, retention-focused game systems, destruction mechanics, scrap economy, upgrade balancing, unlockable areas, persistent cleanup, and competitive Smash Rush events.

### Living-World RPG / Simulation — Unity

Building a medieval sandbox simulation where autonomous characters, settlements, economies, relationships, crime, and survival systems interact to create an evolving world.

The goal is for the player and NPCs to operate under the same underlying rules so that stories and conflicts emerge naturally from the simulation rather than relying primarily on scripted events.

**Current focus:** simulation architecture, autonomous NPC behavior, world-state systems, emergent interactions, and Unity/C# development.

### Coursework

I'm completing the final year of my B.S. in Computer Science at **Central Michigan University**, graduating **May 2027**.

**Fall 2026:** Software Development Tools · Senior Design I · Supervised Machine Learning · Social Engineering, Security Law, Policy & Ethics · Elementary Number Theory

**Spring 2027:** Senior Design II · Computer Security & Cryptography · Data Communications & Computer Networks · Mobile Application Development

## Source Code & Technical Walkthroughs

Several of my projects use private repositories because they contain active product code, strategy logic, infrastructure details, or other implementation details I don't publish openly.

I'm happy to **share relevant source code or walk through the implementation privately with recruiters, hiring managers, and interviewers** upon request.

If you'd like to discuss one of my projects in more detail, feel free to contact me through [LinkedIn](https://www.linkedin.com/in/greyson-fischer/).

## Connect

[LinkedIn](https://www.linkedin.com/in/greyson-fischer/) · [GitHub](https://github.com/dgreyson3)
