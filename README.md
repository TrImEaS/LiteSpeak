#🚦 Project Status: Active Development
# LiteSpeak 🚀

LiteSpeak is a lightweight, high-performance communication platform designed for gamers and power users. It focuses on minimal resource consumption and ultra-low latency, ensuring your hardware power stays where it matters: in your game.

## 🎯 The Core Concept
A streamlined alternative to heavy messaging apps. LiteSpeak is engineered to be fast, stable, and "invisible" to your CPU, providing only the essential tools for high-level coordination.

## ✨ Key Features

### 🛠 Functional Features
- **Groups:** Simplified community structure (max 2 voice/2 text channels per group).
- **Social Management:** Full friend system (Add/Block/Delete) and Private Messaging (DMs).
- **Custom Soundboard:** 8 default sounds + support for up to 20 custom uploads per group.
- **Advanced Screen Share:** High-quality streaming with selectable resolutions (480p, 720p, 1080p).
- **Remote Mic:** Unique integration allowing your **smartphone** (LiteSpeak Mobile) to act as a wireless microphone for your Desktop client.
- **XP Mode:** A dedicated performance toggle that removes all animations and effects, reverting to a "Windows XP-style" UI to maximize CPU availability.

### 💻 Technical Stack
- **Frontend:** React.js + Vite (for ultra-fast bundling and HMR).
- **Desktop Wrapper:** **Tauri (Rust)** – Chosen for its security and minimal resource footprint compared to Electron.
- **Mobile:** React Native (Expo) for efficient mobile-to-desktop audio bridging.
- **Backend:** NestJS (Scalable & Modular architecture).
- **Real-Time:** Socket.io (Chat) & WebRTC (P2P Voice/Video).
- **Databases:**
  - **MongoDB:** For flexible cloud storage (messages and group configs).
  - **SQLite:** For fast, lightweight local persistence of client settings.
- **Language:** TypeScript (Strictly typed for reliable data and WebRTC handling).

### 🚀 Infrastructure & Performance
- **Self-Hosted Ready:** Optimized for 2 vCPU / 4 GB RAM VPS environments.
- **P2P Architecture:** Media streaming is Peer-to-Peer to minimize server bandwidth and latency.
- **Real-Time Monitoring:** Integrated latency and bitrate tracking using WebRTC `getStats()` API (Ping/Packet Loss).

## 🌍 Open Source & Status
LiteSpeak is an **Open Source** project (MIT License) currently in the **Architectural Phase**. 

I am actively working on:
1. Core NestJS backend and WebSocket infrastructure.
2. WebRTC P2P handshake logic.
3. The "XP Mode" minimalist UI design using Tauri.

---
*Developed by Thomas Rojas - Full Stack Developer*
