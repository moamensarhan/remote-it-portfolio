Case Study: Network Slowdown Caused by VPN Routing

---
Overview

Browsing became significantly slower despite stable Wi-Fi signal. Investigation found an active VPN connection routing traffic through a distant server, increasing latency and reducing page responsiveness.

Time to Resolution ~10 minutes

---

Environment

OS: Windows 10

Connection: Wi-Fi

VPN Client: ProtonVPN (free tier)

Context: Personal desktop workstation

---

Reported Symptoms

Slow browsing

Pages failing to load intermittently

Wi-Fi connected and functional

---

Initial Assessment

Wi-Fi signal consistent with normal baseline

Issue reproduced across multiple browsers

Determined to be system-wide, not application-specific

---

Investigation

Compared with mobile device on same network, which performed normally

Opened Resource Monitor to check active processes

Identified ProtonVPN as actively routing traffic

VPN connection confirmed to be using a distant server

<img width="1127" height="148" alt="vpn-bandwidth-usage" src="https://github.com/user-attachments/assets/007c7026-b352-4eb5-a08f-0cc1c39fc84b" />


---

Root Cause

VPN routing traffic through a distant server, increasing latency and causing slow browsing performance

---

Resolution

VPN was disabled after confirming it was not required at the time


---

Verification

Browsing performance returned to normal across all sites and browsers

No further connectivity issues observed

---

Advisory

Use VPN only when needed or configure a closer server to reduce latency
