<h1 align="center">🔐 PicoSecure Threat Simulation - TryHackMe</h1>

<h2>🧠 Summary:</h2>

This project is based on the **TryHackMe PicoSecure Threat Simulation** — a realistic, hands-on purple-team engagement. The scenario simulated an internal corporate SOC environment, where I worked as a Blue Team analyst to detect and stop a simulated adversary executing multiple malware samples.

The goal was to progressively detect threats following the **Pyramid of Pain** model — from basic indicators like hashes to advanced detection of attacker behavior and tools.

---

<h2>👨‍💻 What I Did:</h2>

- 🛡️ Detected 5 malware samples (sample1.exe to sample5.exe) through log analysis, Windows Defender config, and IOC mapping.
- 🔍 Mapped threats to the **MITRE ATT&CK** framework and **Pyramid of Pain** indicators.
- 🧪 Analyzed attacker behavior and executed defensive techniques.
- 🧠 Detected and blocked a simulated APT (Sphinx) as the final challenge.
- ✅ Captured all 6 flags successfully.

---

<h2>🧰 Tools & Concepts Used:</h2>

- Windows Defender & Windows Event Logs
- File Hash & Signature-Based Detection
- MITRE ATT&CK TTPs
- Network Behavior Monitoring
- PowerShell Analysis
- Purple Teaming & Detection Engineering
- Threat Simulation Techniques

---

<h2>🏁 Flags Captured:</h2>

| Sample       | Indicator Type     | Detection Focus         | Status          |
|--------------|--------------------|--------------------------|-----------------|
| `sample1.exe`| File Hash          | Static hash detection    | ✅ Flag 1 Found |
| `sample2.exe`| Domain/IP Address  | DNS/Network IOC          | ✅ Flag 2 Found |
| `sample3.exe`| Network Behavior   | Suspicious activity logs | ✅ Flag 3 Found |
| `sample4.exe`| Tools              | Known malicious tool     | ✅ Flag 4 Found |
| `sample5.exe`| Tactics/Techniques | Command & control pattern| ✅ Flag 5 Found |
| `Sphinx`     | APT Simulation     | Advanced TTP Detection   | ✅ Final Flag   |

---

<h2>📸 Screenshots:</h2>

> Uploads `/screenshots`
![Flag 1](https://github.com/Jaysolex/PicoSecure-Threat-Simulation/blob/main/screenshots/%20flag%201.png)
