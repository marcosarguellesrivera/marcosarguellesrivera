# 👋 Marcos Argüelles Rivera

**Software Engineer · DevOps · Builder of tools people actually use every day**

📍 Oviedo, Asturias (Spain) &nbsp;·&nbsp; 🎓 B.Sc. Software Engineering (Universidad de Oviedo) + Master's in DevOps &nbsp;·&nbsp; 📫 [marcosarguellesrivera@gmail.com](mailto:marcosarguellesrivera@gmail.com)

> [!NOTE]
> 💡 I like building **products, not just code**: things with a clear data model, a careful UI and a pipeline that ships them.
> Most of my side projects started as a tool I needed myself — to learn, to study, to organise — and grew into apps other people can use.

---

## 🧭 What I bring

| | |
|---|---|
| 🧱 **Full-stack product work** | From the database schema and access policies up to the last pixel of the UI. React / Next.js on the web, Flutter on mobile. |
| 🗂️ **Data modelling & backend** | Postgres with Row-Level Security, migrations and database tests (pgTAP). Schema-validated content packages. |
| ⚙️ **DevOps mindset** | CI/CD with GitHub Actions, automated deploys (Vercel, GitHub Pages), reproducible environments, tests as part of the pipeline. |
| ⛓️ **Distributed & trustless systems** | Smart contracts in Solidity, oracle networks (Chainlink Functions & Automation), gas optimisation with bit-packing. |
| 🤖 **AI-assisted features** | LLM integrations that stay useful and private (user-owned API keys, graceful fallback when there is no key). |
| ✍️ **Writing things down** | Design docs and implementation plans before code; READMEs that let someone else run the project in five minutes. |

---

## 🚀 Featured projects

| Project | What it is | Stack | Links |
|---|---|---|---|
| 🎲 **dBet** | Fully autonomous, trustless sports-betting protocol (my Bachelor's thesis) | Solidity · Hardhat · Chainlink · Next.js · Ethers.js | [Live](https://d-bet.vercel.app) · [Code](https://github.com/marcosarguellesrivera/dBet) |
| 📚 **Daily Learn** | Android + web app to learn a bit of everything, 5–10 minutes a day | Flutter · Riverpod · Supabase (Postgres + RLS) · Node | 🚧 In progress |
| ☁️ **AZ-900 Trainer** | Study app for the Microsoft Azure Fundamentals certification | Vanilla JS · HTML/CSS · Vercel | [Live](https://az900-trainer.vercel.app) |
| 🇬🇧 **B2 First Prep** | Full Cambridge B2 First preparation suite with AI marking | Vanilla JS · Web Speech API · Claude API | [Live](https://b2-ingles.vercel.app) |
| 🔨 **Auction DApp** | On-chain auctions with automatic refunds, deployed on BSC testnet | Solidity · Next.js · Ethers.js · GitHub Actions | [Live](https://marcosarguellesrivera.github.io/auction-dapp/) · [Code](https://github.com/marcosarguellesrivera/auction-dapp) |

<details>
<summary><b>🎲 dBet — trustless sports betting, run entirely by code</b></summary>
<br>

Traditional betting platforms hold your money and decide who won. **dBet** replaces that trust with smart contracts and decentralised oracles.

- **Pari-mutuel pools on Ethereum:** every bet and every payout lives on-chain; users keep custody of their funds.
- **Zero human operators:** Chainlink Automation wakes the contract up to schedule new matches on its own.
- **Verifiable results:** Chainlink Functions fetch fixtures and final scores from public sports APIs off-chain and inject them on-chain.
- **Gas-efficient by design:** match data is bit-packed off-chain and unpacked with bitwise operations in Solidity; conditional logic is pushed off-chain.
- **Tested end-to-end:** Hardhat test suite for the contract and tests for the Chainlink CRE workflows (staging / production configs).

`Solidity` `Hardhat` `Chainlink Functions` `Chainlink Automation` `TypeScript` `Next.js` `Ethers.js` `Vercel`

</details>

<details>
<summary><b>📚 Daily Learn — micro-learning app with a topic store</b></summary>
<br>

Short daily sessions across several topics, with a store of topics, per-user progress and moderation.

- **Flutter client for Android and web**, feature-first architecture (`auth`, `today`, `session`, `store`, `progress`…) with Riverpod and go_router.
- **Supabase backend:** versioned SQL migrations, **Row-Level Security** policies, and **pgTAP database tests** run against the linked project.
- **Content as data:** each topic is a `topic.json` package validated against a **JSON Schema**; a Node toolchain validates topics and generates the seed.
- **Google sign-in** on both web and Android.
- Built from a written **design spec and implementation plans** before the first line of code.

`Flutter` `Dart` `Riverpod` `Supabase` `PostgreSQL` `RLS` `pgTAP` `JSON Schema` `Node.js`

</details>

<details>
<summary><b>🇬🇧 B2 First Prep — a whole exam in the browser, no backend</b></summary>
<br>

- All **7 Reading & Use of English parts** with auto-marking, explanations and timers; a **full mock exam** with an estimated Cambridge English Scale score.
- **Writing:** 23 tasks with word counter, official checklist and model answers.
- **Listening & Speaking** using speech synthesis as the examiner, recording and automatic transcription.
- **Drills with spaced repetition** for phrasal verbs, collocations and word formation.
- **Optional AI marking with Claude** using the official Cambridge criteria. The API key never leaves the browser, and without a key the app generates a ready-to-paste prompt so anyone can still get feedback.
- Progress stored locally with import / export.

`JavaScript` `Web Speech API` `MediaRecorder` `Claude API` `localStorage`

</details>

<details>
<summary><b>☁️ AZ-900 Trainer — Azure Fundamentals, one domain at a time</b></summary>
<br>

- Lessons, question banks and scenario-based practice organised by the official exam domains.
- Quiz engine, progress tracking and a hand-made design system documented in a `DESIGN.md`.
- Zero dependencies, deployed on Vercel.

`JavaScript` `HTML` `CSS` `Vercel` `Azure`

</details>

<details>
<summary><b>🎓 University work</b></summary>
<br>

- **[DLP](https://github.com/marcosarguellesrivera/DLP)** — Programming Language Design: lab work on language processors (lexing, parsing, semantic analysis, code generation).
- **[F1Desktop](https://github.com/marcosarguellesrivera/F1Desktop)** — Web Software & Standards: a standards-compliant site in HTML, CSS, JavaScript and PHP.
- **Distributed Systems & Internet** — web applications built in Java and Node.js.

</details>

---

## 🛠️ Toolbox

<p>
  <img src="https://skillicons.dev/icons?i=ts,js,java,dart,solidity,php,html,css&perline=8" alt="Languages" /><br>
  <img src="https://skillicons.dev/icons?i=react,nextjs,flutter,nodejs,postgres,supabase&perline=8" alt="Frameworks and data" /><br>
  <img src="https://skillicons.dev/icons?i=git,github,githubactions,azure,vercel,linux,vscode&perline=8" alt="DevOps and tooling" />
</p>

---

## 🧩 How I work

- ☑️ **Spec first, then code.** A short design doc saves a week of rework.
- ☑️ **Security is part of the data model**, not a layer on top (RLS policies, least-privilege grants, keys that stay on the client).
- ☑️ **If it isn't tested and deployed, it isn't done.** CI, migrations and seeds are part of the feature.
- ☑️ **Small, focused tools beat big, vague ones.** Every project above solves one problem well.

---

<p align="center">
  <i>Currently looking for software engineering roles where product craft and solid infrastructure meet.</i><br>
  <a href="mailto:marcosarguellesrivera@gmail.com">📫 Let's talk</a>
</p>
