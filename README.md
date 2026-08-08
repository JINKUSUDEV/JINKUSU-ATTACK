<h1 align="center">JINKUSU ATTACK</h1>

<p align="center">
  <strong>Advanced Multi-Layer Stress Testing Console</strong><br/>
  <code>v4.0.0</code> · Windows Desktop · <strong>100% Free</strong>
</p>

<p align="center">
  <a href="https://jinkusu.dev"><img src="https://img.shields.io/badge/Download-jinkusu.dev-e10600?style=for-the-badge" alt="Download"/></a>
  <a href="https://t.me/JINKUSUDEVELOP"><img src="https://img.shields.io/badge/Telegram-JINKUSUDEVELOP-0088cc?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"/></a>
</p>

<p align="center">
  Layer 7 & Layer 4 · 90+ Methods · Live Metrics · Recon Tools · Hackermode UI
</p>

---

## Table of contents

- [Overview](#overview)
- [Download free](#download-free)
- [Step-by-step — how to use](#step-by-step--how-to-use)
- [What the console can do](#what-the-console-can-do)
- [Feature list](#feature-list)
- [Platform stats](#platform-stats)
- [Screens & UI](#screens--ui)
- [Build from source](#build-from-source)
- [Project structure](#project-structure)
- [Links & community](#links--community)
- [Legal notice](#legal-notice)

---

## Overview

**JINKUSU ATTACK** is a **Windows desktop application** that delivers a full **stress testing & penetration recon console** in a single hackermode interface — black background, red accents, terminal animations, live graphs, and real-time logs.

There is **no hosting**, **no subscription**, and **no server setup**. Install on your PC, generate a **free device key**, and run the entire platform locally with **premium-level access** unlocked for every user.

The UI simulates attack sessions in the browser engine (Electron). Use it only for **authorized testing** on systems you own or have explicit permission to assess.

| | |
|---|---|
| **Version** | `4.0.0` |
| **Platform** | Windows 10 / 11 (x64) |
| **Price** | Free |
| **Login** | Device key (`JINK-XXXX-XXXX-XXXX`) per PC |
| **Methods** | 90+ (Layer 7 + Layer 4) |
| **Theme** | Hackermode — black / white / red |

---

## Download free

Get the latest installer from the official platform or Telegram channel:

| Resource | URL | Description |
|----------|-----|-------------|
| **Official website** | **[https://jinkusu.dev](https://jinkusu.dev)** | Download `JINKUSU-ATTACK-Setup-4.0.0.exe` |
| **Telegram channel** | **[https://t.me/JINKUSUDEVELOP](https://t.me/JINKUSUDEVELOP)** | Releases, updates & community |

```text
Installer file : JINKUSU-ATTACK-Setup-4.0.0.exe
Portable build : desktop/dist/win-unpacked/JINKUSU ATTACK.exe  (after building)
```

---

## Step-by-step — how to use

### Step 1 — Download & install

1. Open **[jinkusu.dev](https://jinkusu.dev)** or **[Telegram @JINKUSUDEVELOP](https://t.me/JINKUSUDEVELOP)**.
2. Download **`JINKUSU-ATTACK-Setup-4.0.0.exe`**.
3. Run the installer → choose folder → finish setup.
4. Launch **JINKUSU ATTACK** from Desktop or Start Menu.

### Step 2 — Generate your device key (first time only)

1. On first launch you see the **login screen** (hackermode UI).
2. Click **⚡ Generate My Device Key**.
3. Your unique key appears: `JINK-XXXX-XXXX-XXXX`.
4. **Copy and save it** — you will use it on every login on this PC.
5. Click **Continue to Login**.

> The key is stored securely on your machine (`%APPDATA%\jinkusu-attack\`). It is bound to this device — free, no email, no payment.

### Step 3 — Log in

1. Enter your **device key** (pre-filled after first setup).
2. Click **▶ Access Platform**.
3. The main **attack console** opens with full access.

### Step 4 — Configure your target

1. Enter **target URL or IP** in the scope field.
2. Set **port** (default `80` / `443`).
3. Choose **duration** (seconds) and **thread count**.
4. Optional: add **custom HTTP headers**, select **proxy list**, pick a **preset profile**.

### Step 5 — Select an attack method

1. Browse the **method library** (tabs: Layer 7, Layer 4, Bypass, Amplification, Game, etc.).
2. Click any method to see **info modal** — layer, group, latency range, burst factor, description.
3. Click **▶ START** to begin the simulated session.

### Step 6 — Monitor live

While a session runs you get:

- **Packets/sec** and **bandwidth estimate**
- **Error rate** and **progress bar**
- **Canvas traffic graph** (rolling 60-point window)
- **Real-time log stream** in the terminal panel
- **Status pill** — ARMED / RUNNING / COMPLETE

### Step 7 — Stop, review & export

1. Click **■ STOP** to end the session.
2. View the **Attack Summary** modal — target, method, totals, duration.
3. **Export report** as text or open **session history** (last 20 runs, one-click re-run).

### Step 8 — Recon tools (optional)

From the same console:

| Tool | What it does |
|------|----------------|
| **Real IP Finder** | DoH lookup, CF detection, geolocation, crt.sh, PTR |
| **Port Scanner** | HTTP probe — Web / DB / Game / SSH presets |
| **Proxy Manager** | Load, validate & rotate HTTP/SOCKS proxies |

---

## What the console can do

```
┌─────────────────────────────────────────────────────────────┐
│  JINKUSU ATTACK v4.0.0                                      │
├─────────────────────────────────────────────────────────────┤
│  TARGET  →  METHOD  →  CONFIGURE  →  START  →  MONITOR     │
│     │         │           │            │          │         │
│   URL/IP   L7 / L4    threads/      session    logs +     │
│   + port   90+ opts   duration/     simulation   graph     │
│                       proxies                               │
└─────────────────────────────────────────────────────────────┘
```

- **Plan & launch** multi-layer test sessions from one dashboard  
- **Bypass vectors** — Cloudflare, Imperva, Sucuri, CDN shields (UI simulation)  
- **Slow attacks** — Slowloris, RUDY, slow download  
- **Amplification** — DNS, NTP, MEM, CLDAP, STUN, TFTP (simulated metrics)  
- **Game floods** — Minecraft, FiveM, Rust, TeamSpeak, Valve  
- **Multi-attack** — run several methods in parallel on one target  
- **Guide built-in** — step-by-step tabs: L7, L4, Bypass, Amplify, Proxy, Recon  

---

## Feature list

### Windows desktop platform

- Native **Electron** app — offline after install  
- **100% free** — no checkout, no API server, no VPS  
- **Device-key authentication** — one key per PC  
- **Premium access** locally for all users  
- **NSIS installer** — professional setup wizard  
- **Custom frameless titlebar** — matches hackermode design  
- **App icon** — same logo as website favicon  
- Official links in titlebar: Web · Telegram  

### Layer 7 (application layer)

| Category | Examples |
|----------|----------|
| HTTP Flood | GET, POST, HEAD, PPS, STRESS, BOMB, DYN, COOKIE, NULL |
| Slow attacks | Slowloris, RUDY, DOWNLOADER |
| CF / WAF bypass | CFB, CFBUAM, IMPERVA, SUCURI, BYPASS, CC |
| Shield bypass | GSB, DGB, AVB |
| Modern protocols | HTTP/2, HTTP/2 Rapid Reset, WebSocket, GraphQL, QUIC |
| DNS / cache | DNS Water Torture, Cache Poison, PURGE |
| Bot / exploit | BOT (Googlebot), XMLRPC, APACHE, SESSION |

### Layer 4 (network layer)

| Category | Examples |
|----------|----------|
| TCP/UDP flood | SYN, TCP, UDP, OVH-UDP, CPS, CONNECTION |
| TCP flags | FIN, RST, XMAS |
| Amplification | MEM, NTP, DNS, CHAR, CLDAP, ARD, RDP, CoAP, STUN, TFTP, DTLS |
| Game protocols | Minecraft, FiveM, TeamSpeak 3, Rust, ArmA, Valve |

### Analytics & tools

- Live **packets/sec** + **bandwidth** chart  
- **Session history** (20 last runs, stored locally)  
- **Export report** after each session  
- **Attack guide** modal with 8 tabs  
- **Method info** popup per vector  
- **Custom HTTP headers** with quick presets  
- **Multi-attack orchestrator** — parallel methods, combined stats  
- **Proxy manager** — HTTP/HTTPS/SOCKS4/SOCKS5 rotation  

### UI / UX

- Hackermode theme (`#050505` bg, `#e10600` red, `#00e57a` green)  
- Glitch animations, scanlines, logo glow, pulsing buttons  
- Terminal-style log with color-coded lines  
- Responsive panels — target, methods, metrics, logs  
- Landing page with animated hero terminal demo  

---

## Platform stats

| Stat | Value |
|------|-------|
| Attack methods | **90+** |
| Layer 7 methods | **45** |
| Layer 4 methods | **39** |
| Preset profiles | **12** |
| Recon tools | **6** |
| Peak simulation | **100K+ pkt/s** |

---

## Screens & UI

> Add screenshots to `/docs/screenshots/` and embed here after release.

| Screen | Description |
|--------|-------------|
| Login | Device key generation + hackermode login box |
| Console | Main attack dashboard with methods & live graph |
| Landing | Product overview with animated terminal |
| Summary | Post-attack report modal with export |

---

## Build from source

**Requirements:** Node.js 18+, Windows 10/11

```powershell
# From project folder (after you have the source)
powershell -ExecutionPolicy Bypass -File .\build-installer.ps1
```

Output:

```text
desktop\dist\JINKUSU-ATTACK-Setup-4.0.0.exe
```

**Dev mode** (no installer):

```powershell
cd desktop
npm install
npm start
```

More details: [README-WINDOWS.md](./README-WINDOWS.md)

---



---

## Links & community

| | Link |
|---|------|
| **Website** | [https://jinkusu.dev](https://jinkusu.dev) |
| **Telegram** | [https://t.me/JINKUSUDEVELOP](https://t.me/JINKUSUDEVELOP) |

Join **Telegram** for new releases, support, and announcements.  
Download the latest build free from **jinkusu.dev**.

---

## Legal notice

> **Authorized testing only.**

JINKUSU ATTACK is provided **free of charge** for legitimate security research and performance testing. You must have **explicit written permission** before testing any target you do not own.

The developers are **not responsible** for misuse, illegal activity, or damage caused by users. By downloading and using this software you agree to comply with all applicable laws in your jurisdiction.

---

<p align="center">
  <strong>JINKUSU ATTACK v4.0.0</strong><br/>
  Created by <strong>JINKUSU</strong><br/>
  <a href="https://jinkusu.dev">jinkusu.dev</a> · <a href="https://t.me/JINKUSUDEVELOP">@JINKUSUDEVELOP</a>
</p>
