<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/omarbabba779xx/omarbabba779xx/main/assets/name-dark.svg?v=50" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/omarbabba779xx/omarbabba779xx/main/assets/name-light.svg?v=50" />
  <img src="https://raw.githubusercontent.com/omarbabba779xx/omarbabba779xx/main/assets/name-dark.svg?v=50" alt="Omar Babba — Defensive Cybersecurity & SOC Detection Engineer" width="100%" />
</picture>

</div>

<div align="center">

[![Status](https://img.shields.io/badge/STATUS-Open%20to%20SOC%20Internships-2563eb?style=flat-square&logoColor=white)](https://linkedin.com/in/omarbabba)
[![Specialization](https://img.shields.io/badge/SPECIALIZATION-SOC%20%26%20Detection%20Engineering-1e293b?style=flat-square&logoColor=white)](https://github.com/omarbabba779xx)
[![Institution](https://img.shields.io/badge/INSTITUTION-EMSI%20Tanger-0f172a?style=flat-square&logoColor=white)](https://github.com/omarbabba779xx)

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-omarbabba-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/omarbabba)
[![Email](https://img.shields.io/badge/Email-omarbabba27%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:omarbabba27@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-omarbabba779xx-24292F?style=flat-square&logo=github&logoColor=white)](https://github.com/omarbabba779xx)

</div>

<br/>

### 🎯 Executive Overview

I am a **4th-year Computer Science & Networks Engineering student at EMSI Tanger**, specializing in **defensive cybersecurity**, **SOC operations**, and **detection engineering**. My work focuses on bridging the gap between raw telemetry ingestion and actionable defensive response:

- ▹ **Detection-as-Code:** Authoring and validating production-grade SigmaHQ detection rules mapped to the MITRE ATT&CK enterprise matrix.
- ▹ **SOC Automation (SOAR):** Designing event-driven alert pipelines connecting Wazuh SIEM to n8n SOAR workflows with token-authenticated ingress and deduplication.
- ▹ **DFIR & Threat Hunting:** Performing deep-packet network forensic investigations (Wireshark, Zeek, tcpdump) and sandbox malware behavioral analysis (REMnux, YARA).
- ▹ **Industrial Security Experience:** Hands-on internship at **Amendis Tangier (Groupe Veolia)** delivering corporate cybersecurity awareness, phishing simulation tracking, and exposure to SCADA operations.

---

### 🔄 Detection & Response Workflow

<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/omarbabba779xx/omarbabba779xx/main/assets/soc-pipeline-dark.svg?v=30" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/omarbabba779xx/omarbabba779xx/main/assets/soc-pipeline-light.svg?v=30" />
  <img src="https://raw.githubusercontent.com/omarbabba779xx/omarbabba779xx/main/assets/soc-pipeline-dark.svg?v=30" alt="SOC Workflow Lifecycle" width="100%" />
</picture>

</div>

<br/>

| Stage | Focus Area | Technical Implementations |
|:---:|---|---|
| **01 · INGEST** | Multi-Source Signal Collection | Windows Event Logs (EVTX via Sysmon), Linux auditd, Zeek NSM connection logs, firewall telemetry |
| **02 · DETECT** | Rule Correlation & ATT&CK Mapping | SigmaHQ detection rules, MITRE ATT&CK technique tags, Wazuh active ruleset correlation |
| **03 · TRIAGE** | Automated Ingress & Prioritization | Token-authenticated webhook ingress, alert deduplication, severity scoring, false-positive reduction |
| **04 · INVESTIGATE** | Deep-Dive Forensics & Sandboxing | Wireshark/tcpdump packet inspection, REMnux behavioral sandboxing, process-tree forensics |
| **05 · RESPOND** | Automated SOAR Orchestration | n8n event-driven playbooks, automated notification dispatch, quarantine & containment |
| **06 · REPORT** | Threat Intel & Root-Cause Closure | Structured IOC feeds (CSV/JSON), STIX 2.1 bundles, YARA signatures, post-incident documentation |

---

### 🛡️ Featured Engineering Projects

<table>
<tr>
<td width="33%" valign="top">

#### ⚙️ [wazuh-n8n-soc-pipeline](https://github.com/omarbabba779xx/wazuh-n8n-soc-pipeline)
`Event-Driven SOC Automation`

Automated end-to-end alert pipeline connecting Wazuh SIEM to n8n SOAR workflows for rapid incident response.

- ▹ **Sub-Second Latency:** Real-time Wazuh Integrator webhook dispatch with high-throughput queueing
- ▹ **Ingress Security:** Token-authenticated API endpoint with dynamic severity routing
- ▹ **Alert Deduplication:** Silent de-duplication engine preventing alert fatigue
- ▹ **Resilient Replay:** Automatic disk-queue failover replay upon network or service interruption

<br/>

`Wazuh` `n8n` `Python` `OAuth2` `Docker` `REST API`

<br/>

[**Explore Repository ↗**](https://github.com/omarbabba779xx/wazuh-n8n-soc-pipeline)

</td>
<td width="33%" valign="top">

#### 🔬 [malware-sandbox-analysis-lab](https://github.com/omarbabba779xx/malware-sandbox-analysis-lab)
`DFIR & Behavioral Reverse Engineering`

In-depth static and dynamic behavioral triage of 5 live malware families inside isolated REMnux environments.

- ▹ **Sample Triage:** Analyzed infostealers, loaders, and trojans (Lumma Stealer, NetSupport RAT, DarkGate)
- ▹ **Evasion Dissection:** Documented process hollowing, padding bloat, anti-sandbox sleep & API hashing
- ▹ **Threat Extraction:** Extracted C2 network indicators, payload staging URLs & behavioral timelines
- ▹ **IOC Feeds:** Exported structured STIX 2.1 bundles, consolidated CSV/JSON IOCs & custom YARA rules

<br/>

`REMnux` `Wireshark` `YARA` `MITRE ATT&CK` `PEstudio`

<br/>

[**Explore Repository ↗**](https://github.com/omarbabba779xx/malware-sandbox-analysis-lab)

</td>
<td width="33%" valign="top">

#### 🌐 [network-traffic-monitoring-lab](https://github.com/omarbabba779xx/network-traffic-monitoring-lab)
`Network Forensics & Threat Hunting`

Threat hunting and packet-level forensic investigation across real malware PCAPs with detection validation.

- ▹ **Intrusion Analysis:** Investigated 5 real PCAPs uncovering C2 beacons, Cloudflare tunnel abuse & RAT check-ins
- ▹ **Multi-Tool Correlation:** Correlated network telemetry via Wireshark, tshark, tcpdump, Zeek & NetworkMiner
- ▹ **Detection-as-Code:** Authored 7 production SigmaHQ rules validated against Zircolite with 0 false positives
- ▹ **Baseline Telemetry:** Captured and analyzed 11,430+ packets of baseline traffic with full MAC anonymization

<br/>

`Wireshark` `Zeek` `SigmaHQ` `Zircolite` `tcpdump` `PCAP`

<br/>

[**Explore Repository ↗**](https://github.com/omarbabba779xx/network-traffic-monitoring-lab)

</td>
</tr>
</table>

---

### ⚡ Technical Competencies & Security Arsenal

| Domain | Core Competencies & Methodologies |
|---|---|
| **SOC & Detection Engineering** | SIEM/SOAR architectures, SigmaHQ rules, MITRE ATT&CK mapping, OCSF schema, alert triage workflows, log correlation |
| **Incident & Intrusion Management** | Preparation, triage, containment, eradication, recovery, Windows EVTX (Sysmon), Linux auditd, Zeek NSM |
| **Network Security & Forensics** | IPsec/IKE, OpenVPN, WireGuard, GRE, OSPF, SNMP, NetFlow/sFlow, Wireshark, tcpdump, Zeek, NetworkMiner |
| **Application & Endpoint Security** | OWASP Top 10, SQLi, XSS, SSRF, access control enforcement, APK reverse engineering, mobile root detection |
| **Blockchain Security & Auditing** | Ethereum, Solidity smart contracts, ERC-20/ERC-721, Slither static analysis, Semgrep, Gitleaks, reentrancy guards |

<br/>

<div align="center">

<img src="https://skillicons.dev/icons?i=python,bash,linux,docker,git,postgres,react,ts,solidity,wireshark&theme=dark" />

</div>

<br/>

**SIEM & Centralized Log Management**
`Splunk` `IBM QRadar` `Microsoft Sentinel` `Elasticsearch (ELK)` `Graylog` `Wazuh Manager`

**SOAR, Automation & Incident Case Management**
`Cortex XSOAR` `Shuffle SOAR` `TheHive` `MISP Threat Sharing` `n8n Workflows`

**IDS / NSM / Detection Engineering**
`Suricata IDS/IPS` `Zeek Network Monitor` `Snort` `SigmaHQ Detection` `YARA Signatures` `Microsoft Sysmon`

**Digital Forensics & Threat Hunting (DFIR)**
`Velociraptor` `Osquery` `Volatility Framework` `KAPE` `NetworkMiner` `Wireshark / tshark`

**EDR & Cloud Detection Platforms**
`CrowdStrike Falcon` `Microsoft Defender for Endpoint` `Google Chronicle / SecOps`

---

### 🎓 Education & Industry Experience

#### 🎓 Cycle Ingénieur — Informatique et Réseaux
**EMSI (École Marocaine des Sciences de l'Ingénieur), Tanger** · *2022 – Present*
- ▹ **Network & Infrastructure Security:** IPsec/IKE, OpenVPN, WireGuard, routing protocols (OSPF, GRE), Wireshark packet capture, Zabbix/Prometheus monitoring
- ▹ **Web & Mobile Penetration Testing:** OWASP Top 10 vulnerability assessment, SQL injection, XSS, APK decompilation and runtime analysis (InsecureBank, InsecureShop)
- ▹ **SOC Methodologies:** Event correlation, SEC555 log analysis, SigmaHQ detection development, MITRE ATT&CK framework navigation

#### 💼 Cybersecurity Awareness Intern
**Amendis Tangier (Groupe Veolia)** · *August 2025*
- ▹ Delivered corporate security training covering the CIA triad, endpoint threat vectors, phishing recognition, and operational hygiene
- ▹ Gained practical exposure to operational SCADA environments, Riot security platform, and GLPI asset tracking workflows
- ▹ Coordinated an internal phishing simulation campaign resulting in a measurable drop in employee click-through rates

---

### 📊 GitHub Activity & Metrics

<div align="center">

<img height="165em" src="https://github-readme-stats-eight-theta.vercel.app/api?username=omarbabba779xx&show_icons=true&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9&count_private=true" />
<img height="165em" src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=omarbabba779xx&layout=compact&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&langs_count=8" />

</div>

---

<div align="center">

**Languages:** French (Advanced) · English (Advanced) · Arabic (Native)

<sub>Open to SOC Analyst &amp; Detection Engineering internship opportunities (2025–2026) — connect via [LinkedIn](https://linkedin.com/in/omarbabba) or [Email](mailto:omarbabba27@gmail.com).</sub>

</div>
