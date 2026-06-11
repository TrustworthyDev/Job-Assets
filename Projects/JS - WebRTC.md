Instant: Real-Time Meeting Translation
Instant is a cross‑platform app for 1:1 and group meetings with real‑time transcription and translation. It supports quick calls, calendar scheduling, adding/removing participants, finding users on a map, and starting a call with a QR code. For large events there’s a Conference Mode: several speakers can talk while thousands listen with live translation and captions at near‑imperceptible latency.

Remove language friction in online meetings. Start instantly or schedule. Up to 50 participants, or thousands of listeners in Conference Mode.

- Speak naturally in your language – captions & translated audio in real time
- One platform for quick calls, scheduled meetings, and large broadcasts
- Join fast via QR code, map discovery, and invites

## Problem
- On-the-fly translation with live captions needed
- Minimal latency via WebRTC
- Simple scheduling & participant control
- Both small meetings and large conferences

## Challenge
- Plavno identified 4 challenges that consistently break live multilingual experiences:
- Real-time Translation: Natural speech translation with minimal latency and high accuracy
- Flexible Formats: Support for 1:1, groups, and multi-speaker broadcast modes
- Smooth UX: Instant start, calendar integration, map discovery, and QR joining
- Reliability & Scale: Elastic cloud scaling with consistent performance

## Solution
The multilingual voice stack for calls and conferences — modular components, sub-second path, domain accuracy, global reach. Before the architecture, here’s what it does:
# product Highlights
- Real‑time pipeline: Speech → Transcription → Machine Translation → TTS/Subtitles.
- Two call modes: instant and scheduled.
- Groups up to 50: add/remove participants on the fly.
- Conference Mode: multiple speakers, thousands of listeners.
- Map search and QR code call creation.
- Call history  for 1:1 and group sessions.
- Low‑latency WebRTC resilient to packet loss.
# User Flows
- Start Now: create a room and invite via QR/link.
- Schedule: pick time, participants, and roles (speakers/listeners).
- Join a Conference: select language, listen with translated audio, read captions.

# Experience & Scale
- Live experience: Sub-second perceived latency that feels conversational.
- Accuracy under pressure: Maintains domain fidelity during fast speech and code-switching.
- Operational simplicity: Plug-in SDKs; deploy without backend surgery.
- Audience scale: Thousands of concurrent listeners per session, multi-region.
- Post-event assets: Clean audio + VTT/SRT delivered automatically.

## Deep Dive: Project Architecture
- Clients: Web (React) and Mobile (React Native) connect to media servers via WebRTC. State via Redux Toolkit / React Query.
- RTC/Media layer: nodes on AWS EC2; signaling over WebSocket; media processing in Express/WebRTC services.
- STT: dedicated speech‑to‑text server returns partial and final transcripts.
- NMT (translation): machine translation module produces target‑language text.
- TTS: Azure TTS synthesizes audio; subtitles stream to clients in parallel.

## Hard Problems We Solved
- Real-Time, Natural Translation
Deliver natural, real‑time speech translation.
- Flexible Session Formats
Support formats: 1:1, groups up to 50, and multi‑speaker → thousands of listeners.
- Frictionless UX
Keep UX smooth: instant start, calendar, map, QR, and call history.
- Cloud-Scale Reliability
Ensure reliability and elastic scaling on cloud infrastructure.

## Quality & Fidelity 
Horizontal scaling with consistent performance.

# Live Transcripts & Captions
Streaming transcripts and captions.

Streaming ASR
Partial/Final
Punctuation
MVP

# Instant Language Switching
Client‑side language switching without reconnects.

Per-listener
Hot switch
No reconnect
MVP

# Roles & Moderation
Role control (speaker/listener) and moderation tools in conferences.

Raise hand
Queue
Mute/Remove
MVP

# Context & Domain Adaptation
Custom glossaries, RAG domain terms, and pronunciation control keep names & acronyms correct.

Glossaries
RAG Terms
Pronunciation
MVP

### Key Performance Flow
End-to-end pipeline: join, transcribe, translate, speak.

01. Create & Share
Host opens an instant or scheduled room and shares a link or QR.

02. Connect & Ingest (WebRTC)
Listeners join via WebRTC; speaker audio streams to the media server.

03. Live STT
Streaming ASR returns partial and final transcripts in real time.

04. Sync to Voice & Captions
Translated text drives TTS for audio while the UI renders subtitles in parallel.

AI Speech & Quality Stack
- Streaming STT (partial + final transcripts)
- NMT for live translation to multiple languages
- Azure Neural TTS for natural translated audio; captions in parallel
- Client-side language switching; roles & moderation for conferences

Delivery & Automation
- Instant & Scheduled calls (calendar integration)
- QR/link join and map search; add/remove participants on the fly
- Optional S3 storage for transcripts/recordings with configurable retention
- Admin console (Refine + React Query) to manage sessions, users, roles

Throughput & Scale
- 1:1 + groups up to 50 participants
- Conference Mode: multi-speaker → thousands of listeners
- Sub-second perceived latency with WebRTC + streaming STT/NMT/TTS
- Horizontal scaling of RTC/STT/TTS nodes on AWS EC2

### Tech Stack
# Frontend
React, Redux Toolkit, And Design, Vercel, WebSocket
# Speech  & Language
Straming STT, NMT, Azure Neural TTS
# Mobile
React Native, WebRTC, Redux Toolkit
# Admin & Ops
Refine, React Query, NestJS + Sockets Monitoring
# Backend & Orchestration
Nest.js (TS), MySQL, AWS EC2, Cloudflare, AWS S3
# Media/RTC
WebRTC, WebSocket, AWS EC2, Horizontal Scaling
