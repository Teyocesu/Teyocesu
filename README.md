# Teyocesu

I build and ship practical software across local-first desktop applications, backend and web systems, developer tooling, mobile apps, and platform/protocol integrations. My current work emphasizes on-device processing, bounded data flows, authenticated local communication, and release, CI, and test workflows.

## Current focus

- Desktop applications that keep audio, text, and user state local where possible.
- Web and API systems with explicit storage, validation, and security boundaries.
- Developer tools and protocol integrations for controlled local or LAN workflows.
- Reproducible builds, checksums, automated tests, and recovery paths around releases.

## Flagship projects

| Project | Status | What it does |
|---|---|---|
| [ClassScribe](https://github.com/Teyocesu/ClassScribe) | Public · [v0.8.0](https://github.com/Teyocesu/ClassScribe/releases/latest) | Local-first desktop app for recording classes and creating editable, speaker-aware transcripts on macOS and Windows. Speech processing runs on the device, with live editing, recovery, speaker handling, exports, and tested release artifacts. |
| [LyricsChatbox](https://github.com/Teyocesu/LyricsChatbox) | Public · [v0.4.0](https://github.com/Teyocesu/LyricsChatbox/releases/latest) | Windows C#/.NET/WPF app that follows native Apple Music playback, finds synchronized lyrics, and sends the current line to the VRChat OSC Chatbox. Accounts, telemetry, Apple credentials, and a backend are not required. |
| [Prueba Digital](https://github.com/Teyocesu/Prueba-Digital) | Public | Browser-side evidence tool that preserves file bytes, calculates SHA-256 integrity hashes, associates supporting captures, and generates an organized manifest/package with independent verification. |
| [Polivalent Media Downloader](https://github.com/Teyocesu/Polivalent-Media-Downloader) | Public | FastAPI/React tool for authorized public media links, using a closed platform allowlist, ephemeral one-time downloads, cleanup, and Docker-supported deployment. It does not target DRM, paywall, or private-access bypassing. |

## Selected private engineering work

| Project | Status | What it does |
|---|---|---|
| Avatar Remote | Private · closed-source | Local-first desktop/mobile bridge for VRChat OSC and OSCQuery, with authenticated realtime communication, LAN pairing/security, and mobile control of avatar parameters. |
| WorkflowMCP | Private · closed-source | Local read-only MCP server that provides Codex with bounded canonical project context, Git state, and validation guidance for spec-driven repositories. |
| Manga Tracker | Private · closed-source | WhatsApp + web workflow for multi-user manga collection tracking, persistent state, and editorial/provider integrations. |

## Currently building

- [Avatar Doctor](https://github.com/Teyocesu/Avatar-Doctor) — **Public · pre-alpha.** A Unity Editor package with a presentation-only window plus deterministic package validation and release-artifact workflows. Avatar discovery, scanning, diagnostics, repairs, Quest preparation, and publishing remain planned rather than implemented.
- EscudoPago — **Private · bootstrap/early.** A B2B concept for helping Mercado Pago merchants organize and manage chargebacks with a strict security posture. It is not production-ready and is not for real data or credentials.

## Additional / earlier projects

- [Manga Reader Selfhosted](https://github.com/Teyocesu/Manga-Reader-Selfhosted) — Local-first reader for personal CBZ/ZIP archives with uploads, reading progress, page/webtoon modes, quotas, and private-network access.
- [Desafio Calculo Mental](https://github.com/Teyocesu/Desafio-Calculo-Mental) — Expo/React Native/TypeScript mobile math game with local history and statistics.
- [Desafio Reaccion Android](https://github.com/Teyocesu/desafio-reaccion-android) — Offline Kotlin/Jetpack Compose reaction and attention game with local scores and history.

## Core technology stack

- **Languages:** Swift · C# · TypeScript · Python · Kotlin
- **Desktop and UI:** SwiftUI · WPF · React
- **Backend and data:** .NET · FastAPI · Node.js · PostgreSQL / SQLite
- **Delivery:** Docker · GitHub Actions · Git
