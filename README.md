<!-- ═══════════════════════════════════════════════════════════════════════════════
     SABRI WALID — GitHub Profile README
     Scientific / Academic / Engineering Portfolio — Single-file edition

     ┌─ DESIGN SYSTEM ─────────────────────────────────────────────────────────┐
     │  #0D1117  Background primary                                            │
     │  #161B22  Background secondary                                          │
     │  #1C2128  Technical surface                                             │
     │  #3FB950  Scientific green   — positive indicators, key elements        │
     │  #39FF88  Terminal green     — flows, accent points                     │
     │  #58A6FF  Technical blue     — infrastructure, connections              │
     │  #79C0FF  Discrete cyan      — analytical information                   │
     │  #E6EDF3  Primary text                                                  │
     │  #8B949E  Secondary text                                                │
     │  #30363D  Borders, grids, separators                                    │
     └─────────────────────────────────────────────────────────────────────────┘

     ┌─ GITHUB COMPATIBILITY ──────────────────────────────────────────────────┐
     │  · All graphics are inline SVG (no external asset files required).      │
     │  · No JavaScript, no <style>, no <iframe>, no CSS assumptions.          │
     │  · No <animate> / <animateTransform> (removed by GitHub sanitizer).     │
     │  · No fake monitoring data: every diagram is conceptual.                │
     │  · Every SVG carries its own <defs> with unique IDs to avoid            │
     │    gradient collisions when many SVGs share the same page.              │
     │  · width="100%" + fixed viewBox = responsive on desktop and mobile.     │
     └─────────────────────────────────────────────────────────────────────────┘

     ┌─ FILE STRUCTURE ────────────────────────────────────────────────────────┐
     │  ZONE A · Header banner + identity strip                                │
     │  ZONE B · Professional overview + profile card                          │
     │  ZONE C · Cybersecurity pipeline (A)                                    │
     │  ZONE D · Threat-detection pipeline (B)                                 │
     │  ZONE E · Network & security architecture (C)                           │
     │  ZONE F · Machine-learning pipeline (D)                                 │
     │  ZONE G · Supervision & analysis diagram (E)                            │
     │  ZONE H · Technical domains (6 groups)                                  │
     │  ZONE I · Featured projects (6 technical sheets + project pipelines)    │
     │  ZONE J · Engineering experience                                        │
     │  ZONE K · Academic background + training + languages                    │
     │  ZONE L · Contact                                                       │
     │  ZONE M · Footer                                                        │
     └─────────────────────────────────────────────────────────────────────────┘
     ═══════════════════════════════════════════════════════════════════════════════ -->

<div align="center">

<!-- ═══════════════════════════════════════════════════════════════════════════════
     ZONE A — HEADER BANNER
     Composition: dark grid, network node clusters, data-flow accents, name,
     specialty, subtitle, technical meta strip. All drawn as inline SVG.
     ═══════════════════════════════════════════════════════════════════════════════ -->

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 340" width="100%" height="340" role="img" aria-label="SABRI WALID — Networks, Cybersecurity, Cloud">
  <defs>
    <linearGradient id="zABg" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%"   stop-color="#0D1117"/>
      <stop offset="60%"  stop-color="#11161D"/>
      <stop offset="100%" stop-color="#161B22"/>
    </linearGradient>
    <linearGradient id="zAAccent" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%"   stop-color="#39FF88"/>
      <stop offset="50%"  stop-color="#58A6FF"/>
      <stop offset="100%" stop-color="#39FF88"/>
    </linearGradient>
    <pattern id="zAGrid" width="40" height="40" patternUnits="userSpaceOnUse">
      <path d="M 40 0 L 0 0 0 40" fill="none" stroke="#30363D" stroke-width="0.6" opacity="0.55"/>
    </pattern>
    <pattern id="zAGridFine" width="10" height="10" patternUnits="userSpaceOnUse">
      <path d="M 10 0 L 0 0 0 10" fill="none" stroke="#30363D" stroke-width="0.25" opacity="0.25"/>
    </pattern>
    <radialGradient id="zAGlowG" cx="0.5" cy="0.5" r="0.5">
      <stop offset="0%"   stop-color="#39FF88" stop-opacity="0.18"/>
      <stop offset="100%" stop-color="#39FF88" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="zAGlowB" cx="0.5" cy="0.5" r="0.5">
      <stop offset="0%"   stop-color="#58A6FF" stop-opacity="0.18"/>
      <stop offset="100%" stop-color="#58A6FF" stop-opacity="0"/>
    </radialGradient>
  </defs>

  <rect width="1200" height="340" fill="url(#zABg)"/>
  <rect width="1200" height="340" fill="url(#zAGrid)"/>
  <rect width="1200" height="340" fill="url(#zAGridFine)"/>
  <circle cx="150" cy="90" r="220" fill="url(#zAGlowG)"/>
  <circle cx="1050" cy="280" r="240" fill="url(#zAGlowB)"/>

  <!-- Left network node cluster -->
  <g stroke="#39FF88" stroke-width="1" fill="none" opacity="0.85">
    <line x1="60"  y1="70"  x2="140" y2="130"/>
    <line x1="140" y1="130" x2="90"  y2="210"/>
    <line x1="140" y1="130" x2="230" y2="100"/>
    <line x1="230" y1="100" x2="280" y2="190"/>
    <line x1="90"  y1="210" x2="180" y2="260"/>
    <line x1="180" y1="260" x2="280" y2="190"/>
    <line x1="230" y1="100" x2="330" y2="150"/>
  </g>
  <g fill="#39FF88">
    <circle cx="60"  cy="70"  r="3.5"/>
    <circle cx="140" cy="130" r="4.5"/>
    <circle cx="90"  cy="210" r="3.5"/>
    <circle cx="230" cy="100" r="4"/>
    <circle cx="280" cy="190" r="3.5"/>
    <circle cx="180" cy="260" r="3.5"/>
    <circle cx="330" cy="150" r="3"/>
  </g>

  <!-- Right data-flow accents -->
  <g stroke="#58A6FF" stroke-width="1" fill="none" opacity="0.75">
    <line x1="950"  y1="80"  x2="1040" y2="130"/>
    <line x1="1040" y1="130" x2="1120" y2="90"/>
    <line x1="1040" y1="130" x2="1080" y2="220"/>
    <line x1="1080" y1="220" x2="990"  y2="270"/>
    <line x1="990"  y1="270" x2="900"  y2="220"/>
    <line x1="900"  y1="220" x2="950"  y2="80"/>
    <line x1="950"  y1="80"  x2="870"  y2="150"/>
  </g>
  <g fill="#58A6FF">
    <circle cx="950"  cy="80"  r="3.5"/>
    <circle cx="1040" cy="130" r="4.5"/>
    <circle cx="1120" cy="90"  r="3.5"/>
    <circle cx="1080" cy="220" r="4"/>
    <circle cx="990"  cy="270" r="3.5"/>
    <circle cx="900"  cy="220" r="3.5"/>
    <circle cx="870"  cy="150" r="3"/>
  </g>

  <!-- Top / bottom accent lines -->
  <rect x="0" y="0"   width="1200" height="2" fill="url(#zAAccent)" opacity="0.9"/>
  <rect x="0" y="338" width="1200" height="2" fill="url(#zAAccent)" opacity="0.9"/>

  <!-- Top-left label -->
  <text x="40" y="42" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="11" fill="#8B949E" letter-spacing="3">▸ PROFILE · ESTK · UCA · MOROCCO</text>

  <!-- Name -->
  <text x="600" y="160" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="64" font-weight="700" fill="#E6EDF3" letter-spacing="8">SABRI WALID</text>

  <!-- Specialty -->
  <text x="600" y="206" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="18" font-weight="600" fill="#39FF88" letter-spacing="6">NETWORKS · CYBERSECURITY · CLOUD</text>

  <!-- Subtitle -->
  <text x="600" y="234" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="12" fill="#58A6FF" letter-spacing="3">Technical Portfolio | Security Research | Infrastructure</text>

  <!-- Meta strip -->
  <text x="40" y="316" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="10" fill="#8B949E" letter-spacing="2">BACHELOR · RÉSEAUX, CLOUD &amp; CYBERSÉCURITÉ · 2026–2027</text>
  <text x="1160" y="316" text-anchor="end" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="10" fill="#8B949E" letter-spacing="2">github.com/waalidcyber</text>
</svg>

<br/>

<sub>
  <code>Technical Portfolio</code> &nbsp;·&nbsp;
  <code>Security Research</code> &nbsp;·&nbsp;
  <code>Infrastructure</code>
</sub>

<br/><br/>

<!-- ═══════════════════════════════════════════════════════════════════════════════
     DIVIDER #1
     ═══════════════════════════════════════════════════════════════════════════════ -->

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 24" width="100%" height="24" role="presentation" aria-hidden="true">
  <defs>
    <linearGradient id="dv1" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%"   stop-color="#30363D" stop-opacity="0"/>
      <stop offset="20%"  stop-color="#30363D" stop-opacity="1"/>
      <stop offset="50%"  stop-color="#39FF88" stop-opacity="0.9"/>
      <stop offset="80%"  stop-color="#30363D" stop-opacity="1"/>
      <stop offset="100%" stop-color="#30363D" stop-opacity="0"/>
    </linearGradient>
  </defs>
  <line x1="40" y1="12" x2="560" y2="12" stroke="url(#dv1)" stroke-width="1"/>
  <circle cx="600" cy="12" r="4" fill="#0D1117" stroke="#39FF88" stroke-width="1.4"/>
  <circle cx="600" cy="12" r="1.4" fill="#39FF88"/>
  <line x1="580" y1="12" x2="592" y2="12" stroke="#58A6FF" stroke-width="1"/>
  <line x1="608" y1="12" x2="620" y2="12" stroke="#58A6FF" stroke-width="1"/>
  <line x1="640" y1="12" x2="1160" y2="12" stroke="url(#dv1)" stroke-width="1"/>
</svg>

</div>

<!-- ═══════════════════════════════════════════════════════════════════════════════
     ZONE B — PROFESSIONAL OVERVIEW + PROFILE CARD
     ═══════════════════════════════════════════════════════════════════════════════ -->

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
    <linearGradient id="dv2" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%"   stop-color="#30363D" stop-opacity="0"/>
      <stop offset="20%"  stop-color="#30363D" stop-opacity="1"/>
      <stop offset="50%"  stop-color="#39FF88" stop-opacity="0.9"/>
      <stop offset="80%"  stop-color="#30363D" stop-opacity="1"/>
      <stop offset="100%" stop-color="#30363D" stop-opacity="0"/>
    </linearGradient>
  </defs>
  <line x1="40" y1="12" x2="560" y2="12" stroke="url(#dv2)" stroke-width="1"/>
  <circle cx="600" cy="12" r="4" fill="#0D1117" stroke="#39FF88" stroke-width="1.4"/>
  <circle cx="600" cy="12" r="1.4" fill="#39FF88"/>
  <line x1="580" y1="12" x2="592" y2="12" stroke="#58A6FF" stroke-width="1"/>
  <line x1="608" y1="12" x2="620" y2="12" stroke="#58A6FF" stroke-width="1"/>
  <line x1="640" y1="12" x2="1160" y2="12" stroke="url(#dv2)" stroke-width="1"/>
</svg>

</div>

<!-- ═══════════════════════════════════════════════════════════════════════════════
     ZONE C — PIPELINE A · CYBERSECURITY PIPELINE
     NETWORK INFRASTRUCTURE → DATA COLLECTION → THREAT DETECTION → ANALYSIS → RESPONSE
     Larger, numbered stages with double-border blocks, connector arrows,
     internal accent bars and a legend row below.
     ═══════════════════════════════════════════════════════════════════════════════ -->

<div align="center">

### <samp>› Pipeline A · Cybersecurity</samp>

<sub>Conceptual representation of the security lifecycle — not a deployed system.</sub>

<br/><br/>

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 300" width="100%" height="300" role="img" aria-label="Cybersecurity pipeline: infrastructure, collection, detection, analysis, response">
  <defs>
    <linearGradient id="pABg" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%"   stop-color="#0D1117"/>
      <stop offset="100%" stop-color="#161B22"/>
    </linearGradient>
    <linearGradient id="pAFlow" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%"   stop-color="#39FF88"/>
      <stop offset="50%"  stop-color="#58A6FF"/>
      <stop offset="100%" stop-color="#39FF88"/>
    </linearGradient>
    <linearGradient id="pAStageBg" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%"   stop-color="#1C2128"/>
      <stop offset="100%" stop-color="#161B22"/>
    </linearGradient>
    <pattern id="pAGrid" width="20" height="20" patternUnits="userSpaceOnUse">
      <path d="M 20 0 L 0 0 0 20" fill="none" stroke="#30363D" stroke-width="0.4" opacity="0.35"/>
    </pattern>
    <marker id="pAArrow" viewBox="0 0 10 10" refX="8" refY="5" markerWidth="7" markerHeight="7" orient="auto-start-reverse">
      <path d="M 0 0 L 10 5 L 0 10 z" fill="#58A6FF"/>
    </marker>
  </defs>

  <rect width="1200" height="300" fill="url(#pABg)"/>
  <rect width="1200" height="300" fill="url(#pAGrid)"/>
  <rect x="0.5" y="0.5" width="1199" height="299" fill="none" stroke="#30363D" stroke-width="1"/>

  <text x="30" y="32" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="11" fill="#8B949E" letter-spacing="3">▸ PIPELINE A · CYBERSECURITY LIFECYCLE</text>

  <!-- Main connector line -->
  <line x1="150" y1="150" x2="1050" y2="150" stroke="url(#pAFlow)" stroke-width="2" stroke-dasharray="7 7" marker-end="url(#pAArrow)"/>

  <!-- Stage 1 · Network Infrastructure -->
  <g>
    <rect x="70"  y="100" width="170" height="100" rx="7" fill="url(#pAStageBg)" stroke="#58A6FF" stroke-width="1.4"/>
    <rect x="70"  y="100" width="170" height="4"   rx="2" fill="#58A6FF"/>
    <text x="155" y="128" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="10" fill="#58A6FF" letter-spacing="2">01</text>
    <text x="155" y="152" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="12" font-weight="700" fill="#E6EDF3">NETWORK</text>
    <text x="155" y="170" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="12" font-weight="700" fill="#E6EDF3">INFRASTRUCTURE</text>
    <text x="155" y="188" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9" fill="#8B949E">switching · routing · segmentation</text>
  </g>

  <!-- Stage 2 · Data Collection -->
  <g>
    <rect x="295" y="100" width="170" height="100" rx="7" fill="url(#pAStageBg)" stroke="#39FF88" stroke-width="1.4"/>
    <rect x="295" y="100" width="170" height="4"   rx="2" fill="#39FF88"/>
    <text x="380" y="128" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="10" fill="#39FF88" letter-spacing="2">02</text>
    <text x="380" y="152" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="12" font-weight="700" fill="#E6EDF3">DATA</text>
    <text x="380" y="170" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="12" font-weight="700" fill="#E6EDF3">COLLECTION</text>
    <text x="380" y="188" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9" fill="#8B949E">logs · events · telemetry</text>
  </g>

  <!-- Stage 3 · Threat Detection -->
  <g>
    <rect x="520" y="100" width="170" height="100" rx="7" fill="url(#pAStageBg)" stroke="#39FF88" stroke-width="1.4"/>
    <rect x="520" y="100" width="170" height="4"   rx="2" fill="#39FF88"/>
    <text x="605" y="128" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="10" fill="#39FF88" letter-spacing="2">03</text>
    <text x="605" y="152" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="12" font-weight="700" fill="#E6EDF3">THREAT</text>
    <text x="605" y="170" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="12" font-weight="700" fill="#E6EDF3">DETECTION</text>
    <text x="605" y="188" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9" fill="#8B949E">signatures · anomalies · rules</text>
  </g>

  <!-- Stage 4 · Analysis -->
  <g>
    <rect x="745" y="100" width="170" height="100" rx="7" fill="url(#pAStageBg)" stroke="#79C0FF" stroke-width="1.4"/>
    <rect x="745" y="100" width="170" height="4"   rx="2" fill="#79C0FF"/>
    <text x="830" y="128" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="10" fill="#79C0FF" letter-spacing="2">04</text>
    <text x="830" y="152" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="12" font-weight="700" fill="#E6EDF3">ANALYSIS</text>
    <text x="830" y="170" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9" fill="#8B949E">correlation · scoring · triage</text>
  </g>

  <!-- Stage 5 · Response -->
  <g>
    <rect x="970" y="100" width="170" height="100" rx="7" fill="url(#pAStageBg)" stroke="#39FF88" stroke-width="1.4"/>
    <rect x="970" y="100" width="170" height="4"   rx="2" fill="#39FF88"/>
    <text x="1055" y="128" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="10" fill="#39FF88" letter-spacing="2">05</text>
    <text x="1055" y="152" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="12" font-weight="700" fill="#E6EDF3">RESPONSE</text>
    <text x="1055" y="170" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9" fill="#8B949E">containment · blocking</text>
  </g>

  <!-- Connector dots -->
  <g fill="#0D1117" stroke="#58A6FF" stroke-width="1.2">
    <circle cx="255" cy="150" r="4"/>
    <circle cx="480" cy="150" r="4"/>
    <circle cx="705" cy="150" r="4"/>
    <circle cx="930" cy="150" r="4"/>
  </g>

  <!-- Legend -->
  <g font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9" fill="#8B949E">
    <rect x="70"  y="238" width="10" height="10" fill="none" stroke="#58A6FF" stroke-width="1.2"/>
    <text x="88"  y="247">infrastructure</text>
    <rect x="200" y="238" width="10" height="10" fill="none" stroke="#39FF88" stroke-width="1.2"/>
    <text x="218" y="247">security stage</text>
    <rect x="340" y="238" width="10" height="10" fill="none" stroke="#79C0FF" stroke-width="1.2"/>
    <text x="358" y="247">analysis</text>
    <line x1="460" y1="243" x2="500" y2="243" stroke="#58A6FF" stroke-width="1.5" stroke-dasharray="4 3"/>
    <text x="508" y="247">direction of flow</text>
  </g>

  <text x="30" y="285" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9" fill="#8B949E" letter-spacing="2">CONCEPTUAL DIAGRAM · NOT A DEPLOYED SYSTEM · FOR ILLUSTRATION ONLY</text>
</svg>

</div>

<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 24" width="100%" height="24" role="presentation" aria-hidden="true">
  <defs>
    <linearGradient id="dv3" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%"   stop-color="#30363D" stop-opacity="0"/>
      <stop offset="20%"  stop-color="#30363D" stop-opacity="1"/>
      <stop offset="50%"  stop-color="#39FF88" stop-opacity="0.9"/>
      <stop offset="80%"  stop-color="#30363D" stop-opacity="1"/>
      <stop offset="100%" stop-color="#30363D" stop-opacity="0"/>
    </linearGradient>
  </defs>
  <line x1="40" y1="12" x2="560" y2="12" stroke="url(#dv3)" stroke-width="1"/>
  <circle cx="600" cy="12" r="4" fill="#0D1117" stroke="#39FF88" stroke-width="1.4"/>
  <circle cx="600" cy="12" r="1.4" fill="#39FF88"/>
  <line x1="580" y1="12" x2="592" y2="12" stroke="#58A6FF" stroke-width="1"/>
  <line x1="608" y1="12" x2="620" y2="12" stroke="#58A6FF" stroke-width="1"/>
  <line x1="640" y1="12" x2="1160" y2="12" stroke="url(#dv3)" stroke-width="1"/>
</svg>

</div>

<!-- ═══════════════════════════════════════════════════════════════════════════════
     ZONE D — PIPELINE B · THREAT DETECTION
     EVENTS → COLLECTION → PREPROCESSING → DETECTION → ANALYSIS → RESPONSE
     Vertical two-row serpentine layout for compact width.
     ═══════════════════════════════════════════════════════════════════════════════ -->

<div align="center">

### <samp>› Pipeline B · Threat Detection</samp>

<sub>Conceptual event flow from raw telemetry to defensive response.</sub>

<br/><br/>

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 300" width="100%" height="300" role="img" aria-label="Threat detection pipeline: events, collection, preprocessing, detection, analysis, response">
  <defs>
    <linearGradient id="pBBg" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%"   stop-color="#0D1117"/>
      <stop offset="100%" stop-color="#161B22"/>
    </linearGradient>
    <linearGradient id="pBRow1" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%"   stop-color="#39FF88"/>
      <stop offset="100%" stop-color="#58A6FF"/>
    </linearGradient>
    <linearGradient id="pBRow2" x1="1" y1="0" x2="0" y2="0">
      <stop offset="0%"   stop-color="#79C0FF"/>
      <stop offset="100%" stop-color="#39FF88"/>
    </linearGradient>
    <marker id="pBArrow" viewBox="0 0 10 10" refX="8" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse">
      <path d="M 0 0 L 10 5 L 0 10 z" fill="#58A6FF"/>
    </marker>
  </defs>

  <rect width="1200" height="300" fill="url(#pBBg)"/>
  <rect x="0.5" y="0.5" width="1199" height="299" fill="none" stroke="#30363D" stroke-width="1"/>

  <text x="30" y="32" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="11" fill="#8B949E" letter-spacing="3">▸ PIPELINE B · THREAT DETECTION</text>

  <!-- Row 1 connector -->
  <line x1="140" y1="95" x2="1060" y2="95" stroke="url(#pBRow1)" stroke-width="2" stroke-dasharray="6 6"/>
  <line x1="1060" y1="95" x2="1100" y2="140" stroke="#58A6FF" stroke-width="2" marker-end="url(#pBArrow)"/>

  <!-- Row 1 boxes -->
  <g>
    <rect x="60"  y="55" width="160" height="80" rx="6" fill="#161B22" stroke="#39FF88" stroke-width="1.2"/>
    <text x="140" y="78"  text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9"  fill="#39FF88" letter-spacing="2">EVENT</text>
    <text x="140" y="100" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="11" font-weight="700" fill="#E6EDF3">RAW SIGNALS</text>
    <text x="140" y="120" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9"  fill="#8B949E">logs · flow · auth</text>
  </g>
  <g>
    <rect x="260" y="55" width="160" height="80" rx="6" fill="#161B22" stroke="#58A6FF" stroke-width="1.2"/>
    <text x="340" y="78"  text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9"  fill="#58A6FF" letter-spacing="2">COLLECT</text>
    <text x="340" y="100" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="11" font-weight="700" fill="#E6EDF3">INGESTION</text>
    <text x="340" y="120" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9"  fill="#8B949E">normalisation</text>
  </g>
  <g>
    <rect x="460" y="55" width="160" height="80" rx="6" fill="#161B22" stroke="#39FF88" stroke-width="1.2"/>
    <text x="540" y="78"  text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9"  fill="#39FF88" letter-spacing="2">PREPROCESS</text>
    <text x="540" y="100" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="11" font-weight="700" fill="#E6EDF3">FEATURES</text>
    <text x="540" y="120" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9"  fill="#8B949E">cleaning · encoding</text>
  </g>
  <g>
    <rect x="660" y="55" width="160" height="80" rx="6" fill="#161B22" stroke="#39FF88" stroke-width="1.2"/>
    <text x="740" y="78"  text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9"  fill="#39FF88" letter-spacing="2">DETECT</text>
    <text x="740" y="100" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="11" font-weight="700" fill="#E6EDF3">MODEL</text>
    <text x="740" y="120" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9"  fill="#8B949E">rules · ML · hybrid</text>
  </g>
  <g>
    <rect x="860" y="55" width="160" height="80" rx="6" fill="#161B22" stroke="#79C0FF" stroke-width="1.2"/>
    <text x="940" y="78"  text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9"  fill="#79C0FF" letter-spacing="2">ANALYSE</text>
    <text x="940" y="100" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="11" font-weight="700" fill="#E6EDF3">CORRELATION</text>
    <text x="940" y="120" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9"  fill="#8B949E">severity scoring</text>
  </g>

  <!-- Row 2 connector (reverse) -->
  <line x1="1060" y1="205" x2="140" y2="205" stroke="url(#pBRow2)" stroke-width="2" stroke-dasharray="6 6"/>

  <!-- Row 2 box -->
  <g>
    <rect x="460" y="165" width="280" height="80" rx="6" fill="#161B22" stroke="#39FF88" stroke-width="1.4"/>
    <rect x="460" y="165" width="280" height="4"  rx="2" fill="#39FF88"/>
    <text x="600" y="188" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9"  fill="#39FF88" letter-spacing="2">RESPONSE</text>
    <text x="600" y="212" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="12" font-weight="700" fill="#E6EDF3">CONTAINMENT · BLOCKING · LOGGING</text>
    <text x="600" y="232" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9"  fill="#8B949E">temporary IP block · notifications · evidence</text>
  </g>

  <!-- Drop connectors -->
  <line x1="940" y1="135" x2="940" y2="165" stroke="#58A6FF" stroke-width="1.5" marker-end="url(#pBArrow)"/>
  <line x1="940" y1="205" x2="740" y2="205" stroke="#58A6FF" stroke-width="2" marker-end="url(#pBArrow)"/>

  <text x="30" y="285" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9" fill="#8B949E" letter-spacing="2">CONCEPTUAL DIAGRAM · NOT A DEPLOYED SYSTEM · FOR ILLUSTRATION ONLY</text>
</svg>

</div>

<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 24" width="100%" height="24" role="presentation" aria-hidden="true">
  <defs>
    <linearGradient id="dv4" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%"   stop-color="#30363D" stop-opacity="0"/>
      <stop offset="20%"  stop-color="#30363D" stop-opacity="1"/>
      <stop offset="50%"  stop-color="#39FF88" stop-opacity="0.9"/>
      <stop offset="80%"  stop-color="#30363D" stop-opacity="1"/>
      <stop offset="100%" stop-color="#30363D" stop-opacity="0"/>
    </linearGradient>
  </defs>
  <line x1="40" y1="12" x2="560" y2="12" stroke="url(#dv4)" stroke-width="1"/>
  <circle cx="600" cy="12" r="4" fill="#0D1117" stroke="#39FF88" stroke-width="1.4"/>
  <circle cx="600" cy="12" r="1.4" fill="#39FF88"/>
  <line x1="580" y1="12" x2="592" y2="12" stroke="#58A6FF" stroke-width="1"/>
  <line x1="608" y1="12" x2="620" y2="12" stroke="#58A6FF" stroke-width="1"/>
  <line x1="640" y1="12" x2="1160" y2="12" stroke="url(#dv4)" stroke-width="1"/>
</svg>

</div>

<!-- ═══════════════════════════════════════════════════════════════════════════════
     ZONE E — ARCHITECTURE C · NETWORK & SECURITY ARCHITECTURE
     Layered schema: perimeter → endpoints → log collection → supervision →
     security controls. Drawn as a layered block diagram with connectors.
     ═══════════════════════════════════════════════════════════════════════════════ -->

<div align="center">

### <samp>› Architecture C · Network & Security</samp>

<sub>Conceptual layered view of network, logging and supervision relationships.</sub>

<br/><br/>

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 340" width="100%" height="340" role="img" aria-label="Network and security architecture: perimeter, endpoints, log collection, supervision, security controls">
  <defs>
    <linearGradient id="pCBg" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%"   stop-color="#0D1117"/>
      <stop offset="100%" stop-color="#161B22"/>
    </linearGradient>
    <linearGradient id="pCLayer" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%"   stop-color="#1C2128"/>
      <stop offset="100%" stop-color="#161B22"/>
    </linearGradient>
    <marker id="pCArrow" viewBox="0 0 10 10" refX="8" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse">
      <path d="M 0 0 L 10 5 L 0 10 z" fill="#58A6FF"/>
    </marker>
  </defs>

  <rect width="1200" height="340" fill="url(#pCBg)"/>
  <rect x="0.5" y="0.5" width="1199" height="339" fill="none" stroke="#30363D" stroke-width="1"/>

  <text x="30" y="32" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="11" fill="#8B949E" letter-spacing="3">▸ ARCHITECTURE C · NETWORK &amp; SECURITY</text>

  <!-- Layer bands -->
  <g>
    <!-- Perimeter -->
    <rect x="40" y="55" width="1120" height="52" rx="4" fill="url(#pCLayer)" stroke="#58A6FF" stroke-width="1.2"/>
    <text x="60" y="78"  font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="10" fill="#58A6FF" letter-spacing="2">L1 · PERIMETER</text>
    <text x="60" y="96"  font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="11" fill="#E6EDF3">Firewall · WAF · IDS · segmentation · VLAN</text>
    <circle cx="1120" cy="81" r="5" fill="#0D1117" stroke="#58A6FF" stroke-width="1.2"/>
  </g>

  <line x1="600" y1="107" x2="600" y2="125" stroke="#58A6FF" stroke-width="1.5" marker-end="url(#pCArrow)"/>

  <g>
    <!-- Endpoints -->
    <rect x="40" y="125" width="1120" height="52" rx="4" fill="url(#pCLayer)" stroke="#39FF88" stroke-width="1.2"/>
    <text x="60" y="148" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="10" fill="#39FF88" letter-spacing="2">L2 · ENDPOINTS</text>
    <text x="60" y="166" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="11" fill="#E6EDF3">Linux · Windows · VirtualBox guests · web applications</text>
    <circle cx="1120" cy="151" r="5" fill="#0D1117" stroke="#39FF88" stroke-width="1.2"/>
  </g>

  <line x1="600" y1="177" x2="600" y2="195" stroke="#58A6FF" stroke-width="1.5" marker-end="url(#pCArrow)"/>

  <g>
    <!-- Log collection -->
    <rect x="40" y="195" width="1120" height="52" rx="4" fill="url(#pCLayer)" stroke="#39FF88" stroke-width="1.2"/>
    <text x="60" y="218" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="10" fill="#39FF88" letter-spacing="2">L3 · LOG COLLECTION</text>
    <text x="60" y="236" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="11" fill="#E6EDF3">Authentication events · flow data · application logs · WAF alerts</text>
    <circle cx="1120" cy="221" r="5" fill="#0D1117" stroke="#39FF88" stroke-width="1.2"/>
  </g>

  <line x1="600" y1="247" x2="600" y2="265" stroke="#58A6FF" stroke-width="1.5" marker-end="url(#pCArrow)"/>

  <g>
    <!-- Supervision -->
    <rect x="40" y="265" width="1120" height="52" rx="4" fill="url(#pCLayer)" stroke="#79C0FF" stroke-width="1.2"/>
    <text x="60" y="288" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="10" fill="#79C0FF" letter-spacing="2">L4 · SUPERVISION</text>
    <text x="60" y="306" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="11" fill="#E6EDF3">Zabbix · dashboards · metrics · alerting · analysis</text>
    <circle cx="1120" cy="291" r="5" fill="#0D1117" stroke="#79C0FF" stroke-width="1.2"/>
  </g>

  <text x="30" y="332" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9" fill="#8B949E" letter-spacing="2">CONCEPTUAL LAYERED VIEW · NOT A DEPLOYED SYSTEM</text>
</svg>

</div>

<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 24" width="100%" height="24" role="presentation" aria-hidden="true">
  <defs>
    <linearGradient id="dv5" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%"   stop-color="#30363D" stop-opacity="0"/>
      <stop offset="20%"  stop-color="#30363D" stop-opacity="1"/>
      <stop offset="50%"  stop-color="#39FF88" stop-opacity="0.9"/>
      <stop offset="80%"  stop-color="#30363D" stop-opacity="1"/>
      <stop offset="100%" stop-color="#30363D" stop-opacity="0"/>
    </linearGradient>
  </defs>
  <line x1="40" y1="12" x2="560" y2="12" stroke="url(#dv5)" stroke-width="1"/>
  <circle cx="600" cy="12" r="4" fill="#0D1117" stroke="#39FF88" stroke-width="1.4"/>
  <circle cx="600" cy="12" r="1.4" fill="#39FF88"/>
  <line x1="580" y1="12" x2="592" y2="12" stroke="#58A6FF" stroke-width="1"/>
  <line x1="608" y1="12" x2="620" y2="12" stroke="#58A6FF" stroke-width="1"/>
  <line x1="640" y1="12" x2="1160" y2="12" stroke="url(#dv5)" stroke-width="1"/>
</svg>

</div>

<!-- ═══════════════════════════════════════════════════════════════════════════════
     ZONE F — PIPELINE D · MACHINE LEARNING
     Data preparation → feature extraction → training → anomaly detection → evaluation
     ═══════════════════════════════════════════════════════════════════════════════ -->

<div align="center">

### <samp>› Pipeline D · Machine Learning</samp>

<sub>Conceptual ML workflow used across anomaly-detection projects.</sub>

<br/><br/>

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 280" width="100%" height="280" role="img" aria-label="Machine learning pipeline: data preparation, feature extraction, training, anomaly detection, evaluation">
  <defs>
    <linearGradient id="pDBg" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%"   stop-color="#0D1117"/>
      <stop offset="100%" stop-color="#161B22"/>
    </linearGradient>
    <linearGradient id="pDFlow" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%"   stop-color="#39FF88"/>
      <stop offset="50%"  stop-color="#58A6FF"/>
      <stop offset="100%" stop-color="#79C0FF"/>
    </linearGradient>
    <marker id="pDArrow" viewBox="0 0 10 10" refX="8" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse">
      <path d="M 0 0 L 10 5 L 0 10 z" fill="#58A6FF"/>
    </marker>
  </defs>

  <rect width="1200" height="280" fill="url(#pDBg)"/>
  <rect x="0.5" y="0.5" width="1199" height="279" fill="none" stroke="#30363D" stroke-width="1"/>

  <text x="30" y="32" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="11" fill="#8B949E" letter-spacing="3">▸ PIPELINE D · MACHINE LEARNING</text>

  <line x1="150" y1="135" x2="1050" y2="135" stroke="url(#pDFlow)" stroke-width="2" stroke-dasharray="7 7" marker-end="url(#pDArrow)"/>

  <!-- 5 stages -->
  <g>
    <rect x="70"  y="95" width="180" height="80" rx="6" fill="#161B22" stroke="#39FF88" stroke-width="1.2"/>
    <text x="160" y="120" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9"  fill="#39FF88" letter-spacing="2">01 · PREPARE</text>
    <text x="160" y="142" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="11" font-weight="700" fill="#E6EDF3">DATA PREPARATION</text>
    <text x="160" y="160" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9"  fill="#8B949E">cleaning · balancing</text>
  </g>
  <g>
    <rect x="290" y="95" width="180" height="80" rx="6" fill="#161B22" stroke="#58A6FF" stroke-width="1.2"/>
    <text x="380" y="120" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9"  fill="#58A6FF" letter-spacing="2">02 · FEATURES</text>
    <text x="380" y="142" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="11" font-weight="700" fill="#E6EDF3">EXTRACTION</text>
    <text x="380" y="160" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9"  fill="#8B949E">encoding · scaling</text>
  </g>
  <g>
    <rect x="510" y="95" width="180" height="80" rx="6" fill="#161B22" stroke="#39FF88" stroke-width="1.2"/>
    <text x="600" y="120" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9"  fill="#39FF88" letter-spacing="2">03 · TRAIN</text>
    <text x="600" y="142" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="11" font-weight="700" fill="#E6EDF3">MODEL FIT</text>
    <text x="600" y="160" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9"  fill="#8B949E">XGBoost · sklearn</text>
  </g>
  <g>
    <rect x="730" y="95" width="180" height="80" rx="6" fill="#161B22" stroke="#39FF88" stroke-width="1.2"/>
    <text x="820" y="120" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9"  fill="#39FF88" letter-spacing="2">04 · DETECT</text>
    <text x="820" y="142" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="11" font-weight="700" fill="#E6EDF3">ANOMALIES</text>
    <text x="820" y="160" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9"  fill="#8B949E">Isolation Forest · OCSVM</text>
  </g>
  <g>
    <rect x="950" y="95" width="180" height="80" rx="6" fill="#161B22" stroke="#79C0FF" stroke-width="1.2"/>
    <text x="1040" y="120" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9"  fill="#79C0FF" letter-spacing="2">05 · EVALUATE</text>
    <text x="1040" y="142" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="11" font-weight="700" fill="#E6EDF3">METRICS</text>
    <text x="1040" y="160" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9"  fill="#8B949E">F1 · precision · recall</text>
  </g>

  <!-- Connector dots -->
  <g fill="#0D1117" stroke="#58A6FF" stroke-width="1.2">
    <circle cx="250" cy="135" r="4"/>
    <circle cx="470" cy="135" r="4"/>
    <circle cx="690" cy="135" r="4"/>
    <circle cx="910" cy="135" r="4"/>
  </g>

  <text x="30" y="260" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9" fill="#8B949E" letter-spacing="2">CONCEPTUAL WORKFLOW · NOT A DEPLOYED SYSTEM · USED ACROSS ANOMALY-DETECTION PROJECTS</text>
</svg>

</div>

<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 24" width="100%" height="24" role="presentation" aria-hidden="true">
  <defs>
    <linearGradient id="dv6" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%"   stop-color="#30363D" stop-opacity="0"/>
      <stop offset="20%"  stop-color="#30363D" stop-opacity="1"/>
      <stop offset="50%"  stop-color="#39FF88" stop-opacity="0.9"/>
      <stop offset="80%"  stop-color="#30363D" stop-opacity="1"/>
      <stop offset="100%" stop-color="#30363D" stop-opacity="0"/>
    </linearGradient>
  </defs>
  <line x1="40" y1="12" x2="560" y2="12" stroke="url(#dv6)" stroke-width="1"/>
  <circle cx="600" cy="12" r="4" fill="#0D1117" stroke="#39FF88" stroke-width="1.4"/>
  <circle cx="600" cy="12" r="1.4" fill="#39FF88"/>
  <line x1="580" y1="12" x2="592" y2="12" stroke="#58A6FF" stroke-width="1"/>
  <line x1="608" y1="12" x2="620" y2="12" stroke="#58A6FF" stroke-width="1"/>
  <line x1="640" y1="12" x2="1160" y2="12" stroke="url(#dv6)" stroke-width="1"/>
</svg>

</div>

<!-- ═══════════════════════════════════════════════════════════════════════════════
     ZONE G — DIAGRAM E · SUPERVISION & ANALYSIS
     Virtual machines → monitoring → metrics → alerting → analysis → dashboard
     ═══════════════════════════════════════════════════════════════════════════════ -->

<div align="center">

### <samp>› Diagram E · Supervision & Analysis</samp>

<sub>Conceptual supervision loop inspired by VirtualBox + Zabbix lab layouts.</sub>

<br/><br/>

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 300" width="100%" height="300" role="img" aria-label="Supervision and analysis diagram: virtual machines, monitoring, metrics, alerts, analysis, dashboard">
  <defs>
    <linearGradient id="pEBg" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%"   stop-color="#0D1117"/>
      <stop offset="100%" stop-color="#161B22"/>
    </linearGradient>
    <linearGradient id="pERing" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%"   stop-color="#39FF88"/>
      <stop offset="100%" stop-color="#58A6FF"/>
    </linearGradient>
    <marker id="pEArrow" viewBox="0 0 10 10" refX="8" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse">
      <path d="M 0 0 L 10 5 L 0 10 z" fill="#58A6FF"/>
    </marker>
  </defs>

  <rect width="1200" height="300" fill="url(#pEBg)"/>
  <rect x="0.5" y="0.5" width="1199" height="299" fill="none" stroke="#30363D" stroke-width="1"/>

  <text x="30" y="32" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="11" fill="#8B949E" letter-spacing="3">▸ DIAGRAM E · SUPERVISION &amp; ANALYSIS</text>

  <!-- Ring (conceptual feedback loop) -->
  <circle cx="600" cy="165" r="95" fill="none" stroke="url(#pERing)" stroke-width="1.5" stroke-dasharray="5 5" opacity="0.9"/>

  <!-- 6 nodes around the ring -->
  <!-- Top-left -->
  <g>
    <rect x="200" y="70" width="160" height="60" rx="6" fill="#161B22" stroke="#39FF88" stroke-width="1.2"/>
    <text x="280" y="92"  text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9"  fill="#39FF88" letter-spacing="2">VMs</text>
    <text x="280" y="112" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="11" font-weight="700" fill="#E6EDF3">VirtualBox lab</text>
  </g>
  <!-- Top-right -->
  <g>
    <rect x="840" y="70" width="160" height="60" rx="6" fill="#161B22" stroke="#58A6FF" stroke-width="1.2"/>
    <text x="920" y="92"  text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9"  fill="#58A6FF" letter-spacing="2">MONITORING</text>
    <text x="920" y="112" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="11" font-weight="700" fill="#E6EDF3">Zabbix</text>
  </g>
  <!-- Right -->
  <g>
    <rect x="900" y="180" width="160" height="60" rx="6" fill="#161B22" stroke="#79C0FF" stroke-width="1.2"/>
    <text x="980" y="202" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9"  fill="#79C0FF" letter-spacing="2">METRICS</text>
    <text x="980" y="222" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="11" font-weight="700" fill="#E6EDF3">time series</text>
  </g>
  <!-- Bottom -->
  <g>
    <rect x="520" y="230" width="160" height="50" rx="6" fill="#161B22" stroke="#39FF88" stroke-width="1.2"/>
    <text x="600" y="252" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9"  fill="#39FF88" letter-spacing="2">ALERTS</text>
    <text x="600" y="270" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="11" font-weight="700" fill="#E6EDF3">thresholds</text>
  </g>
  <!-- Left -->
  <g>
    <rect x="140" y="180" width="160" height="60" rx="6" fill="#161B22" stroke="#58A6FF" stroke-width="1.2"/>
    <text x="220" y="202" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9"  fill="#58A6FF" letter-spacing="2">DASHBOARD</text>
    <text x="220" y="222" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="11" font-weight="700" fill="#E6EDF3">analysis UI</text>
  </g>
  <!-- Center -->
  <g>
    <rect x="520" y="140" width="160" height="50" rx="6" fill="#1C2128" stroke="#39FF88" stroke-width="1.4"/>
    <text x="600" y="162" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9"  fill="#39FF88" letter-spacing="2">ANALYSIS</text>
    <text x="600" y="180" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="11" font-weight="700" fill="#E6EDF3">correlation</text>
  </g>

  <!-- Connectors -->
  <line x1="360" y1="100" x2="520" y2="160" stroke="#58A6FF" stroke-width="1.2" stroke-dasharray="4 3" marker-end="url(#pEArrow)"/>
  <line x1="840" y1="100" x2="680" y2="160" stroke="#58A6FF" stroke-width="1.2" stroke-dasharray="4 3" marker-end="url(#pEArrow)"/>
  <line x1="900" y1="210" x2="680" y2="180" stroke="#79C0FF" stroke-width="1.2" stroke-dasharray="4 3" marker-end="url(#pEArrow)"/>
  <line x1="520" y1="255" x2="620" y2="190" stroke="#39FF88" stroke-width="1.2" stroke-dasharray="4 3" marker-end="url(#pEArrow)"/>
  <line x1="300" y1="210" x2="520" y2="170" stroke="#58A6FF" stroke-width="1.2" stroke-dasharray="4 3" marker-end="url(#pEArrow)"/>

  <text x="30" y="290" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9" fill="#8B949E" letter-spacing="2">CONCEPTUAL FEEDBACK LOOP · NOT A DEPLOYED SYSTEM</text>
</svg>

</div>

<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 24" width="100%" height="24" role="presentation" aria-hidden="true">
  <defs>
    <linearGradient id="dv7" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%"   stop-color="#30363D" stop-opacity="0"/>
      <stop offset="20%"  stop-color="#30363D" stop-opacity="1"/>
      <stop offset="50%"  stop-color="#39FF88" stop-opacity="0.9"/>
      <stop offset="80%"  stop-color="#30363D" stop-opacity="1"/>
      <stop offset="100%" stop-color="#30363D" stop-opacity="0"/>
    </linearGradient>
  </defs>
  <line x1="40" y1="12" x2="560" y2="12" stroke="url(#dv7)" stroke-width="1"/>
  <circle cx="600" cy="12" r="4" fill="#0D1117" stroke="#39FF88" stroke-width="1.4"/>
  <circle cx="600" cy="12" r="1.4" fill="#39FF88"/>
  <line x1="580" y1="12" x2="592" y2="12" stroke="#58A6FF" stroke-width="1"/>
  <line x1="608" y1="12" x2="620" y2="12" stroke="#58A6FF" stroke-width="1"/>
  <line x1="640" y1="12" x2="1160" y2="12" stroke="url(#dv7)" stroke-width="1"/>
</svg>

</div>

<!-- ═══════════════════════════════════════════════════════════════════════════════
     ZONE H — TECHNICAL DOMAINS
     Six grouped tables, aligned two-by-two, with a small color-coded header strip.
     ═══════════════════════════════════════════════════════════════════════════════ -->

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
    <linearGradient id="dv8" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%"   stop-color="#30363D" stop-opacity="0"/>
      <stop offset="20%"  stop-color="#30363D" stop-opacity="1"/>
      <stop offset="50%"  stop-color="#39FF88" stop-opacity="0.9"/>
      <stop offset="80%"  stop-color="#30363D" stop-opacity="1"/>
      <stop offset="100%" stop-color="#30363D" stop-opacity="0"/>
    </linearGradient>
  </defs>
  <line x1="40" y1="12" x2="560" y2="12" stroke="url(#dv8)" stroke-width="1"/>
  <circle cx="600" cy="12" r="4" fill="#0D1117" stroke="#39FF88" stroke-width="1.4"/>
  <circle cx="600" cy="12" r="1.4" fill="#39FF88"/>
  <line x1="580" y1="12" x2="592" y2="12" stroke="#58A6FF" stroke-width="1"/>
  <line x1="608" y1="12" x2="620" y2="12" stroke="#58A6FF" stroke-width="1"/>
  <line x1="640" y1="12" x2="1160" y2="12" stroke="url(#dv8)" stroke-width="1"/>
</svg>

</div>

<!-- ═══════════════════════════════════════════════════════════════════════════════
     ZONE I — FEATURED PROJECTS
     Six technical sheets, aligned two-by-two.
     Each sheet: id, title, description, stack, features, optional screenshot slot.
     Project-specific pipelines are drawn for projects whose architecture is
     confirmed by the user or publicly documented.
     ═══════════════════════════════════════════════════════════════════════════════ -->

### <samp>› Featured Projects</samp>

<br/>

<table width="100%">
<tr>
<td width="50%" valign="top">

#### `01` — Banking Anomaly Detection

> Detection of anomalous banking transactions using Python, Flask and Machine Learning.

**Stack** · `Python` · `Flask` · `Machine Learning`

**Reported metric** · F1-score (declared): `0.9632`

**Scope**
- Transaction anomaly detection
- Flask-based inference service

<sub>*Screenshot slot (optional):* `assets/projects/banking.png`</sub>

</td>
<td width="50%" valign="top">

#### `02` — NeuroSecure

> Cybersecurity project developed in the context of a technical internship at **MORITSOFT**.

**Stack** · `Flask` · `WAF` · `IDS` · `OTP` · `XGBoost`

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

**Stack** · `Python` · `PySide6`

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

**Stack** · `Python` · `Flask`

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

**Stack** · `Zabbix` · `VirtualBox` · `Machine Learning` · `Flask` · `React`

**Features**
- Network monitoring
- Dashboard-based visualization

<sub>*Screenshot slot (optional):* `assets/projects/zabbix.png`</sub>

</td>
</tr>
</table>

> **Note** — Project repositories and screenshots will be linked here after their availability and contents have been verified. No repository URL or performance figure is published unless it is publicly verifiable.

<br/>

<!-- ── Project F · NeuroSecure · conceptual pipeline ────────────────────────── -->

<div align="center">

#### `02` — NeuroSecure · conceptual detection flow

<sub>Protection layers illustrated from the declared project scope.</sub>

<br/>

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 200" width="100%" height="200" role="img" aria-label="NeuroSecure conceptual flow: HTTP request, WAF inspection, XSS and SQLi detection, behavioural scoring, IP blocking, logging">
  <defs>
    <linearGradient id="nsBg" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%"   stop-color="#0D1117"/>
      <stop offset="100%" stop-color="#161B22"/>
    </linearGradient>
    <marker id="nsArrow" viewBox="0 0 10 10" refX="8" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse">
      <path d="M 0 0 L 10 5 L 0 10 z" fill="#58A6FF"/>
    </marker>
  </defs>
  <rect width="1200" height="200" fill="url(#nsBg)"/>
  <rect x="0.5" y="0.5" width="1199" height="199" fill="none" stroke="#30363D" stroke-width="1"/>
  <text x="30" y="30" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="10" fill="#8B949E" letter-spacing="2">▸ NEUROSECURE · CONCEPTUAL DETECTION FLOW</text>

  <line x1="140" y1="115" x2="1060" y2="115" stroke="#58A6FF" stroke-width="1.5" stroke-dasharray="6 6" marker-end="url(#nsArrow)"/>

  <g>
    <rect x="70"  y="85" width="150" height="60" rx="5" fill="#161B22" stroke="#58A6FF" stroke-width="1.2"/>
    <text x="145" y="108" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9" fill="#58A6FF" letter-spacing="1">INGRESS</text>
    <text x="145" y="128" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="10" font-weight="700" fill="#E6EDF3">HTTP request</text>
  </g>
  <g>
    <rect x="255" y="85" width="150" height="60" rx="5" fill="#161B22" stroke="#39FF88" stroke-width="1.2"/>
    <text x="330" y="108" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9" fill="#39FF88" letter-spacing="1">WAF</text>
    <text x="330" y="128" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="10" font-weight="700" fill="#E6EDF3">inspection</text>
  </g>
  <g>
    <rect x="440" y="85" width="150" height="60" rx="5" fill="#161B22" stroke="#39FF88" stroke-width="1.2"/>
    <text x="515" y="108" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9" fill="#39FF88" letter-spacing="1">DETECTION</text>
    <text x="515" y="128" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="10" font-weight="700" fill="#E6EDF3">XSS · SQLi</text>
  </g>
  <g>
    <rect x="625" y="85" width="150" height="60" rx="5" fill="#161B22" stroke="#79C0FF" stroke-width="1.2"/>
    <text x="700" y="108" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9" fill="#79C0FF" letter-spacing="1">SCORING</text>
    <text x="700" y="128" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="10" font-weight="700" fill="#E6EDF3">XGBoost</text>
  </g>
  <g>
    <rect x="810" y="85" width="150" height="60" rx="5" fill="#161B22" stroke="#39FF88" stroke-width="1.2"/>
    <text x="885" y="108" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9" fill="#39FF88" letter-spacing="1">BLOCK</text>
    <text x="885" y="128" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="10" font-weight="700" fill="#E6EDF3">temporary IP</text>
  </g>
  <g>
    <rect x="995" y="85" width="150" height="60" rx="5" fill="#161B22" stroke="#58A6FF" stroke-width="1.2"/>
    <text x="1070" y="108" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9" fill="#58A6FF" letter-spacing="1">LOG</text>
    <text x="1070" y="128" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="10" font-weight="700" fill="#E6EDF3">evidence</text>
  </g>

  <text x="30" y="185" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9" fill="#8B949E" letter-spacing="2">CONCEPTUAL SCOPE · NOT A DEPLOYED SYSTEM</text>
</svg>

</div>

<br/>

<!-- ── Project F · Menara CyberShield · conceptual architecture ──────────────── -->

<div align="center">

#### `03` — Menara CyberShield · conceptual modules

<sub>Module layout derived from the project description.</sub>

<br/>

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 240" width="100%" height="240" role="img" aria-label="Menara CyberShield conceptual modules: industrial cybersecurity, inventory, truck tracking, dashboards, reporting">
  <defs>
    <linearGradient id="mcBg" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%"   stop-color="#0D1117"/>
      <stop offset="100%" stop-color="#161B22"/>
    </linearGradient>
  </defs>
  <rect width="1200" height="240" fill="url(#mcBg)"/>
  <rect x="0.5" y="0.5" width="1199" height="239" fill="none" stroke="#30363D" stroke-width="1"/>
  <text x="30" y="30" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="10" fill="#8B949E" letter-spacing="2">▸ MENARA CYBERSHIELD · CONCEPTUAL MODULES</text>

  <g>
    <rect x="60"  y="70" width="220" height="70" rx="5" fill="#161B22" stroke="#39FF88" stroke-width="1.2"/>
    <text x="170" y="94"  text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9" fill="#39FF88" letter-spacing="1">SECURITY</text>
    <text x="170" y="116" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="11" font-weight="700" fill="#E6EDF3">industrial cybersecurity</text>
  </g>
  <g>
    <rect x="320" y="70" width="220" height="70" rx="5" fill="#161B22" stroke="#58A6FF" stroke-width="1.2"/>
    <text x="430" y="94"  text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9" fill="#58A6FF" letter-spacing="1">OPERATIONS</text>
    <text x="430" y="116" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="11" font-weight="700" fill="#E6EDF3">inventory management</text>
  </g>
  <g>
    <rect x="580" y="70" width="220" height="70" rx="5" fill="#161B22" stroke="#58A6FF" stroke-width="1.2"/>
    <text x="690" y="94"  text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9" fill="#58A6FF" letter-spacing="1">LOGISTICS</text>
    <text x="690" y="116" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="11" font-weight="700" fill="#E6EDF3">truck tracking</text>
  </g>
  <g>
    <rect x="840" y="70" width="220" height="70" rx="5" fill="#161B22" stroke="#79C0FF" stroke-width="1.2"/>
    <text x="950" y="94"  text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9" fill="#79C0FF" letter-spacing="1">REPORTING</text>
    <text x="950" y="116" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="11" font-weight="700" fill="#E6EDF3">dashboards &amp; reports</text>
  </g>

  <!-- Shared platform base -->
  <rect x="60" y="165" width="1000" height="46" rx="5" fill="#1C2128" stroke="#39FF88" stroke-width="1.2"/>
  <text x="560" y="186" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9" fill="#39FF88" letter-spacing="1">SHARED APPLICATION PLATFORM</text>
  <text x="560" y="204" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="10" fill="#E6EDF3">Python · PySide6</text>

  <text x="30" y="232" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9" fill="#8B949E" letter-spacing="2">CONCEPTUAL MODULES · NOT A DEPLOYED SYSTEM</text>
</svg>

</div>

<br/>

<!-- ── Project F · Zabbix + AI · conceptual lab topology ────────────────────── -->

<div align="center">

#### `06` — Zabbix + AI · conceptual lab topology

<sub>Five virtual machines illustrated as a monitoring cluster.</sub>

<br/>

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 220" width="100%" height="220" role="img" aria-label="Zabbix and AI lab topology: five VirtualBox machines feeding Zabbix monitoring and analysis">
  <defs>
    <linearGradient id="zbBg" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%"   stop-color="#0D1117"/>
      <stop offset="100%" stop-color="#161B22"/>
    </linearGradient>
    <marker id="zbArrow" viewBox="0 0 10 10" refX="8" refY="5" markerWidth="6" markerHeight="6" orient="auto-start-reverse">
      <path d="M 0 0 L 10 5 L 0 10 z" fill="#58A6FF"/>
    </marker>
  </defs>
  <rect width="1200" height="220" fill="url(#zbBg)"/>
  <rect x="0.5" y="0.5" width="1199" height="219" fill="none" stroke="#30363D" stroke-width="1"/>
  <text x="30" y="30" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="10" fill="#8B949E" letter-spacing="2">▸ ZABBIX + AI · CONCEPTUAL LAB TOPOLOGY</text>

  <!-- Five VMs -->
  <g>
    <rect x="70"  y="65" width="80" height="40" rx="4" fill="#161B22" stroke="#39FF88" stroke-width="1"/>
    <text x="110" y="89" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9" fill="#E6EDF3">VM 01</text>
  </g>
  <g>
    <rect x="170" y="65" width="80" height="40" rx="4" fill="#161B22" stroke="#39FF88" stroke-width="1"/>
    <text x="210" y="89" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9" fill="#E6EDF3">VM 02</text>
  </g>
  <g>
    <rect x="270" y="65" width="80" height="40" rx="4" fill="#161B22" stroke="#39FF88" stroke-width="1"/>
    <text x="310" y="89" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9" fill="#E6EDF3">VM 03</text>
  </g>
  <g>
    <rect x="370" y="65" width="80" height="40" rx="4" fill="#161B22" stroke="#39FF88" stroke-width="1"/>
    <text x="410" y="89" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9" fill="#E6EDF3">VM 04</text>
  </g>
  <g>
    <rect x="470" y="65" width="80" height="40" rx="4" fill="#161B22" stroke="#39FF88" stroke-width="1"/>
    <text x="510" y="89" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9" fill="#E6EDF3">VM 05</text>
  </g>

  <!-- Bus lines -->
  <g stroke="#58A6FF" stroke-width="1" fill="none" stroke-dasharray="4 3">
    <path d="M 110 105 L 110 135 L 700 135"/>
    <path d="M 210 105 L 210 135 L 700 135"/>
    <path d="M 310 105 L 310 135 L 700 135"/>
    <path d="M 410 105 L 410 135 L 700 135"/>
    <path d="M 510 105 L 510 135 L 700 135"/>
  </g>

  <line x1="700" y1="135" x2="820" y2="135" stroke="#58A6FF" stroke-width="1.5" marker-end="url(#zbArrow)"/>

  <!-- Zabbix -->
  <g>
    <rect x="820" y="105" width="150" height="60" rx="5" fill="#161B22" stroke="#79C0FF" stroke-width="1.2"/>
    <text x="895" y="128" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9" fill="#79C0FF" letter-spacing="1">MONITORING</text>
    <text x="895" y="148" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="10" font-weight="700" fill="#E6EDF3">Zabbix</text>
  </g>

  <!-- AI layer -->
  <g>
    <rect x="1000" y="105" width="150" height="60" rx="5" fill="#161B22" stroke="#39FF88" stroke-width="1.2"/>
    <text x="1075" y="128" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9" fill="#39FF88" letter-spacing="1">ANALYSIS</text>
    <text x="1075" y="148" text-anchor="middle" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="10" font-weight="700" fill="#E6EDF3">ML · Flask · React</text>
  </g>

  <text x="30" y="200" font-family="ui-monospace, SFMono-Regular, Menlo, monospace" font-size="9" fill="#8B949E" letter-spacing="2">CONCEPTUAL TOPOLOGY · NOT A DEPLOYED SYSTEM</text>
</svg>

</div>

<div align="center">

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 24" width="100%" height="24" role="presentation" aria-hidden="true">
  <defs>
    <linearGradient id="dv9" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%"   stop-color="#30363D" stop-opacity="0"/>
      <stop offset="20%"  stop-color="#30363D" stop-opacity="1"/>
      <stop offset="50%"  stop-color="#39FF88" stop-opacity="0.9"/>
      <stop offset="80%"  stop-color="#30363D" stop-opacity="1"/>
      <stop offset="100%" stop-color="#30363D" stop-opacity="0"/>
    </linearGradient>
  </defs>
  <line x1="40" y1="12" x2="560" y2="12" stroke="url(#dv9)" stroke-width="1"/>
  <circle cx="600" cy="12" r="4" fill="#0D1117" stroke="#39FF88" stroke-width="1.4"/>
  <circle cx="600" cy="12" r="1.4" fill="#39FF88"/>
  <line x1="580" y1="12" x2="592" y2="12" stroke="#58A6FF" stroke-width="1"/>
  <line x1="608" y1="12" x2="620" y2="12" stroke="#58A6FF" stroke-width="1"/>
  <line x1="640" y1="12" x2="1160" y2="12" stroke="url(#dv9)" stroke-width="1"/>
</svg>

</div>

<!-- ═══════════════════════════════════════════════════════════════════════════════
     ZONE J — ENGINEERING EXPERIENCE
     ═══════════════════════════════════════════════════════════════════════════════ -->

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
    <linearGradient id="dv10" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%"   stop-color="#30363D" stop-opacity="0"/>
      <stop offset="20%"  stop-color="#30363D" stop-opacity="1"/>
      <stop offset="50%"  stop-color="#39FF88" stop-opacity="0.9"/>
      <stop offset="80%"  stop-color="#30363D" stop-opacity="1"/>
      <stop offset="100%" stop-color="#30363D" stop-opacity="0"/>
    </linearGradient>
  </defs>
  <line x1="40" y1="12" x2="560" y2="12" stroke="url(#dv10)" stroke-width="1"/>
  <circle cx="600" cy="12" r="4" fill="#0D1117" stroke="#39FF88" stroke-width="1.4"/>
  <circle cx="600" cy="12" r="1.4" fill="#39FF88"/>
  <line x1="580" y1="12" x2="592" y2="12" stroke="#58A6FF" stroke-width="1"/>
  <line x1="608" y1="12" x2="620" y2="12" stroke="#58A6FF" stroke-width="1"/>
  <line x1="640" y1="12" x2="1160" y2="12" stroke="url(#dv10)" stroke-width="1"/>
</svg>

</div>

<!-- ═══════════════════════════════════════════════════════════════════════════════
     ZONE K — ACADEMIC BACKGROUND + TRAINING + LANGUAGES
     ═══════════════════════════════════════════════════════════════════════════════ -->

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
    <linearGradient id="dv11" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%"   stop-color="#30363D" stop-opacity="0"/>
      <stop offset="20%"  stop-color="#30363D" stop-opacity="1"/>
      <stop offset="50%"  stop-color="#39FF88" stop-opacity="0.9"/>
      <stop offset="80%"  stop-color="#30363D" stop-opacity="1"/>
      <stop offset="100%" stop-color="#30363D" stop-opacity="0"/>
    </linearGradient>
  </defs>
  <line x1="40" y1="12" x2="560" y2="12" stroke="url(#dv11)" stroke-width="1"/>
  <circle cx="600" cy="12" r="4" fill="#0D1117" stroke="#39FF88" stroke-width="1.4"/>
  <circle cx="600" cy="12" r="1.4" fill="#39FF88"/>
  <line x1="580" y1="12" x2="592" y2="12" stroke="#58A6FF" stroke-width="1"/>
  <line x1="608" y1="12" x2="620" y2="12" stroke="#58A6FF" stroke-width="1"/>
  <line x1="640" y1="12" x2="1160" y2="12" stroke="url(#dv11)" stroke-width="1"/>
</svg>

</div>

<!-- ═══════════════════════════════════════════════════════════════════════════════
     ZONE L — CONTACT
     ═══════════════════════════════════════════════════════════════════════════════ -->

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
    <linearGradient id="dv12" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%"   stop-color="#30363D" stop-opacity="0"/>
      <stop offset="20%"  stop-color="#30363D" stop-opacity="1"/>
      <stop offset="50%"  stop-color="#39FF88" stop-opacity="0.9"/>
      <stop offset="80%"  stop-color="#30363D" stop-opacity="1"/>
      <stop offset="100%" stop-color="#30363D" stop-opacity="0"/>
    </linearGradient>
  </defs>
  <line x1="40" y1="12" x2="560" y2="12" stroke="url(#dv12)" stroke-width="1"/>
  <circle cx="600" cy="12" r="4" fill="#0D1117" stroke="#39FF88" stroke-width="1.4"/>
  <circle cx="600" cy="12" r="1.4" fill="#39FF88"/>
  <line x1="580" y1="12" x2="592" y2="12" stroke="#58A6FF" stroke-width="1"/>
  <line x1="608" y1="12" x2="620" y2="12" stroke="#58A6FF" stroke-width="1"/>
  <line x1="640" y1="12" x2="1160" y2="12" stroke="url(#dv12)" stroke-width="1"/>
</svg>

</div>

<!-- ═══════════════════════════════════════════════════════════════════════════════
     ZONE M — FOOTER
     ═══════════════════════════════════════════════════════════════════════════════ -->

<div align="center">

<sub>
  <code>SABRI WALID</code> &nbsp;·&nbsp;
  <code>ESTK · Université Cadi Ayyad</code> &nbsp;·&nbsp;
  <code>2026 – 2027</code>
</sub>

<br/><br/>

<sub>
  Single-file GitHub Profile README · inline SVG only · no external assets required.
</sub>

</div>
