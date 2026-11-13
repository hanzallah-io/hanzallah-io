<div align="center">

# Muhammad Hanzallah

**Blue Team · SOC Analyst**

Detect • Investigate • Respond • Report
BS Data Science @ UET Lahore · Lahore, Pakistan 🇵🇰

[![LinkedIn](https://img.shields.io/badge/LinkedIn-hanzallah--io-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/hanzallah-io)
[![SOC Lab](https://img.shields.io/badge/Flagship-soc--blue--team--lab-2ea44f?style=for-the-badge&logo=github)](https://github.com/hanzallah-io/soc-blue-team-lab)

</div>

---

## 🛡️ About

I build and operate defensive security labs, with a focus on the full SOC pipeline: telemetry → detection → investigation → threat intel → incident response → forensics. My data science background shapes how I work: validate that the data actually reaches the detection layer before trusting a rule.

```text
hanzallah-io@github ~ $ whoami
> Blue team. Evidence first. Document everything.
```

## 🔬 Flagship: [soc-blue-team-lab](https://github.com/hanzallah-io/soc-blue-team-lab)

A segmented multi-VM SOC lab built over a 90-day Cyberster internship: Kali → pfSense → Windows 11 endpoint → Wazuh SIEM on Ubuntu.

| Module | Coverage |
| ------ | -------- |
| Detection Engineering | Custom Wazuh and Suricata rules, FIM, SSH brute-force detection, Active Response |
| Network Segmentation | pfSense routing and firewall rules, GeoIP filtering |
| Threat Intelligence | VirusTotal and URLhaus enrichment, MITRE ATT&CK mapping |
| Incident Response | NIST SP 800-61 procedures, insider-threat investigation |
| Digital Forensics | Volatility 3, Autopsy, LECmd, browser/LNK/USB artifacts, `.E01` images |

**Selected findings**
- **Silent FIM failure:** a Wazuh rule matched `file` instead of `syscheck.path`. Found by reading the raw alert JSON.
- **VirusTotal integration:** patched the bundled Wazuh script from the deprecated API v2 to v3 (header auth), which restored enrichment.
- **pfSense boot failure:** fixed a Hyper-V / VT-x conflict in VirtualBox.

## 🧰 Tech Stack

**SIEM / IDS:** &nbsp;
![Wazuh](https://img.shields.io/badge/Wazuh-005571?logo=wazuh&logoColor=white)
![Suricata](https://img.shields.io/badge/Suricata-EF3B2D)
![pfSense](https://img.shields.io/badge/pfSense-212121?logo=pfsense&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?logo=wireshark&logoColor=white)

**Threat intel / analysis:** &nbsp;
![VirusTotal](https://img.shields.io/badge/VirusTotal-394EFF?logo=virustotal&logoColor=white)
![URLhaus](https://img.shields.io/badge/URLhaus-Abuse.ch-orange)
![ANY.RUN](https://img.shields.io/badge/ANY.RUN-00A2FF)
![CyberChef](https://img.shields.io/badge/CyberChef-blue)

**Forensics:** &nbsp;
![Volatility](https://img.shields.io/badge/Volatility_3-555)
![Autopsy](https://img.shields.io/badge/Autopsy-333)

**Frameworks:** &nbsp;
![MITRE ATT&CK](https://img.shields.io/badge/MITRE-ATT%26CK-orange)
![NIST](https://img.shields.io/badge/NIST-SP_800--61-blue)

**Platforms / scripting:** &nbsp;
![Kali](https://img.shields.io/badge/Kali-557C94?logo=kalilinux&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?logo=ubuntu&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D4?logo=windows&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)

## 🏆 Credentials

| Credential | Issuer |
| ---------- | ------ |
| SOC Analyst Internship, Batch 2 (Certificate + Letter of Experience) | Cyberster |
| Professional Diploma in Advanced Cybersecurity (incl. CEH module) | PNY Training |
| MCSA | PNY Training |
| CCNA | Cisco |

## 📬 Let's Connect

Open to **SOC Analyst internships and junior blue team roles**.

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?logo=linkedin&logoColor=white)](https://linkedin.com/in/hanzallah-io)