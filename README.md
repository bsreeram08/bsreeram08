<a href="https://sreerams.in"><img src="assets/header.svg" alt="Sreeram Balamurugan — Architect. Payments, identity, and developer tooling." width="100%"></a>

<p align="center">
  <a href="https://sreerams.in"><img src="https://img.shields.io/badge/sreerams.in-0e0e0c?style=for-the-badge&logo=googlechrome&logoColor=f3f1ec" alt="Website"></a>
  <a href="https://www.linkedin.com/in/bsreeram08/"><img src="https://img.shields.io/badge/LinkedIn-0e0e0c?style=for-the-badge&logo=linkedin&logoColor=f3f1ec" alt="LinkedIn"></a>
  <a href="https://twitter.com/bsreeram081999"><img src="https://img.shields.io/badge/@bsreeram081999-0e0e0c?style=for-the-badge&logo=x&logoColor=f3f1ec" alt="X"></a>
  <a href="mailto:me@sreerams.in"><img src="https://img.shields.io/badge/me@sreerams.in-b83230?style=for-the-badge&logo=maildotru&logoColor=f3f1ec" alt="Email"></a>
</p>

<p align="center"><i>Building something that moves money? Let's talk.</i></p>

<br>

## `§ 01` About

Architect with **6+ years** building enterprise systems at Surfboard Payments. I work on the cross-cutting parts: authentication, payments, analytics, and developer platforms. Outside work I build tools I want to use, mostly in TypeScript, Go, Kotlin, and Swift.

<table>
  <tr>
    <td align="center" width="25%"><h3>50K+</h3><sub>users on the IAM platform<br>99.9% uptime</sub></td>
    <td align="center" width="25%"><h3>$1M+</h3><sub>processed per month<br>99.95% success rate</sub></td>
    <td align="center" width="25%"><h3>10M+</h3><sub>analytics events<br>per day</sub></td>
    <td align="center" width="25%"><h3>100+</h3><sub>developers on our SDKs<br>70% faster integration</sub></td>
  </tr>
</table>

## `§ 02` Now

| Status | Project | What's happening |
|:--|:--|:--|
| `BUILDING` | [**EMV Android SDK**](https://bsreeram08.github.io/emv-android-sdk/) | Tap-to-phone card acceptance: a Go EMV kernel behind a Kotlin SDK. Latest work adds Kernel 8 and NFC diagnostics with no card data. |
| `SHIPPING` | [**GURL**](https://github.com/bsreeram08/gurl) | CLI API workbench. Collections, encrypted secrets, and a collection runner. |
| `BUILDING` | [**Burrow**](https://github.com/bsreeram08/burrow) | Self-hosted encrypted messenger. Latest work puts the account key on every device, with encrypted backup and key rotation. |
| `BUILDING` | **Intent Launcher** | An Android home screen that is one intent bar. Other apps' shortcuts become tools; harder requests go to Claude. |

## `§ 03` Selected work

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>💳 <a href="https://bsreeram08.github.io/emv-android-sdk/">EMV Android SDK</a></h3>
      <sub><code>Go</code> <code>Kotlin</code> <code>Android NFC</code> <code>cgo</code> <code>EMV</code></sub>
      <p>Contactless card acceptance on an Android phone's NFC reader, no separate terminal. A Go EMV kernel (Visa, Mastercard, Kernel 8 in progress) behind a Kotlin SDK, with card-response parsers fuzzed from every kernel state.</p>
      <sub>Commercial · pre-release · not yet certified</sub>
    </td>
    <td width="50%" valign="top">
      <h3>🔒 <a href="https://github.com/bsreeram08/burrow">Burrow</a></h3>
      <sub><code>Bun</code> <code>Flutter</code> <code>Rust</code> <code>MLS</code> <code>WebRTC</code></sub>
      <p>Self-hosted end-to-end encrypted messenger: Bun server, web client, and Flutter app for iOS, Android, and macOS. MLS group chats, QR device linking, encrypted backup, and calls with a six-digit verification code.</p>
      <sub>In active development · MIT</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>⚡ <a href="https://github.com/bsreeram08/gurl">GURL</a></h3>
      <sub><code>Go</code> <code>goja</code> <code>CLI</code></sub>
      <p>Terminal-native API workbench. Named requests, environments, encrypted secrets, JS hooks, assertions, and a runner across HTTP, GraphQL, gRPC, WebSocket, and SSE. Imports OpenAPI, Insomnia, Bruno, Postman, and HAR.</p>
      <sub>Homebrew · GHCR</sub>
    </td>
    <td width="50%" valign="top">
      <h3>🧰 <a href="https://tlv.sreerams.in">Payment Card Tools</a></h3>
      <sub><code>TypeScript</code> <code>Astro</code> <code>React</code> <code>EMV</code> <code>ISO 8583</code></sub>
      <p>Local-first workspace for EMV, ISO 8583, crypto, PIN blocks, and encoding. Parse BER-TLV, compose ISO 8583 messages, inspect APDUs, and validate EMV config and CA keys.</p>
      <sub><a href="https://tlv.sreerams.in">Live</a> · <a href="https://github.com/bsreeram08/tlv_parser_utility_ui">Source</a></sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🧭 <a href="https://chowser.sreerams.in">Chowser</a></h3>
      <sub><code>Swift</code> <code>SwiftUI</code> <code>macOS</code></sub>
      <p>Native macOS browser chooser. Click a link anywhere and pick the browser and profile that opens it, or let routing rules and URL rewrites decide. Opt-in link history.</p>
      <sub>v3.9.14 · <a href="https://github.com/bsreeram08/chowser">Source</a></sub>
    </td>
    <td width="50%" valign="top">
      <h3>📱 Intent Launcher</h3>
      <sub><code>Kotlin</code> <code>Compose</code> <code>Claude API</code></sub>
      <p>An Android home screen that is a single intent bar. Uses other apps' shortcuts as tools, learns my phrasing, and sends harder requests to Claude. A Mac menu-bar app syncs clipboard over the local network.</p>
      <sub>Personal daily driver · private</sub>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🏭 Payroll Rewrite</h3>
      <sub><code>Go</code> <code>SQLite</code> <code>dBase</code> <code>WebView2</code></sub>
      <p>Replaced a manufacturer's Clipper/dBase payroll program with one Go Windows executable. Lossless import, keystroke-identical entry screens, and export back to the old format.</p>
      <sub>Byte-identical on 465 reference reports</sub>
    </td>
    <td width="50%" valign="top">
      <h3>🎆 Sudharsan Traders</h3>
      <sub><code>Next.js</code> <code>GSAP</code> <code>SQLite</code> <code>Razorpay</code></sub>
      <p>A one-season Diwali store for one truck of Sivakasi crackers: 200 reserved seats across six areas, cart and checkout, UPI and Razorpay links, and kid-safe and low-noise filters.</p>
      <sub>Diwali 2026</sub>
    </td>
  </tr>
</table>

<details>
<summary><b>More projects</b> — agent tooling, CLI tools, MCP servers, web apps</summary>
<br>

| Project | Stack | What it does |
|:--|:--|:--|
| [**Cloum**](https://github.com/bsreeram08/cloum) | TypeScript · Bun | Multi-cloud Kubernetes connection manager for GKE, EKS, and AKS, with auth switching and registry login |
| [**JetID CLI**](https://github.com/bsreeram08/jetid-cli) | TypeScript · Bun | Lexically sortable, cryptographically random IDs from the terminal, with snowflake support |
| [**JWT CLI**](https://github.com/bsreeram08/jwt-cli) | TypeScript · Bun | Instant JWT decode in the terminal. Zero dependencies |
| [**Forge Council**](https://github.com/bsreeram08/forge-council) | TypeScript · Bun · Mastra | Multi-agent engineering council: 12 specialised agents turn a vague idea into a production-ready plan |
| [**Intent Receipt**](https://github.com/bsreeram08/pi-intent-receipt) | TypeScript · Pi | Write `Intent.md`, run `/receipt`: an isolated writer builds it, the host runs the tests and prints a receipt |
| [**Progressive Memory**](https://github.com/bsreeram08/progressive-memory) | Bun · Qdrant · Ollama | Retain, recall, and decay memory hooks for OpenClaw agents on a self-hosted vector store |
| [**Hound Review**](https://github.com/bsreeram08/houndreview) | Bun · GitHub Apps | GitHub App that reviews PRs with a local agent and posts the result as a comment |
| [**PetBuddy**](https://github.com/bsreeram08/petbuddy) | Swift · macOS | Pixel desktop pet that reacts to friends' Slack and Telegram messages. Pre-alpha |
| [**Cogni-Docs**](https://github.com/bsreeram08/Cogni-Docs) | MCP · ChromaDB · Elysia | Local-first MCP server for searching private docs that can't leave your machine |
| [**Git Commands MCP**](https://github.com/bsreeram08/git-commands-mcp) | TypeScript · MCP | Git repository browser over the Model Context Protocol |
| [**AI Personal Journal**](https://journal.sreerams.in) | Next.js · Gemini · Firebase | Journaling with AI entry analysis, insights, and full-text search |
| [**Terrible Cards**](https://github.com/bsreeram08/terrible_cards) | SolidJS · Firebase · GSAP | Real-time multiplayer card game with live Firestore sync |
| **Secure Clipboard** | Flutter · X25519 | End-to-end encrypted clipboard sync across iOS, Android, macOS, and web |

</details>

## `§ 04` Packages

| Package | |
|:--|:--|
| [![npm](https://img.shields.io/npm/v/@bsreeram08/qrmotion?style=flat-square&color=b83230&label=@bsreeram08/qrmotion)](https://www.npmjs.com/package/@bsreeram08/qrmotion) | Animated QR codes where every frame still scans. Zero deps, SVG / canvas / terminal output, MCP server · [source](https://github.com/bsreeram08/qrmotion) |
| [![npm](https://img.shields.io/npm/v/@jetit/id?style=flat-square&color=0e0e0c&label=@jetit/id)](https://www.npmjs.com/package/@jetit/id) | Sortable, cryptographically random IDs |
| [![npm](https://img.shields.io/npm/v/git-commands-mcp?style=flat-square&color=0e0e0c&label=git-commands-mcp)](https://www.npmjs.com/package/git-commands-mcp) | Git over MCP |
| [![npm](https://img.shields.io/npm/v/@mareers/async-throttle?style=flat-square&color=0e0e0c&label=@mareers/async-throttle)](https://www.npmjs.com/package/@mareers/async-throttle) | Async tasks in parallel batches with configurable concurrency |
| [![npm](https://img.shields.io/npm/v/@mareers/google-bigquery-ts?style=flat-square&color=0e0e0c&label=@mareers/google-bigquery-ts)](https://www.npmjs.com/package/@mareers/google-bigquery-ts) | Type-safe BigQuery wrapper with full TypeScript inference |
| [![npm](https://img.shields.io/npm/v/@mareers/dexie-ts-extended?style=flat-square&color=0e0e0c&label=@mareers/dexie-ts-extended)](https://www.npmjs.com/package/@mareers/dexie-ts-extended) | TypeScript-first wrapper over DexieJS for IndexedDB |
| [![JitPack](https://img.shields.io/jitpack/version/com.github.bsreeram08/Ber-TLV-Kotlin?style=flat-square&color=0e0e0c&label=Ber-TLV-Kotlin)](https://jitpack.io/#bsreeram08/Ber-TLV-Kotlin) | BER-TLV parser for the JVM, used in Android payment terminals |

## `§ 05` Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,bun,go,kotlin,swift,dart,flutter,rust,erlang&theme=dark" alt="Languages"><br>
  <img src="https://skillicons.dev/icons?i=react,solidjs,nextjs,astro,postgres,redis,firebase,gcp,kubernetes,docker,githubactions&theme=dark" alt="Frameworks and infrastructure">
</p>

<br>

<p align="center">
  <sub><code>SRB</code> · building resilient systems, one architecture decision at a time · <a href="https://sreerams.in">sreerams.in</a></sub><br><br>
  <img src="https://komarev.com/ghpvc/?username=bsreeram08&label=profile%20views&color=0e0e0c&style=flat-square" alt="Profile views">
</p>

<!-- Last updated: November 2026 -->
