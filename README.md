## Hi, I'm Hardhika Helmi

Security & Forensics Analyst - building detection labs, simulating
attacks, and investigating them from the defender side.

Currently focused on NFIR (Network Forensics & Incident Response).
The approach: run a campaign, generate real evidence, then investigate
starting from Wazuh alerts - not from knowing what the attacker did.

### Active Project

**[Security-Investigation-Lab](https://github.com/DkHelmi/Security-Investigation-Lab)**  
Hands-on security lab built on VirtualBox. Structured around incident
cases - each case is a full investigation from alert triage to
conclusion, written as real-time investigator notes.

Stack: `Wazuh 4.9` `Sysmon` `Windows Server 2022` `Active Directory` `Kali Linux`

#### Cases

| Case | Scenario | Status |
|------|----------|--------|
| [INC-001](https://github.com/DkHelmi/Security-Investigation-Lab/tree/main/INC-001-rdp-intrusion) | Password spray → RDP → WinRM lateral movement → persistence | ✅ Completed |
| INC-002 | C2 beaconing via persistence dari INC-001 | 📋 Planned |
| INC-003 | Living off the land, domain dominance | 📋 Planned |

### Roadmap

    Adversary Emulation    [active]
    Network Forensics      [planned]
    Network Security Mon   [planned]
    Incident Response      [planned]
    Cloud Security         [planned]

### Currently Learning

- Log correlation & cross-host timeline reconstruction
- Network traffic analysis - Wireshark, Zeek
- Custom SIEM detection rules (Wazuh)
- Active Directory attack paths & defenses

### Certs

`CompTIA Security+` `CEH` `Fortinet NSE 1-3` `CCNP (in progress)`

*All lab work documented at [Security-Investigation-Lab](https://github.com/DkHelmi/Security-Investigation-Lab)*
