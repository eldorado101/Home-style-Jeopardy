# Home-style-Jeopardy
Mult-Player Jeopardy style game build for fun


[![Node.js](https://img.shields.io/badge/Node.js-18+-green?logo=node.js)](https://nodejs.org/)
[![Socket.IO](https://img.shields.io/badge/Socket.IO-4.x-blue?logo=socket.io)](https://socket.io/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Chromebook Ready](https://img.shields.io/badge/Chromebook-✅-red?logo=googlechrome)](https://www.google.com/chromebook/)

A real-time, multiplayer Jeopardy-style game show that runs on your local network. Host on a Chromebook connected to a TV, and let players join from their phones—no app installation required!

![Demo](https://img.shields.io/badge/Demo-See_Below-purple?style=for-the-badge)

---

##  Features

-  **Zero Installation** - Players join via QR code or URL in their mobile browser
-  **TV-Optimized Display** - Clean, high-contrast host interface for big screens
-  **Real-Time Buzzer System** - Sub-100ms latency with WebSocket technology
-  **Built-in Sound Effects** - Web Audio API buzzers, correct/wrong answers
-  **Auto-Generated QR Codes** - Instant player onboarding
-  **Live Score Tracking** - Automatic score updates across all devices
-  **Server-Authoritative** - Anti-cheat protection built-in
-  **LAN-Only** - No internet required after setup (except QR generation)
-  **Up to 6 Players** - Perfect for game nights, classrooms, or team building

---

##  Quick Start (Chromebook)

### Prerequisites
- Chromebook with **Linux (Beta)** enabled
- Node.js 18+ (will install automatically)
- Devices on the **same WiFi network**

### One-Line Setup

```bash
mkdir jeopardy && cd jeopardy && npm init -y && npm i express socket.io && curl -O https://raw.githubusercontent.com/YOUR_USERNAME/jeopardy-live/main/server.js && mkdir -p public && curl -O https://raw.githubusercontent.com/YOUR_USERNAME/jeopardy-live/main/public/host.html -o public/host.html && curl -O https://raw.githubusercontent.com/YOUR_USERNAME/jeopardy-live/main/public/player.html -o public/player.html && node server.js
