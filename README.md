<div align="center">

# Omar Babba

### Aspiring SOC Analyst — Detection Engineering & Threat Intelligence

Tangier, Morocco

</div>

<p align="center">
I build the tools I'd want to use on a SOC floor: detection rules mapped to real adversary behavior, an IDS that learns without leaking data, and a range to safely emulate the threats I study. Learning by shipping — not just reading playbooks.
</p>

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:omarbabba27@gmail.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/omarbabba779xx)

</div>

---

### What I'm learning by building

| Domain | What that looks like in practice |
|---|---|
| **Detection Engineering** | Writing and testing Sigma rules against real attack techniques, not copy-pasting from a repo |
| **Threat Intelligence** | Structuring IOCs/TTPs as STIX2 so they're actually usable downstream |
| **Adversary Emulation** | Replaying APT29 / FIN7 / Lazarus TTPs to see what my own detections miss |
| **Applied ML for Security** | Training IDS models and being honest about their failure modes (drift, adversarial input, privacy) |

---

## Projects

<table>
<tr>
<td width="50%" valign="top">

### [CyberTwin-SOC](https://github.com/omarbabba779xx/CyberTwin-SOC-v2)
A SOC digital twin — a sandboxed environment to test detections before they hit production.

- 628 Sigma rules mapped to 622 MITRE ATT&CK techniques
- OCSF-normalized live log ingest
- Multi-tenant auth (OIDC + RBAC)
- 88.7% test coverage

`Python` `FastAPI` `React` `PostgreSQL` `Redis` `Docker`

</td>
<td width="50%" valign="top">

### [FedSentinel](https://github.com/omarbabba779xx/FedSentinel)
A federated learning IDS — trains across nodes without centralizing raw traffic data.

- Byzantine-robust aggregation (Krum, coordinate-median)
- Differential privacy on model updates
- SHAP/LIME so alerts are explainable, not a black box
- Validated across 50 federated clients

`PyTorch` `Federated Learning` `STIX2`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [APT-Simulator](https://github.com/omarbabba779xx/APT-Simulator)
A purple-team range — emulate real adversary playbooks, then check what your SOC actually caught.

- 22 MITRE ATT&CK TTPs across APT29 / FIN7 / Lazarus
- ATT&CK Navigator export for coverage review
- Hash-chained audit log for integrity
- SOAR hooks (TheHive / Cortex)

`Python` `FastAPI` `MITRE ATT&CK` `Sigma`

</td>
<td width="50%" valign="top">

### [Medichain-plus](https://github.com/omarbabba779xx/Medichain-plus)
A dual-blockchain platform exploring integrity and privacy guarantees outside pure security tooling.

- Hyperledger Fabric for hospital-side records
- Polygon/USDC for instant settlement
- ZK-proof enrollment for patient privacy

`Hyperledger Fabric` `Solidity` `Polygon`

</td>
</tr>
</table>

---

## Toolbox

<div align="center">

<img src="https://skillicons.dev/icons?i=python,fastapi,react,ts,postgres,redis,docker,kubernetes,pytorch,sklearn,grafana,prometheus,linux,git&theme=dark" />

</div>

<div align="center">

`Sigma` `MITRE ATT&CK` `YARA` `OCSF` `STIX2 / TAXII2` `MISP` `TheHive` `Cortex` `Semgrep` `Checkov` `Trivy`

</div>

---

## GitHub Activity

<div align="center">

<img height="165em" src="https://github-readme-stats.vercel.app/api?username=omarbabba779xx&show_icons=true&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9&count_private=true" />
<img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=omarbabba779xx&layout=compact&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&langs_count=8" />

</div>

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com?user=omarbabba779xx&hide_border=true&background=0d1117&stroke=0d1117&ring=58a6ff&fire=58a6ff&currStreakNum=c9d1d9&sideNums=c9d1d9&currStreakLabel=58a6ff&sideLabels=c9d1d9&dates=6e7681" />

</div>

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=omarbabba779xx&bg_color=0d1117&color=58a6ff&line=58a6ff&point=c9d1d9&hide_border=true&hide_title=true" />

</div>

---

<div align="center">

<sub>Open to SOC analyst / detection engineering roles and internships — reach out via LinkedIn or email above.</sub>

</div>
