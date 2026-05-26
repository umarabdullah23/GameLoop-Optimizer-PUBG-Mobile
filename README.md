<div align="center">

# GameLoop Optimizer

### Stop the Stutter. Start Winning.

**130 background Windows processes are killing your FPS. We cut them to ~55.**

[![Latest Release](https://img.shields.io/github/v/release/umarabdullah23/gameloop-optimizer-releases?style=for-the-badge&color=3DD9FF&label=Latest)](https://github.com/umarabdullah23/gameloop-optimizer-releases/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/umarabdullah23/gameloop-optimizer-releases/total?style=for-the-badge&color=ff6b35&label=Downloads)](https://github.com/umarabdullah23/gameloop-optimizer-releases/releases)
[![Website](https://img.shields.io/badge/Website-gameloopoptimizer.com-3DD9FF?style=for-the-badge)](https://gameloopoptimizer.com)
[![Discord](https://img.shields.io/badge/Discord-Jeral_Gaming-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.gg/TxXFafMmy)
[![YouTube](https://img.shields.io/badge/YouTube-@JeralGaming-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/@JeralGaming)

</div>

---

## 🎯 What it does

Free Windows desktop tool for **PUBG Mobile players on GameLoop emulator**. Built to fix stutter, lag spikes, and bad 1% lows on Windows 10 / 11.

| Metric                          | Result                              |
| ------------------------------- | ----------------------------------- |
| Background Windows processes    | **130+ → ~55** (Nuclear Blast tier) |
| PUBG Mobile ping                | **−20ms** average                   |
| 1% lows (frame stability)       | **+23%** improvement                |
| DPC latency (system smoothness) | **7x reduction** on RTX 40-series   |
| Background resource consumers   | **−75%**                            |

---

## ⬇️ Download

### **[Download GameLoopOptimizerClient.exe](https://github.com/umarabdullah23/gameloop-optimizer-releases/releases/latest/download/GameLoopOptimizerClient.exe)** (68.7 MB)

- Windows 10 (build 19045+) or Windows 11 64-bit
- 4 GB RAM minimum, 8 GB recommended
- Administrator privileges required
- **No installer. No telemetry. No .NET or Python runtime.** Just run the .exe.

> SmartScreen warning? Click **More info → Run anyway**. The binary is signed and the code is open here on GitHub Releases.

---

## ✨ Features

### 🔧 Process Reduction Engine — 7 safety tiers

| Tier | Name           | Process delta            | Risk      |
| :--: | -------------- | ------------------------ | --------- |
|  0   | Everyday       | No change                | Zero      |
|  1   | Gamer          | −15 to −20               | Very Low  |
|  2   | Competitive    | −25 to −35               | Low       |
|  3   | Optimizer      | −40 to −55               | Medium    |
|  4   | Beast          | −70+                     | High      |
|  5   | Tactical Nuke  | → 70–80 processes total  | Very High |
|  6   | Nuclear Blast  | → 50–60 processes total  | Extreme   |

Every change is backed up first. One-click restore. WiFi-safe, audio-safe, anti-cheat-safe by default.

### 🌐 Network Optimizer
DNS swap (Cloudflare / Google / Quad9) · interrupt-moderation disable · DSCP=46 EF QoS marking · Nagle disable.

### 🎮 GameLoop Settings
Direct Tencent registry tweaks: VM RAM, CPU count, FXAA, Vulkan, hardware decoding, renderer engine.

### 🧹 Cleanup Engine
Shader caches · GameLoop logs · AppMarket web cache · Windows temp · MobileGamePCShared artifacts.

### 💾 Save File Editor
Direct `.sav` editing for PUBG Mobile · 6 graphics presets (60 fps balanced → 120 fps HDR ultra).

### ↩️ One-Click Restore
Every change snapshots state before execution. Settings page restores everything in one click.

### 🚀 Hardware-aware (Pro tier)

- **NVIDIA (50+ tweaks):** TDR Delay, RM Watchdog, GSP Firmware (7x DPC reduction on Ada+), MSI Interrupt Mode (10–20x DPC reduction), ReBAR detection, DRS GameLoop Profile Import
- **AMD (35+ tweaks):** Gaming Power Profile, TSC Sync Policy (multi-CCD fix), Heterogeneous Scheduling, ULPS disable, CCD0 pinning (80ns inter-CCD fix), Hyper-V detect
- **Intel (35+ tweaks):** Speed Shift EPP=0 (6th gen+), Hybrid Thread Scheduling (12th–15th gen), E-Core Performance Floor, C-State Limit (3rd–9th gen desktop), Connected Standby disable

---

## 🛡️ Safety

- ✅ **Protects WiFi** — WlanSvc, camsvc, Wcmsvc never disabled
- ✅ **Protects audio** — Audiosrv, AudioEndpointBuilder never disabled
- ✅ **Protects login** — TokenBroker, NgcSvc never disabled
- ✅ **Protects Defender / firewall** — mpssvc, WinDefend, wscsvc protected (configurable)
- ✅ **Protects gaming peripherals** — Razer Synapse, Corsair iCUE, Logitech G Hub, ASUS Armoury Crate, JBL Quantum preserved
- ✅ **No anti-cheat interference** — anti-cheat processes excluded from kill lists
- ✅ **No game memory editing** — never reads, modifies, or injects into PUBG Mobile or GameLoop
- ✅ **TEMP-only by default** — most changes reverted on reboot
- ✅ **Backup-first** — every action snapshots state before execution

---

## 💰 Pricing

| Plan          | Price            | Highlights                                                                  |
| ------------- | ---------------- | --------------------------------------------------------------------------- |
| Free          | $0 / forever     | Tiers 0–2 · basic DNS · 3 cleanups/day · backup & restore                   |
| Trial         | $0 / 7 days      | Full Pro for 7 days · all 7 tiers · save editor · GameLoop settings         |
| Pro Monthly   | $4.99 / month    | All Pro features · Nuclear Blast · unlimited cleanups · hardware-aware     |
| Pro 3-Month   | $11.99 / quarter | Pro Monthly + save 20% · priority support · cloud sync                      |

14-day money-back guarantee on Pro.

---

## 📖 How to use

1. Download `GameLoopOptimizerClient.exe` from the [latest release](https://github.com/umarabdullah23/gameloop-optimizer-releases/releases/latest)
2. Right-click → **Run as administrator** (required for service management)
3. Pick your optimization tier (start at **Gamer** if you're new)
4. Click **Apply**
5. Launch GameLoop and play

---

## ❓ FAQ

**Will it get me banned from PUBG Mobile?**
No. The optimizer only touches Windows and GameLoop's own configuration — never the game files, network packets, or memory of PUBG Mobile itself. It is not a cheat, hack, or aimbot.

**Will it work on a low-end PC?**
Yes. Tested on Celeron N4020 budget laptops up to Ryzen 9 desktops. Low-end PCs typically see the biggest gains.

**How is this different from Discord / YouTube optimization packs?**
Discord packs are one-way `.reg` scripts with no restore. GameLoop Optimizer has a UI, 7 safety tiers, backups before every change, hardware-aware NVIDIA/AMD/Intel tweaks, and **400+ optimizations** vs the typical 10–20 in those packs.

**Does it work with games other than PUBG Mobile?**
Yes. All Windows-level optimizations benefit any GPU/CPU-bound game: Valorant, CS2, Apex, Free Fire, BGMI, etc.

**Do I need to reboot?**
Most tweaks apply immediately. A few (BCDEdit boot tweaks, scheduled task changes) need a reboot — the app shows a "Reboot recommended" notice when relevant.

---

## 🌐 Links

- **Website:** [gameloopoptimizer.com](https://gameloopoptimizer.com)
- **Discord:** [discord.gg/TxXFafMmy](https://discord.gg/TxXFafMmy)
- **YouTube:** [@JeralGaming](https://www.youtube.com/@JeralGaming)
- **Issues / bugs:** [Open an issue](https://github.com/umarabdullah23/gameloop-optimizer-releases/issues)
- **Creator:** Umar Abdullah (Jeral Gaming community)

---

## 📝 License

Proprietary. Free tier and 7-day Pro trial available without payment. Pro features require a license key.

---

<div align="center">

**[⬇ Download now](https://github.com/umarabdullah23/gameloop-optimizer-releases/releases/latest/download/GameLoopOptimizerClient.exe)** · **[Visit website](https://gameloopoptimizer.com)** · **[Join Discord](https://discord.gg/TxXFafMmy)**

</div>
