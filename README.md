## Hi, I'm Hardhika Helmi

Security & Forensics Analyst in learning - building detection labs, simulating attacks, and learning how to investigate them properly.

Currently focused on **Network Forensics & Incident Response**. The approach: build a lab, break things, document what happened, repeat.

---

### Active Project

**[Security-Investigation-Lab](https://github.com/DkHelmi/Security-Investigation-Lab)** - A hands-on security lab built from scratch on VirtualBox. Structured into lab categories - each with its own investigations, documentation, and detection analysis.

#### Adversary Emulation
Full attack chain simulation - from initial access to domain compromise, monitored by Wazuh SIEM.

| # | Case | Technique | Status |
|---|------|-----------|--------|
| 001 | Brute Force RDP Attack | T1110.001 | ✅ |
| 002 | Suspicious PowerShell Execution | T1059.001 | ✅ |
| 003 | Lateral Movement via WinRM | T1021.006 | ✅ |
| 004 | Domain Recon & Password Spraying | T1087.002, T1110.003 | 🔄 |

Stack: `Wazuh 4.9` `Sysmon` `Windows Server 2022` `Active Directory` `Kali Linux`

---

### Roadmap

```
   [✅] Adversary Emulation        
   [ ] Network Forensics           
   [ ] Network Security Monitoring 
   [ ] Incident Response           
   [ ] Cloud Security              
```

Lab first, always.

---

### Currently Learning

- Log correlation & cross-host timeline reconstruction
- Network traffic analysis - Wireshark, Zeek
- Custom SIEM detection rules (Wazuh)
- Active Directory attack paths & defenses

---

*All lab work documented at [Security-Investigation-Lab](https://github.com/DkHelmi/Security-Investigation-Lab)*
