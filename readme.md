# 🕵️‍♂️ MLRID - Multi-Layer Real IP De-Anonymizer

**MLRID** (Multi-Layer Real IP De-Anonymizer) is an advanced OSINT + Web Reconnaissance tool designed to uncover the **real IP addresses** and digital fingerprints of users behind **VPNs, Proxies, TOR, or Anonymizers**.

It performs **multi-layer deanonymization** using techniques like **WebRTC leaks, DNS leaks, device fingerprinting, behavioral profiling, and timing attacks** — making it ideal for adversary emulation, Red Teaming, and fraud detection operations.

---

## 🚀 Features

- 🔍 **WebRTC Leak Detection**
- 🌐 **Public & Internal IP Exposure**
- 🧠 **Device & Browser Fingerprinting**
- 🌎 **DNS Leak Monitoring**
- 🎯 **Behavioral Tracking (Mouse/Touch/Scroll Profiling)**
- ⏱️ **Timing & Clock Skew Analysis**
- 🛡️ **VPN/Proxy/TOR Detection & Flagging**
- 📡 **GeoIP & ASN Recon**
- 📁 **Log Storage for Investigation & Correlation**

---

## 📸 Demo Screenshot

![MLRID Screenshot](screenshot.png)

---

## 🛠️ How It Works

MLRID combines multiple real-time and passive reconnaissance layers:

1. **JavaScript Payload Injection** on victim’s browser (via phishing, C2, etc.)
2. **WebRTC + STUN + ICE Gathering** to reveal internal and public IPs
3. **JavaScript-based Fingerprinting** (canvas, audio, font, timezone)
4. **DNS Leak Detection** by forcing DNS resolution to controlled endpoints
5. **Behavioral Pattern Collection** to correlate unique activity

---

## 📦 Installation

```bash
git clone https://github.com/yourusername/MLRID-Tool.git
cd MLRID-Tool
python3 -m myenv venv
source myenv/bin/activate
python3 mlrid.py
