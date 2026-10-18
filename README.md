# ⚡ SOC & DFIR Interactive Analyst Deskmat

An immediate, lightweight, and interactive analyst dashboard designed for secondary monitors, optimized to streamline workflows during **Live Triage, Incident Response, and Cyber Threat Hunting** activities.

The grid layout emulates the exact proportions of a **physical 90x40 cm extended deskmat**. It serves both as a virtual desktop extension during live ticket investigations and as a blueprint/prototype for a future physical print.

---

## 🎯 Project Overview & Motivation
During incident response and compromised host investigations, speed is paramount. Continuously searching for exact command syntaxes or looking up Windows Event ID correlations slows down containment efforts.

This project solves that friction by centralizing the most critical **Windows, Linux, and Network Forensics** artifacts into a single, non-intrusive dark interface. Equipped with a **One-Click Copy** feature, it allows analysts to execute commands in triage terminals instantly.

---

## 🚀 Key Features
* 📊 **Emulative Layout:** Spatial grid layout specifically designed for quick visual muscle memory retrieval.
* 📋 **One-Click Copy:** Every command and Event ID includes a dedicated button to copy the syntax directly to your clipboard, minimizing typing errors and response times.
* 🪟 **Comprehensive Windows Coverage:** Mappings for critical Event IDs (Logon types, Process Creation, Persistence), LOLBins (`certutil`, etc.), and advanced process injection detection.
* 🐧 **Linux Live Forensics:** Built-in checks for deleted in-memory executables (`/proc/*/exe`), persistence crontabs, and network sockets.
* 🌐 **Network Forensics & C2 Hunting:** Ready-to-go commands for native Windows Packet Captures and targeted Linux C2 sniffing via `tcpdump` and `ss`.
* 🔋 **Zero Dependencies:** Built entirely with pure HTML5, CSS3, and JavaScript. No servers required, no external dependencies, making it 100% safe to run in isolated, air-gapped forensic environments or analysis sandboxes.

---

## 💻 How to Use
1. Download or clone this repository to your machine.
2. Double-click the `deskmat.html` (or `index.html`) file to open it in any modern web browser.
3. Drag the window to your secondary or tertiary monitor and use it seamlessly during live operations.

---

## 🛠️ Implemented Commands (Overview)
The dashboard is structurally organized into 6 core logical sections:
1. **Windows Event IDs:** Authentication flow mappings (Logon types) and core Sysmon activity monitoring.
2. **Windows Triage & PowerShell:** File hashing, active driver querying (Rootkit hunting), and process behavior auditing.
3. **Windows Persistence & Lateral Movement:** Registry run-key inspections, Winlogon hijacking detection, and active SMB inbound sessions.
4. **Linux Live Triage:** File integrity checking via Magic Bytes, transient directory monitoring, and user execution history analysis.
5. **Linux Persistence & Rootkits:** Auditing rogue SUID/SGID files, kernel module inspection, and system binary validation.
6. **Network Forensics & C2 Hunting:** Persistent loop socket monitoring and automated traffic dumps.

---

## 📄 License & Copyright

Copyright © 2026 Pr0Trebor. All rights reserved.

This project is published for educational and portfolio demonstration purposes only. **No license is granted** for public or commercial redistribution, modification, or cloning outside of GitHub. If you wish to use or adapt this project, please contact the author for explicit permission.
---
<img width="1895" height="880" alt="image" src="https://github.com/user-attachments/assets/614d226e-2dad-4af1-afac-45a22e566a43" />

