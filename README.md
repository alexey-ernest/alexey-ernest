<!-- ama:start -->
## Alexey Melnikov

**AI Software Engineer**

Gold Coast, Australia · open for remote roles

I build AI-powered products. These include a résumé agent that answers recruiters' questions, a personal agent that handles everyday tasks, and a house planner that turns a plot of land and a floor plan into a photorealistic model. I also build crypto trading tools: a wallet that explains transactions, a trading desk that watches for price gaps, and a World Cup prediction game for friends. Earlier, I worked on R&amp;D projects, smart city systems, and trading platforms.

### Projects

#### AMA

*Back-end developer · Nov 2026*

AMA \("Ask My Agent"\) is a professional agent. You build a memory of your work by talking to it in one chat and by connecting your GitHub repositories, which it reads in depth. From that memory it keeps a public résumé at your own address, with screenshots and short narrated videos of your projects, and a short video in which an AI avatar of you, with your face and voice, introduces you. On the résumé, recruiters and other visitors can ask your agent about your work, and you decide exactly what each audience may see. It means you no longer have to write up and keep updating your projects by hand, and visitors can get real answers about your work without reaching your private notes or code.

`TypeScript / Node 22` `React 19 + Vite + Tailwind` `Postgres with pgvector` `Anthropic SDK (Claude Opus, Haiku)` `Voyage AI embeddings` `Restate` `SimpleWebAuthn` `Playwright`

<p><a href="https://ama-agent.fly.dev/api/public/alexey-melnikov/videos/vid_4b1144154d06670c"><img src="https://ama-agent.fly.dev/api/public/alexey-melnikov/videos/vid_4b1144154d06670c/play" alt="▶ Watch the video of AMA (0:50)" title="▶ Watch the video of AMA (0:50)" width="320"></a></p>

<p><a href="https://ama-agent.fly.dev/api/public/alexey-melnikov/shots/sht_9ba1059ddeb473f3"><img src="https://ama-agent.fly.dev/api/public/alexey-melnikov/shots/sht_9ba1059ddeb473f3" alt="Landing page" title="Landing page" width="200"></a> <a href="https://ama-agent.fly.dev/api/public/alexey-melnikov/shots/sht_96f31c843a02ee7a"><img src="https://ama-agent.fly.dev/api/public/alexey-melnikov/shots/sht_96f31c843a02ee7a" alt="Résumé" title="Résumé" width="200"></a> <a href="https://ama-agent.fly.dev/api/public/alexey-melnikov/shots/sht_018f9056e8c5e282"><img src="https://ama-agent.fly.dev/api/public/alexey-melnikov/shots/sht_018f9056e8c5e282" alt="Chat: owner tells AMA about work" title="Chat: owner tells AMA about work" width="200"></a> <a href="https://ama-agent.fly.dev/api/public/alexey-melnikov/shots/sht_8b8b1ee98722626e"><img src="https://ama-agent.fly.dev/api/public/alexey-melnikov/shots/sht_8b8b1ee98722626e" alt="Scan report" title="Scan report" width="200"></a> <a href="https://ama-agent.fly.dev/api/public/alexey-melnikov/shots/sht_5bee44e90c14d062"><img src="https://ama-agent.fly.dev/api/public/alexey-melnikov/shots/sht_5bee44e90c14d062" alt="Priya Raman" title="Priya Raman" width="200"></a></p>

---

#### DeepMarket

*Subagents father · Oct 2026 – Nov 2026*

DeepMarket is a personal assistant that runs your errands by hiring specialised sub-agents for you and paying them from your own wallet. It reads your mail and turns what needs doing into tasks and reply drafts, keeps your calendar in step, watches fares, compares stays and products, follows your kids' sports fixtures and checks your bills on sites you are logged in to. Nothing is sent, booked or paid until you approve it with your passkey \(Face ID\).

`Rust` `Restate` `Postgres with pgvector` `TypeScript / Node` `React, Tailwind, Vite` `@simplewebauthn` `Swift / iOS` `Solidity / Foundry`

<p><a href="https://ama-agent.fly.dev/api/public/alexey-melnikov/videos/vid_f81d102773dc19b2"><img src="https://ama-agent.fly.dev/api/public/alexey-melnikov/videos/vid_f81d102773dc19b2/play" alt="▶ Watch the video of DeepMarket (0:57)" title="▶ Watch the video of DeepMarket (0:57)" width="320"></a></p>

---

#### OpenSui

*Sole builder and architect · Aug 2026 – present*

OpenSui is a self-custody wallet for the Sui blockchain. It runs as a Chrome extension, as an iPhone or web app, and as a read-only web portal. Before you sign anything, it shows in plain words what the transaction will do and how your balances will change. You can pay gas in coins other than SUI, save any transaction as a reusable template and run it again on one wallet or many, and ask an AI composer to build a transaction from a sentence. The same wallet also handles swaps, lending, DeepBook trading, perps and Predict, and has encrypted messaging, payments and calls between addresses. The goal is to use Sui apps from one place without signing transactions you cannot read.

`TypeScript` `React` `WXT (MV3 Chrome extension)` `Capacitor` `@mysten/sui SDK (gRPC + GraphQL)` `hash-wasm (Argon2id)` `@noble curves/ciphers/hashes` `Anthropic SDK`

<p><a href="https://ama-agent.fly.dev/api/public/alexey-melnikov/videos/vid_62fc04e84d3bebf0"><img src="https://ama-agent.fly.dev/api/public/alexey-melnikov/videos/vid_62fc04e84d3bebf0/play" alt="▶ Watch the video of OpenSui (0:52)" title="▶ Watch the video of OpenSui (0:52)" width="320"></a></p>

---

#### Varvarovka

*Experimentator · Nov 2026*

Varvarovka \(Varvarovka Hills\) is an AI-assisted house planner built on a 3D model of a real land lot. You talk to a chat. You can start from an empty lot or a scanned floor plan and add a house, change the ground, place furniture and build a garden. Each change shows up in the 3D scene right away and is checked against site, safety and building rules. You can walk through the house, view it at any time of day, and get photoreal renders that keep the real geometry. The aim is to let someone who is not an architect turn a plot and an idea into a correct house sketch they can share.

`three.js` `delaunator` `React + Vite` `ajv` `Postgres 16 + pgvector` `Anthropic Claude` `OpenAI APIs` `Voyage AI`

---

#### EdgeRunner

*Founder and trader · 2022–present*

An arbitrage monitoring and trading desk that keeps live order books in sync across about two dozen crypto exchanges and several on-chain venues. It finds routes where buying and selling across markets, with transfers where needed, pays more than it costs, and ranks them by dollars earned per hour of capital tied up. In one live reading it had 30 of 32 venues live with 19.2K order books synced, and handled about 35.8K book updates per second with 0 dropped events. A 2-shard graph engine scored 1.4M cycles per second and tracked 1,306 live opportunities. At busy market times it passes 100K updates per second. Trading keys never leave the browser.

`Rust` `Tokio` `tokio-tungstenite` `crossbeam-channel` `axum / tower-http` `SQLite (rusqlite)` `crc32fast` `React + Zustand`

<details>
<summary>5 more projects</summary>

#### FIL 2026 — Football Is Life

*Sole builder, architect and player · Apr 2026 – Aug 2026*

FIL 2026 is a social prediction game for the FIFA World Cup 2026 in which friends stake USDC into private leagues, earn virtual points through AI-generated live pop-up questions, position trading on match probabilities and pre-match score predictions, and split the prize pool by stake × points. It adds a collectible NFT player-card layer with on-chain card-for-card trading and fusion, and Team Battles where users field 11 same-nation cards in simulated matches and an in-league World Cup battle tournament.

`TypeScript` `React` `Fastify` `SQLite (better-sqlite3)` `Sui Move` `Anthropic Claude API` `OpenAI gpt-image-2` `Fly.io`

<p><a href="https://ama-agent.fly.dev/api/public/alexey-melnikov/videos/vid_5d497af5d8e2897b"><img src="https://ama-agent.fly.dev/api/public/alexey-melnikov/videos/vid_5d497af5d8e2897b/play" alt="▶ Watch the video of FIL 2026 — Football Is Life (0:41)" title="▶ Watch the video of FIL 2026 — Football Is Life (0:41)" width="320"></a></p>

<p><a href="https://ama-agent.fly.dev/api/public/alexey-melnikov/shots/sht_b3b093e1231146b2"><img src="https://ama-agent.fly.dev/api/public/alexey-melnikov/shots/sht_b3b093e1231146b2" alt="Football Is Life 2026" title="Football Is Life 2026" width="200"></a> <a href="https://ama-agent.fly.dev/api/public/alexey-melnikov/shots/sht_1536db381960c1b9"><img src="https://ama-agent.fly.dev/api/public/alexey-melnikov/shots/sht_1536db381960c1b9" alt="Office World Cup Pool" title="Office World Cup Pool" width="200"></a> <a href="https://ama-agent.fly.dev/api/public/alexey-melnikov/shots/sht_bfcaff2c9898a6f0"><img src="https://ama-agent.fly.dev/api/public/alexey-melnikov/shots/sht_bfcaff2c9898a6f0" alt="Ranks" title="Ranks" width="200"></a> <a href="https://ama-agent.fly.dev/api/public/alexey-melnikov/shots/sht_22a0d36c6c46f0b6"><img src="https://ama-agent.fly.dev/api/public/alexey-melnikov/shots/sht_22a0d36c6c46f0b6" alt="Friday Night Futbol" title="Friday Night Futbol" width="200"></a> <a href="https://ama-agent.fly.dev/api/public/alexey-melnikov/shots/sht_f4129a8042db5794"><img src="https://ama-agent.fly.dev/api/public/alexey-melnikov/shots/sht_f4129a8042db5794" alt="Match 14 live chart with the pop-up question open, 30 s coun" title="Match 14 live chart with the pop-up question open, 30 s coun" width="200"></a> <a href="https://ama-agent.fly.dev/api/public/alexey-melnikov/shots/sht_838fe05a94db1e2c"><img src="https://ama-agent.fly.dev/api/public/alexey-melnikov/shots/sht_838fe05a94db1e2c" alt="Match 14 commentary" title="Match 14 commentary" width="200"></a></p>

---

#### Geological data digitisation at Google X

*Senior Software Engineer · 2021 – Mar 2022*

An R&amp;D engagement at Google X \(via EPAM Systems\) to digitise and structure geological and drilling-well information from petroleum-industry sources for digital geological mapping. I developed the Python software, applied machine-learning, computer-vision and image-processing libraries to detect colours, shapes and patterns in digitised records, and contributed to processing seismic-sensor data, including prototyping, system design, testing and code review.

`Python`

---

#### Self-service systems UI at Walmart

*Senior Software Engineer · Jul 2020 – Jan 2021*

I developed reusable React components and screens for Walmart self-service systems \(via EPAM Systems\), integrated frontend logic with internal APIs, and implemented and tested features in CI and Agile delivery.

`JavaScript` `TypeScript` `React` `Jest` `Enzyme`

---

#### Verizon Smart City

*Senior Software Engineer · May 2019 – Jul 2020*

Smart City systems that collect, process and analyse traffic and location data from traffic lights, emergency vehicles, telecommunications and other urban sources. Via EPAM Systems, I developed REST APIs and backend services, built geospatial visualisations and interactive traffic-analysis maps, and optimised SQL queries, APIs, latency and throughput.

`Scala` `Node.js` `Express` `React` `Kepler.gl` `http4s` `Cats` `AWS Aurora/MySQL` `Docker` `DC/OS` `Jenkins`

---

#### AI-powered trading platform at Watstock

*Lead Software Engineer · Nov 2016 – Sep 2017*

An AI-powered trading platform for market-price and trend prediction. I built big-data pipelines, web APIs for mobile and web apps, GPU cloud infrastructure for neural-network training and MLP, RNN and ELM models, and as technical project manager led a small data-engineering team.

`Spark` `Spark SQL` `Spark Streaming` `AWS EMR` `Node.js` `MongoDB` `Docker` `AWS`

</details>

---

[The whole résumé, and an agent that answers questions about it](https://ama-agent.fly.dev/u/alexey-melnikov)

<sub>This section is kept current by AMA from the résumé: a change made here is written over.</sub>
<!-- ama:end -->
