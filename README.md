<!-- ═══════════════════════════════════════════════════════════════════════════
     SABRI WALID — GitHub Profile README
     Scientific / Academic / Engineering Portfolio
     Single-file version — all graphics inline, no external assets required.

     Palette:
       #0D1117  background primary
       #161B22  background secondary
       #1C2128  technical surface
       #3FB950  scientific green
       #39FF88  terminal green
       #58A6FF  technical blue
       #79C0FF  discrete cyan
       #E6EDF3  primary text
       #8B949E  secondary text
       #30363D  borders

     GitHub compatibility notes:
       - Inline SVG is rendered inside Markdown when wrapped in a <div> or
         used as a block element. GitHub sanitizes <svg> but keeps <rect>,
         <path>, <circle>, <line>, <text>, <g>, <defs>, <linearGradient>,
         <radialGradient>, <pattern>, <marker>. No scripts, no CSS.
       - Animations (<animate>, <animateTransform>) are removed by GitHub
         sanitizer; this file uses none.
       - External images are avoided entirely so the README has zero
         dependency on a banner.svg / pipeline.svg / divider.svg file.
     ═══════════════════════════════════════════════════════════════════════════ -->

<div align="center">

<!-- ═══════════════════════════════════════════════════════════════════════
     ZONE A — HEADER BANNER (inline SVG)
     Name, specialty, subtitle, technical grid, network nodes, data flow.
     ═══════════════════════════════════════════════════════════════════════ -->

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 320" width="100%" height="320" role="img" aria-label="SABRI WALID — Networks, Cybersecurity, Cloud">
  <defs>
    <linearGradient id="hdrBg" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#0D1117"/>
      <stop offset="100%" stop-color="#161B22"/>
    </linearGradient>
    <linearGradient id="hdrAccent" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#39FF88"/>
      <stop offset="100%" stop-color="#58A6FF"/>
    </linearGradient>
    <pattern id="hdrGrid" width="40" height="40" patternUnits="userSpaceOnUse">
      <path d="M 40 0 L 0 0 0 40" fill="none" stroke="#30363D" stroke-width="0.6" opacity="0.55"/>
    </pattern>
    <pattern id="hdrGridFine" width="10" height="10" patternUnits="userSpaceOnUse">
      <path d="M 10 0 L 0 0 0 10" fill="none" stroke="#30363D" stroke-width="0.25" opacity="0.25"/>
    </pattern>
    <radialGradient id="hdrGlowG" cx="0.5" cy="0.5" r="0.5">
      <stop offset="0%" stop-color="#39FF88" stop-opacity="0.18"/>
      <stop offset="100%" stop-color="#39FF88" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="hdrGlowB" cx="0.5" cy="0.5" r="0.5">
      <stop offset="0%" stop-color="#58A6FF" stop-opacity="0.18"/>
      <stop offset="100%" stop-color="#58A6FF" stop-opacity="0"/>
    </radialGradient>
  </defs>
  <rect width="1200" height="320" fill="url(#hdrBg)"/>
  <rect width="1200" height="320" fill="url(#hdrGrid)"/>
  <rect width="1200" height="320" fill="url(#hdrGridFine)"/>
  <circle cx="150" cy="80" r="220" fill="url(#hdrGlowG)"/>
  <circle cx="1050" cy="260" r="240" fill="url(#hdrGlowB)"/>
  <g stroke="#39FF88" stroke-width="1" fill="none" opacity="0.85">
    <line x1="60" y1="60" x2="140" y2="120"/>
    <line x1="140" y1="120" x2="90" y2="200"/>
    <line x1="140" y1="120" x2="230" y2="90"/>
    <line x1="230" y1="90" x2="280" y2="180"/>
    <line x1="90" y1="200" x2="180" y2="250"/>
    <line x1="180" y1="250" x2="280" y2="180"/>
  </g>
  <g fill="#39FF88">
    <circle cx="60" cy="60" r="3.5"/>
    <circle cx="140" cy="120" r="4.5"/>
    <circle cx="90" cy="200" r="3.5"/>
    <circle cx="230" cy="90" r="4"/>
    <circle cx="280" cy="180" r="3.5"/>
    <circle cx="180" cy="250" r="3.5"/>
  </g>
  <g stroke="#58A6FF" stroke-width="1" fill="none" opacity="0.75">
    <line x1="950" y1="70" x2="1040" y2="120"/>
    <line x1="1040" y1="120" x2="1120" y2="80"/>
    <line x1="1040" y1="120" x2="1080" y2="210"/>
    <line x1="1080" y1="210" x2="990" y2="260"/>
    <line x1="990" y1="260" x2="900" y2="210"/>
    <line x1="900" y1="210" x2="950" y2="70"/>
  </g>
  <g fill="#58A6FF">
    <circle cx="950" cy="70" r="3.5"/>
    <circle cx="1040" cy="120" r="4.5"/>
    <circle cx="1120" cy="80" r="3.5"/>
    <circle cx="1080" cy="210" r="4"/>
    <circle cx="990" cy="260" r="3.5"/>
    <circle cx="900" cy="210" r="3.5"/>
  </g>
  <rect x="0" y="0" width="1200" height="2" fill="url(#hdrAccent)" opacity="0.85"/>
  <rect x="0" y="318" width="1200" height="2" fill="url(#hdrAccent)" opacity="0.85"/>
  <text x="40" y="40" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="11" fill="#8B949E" letter-spacing="3">▸ PROFILE · ESTK · UCA · MOROCCO</text>
  <text x="600" y="150" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="64" font-weight="700" fill="#E6EDF3" letter-spacing="8">SABRI WALID</text>
  <text x="600" y="196" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="18" font-weight="600" fill="#39FF88" letter-spacing="6">NETWORKS · CYBERSECURITY · CLOUD</text>
  <text x="600" y="226" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="12" fill="#58A6FF" letter-spacing="3">Technical Portfolio | Security Research | Infrastructure</text>
  <text x="40" y="296" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="10" fill="#8B949E" letter-spacing="2">BACHELOR · RÉSEAUX, CLOUD &amp; CYBERSÉCURITÉ · 2026–2027</text>
  <text x="1160" y="296" text-anchor="end" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="10" fill="#8B949E" letter-spacing="2">github.com/waalidcyber</text>
</svg>

<br/>

<sub>
  <code>Technical Portfolio</code> &nbsp;·&nbsp;
  <code>Security Research</code> &nbsp;·&nbsp;
  <code>Infrastructure</code>
</sub>

<br/><br/>

<!-- ═══════════════════════════════════════════════════════════════════════
     DIVIDER (inline SVG) — reusable, repeated between sections
     ═══════════════════════════════════════════════════════════════════════ -->

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 24" width="100%" height="24" role="presentation" aria-hidden="true">
  <defs>
    <linearGradient id="dvGrad" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#30363D" stop-opacity="0"/>
      <stop offset="20%" stop-color="#30363D" stop-opacity="1"/>
      <stop offset="50%" stop-color="#39FF88" stop-opacity="0.9"/>
      <stop offset="80%" stop-color="#30363D" stop-opacity="1"/>
      <stop offset="100%" stop-color="#30363D" stop-opacity="0"/>
    </linearGradient>
  </defs>
  <line x1="40" y1="12" x2="560" y2="12" stroke="url(#dvGrad)" stroke-width="1"/>
  <circle cx="600" cy="12" r="4" fill="#0D1117" stroke="#39FF88" stroke-width="1.4"/>
  <circle cx="600" cy="12" r="1.4" fill="#39FF88"/>
  <line x1="580" y1="12" x2="592" y2="12" stroke="#58A6FF" stroke-width="1"/>
  <line x1="608" y1="12" x2="620" y2="12" stroke="#58A6FF" stroke-width="1"/>
  <line x1="640" y1="12" x2="1160" y2="12" stroke="url(#dvGrad)" stroke-width="1"/>
</svg>

</div>

<!-- ═══════════════════════════════════════════════════════════════════════════
     ZONE B — PROFESSIONAL OVERVIEW
     ═══════════════════════════════════════════════════════════════════════════ -->

<table width="100%">
<tr>
<td width="60%" valign="top">

### <samp>› Professional Overview</samp>

Bachelor student at the **École Supérieure de Technologie d'El Kelâa des Sraghna**, Université Cadi Ayyad, Morocco.

I work at the intersection of **network security**, **cybersecurity monitoring**, **threat detection** and **Cloud Security**. My objective is to gain practical experience through a cybersecurity internship and to build reliable, well-engineered security solutions.

My background combines **network engineering**, **applied machine learning** and **secure backend development** — a combination I apply to detection, supervision and response problems.

</td>
<td width="40%" valign="top">

### <samp>› Profile Card</samp>

| Field | Value |
|:------|:------|
| **Name** | SABRI WALID |
| **Domain** | Networks · Cybersecurity · Cloud |
| **Program** | Bachelor — Networks, Cybersecurity & Cloud |
| **Institution** | ESTK · Université Cadi Ayyad |
| **Period** | 2026 – 2027 (in progress) |
| **Focus** | Network Security · SOC · Cloud Security |
| **Status** | Open to cybersecurity internship |

</td>
</tr>
</table>

<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 24" width="100%" height="24" role="presentation" aria-hidden="true">
  <defs>
    <linearGradient id="dvGrad2" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#30363D" stop-opacity="0"/>
      <stop offset="20%" stop-color="#30363D" stop-opacity="1"/>
      <stop offset="50%" stop-color="#39FF88" stop-opacity="0.9"/>
      <stop offset="80%" stop-color="#30363D" stop-opacity="1"/>
      <stop offset="100%" stop-color="#30363D" stop-opacity="0"/>
    </linearGradient>
  </defs>
  <line x1="40" y1="12" x2="560" y2="12" stroke="url(#dvGrad2)" stroke-width="1"/>
  <circle cx="600" cy="12" r="4" fill="#0D1117" stroke="#39FF88" stroke-width="1.4"/>
  <circle cx="600" cy="12" r="1.4" fill="#39FF88"/>
  <line x1="580" y1="12" x2="592" y2="12" stroke="#58A6FF" stroke-width="1"/>
  <line x1="608" y1="12" x2="620" y2="12" stroke="#58A6FF" stroke-width="1"/>
  <line x1="640" y1="12" x2="1160" y2="12" stroke="url(#dvGrad2)" stroke-width="1"/>
</svg>

</div>

<!-- ═══════════════════════════════════════════════════════════════════════════
     ZONE C — CONCEPTUAL PIPELINE (inline SVG)
     NETWORK INFRASTRUCTURE → DATA COLLECTION → THREAT DETECTION → ANALYSIS → RESPONSE
     Conceptual diagram of domains of interest — not a deployed system.
     ═══════════════════════════════════════════════════════════════════════════ -->

<div align="center">

### <samp>› Conceptual Pipeline</samp>

<sub>Domains of interest — conceptual diagram, not a deployed system.</sub>

<br/><br/>

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 220" width="100%" height="220" role="img" aria-label="Conceptual pipeline: infrastructure, collection, detection, analysis, response">
  <defs>
    <linearGradient id="plLine" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#39FF88"/>
      <stop offset="50%" stop-color="#58A6FF"/>
      <stop offset="100%" stop-color="#39FF88"/>
    </linearGradient>
    <linearGradient id="plStage" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#1C2128"/>
      <stop offset="100%" stop-color="#161B22"/>
    </linearGradient>
    <marker id="plArrow" viewBox="0 0 10 10" refX="8" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse">
      <path d="M 0 0 L 10 5 L 0 10 z" fill="#58A6FF"/>
    </marker>
  </defs>
  <rect width="1200" height="220" fill="#0D1117"/>
  <rect x="0.5" y="0.5" width="1199" height="219" fill="none" stroke="#30363D" stroke-width="1"/>
  <text x="30" y="30" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="11" fill="#8B949E" letter-spacing="3">▸ CONCEPTUAL PIPELINE · DOMAINS OF INTEREST</text>
  <line x1="100" y1="110" x2="1100" y2="110" stroke="url(#plLine)" stroke-width="2" stroke-dasharray="6 6" marker-end="url(#plArrow)"/>
  <g>
    <rect x="60" y="70" width="160" height="80" rx="6" fill="url(#plStage)" stroke="#39FF88" stroke-width="1.2"/>
    <text x="140" y="100" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="10" fill="#39FF88" letter-spacing="1">01</text>
    <text x="140" y="120" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="11" font-weight="600" fill="#E6EDF3">NETWORK</text>
    <text x="140" y="136" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="11" font-weight="600" fill="#E6EDF3">INFRASTRUCTURE</text>
  </g>
  <g>
    <rect x="280" y="70" width="160" height="80" rx="6" fill="url(#plStage)" stroke="#58A6FF" stroke-width="1.2"/>
    <text x="360" y="100" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="10" fill="#58A6FF" letter-spacing="1">02</text>
    <text x="360" y="120" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="11" font-weight="600" fill="#E6EDF3">DATA</text>
    <text x="360" y="136" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="11" font-weight="600" fill="#E6EDF3">COLLECTION</text>
  </g>
  <g>
    <rect x="500" y="70" width="160" height="80" rx="6" fill="url(#plStage)" stroke="#39FF88" stroke-width="1.2"/>
    <text x="580" y="100" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="10" fill="#39FF88" letter-spacing="1">03</text>
    <text x="580" y="120" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="11" font-weight="600" fill="#E6EDF3">THREAT</text>
    <text x="580" y="136" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="11" font-weight="600" fill="#E6EDF3">DETECTION</text>
  </g>
  <g>
    <rect x="720" y="70" width="160" height="80" rx="6" fill="url(#plStage)" stroke="#79C0FF" stroke-width="1.2"/>
    <text x="800" y="100" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="10" fill="#79C0FF" letter-spacing="1">04</text>
    <text x="800" y="120" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="11" font-weight="600" fill="#E6EDF3">ANALYSIS</text>
  </g>
  <g>
    <rect x="940" y="70" width="160" height="80" rx="6" fill="url(#plStage)" stroke="#39FF88" stroke-width="1.2"/>
    <text x="1020" y="100" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="10" fill="#39FF88" letter-spacing="1">05</text>
    <text x="1020" y="120" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="11" font-weight="600" fill="#E6EDF3">RESPONSE</text>
  </g>
  <g fill="#0D1117" stroke="#58A6FF" stroke-width="1.2">
    <circle cx="240" cy="110" r="4"/>
    <circle cx="460" cy="110" r="4"/>
    <circle cx="680" cy="110" r="4"/>
    <circle cx="900" cy="110" r="4"/>
  </g>
  <text x="30" y="200" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9" fill="#8B949E" letter-spacing="2">CONCEPTUAL DIAGRAM · NOT A DEPLOYED SYSTEM · FOR ILLUSTRATION ONLY</text>
</svg>

</div>

<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 24" width="100%" height="24" role="presentation" aria-hidden="true">
  <defs>
    <linearGradient id="dvGrad3" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#30363D" stop-opacity="0"/>
      <stop offset="20%" stop-color="#30363D" stop-opacity="1"/>
      <stop offset="50%" stop-color="#39FF88" stop-opacity="0.9"/>
      <stop offset="80%" stop-color="#30363D" stop-opacity="1"/>
      <stop offset="100%" stop-color="#30363D" stop-opacity="0"/>
    </linearGradient>
  </defs>
  <line x1="40" y1="12" x2="560" y2="12" stroke="url(#dvGrad3)" stroke-width="1"/>
  <circle cx="600" cy="12" r="4" fill="#0D1117" stroke="#39FF88" stroke-width="1.4"/>
  <circle cx="600" cy="12" r="1.4" fill="#39FF88"/>
  <line x1="580" y1="12" x2="592" y2="12" stroke="#58A6FF" stroke-width="1"/>
  <line x1="608" y1="12" x2="620" y2="12" stroke="#58A6FF" stroke-width="1"/>
  <line x1="640" y1="12" x2="1160" y2="12" stroke="url(#dvGrad3)" stroke-width="1"/>
</svg>

</div>

<!-- ═══════════════════════════════════════════════════════════════════════════
     ZONE D — TECHNICAL DOMAINS
     Six groups: Cybersecurity, Networks, Programming, ML, Backend & DB, Tools.
     Each group rendered as a small HTML table for clean alignment.
     ═══════════════════════════════════════════════════════════════════════════ -->

### <samp>› Technical Domains</samp>

<br/>

<table width="100%">
<tr>
<td width="50%" valign="top">

#### 🛡️ Cybersecurity

| Domain | Coverage |
|:-------|:---------|
| Perimeter | `WAF` · `IDS` |
| Monitoring | `Security Monitoring` · `Threat Detection` |
| Web | `Web Security` · `SQL Injection` · `XSS` |
| Authentication | `OTP` |

</td>
<td width="50%" valign="top">

#### 🌐 Networks

| Domain | Coverage |
|:-------|:---------|
| Protocols | `TCP/IP` · `DNS` · `DHCP` |
| Segmentation | `VLAN` |
| Operations | `Routing` · `Switching` |
| Security | `Network Security` · `Nmap` |

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### 💻 Programming

| Language | Usage |
|:---------|:------|
| `Python` | Tooling · ML · Backend |
| `PHP` | Web development |
| `HTML5` | Interface structure |
| `CSS3` | Interface styling |
| `SQL` | Data querying |

</td>
<td width="50%" valign="top">

#### 🤖 Machine Learning

| Component | Role |
|:----------|:-----|
| `XGBoost` | Supervised detection |
| `scikit-learn` | ML pipeline |
| `Isolation Forest` | Unsupervised anomaly detection |
| `One-Class SVM` | Boundary detection |
| `Autoencoder` | Reconstruction-based detection |
| `Local Outlier Factor` | Density-based detection |
| `pandas` · `NumPy` | Data processing |

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### ⚙️ Backend & Databases

| Component | Role |
|:----------|:-----|
| `Flask` | Application server |
| `REST API` | Service interface |
| `Flask-SocketIO` · `WebSocket` | Real-time channel |
| `MySQL` | Relational storage |

</td>
<td width="50%" valign="top">

#### 🖥️ Tools & Systems

| Tool | Role |
|:-----|:-----|
| `Git` · `GitHub` | Version control |
| `Linux` · `Windows` | Operating systems |
| `VirtualBox` | Virtual lab |
| `Zabbix` | Monitoring |

</td>
</tr>
</table>

<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 24" width="100%" height="24" role="presentation" aria-hidden="true">
  <defs>
    <linearGradient id="dvGrad4" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#30363D" stop-opacity="0"/>
      <stop offset="20%" stop-color="#30363D" stop-opacity="1"/>
      <stop offset="50%" stop-color="#39FF88" stop-opacity="0.9"/>
      <stop offset="80%" stop-color="#30363D" stop-opacity="1"/>
      <stop offset="100%" stop-color="#30363D" stop-opacity="0"/>
    </linearGradient>
  </defs>
  <line x1="40" y1="12" x2="560" y2="12" stroke="url(#dvGrad4)" stroke-width="1"/>
  <circle cx="600" cy="12" r="4" fill="#0D1117" stroke="#39FF88" stroke-width="1.4"/>
  <circle cx="600" cy="12" r="1.4" fill="#39FF88"/>
  <line x1="580" y1="12" x2="592" y2="12" stroke="#58A6FF" stroke-width="1"/>
  <line x1="608" y1="12" x2="620" y2="12" stroke="#58A6FF" stroke-width="1"/>
  <line x1="640" y1="12" x2="1160" y2="12" stroke="url(#dvGrad4)" stroke-width="1"/>
</svg>

</div>

<!-- ═══════════════════════════════════════════════════════════════════════════
     ZONE E — FEATURED PROJECTS
     Six project cards, each with: id, title, description, stack, features,
     optional screenshot slot.
     ═══════════════════════════════════════════════════════════════════════════ -->

### <samp>› Featured Projects</samp>

<br/>

<table width="100%">
<tr>
<td width="50%" valign="top">

#### `01` — Banking Anomaly Detection

> Detection of anomalous banking transactions using Python, Flask and Machine Learning.

**Stack**
`Python` · `Flask` · `Machine Learning`

**Reported metric**
F1-score (declared): `0.9632`

**Scope**
- Transaction anomaly detection
- Flask-based inference service

<sub>*Screenshot slot (optional):* `assets/projects/banking.png`</sub>

</td>
<td width="50%" valign="top">

#### `02` — NeuroSecure

> Cybersecurity project developed in the context of a technical internship at **MORITSOFT**.

**Stack**
`Flask` · `WAF` · `IDS` · `OTP` · `XGBoost`

**Features**
- SQL Injection & XSS detection
- Event logging
- Temporary IP blocking
- Behavioral detection

<sub>*Screenshot slot (optional):* `assets/projects/neurosecure.png`</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### `03` — Menara CyberShield

> Project developed during an internship at **Ménara Préfa**.

**Stack**
`Python` · `PySide6`

**Features**
- Industrial cybersecurity
- Inventory management
- Truck tracking
- Dashboards & reporting

<sub>*Screenshot slot (optional):* `assets/projects/menara.png`</sub>

</td>
<td width="50%" valign="top">

#### `04` — Multi-Module Cybersecurity Platform

> Python & Flask platform combining several cybersecurity functions.

**Stack**
`Python` · `Flask`

**Features**
- Ten modules
- AI chatbot
- AES-256 encryption
- Real-time monitoring
- IP blocking

<sub>*Screenshot slot (optional):* `assets/projects/platform.png`</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

#### `05` — CyberGuard

> Web prototype focused on cybersecurity and access management.

**Features**
- Network scanning
- Log auditing
- Secure authentication
- Anti-intrusion mechanisms

<sub>*Screenshot slot (optional):* `assets/projects/cyberguard.png`</sub>

</td>
<td width="50%" valign="top">

#### `06` — Intelligent Monitoring with Zabbix & AI

> Virtual lab using five VirtualBox machines for infrastructure monitoring and intelligent analysis.

**Stack**
`Zabbix` · `VirtualBox` · `Machine Learning` · `Flask` · `React`

**Features**
- Network monitoring
- Dashboard-based visualization

<sub>*Screenshot slot (optional):* `assets/projects/zabbix.png`</sub>

</td>
</tr>
</table>

> **Note** — Project repositories and screenshots will be linked here after their availability and contents have been verified. No repository URL or performance figure is published unless it is publicly verifiable.

<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 24" width="100%" height="24" role="presentation" aria-hidden="true">
  <defs>
    <linearGradient id="dvGrad5" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#30363D" stop-opacity="0"/>
      <stop offset="20%" stop-color="#30363D" stop-opacity="1"/>
      <stop offset="50%" stop-color="#39FF88" stop-opacity="0.9"/>
      <stop offset="80%" stop-color="#30363D" stop-opacity="1"/>
      <stop offset="100%" stop-color="#30363D" stop-opacity="0"/>
    </linearGradient>
  </defs>
  <line x1="40" y1="12" x2="560" y2="12" stroke="url(#dvGrad5)" stroke-width="1"/>
  <circle cx="600" cy="12" r="4" fill="#0D1117" stroke="#39FF88" stroke-width="1.4"/>
  <circle cx="600" cy="12" r="1.4" fill="#39FF88"/>
  <line x1="580" y1="12" x2="592" y2="12" stroke="#58A6FF" stroke-width="1"/>
  <line x1="608" y1="12" x2="620" y2="12" stroke="#58A6FF" stroke-width="1"/>
  <line x1="640" y1="12" x2="1160" y2="12" stroke="url(#dvGrad5)" stroke-width="1"/>
</svg>

</div>

<!-- ═══════════════════════════════════════════════════════════════════════════
     ZONE F — ENGINEERING EXPERIENCE
     ═══════════════════════════════════════════════════════════════════════════ -->

### <samp>› Engineering Experience</samp>

<br/>

<table width="100%">
<tr>
<td width="25%" valign="top"><b>Period</b></td>
<td width="35%" valign="top"><b>Organization</b></td>
<td width="40%" valign="top"><b>Mission</b></td>
</tr>
<tr>
<td valign="top"><code>Apr 2026 – Jun 2026</code></td>
<td valign="top"><b>MORITSOFT</b><br/><sub>Technical Intern</sub></td>
<td valign="top">Cybersecurity project involving web application protection, intrusion detection and behavioral analysis.</td>
</tr>
<tr>
<td valign="top"><code>Jun 2025 – Jul 2025</code></td>
<td valign="top"><b>Ménara Préfa</b><br/><sub>Intern</sub></td>
<td valign="top">Python and PySide6 project involving industrial cybersecurity and operational monitoring.</td>
</tr>
</table>

<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 24" width="100%" height="24" role="presentation" aria-hidden="true">
  <defs>
    <linearGradient id="dvGrad6" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#30363D" stop-opacity="0"/>
      <stop offset="20%" stop-color="#30363D" stop-opacity="1"/>
      <stop offset="50%" stop-color="#39FF88" stop-opacity="0.9"/>
      <stop offset="80%" stop-color="#30363D" stop-opacity="1"/>
      <stop offset="100%" stop-color="#30363D" stop-opacity="0"/>
    </linearGradient>
  </defs>
  <line x1="40" y1="12" x2="560" y2="12" stroke="url(#dvGrad6)" stroke-width="1"/>
  <circle cx="600" cy="12" r="4" fill="#0D1117" stroke="#39FF88" stroke-width="1.4"/>
  <circle cx="600" cy="12" r="1.4" fill="#39FF88"/>
  <line x1="580" y1="12" x2="592" y2="12" stroke="#58A6FF" stroke-width="1"/>
  <line x1="608" y1="12" x2="620" y2="12" stroke="#58A6FF" stroke-width="1"/>
  <line x1="640" y1="12" x2="1160" y2="12" stroke="url(#dvGrad6)" stroke-width="1"/>
</svg>

</div>

<!-- ═══════════════════════════════════════════════════════════════════════════
     ZONE G — ACADEMIC BACKGROUND
     ═══════════════════════════════════════════════════════════════════════════ -->

### <samp>› Academic Background</samp>

<br/>

<table width="100%">
<tr>
<td width="25%" valign="top"><b>Period</b></td>
<td width="45%" valign="top"><b>Program</b></td>
<td width="30%" valign="top"><b>Institution</b></td>
</tr>
<tr>
<td valign="top"><code>2026 – 2027</code><br/><sub>In progress</sub></td>
<td valign="top"><b>Bachelor — Networks, Cybersecurity and Cloud</b></td>
<td valign="top">École Supérieure de Technologie d'El Kelâa des Sraghna<br/>Université Cadi Ayyad</td>
</tr>
<tr>
<td valign="top"><code>2024 – 2026</code><br/><sub>Honours: Bien</sub></td>
<td valign="top"><b>DUT — Networks, Cybersecurity and Artificial Intelligence</b></td>
<td valign="top">École Supérieure de Technologie d'El Kelâa des Sraghna<br/>Université Cadi Ayyad</td>
</tr>
<tr>
<td valign="top"><code>2023</code></td>
<td valign="top"><b>Baccalaureate — Physical Sciences</b></td>
<td valign="top">—</td>
</tr>
</table>

<br/>

#### Complementary Training

| Course | Provider | Year |
|:-------|:---------|:-----|
| Introduction to Python Programming | Edraak | — |
| Introduction to Cybersecurity | Edraak | 2025 |
| Hacking and Security | MindLuster | 2025 |
| JavaScript for Beginners | Cursa / Traversy Media | 2025 |

<br/>

#### Languages

| Language | Level |
|:---------|:------|
| Arabic | Native |
| French | Professional |
| English | Professional |

<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 24" width="100%" height="24" role="presentation" aria-hidden="true">
  <defs>
    <linearGradient id="dvGrad7" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#30363D" stop-opacity="0"/>
      <stop offset="20%" stop-color="#30363D" stop-opacity="1"/>
      <stop offset="50%" stop-color="#39FF88" stop-opacity="0.9"/>
      <stop offset="80%" stop-color="#30363D" stop-opacity="1"/>
      <stop offset="100%" stop-color="#30363D" stop-opacity="0"/>
    </linearGradient>
  </defs>
  <line x1="40" y1="12" x2="560" y2="12" stroke="url(#dvGrad7)" stroke-width="1"/>
  <circle cx="600" cy="12" r="4" fill="#0D1117" stroke="#39FF88" stroke-width="1.4"/>
  <circle cx="600" cy="12" r="1.4" fill="#39FF88"/>
  <line x1="580" y1="12" x2="592" y2="12" stroke="#58A6FF" stroke-width="1"/>
  <line x1="608" y1="12" x2="620" y2="12" stroke="#58A6FF" stroke-width="1"/>
  <line x1="640" y1="12" x2="1160" y2="12" stroke="url(#dvGrad7)" stroke-width="1"/>
</svg>

</div>

<!-- ═══════════════════════════════════════════════════════════════════════════
     ZONE H — CONTACT
     ═══════════════════════════════════════════════════════════════════════════ -->

### <samp>› Contact</samp>

<br/>

<table width="100%">
<tr>
<td align="center" width="33%">

**GitHub**

[waalidcyber](https://github.com/waalidcyber)

</td>
<td align="center" width="33%">

**LinkedIn**

[Walid Sabri](https://www.linkedin.com/in/walid-sabri-b01412358/)

</td>
<td align="center" width="33%">

**Email**

[w.sabri3107@uca.ac.ma](mailto:w.sabri3107@uca.ac.ma)

</td>
</tr>
</table>

<div align="center">

<br/>

*Interested in cybersecurity, network defense, security monitoring and Cloud Security.*

<br/>

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 24" width="100%" height="24" role="presentation" aria-hidden="true">
  <defs>
    <linearGradient id="dvGrad8" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#30363D" stop-opacity="0"/>
      <stop offset="20%" stop-color="#30363D" stop-opacity="1"/>
      <stop offset="50%" stop-color="#39FF88" stop-opacity="0.9"/>
      <stop offset="80%" stop-color="#30363D" stop-opacity="1"/>
      <stop offset="100%" stop-color="#30363D" stop-opacity="0"/>
    </linearGradient>
  </defs>
  <line x1="40" y1="12" x2="560" y2="12" stroke="url(#dvGrad8)" stroke-width="1"/>
  <circle cx="600" cy="12" r="4" fill="#0D1117" stroke="#39FF88" stroke-width="1.4"/>
  <circle cx="600" cy="12" r="1.4" fill="#39FF88"/>
  <line x1="580" y1="12" x2="592" y2="12" stroke="#58A6FF" stroke-width="1"/>
  <line x1="608" y1="12" x2="620" y2="12" stroke="#58A6FF" stroke-width="1"/>
  <line x1="640" y1="12" x2="1160" y2="12" stroke="url(#dvGrad8)" stroke-width="1"/>
</svg>

</div>

<!-- ═══════════════════════════════════════════════════════════════════════════
     FOOTER NOTE
     ═══════════════════════════════════════════════════════════════════════════ -->

<div align="center">

<sub>
  <code>SABRI WALID</code> &nbsp;·&nbsp;
  <code>ESTK · Université Cadi Ayyad</code> &nbsp;·&nbsp;
  <code>2026 – 2027</code>
</sub>

<br/><br/>

<sub>
  Designed as a single-file GitHub Profile README.
  All graphics are inline SVG — no external asset dependency.
</sub>

</div>
