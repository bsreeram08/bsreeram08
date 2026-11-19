# 👨‍💻 Sreeram Balamurugan (SRB)

<div align="center">

[![Twitter: bsreeram081999](https://img.shields.io/twitter/follow/bsreeram081999?style=social)](https://twitter.com/bsreeram081999)
[![LinkedIn: bsreeram08](https://img.shields.io/badge/-bsreeram08-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/bsreeram08/)](https://www.linkedin.com/in/bsreeram08/)
[![GitHub: bsreeram08](https://img.shields.io/github/followers/bsreeram08?label=follow&style=social)](https://github.com/bsreeram08)
[![Email](https://img.shields.io/badge/Email-me%40sreerams.in-red?style=flat-square&logo=gmail)](mailto:me@sreerams.in)

_Architect solving complex system design problems and building enterprise-grade infrastructure that scales_

</div>

## 💡 About Me

Architect with 6+ years building enterprise systems at Surfboard Payments. I focus on solving complex cross-cutting concerns — authentication, payments, analytics, and developer platforms.

- **Current Role**: Architect @ Surfboard Payments (Oct 2020 – Present)
- **Specialties**: Fintech infrastructure, IAM systems, payment processing, SDK design
- **Core Stack**: TypeScript, Node.js, Bun, PostgreSQL, Redis, Firebase
- **Cross-Platform**: Swift/iOS, Dart/Flutter, Kotlin/Android
- **Architecture**: Microservices, Event-driven systems, Domain-Driven Design

**Impact numbers**:
- 🔐 IAM platform serving **50K+ users** — 99.9% uptime, zero incidents in 2 years
- 💳 Payment system processing **$1M+/month** — 99.95% success rate
- 📊 Analytics pipeline handling **10M+ events/day**
- 📦 SDKs used by **100+ developers** — 70% faster client integration

## 🔭 Now

- **[EMV Android SDK](https://bsreeram08.github.io/emv-android-sdk/)** · _Building_ — Tap-to-phone card acceptance: a Go EMV kernel behind a Kotlin SDK. Latest work adds Kernel 8 and NFC diagnostics with no card data.
- **[GURL](https://github.com/bsreeram08/gurl)** · _Shipping_ — CLI API workbench. Collections, encrypted secrets, and a collection runner.
- **[Burrow](https://github.com/bsreeram08/burrow)** · _Building_ — Self-hosted encrypted messenger with MLS group chats and calls. Latest work puts the account key on every device, with encrypted backup and key rotation.
- **Intent Launcher** · _Building_ — An Android home screen that is one intent bar. Other apps' shortcuts become tools, and harder requests go to Claude.

## 🚀 Projects

### 💳 Payments

#### EMV Android SDK · [Docs](https://bsreeram08.github.io/emv-android-sdk/) · _commercial, pre-release_
_Go · Kotlin · Android NFC · cgo · EMV_

Contactless EMV card acceptance on an Android phone's NFC reader, with no separate terminal. A Go EMV kernel (Visa and Mastercard paths, EMV C-8 Kernel 8 in progress) sits behind a Kotlin SDK: reader lifecycle, kernel-built online requests, a host interface, and NFC diagnostics that carry no card data. The card-response parsers are fuzzed from every kernel state. It is not certified yet and is delivered only to licensed customers.

#### [Payment Card Tools](https://github.com/bsreeram08/tlv_parser_utility_ui) · [Live](https://tlv.sreerams.in)
_TypeScript · Astro · React · EMV · ISO8583_

Local-first workspace for EMV, ISO 8583, cryptography, PIN blocks, card data, and encoding. Parse and edit BER-TLV, compose ISO 8583 messages, inspect APDUs, and validate EMV configuration and CA public keys. Saved work stays in the browser.

---

### 🔒 Messaging

#### [Burrow](https://github.com/bsreeram08/burrow) · _in active development, MIT_
_TypeScript · Bun · Flutter · Rust · MLS · WebRTC_

Self-hosted end-to-end encrypted messenger with a Bun server, a web client, and a Flutter app for iOS, Android, and macOS. MLS group chats, multi-device accounts with QR linking and an encrypted backup, and one-to-one calls with a six-digit verification code. The server holds only encrypted messages and attachments until they are delivered.

---

### 🖥️ Native Apps

#### [Chowser](https://github.com/bsreeram08/chowser) · [Site](https://chowser.sreerams.in)
_Swift · SwiftUI · macOS_

Native macOS browser chooser. Click a link in any app and pick the browser and profile that opens it, or let routing rules and URL rewrites decide. Recent releases add link history, asked for before anything is saved. Released through v3.9.14.

#### Intent Launcher · _private_
_Kotlin · Jetpack Compose · Android · Claude API_

An Android home screen that is a single intent bar. As the default home app it can use other apps' shortcuts as tools, learns my phrasing, and sends harder requests to Claude with my own key. A small Mac menu-bar app syncs plain-text clipboard with the phone over the local network.

---

### ⚡ CLI Tools

#### [GURL](https://github.com/bsreeram08/gurl)
_Go · goja · CLI_

Terminal-native API workbench. Named requests, environments, encrypted collection secrets, JavaScript hooks, assertions, and a collection runner across HTTP, GraphQL, gRPC, WebSocket, and SSE. Imports OpenAPI, Insomnia, Bruno, Postman, and HAR. Distributed with Homebrew and GHCR.

#### [Cloum](https://github.com/bsreeram08/cloum)
_TypeScript · Bun · Kubernetes · GCP · AWS · Azure_

Multi-cloud Kubernetes connection manager. Intercepts kubectl context switching and handles auth/account switching automatically. Supports GKE, EKS, and AKS with cluster discovery via cloud APIs, container registry login (GCR, ECR, ACR), and bulk JSON import.

#### [JetID CLI](https://github.com/bsreeram08/jetid-cli) · [![npm](https://img.shields.io/npm/v/@jetit/id?label=@jetit/id)](https://www.npmjs.com/package/@jetit/id)
_TypeScript · Bun · Distributed Systems_

Generate and convert lexically sortable, cryptographically random IDs from the terminal. Cross-platform multi-arch binary with snowflake ID support.

#### [JWT CLI](https://github.com/bsreeram08/jwt-cli)
_TypeScript · Bun_

Instant JWT decode and inspection in the terminal. Zero dependencies, sub-millisecond startup via Bun.

---

### 🤖 AI & MCP

#### [Cogni-Docs](https://github.com/bsreeram08/Cogni-Docs)
_TypeScript · MCP · Bun · ChromaDB · Xenova · Elysia_

Local-first MCP server for AI assistants to search and query private documentation. Provider-agnostic, built for confidential docs that can't leave your machine. Vector embeddings with ChromaDB, semantic search via Xenova.

#### [AI Personal Journal](https://journal.sreerams.in)
_Next.js · Vertex AI · Gemini · Firebase · TypeScript_

Intelligent journaling app with AI-powered entry analysis, automated insights, full-text search, and calendar navigation. Firebase auth + Firestore for persistence.

#### [Git Commands MCP](https://github.com/bsreeram08/git-commands-mcp) · [![npm](https://img.shields.io/npm/v/git-commands-mcp?label=npm)](https://www.npmjs.com/package/git-commands-mcp)
_Node.js · TypeScript · Bun · MCP_

Git repository browser implementing the Model Context Protocol for AI-assisted git workflows.

---

### 🌐 Web & Real-time

#### [Terrible Cards](https://github.com/bsreeram08/terrible_cards)
_SolidJS · TypeScript · Bun · Firebase · GSAP_

Real-time multiplayer card game with live Firestore sync and smooth GSAP animations.

#### Secure Cross-Device Clipboard
_Flutter · Dart · Firebase · X25519 · E2E Encryption_

End-to-end encrypted clipboard sync across iOS, Android, macOS, and Web. X25519 key exchange with automatic device pairing.

---

### 🏭 Client Builds

#### Payroll Rewrite
_Go · SQLite · dBase · WebView2_

Replaced a manufacturer's Clipper and dBase payroll program with one Go Windows executable on SQLite. Imports the old year folders losslessly, entry screens follow the old program keystroke for keystroke, and it can export back to the old format. Reports are byte-identical to the original on 465 reference reports.

#### Sudharsan Traders
_Next.js · TypeScript · Tailwind · GSAP · SQLite · Razorpay_

A one-season Diwali store for one truck of Sivakasi crackers, with 200 reserved seats across six areas along GST Road. Reservations, cart and checkout, UPI and Razorpay payment links, discount codes, kid-safe and low-noise filters, and an admin view.

---

## 📦 Open Source Packages

| Package | Description |
|---|---|
| [![npm](https://img.shields.io/npm/v/@bsreeram08/qrmotion?label=@bsreeram08/qrmotion)](https://www.npmjs.com/package/@bsreeram08/qrmotion) | Animated QR codes where every frame still scans — zero deps, SVG/canvas/terminal output, MCP server |
| [![npm](https://img.shields.io/npm/v/@mareers/async-throttle?label=@mareers/async-throttle)](https://www.npmjs.com/package/@mareers/async-throttle) | Execute async tasks in parallel batches with configurable concurrency |
| [![npm](https://img.shields.io/npm/v/@mareers/google-bigquery-ts?label=@mareers/google-bigquery-ts)](https://www.npmjs.com/package/@mareers/google-bigquery-ts) | Type-safe ORM wrapper for Google BigQuery with full TypeScript inference |
| [![npm](https://img.shields.io/npm/v/@mareers/dexie-ts-extended?label=@mareers/dexie-ts-extended)](https://www.npmjs.com/package/@mareers/dexie-ts-extended) | TypeScript-first wrapper over DexieJS for IndexedDB |
| [![](https://jitpack.io/v/bsreeram08/Ber-TLV-Kotlin.svg)](https://jitpack.io/#bsreeram08/Ber-TLV-Kotlin) | BER-TLV parser for JVM — used in Android payment terminal integrations |


## 🛠️ Tech Stack

<div align="center">

![TypeScript](https://img.shields.io/badge/-TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Node.js](https://img.shields.io/badge/-Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Bun](https://img.shields.io/badge/-Bun-000000?style=for-the-badge&logo=bun&logoColor=white)
![Swift](https://img.shields.io/badge/-Swift-FA7343?style=for-the-badge&logo=swift&logoColor=white)
![Dart](https://img.shields.io/badge/-Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white)
![Flutter](https://img.shields.io/badge/-Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![Go](https://img.shields.io/badge/-Go-00ADD8?style=for-the-badge&logo=go&logoColor=white)
![Kotlin](https://img.shields.io/badge/-Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Erlang](https://img.shields.io/badge/-Erlang-A90533?style=for-the-badge&logo=erlang&logoColor=white)

![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/-Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Firebase](https://img.shields.io/badge/-Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![BigQuery](https://img.shields.io/badge/-BigQuery-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white)
![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)

![Docker](https://img.shields.io/badge/-Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/-Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/-GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)

</div>

---

<div align="center">
  <i>Building resilient systems, one architecture decision at a time</i>
  <br><br>
  <img src="https://komarev.com/ghpvc/?username=bsreeram08&label=Profile%20views&color=0e75b6&style=flat" alt="Profile visitor" />
</div>

<!-- Last updated: November 2026 -->
