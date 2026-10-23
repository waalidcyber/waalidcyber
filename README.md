<!-- ═══════════════════════════════════════════════════════════════════════════════
     SABRI WALID — Dashboard Scientifique & Cybersécurité (Édition Premium)
     Palette : Bleu (#58A6FF), Cyan (#79C0FF), Violet (#A371F7), 
     Orange (#F0883E), Jaune (#FFD866), Vert (#39FF88), Rouge (#F85149)
     ═══════════════════════════════════════════════════════════════════════════════ -->

<div align="center">

<!-- HEADER W3RE -->
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 240" width="100%" height="240" role="img" aria-label="Header SABRI WALID">
  <defs>
    <linearGradient id="hBg" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0%" stop-color="#0D1117"/>
      <stop offset="50%" stop-color="#11161D"/>
      <stop offset="100%" stop-color="#161B22"/>
    </linearGradient>
    <linearGradient id="hName" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#E6EDF3"/>
      <stop offset="40%" stop-color="#79C0FF"/>
      <stop offset="60%" stop-color="#A371F7"/>
      <stop offset="100%" stop-color="#E6EDF3"/>
    </linearGradient>
    <linearGradient id="hAccent" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#39FF88"/>
      <stop offset="33%" stop-color="#58A6FF"/>
      <stop offset="66%" stop-color="#A371F7"/>
      <stop offset="100%" stop-color="#F0883E"/>
    </linearGradient>
    <pattern id="hGrid" width="30" height="30" patternUnits="userSpaceOnUse">
      <path d="M 30 0 L 0 0 0 30" fill="none" stroke="#30363D" stroke-width="0.5" opacity="0.4"/>
    </pattern>
    <filter id="glowG" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="4" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>
  
  <rect width="1200" height="240" fill="url(#hBg)"/>
  <rect width="1200" height="240" fill="url(#hGrid)"/>
  <rect x="0" y="0" width="1200" height="3" fill="url(#hAccent)"/>
  <rect x="0" y="237" width="1200" height="3" fill="url(#hAccent)"/>

  <!-- Avatar Ring -->
  <g filter="url(#glowG)">
    <circle cx="110" cy="120" r="65" fill="#161B22" stroke="#39FF88" stroke-width="2.5"/>
    <circle cx="110" cy="120" r="55" fill="#0D1117" stroke="#58A6FF" stroke-width="1" stroke-dasharray="4 4"/>
  </g>
  <text x="110" y="135" text-anchor="middle" font-family="ui-monospace, monospace" font-size="48" font-weight="700" fill="#39FF88">W</text>
  <circle cx="160" cy="70" r="8" fill="#3FB950" stroke="#0D1117" stroke-width="2"/>

  <!-- Name & Title -->
  <text x="210" y="85" font-family="ui-monospace, monospace" font-size="42" font-weight="700" fill="url(#hName)" letter-spacing="2">SABRI WALID</text>
  <text x="210" y="120" font-family="ui-monospace, monospace" font-size="16" fill="#79C0FF" letter-spacing="1">Étudiant en Réseaux, Cybersécurité &amp; Cloud</text>
  <text x="210" y="145" font-family="ui-monospace, monospace" font-size="12" fill="#8B949E">Passionné par la sécurité informatique, l'analyse de données et l'IA.</text>
  
  <!-- Badges -->
  <g transform="translate(210, 165)">
    <rect x="0" y="0" width="110" height="24" rx="12" fill="#1C2128" stroke="#58A6FF" stroke-width="1"/>
    <text x="55" y="16" text-anchor="middle" font-family="ui-monospace, monospace" font-size="10" fill="#58A6FF">RÉSEAUX</text>
    <rect x="120" y="0" width="130" height="24" rx="12" fill="#1C2128" stroke="#39FF88" stroke-width="1"/>
    <text x="185" y="16" text-anchor="middle" font-family="ui-monospace, monospace" font-size="10" fill="#39FF88">CYBERSÉCURITÉ</text>
    <rect x="260" y="0" width="110" height="24" rx="12" fill="#1C2128" stroke="#A371F7" stroke-width="1"/>
    <text x="315" y="16" text-anchor="middle" font-family="ui-monospace, monospace" font-size="10" fill="#A371F7">CLOUD · IA</text>
  </g>

  <!-- Carte d'identité -->
  <g transform="translate(880, 40)">
    <rect width="290" height="160" rx="10" fill="#161B22" stroke="#30363D" stroke-width="1"/>
    <rect width="290" height="4" rx="2" fill="#58A6FF"/>
    <text x="20" y="30" font-family="ui-monospace, monospace" font-size="12" font-weight="700" fill="#58A6FF">▸ CARTE D'IDENTITÉ</text>
    <text x="20" y="55" font-family="ui-monospace, monospace" font-size="10" fill="#8B949E">Formation :</text>
    <text x="120" y="55" font-family="ui-monospace, monospace" font-size="10" fill="#E6EDF3">Bachelor Réseaux &amp; Cyber</text>
    <text x="20" y="75" font-family="ui-monospace, monospace" font-size="10" fill="#8B949E">Spécialité :</text>
    <text x="120" y="75" font-family="ui-monospace, monospace" font-size="10" fill="#E6EDF3">Sécurité Réseaux, IA</text>
    <text x="20" y="95" font-family="ui-monospace, monospace" font-size="10" fill="#8B949E">Diplôme :</text>
    <text x="120" y="95" font-family="ui-monospace, monospace" font-size="10" fill="#E6EDF3">DUT (Mention Bien)</text>
    <text x="20" y="115" font-family="ui-monospace, monospace" font-size="10" fill="#8B949E">Statut :</text>
    <text x="120" y="115" font-family="ui-monospace, monospace" font-size="10" fill="#39FF88">En cours · Stage recherché</text>
    <rect x="20" y="130" width="250" height="20" rx="10" fill="#0D1117" stroke="#39FF88" stroke-width="1"/>
    <circle cx="32" cy="140" r="4" fill="#39FF88"/>
    <text x="145" y="144" text-anchor="middle" font-family="ui-monospace, monospace" font-size="9" fill="#39FF88">DISPONIBLE POUR STAGE</text>
  </g>
</svg>

</div>

---

### <samp>› Domaines de compétences</samp>

<table width="100%">
<tr>
<td width="25%" valign="top" align="center" style="background-color:#161B22; border: 1px solid #58A6FF; border-radius: 8px; padding: 12px;">
<h4 style="color:#58A6FF; margin: 0;">🌐 Réseaux &amp; Infra</h4>
<sub style="color:#8B949E;">TCP/IP · VLAN · Routing<br/>Firewall · VPN · SD-WAN</sub>
</td>
<td width="25%" valign="top" align="center" style="background-color:#161B22; border: 1px solid #39FF88; border-radius: 8px; padding: 12px;">
<h4 style="color:#39FF88; margin: 0;">🛡️ Cybersécurité</h4>
<sub style="color:#8B949E;">SOC · SIEM · IDS/IPS<br/>Pentest · Réponse incidents</sub>
</td>
<td width="25%" valign="top" align="center" style="background-color:#161B22; border: 1px solid #A371F7; border-radius: 8px; padding: 12px;">
<h4 style="color:#A371F7; margin: 0;">🧠 Data &amp; IA</h4>
<sub style="color:#8B949E;">Python · Machine Learning<br/>Data Analysis · Deep Learning</sub>
</td>
<td width="25%" valign="top" align="center" style="background-color:#161B22; border: 1px solid #F0883E; border-radius: 8px; padding: 12px;">
<h4 style="color:#F0883E; margin: 0;">⚙️ Systèmes &amp; Virt.</h4>
<sub style="color:#8B949E;">Linux · Windows · Docker<br/>VMware · Cloud · Supervision</sub>
</td>
</tr>
</table>

---

<div align="center">

### <samp>› Pipeline de cybersécurité</samp>
<sub>De la collecte à la réponse : une chaîne de sécurité complète</sub>

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 300" width="100%" height="300" role="img" aria-label="Pipeline de cybersécurité">
  <defs>
    <linearGradient id="pBg" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#0D1117"/>
      <stop offset="100%" stop-color="#161B22"/>
    </linearGradient>
    <marker id="arr" viewBox="0 0 10 10" refX="8" refY="5" markerWidth="6" markerHeight="6" orient="auto">
      <path d="M 0 0 L 10 5 L 0 10 z" fill="#8B949E"/>
    </marker>
    <filter id="shadow" x="-20%" y="-20%" width="140%" height="140%">
      <feDropShadow dx="0" dy="4" stdDeviation="4" flood-color="#000" flood-opacity="0.3"/>
    </filter>
  </defs>
  
  <rect width="1200" height="300" fill="url(#pBg)" rx="12" stroke="#30363D"/>
  
  <!-- Step 1 -->
  <g transform="translate(30, 40)" filter="url(#shadow)">
    <rect width="200" height="130" rx="10" fill="#161B22" stroke="#58A6FF" stroke-width="2"/>
    <rect width="200" height="6" rx="3" fill="#58A6FF"/>
    <circle cx="30" cy="30" r="16" fill="#58A6FF"/>
    <text x="30" y="36" text-anchor="middle" font-family="ui-monospace, monospace" font-size="16" font-weight="700" fill="#0D1117">1</text>
    <text x="110" y="60" text-anchor="middle" font-family="ui-monospace, monospace" font-size="15" font-weight="700" fill="#58A6FF">NETWORK</text>
    <text x="110" y="82" text-anchor="middle" font-family="ui-monospace, monospace" font-size="11" fill="#E6EDF3">Infrastructure</text>
    <text x="110" y="102" text-anchor="middle" font-family="ui-monospace, monospace" font-size="9" fill="#8B949E">Réseaux · Serveurs</text>
    <text x="110" y="116" text-anchor="middle" font-family="ui-monospace, monospace" font-size="9" fill="#8B949E">Endpoints · Cloud</text>
  </g>
  <line x1="235" y1="105" x2="270" y2="105" stroke="#8B949E" stroke-width="2" marker-end="url(#arr)"/>

  <!-- Step 2 -->
  <g transform="translate(270, 40)" filter="url(#shadow)">
    <rect width="200" height="130" rx="10" fill="#161B22" stroke="#79C0FF" stroke-width="2"/>
    <rect width="200" height="6" rx="3" fill="#79C0FF"/>
    <circle cx="30" cy="30" r="16" fill="#79C0FF"/>
    <text x="30" y="36" text-anchor="middle" font-family="ui-monospace, monospace" font-size="16" font-weight="700" fill="#0D1117">2</text>
    <text x="110" y="60" text-anchor="middle" font-family="ui-monospace, monospace" font-size="15" font-weight="700" fill="#79C0FF">DATA</text>
    <text x="110" y="82" text-anchor="middle" font-family="ui-monospace, monospace" font-size="11" fill="#E6EDF3">Collection</text>
    <text x="110" y="102" text-anchor="middle" font-family="ui-monospace, monospace" font-size="9" fill="#8B949E">Logs · Événements</text>
    <text x="110" y="116" text-anchor="middle" font-family="ui-monospace, monospace" font-size="9" fill="#8B949E">Flux réseau · Journaux</text>
  </g>
  <line x1="475" y1="105" x2="510" y2="105" stroke="#8B949E" stroke-width="2" marker-end="url(#arr)"/>

  <!-- Step 3 -->
  <g transform="translate(510, 40)" filter="url(#shadow)">
    <rect width="200" height="130" rx="10" fill="#161B22" stroke="#F0883E" stroke-width="2"/>
    <rect width="200" height="6" rx="3" fill="#F0883E"/>
    <circle cx="30" cy="30" r="16" fill="#F0883E"/>
    <text x="30" y="36" text-anchor="middle" font-family="ui-monospace, monospace" font-size="16" font-weight="700" fill="#0D1117">3</text>
    <text x="110" y="60" text-anchor="middle" font-family="ui-monospace, monospace" font-size="15" font-weight="700" fill="#F0883E">THREAT</text>
    <text x="110" y="82" text-anchor="middle" font-family="ui-monospace, monospace" font-size="11" fill="#E6EDF3">Detection</text>
    <text x="110" y="102" text-anchor="middle" font-family="ui-monospace, monospace" font-size="9" fill="#8B949E">IDS/IPS · SIEM · IA</text>
    <text x="110" y="116" text-anchor="middle" font-family="ui-monospace, monospace" font-size="9" fill="#8B949E">Règles · Corrélations</text>
  </g>
  <line x1="715" y1="105" x2="750" y2="105" stroke="#8B949E" stroke-width="2" marker-end="url(#arr)"/>

  <!-- Step 4 -->
  <g transform="translate(750, 40)" filter="url(#shadow)">
    <rect width="200" height="130" rx="10" fill="#161B22" stroke="#FFD866" stroke-width="2"/>
    <rect width="200" height="6" rx="3" fill="#FFD866"/>
    <circle cx="30" cy="30" r="16" fill="#FFD866"/>
    <text x="30" y="36" text-anchor="middle" font-family="ui-monospace, monospace" font-size="16" font-weight="700" fill="#0D1117">4</text>
    <text x="110" y="60" text-anchor="middle" font-family="ui-monospace, monospace" font-size="15" font-weight="700" fill="#FFD866">ANALYSIS</text>
    <text x="110" y="82" text-anchor="middle" font-family="ui-monospace, monospace" font-size="11" fill="#E6EDF3">Analyse</text>
    <text x="110" y="102" text-anchor="middle" font-family="ui-monospace, monospace" font-size="9" fill="#8B949E">Comportementale</text>
    <text x="110" y="116" text-anchor="middle" font-family="ui-monospace, monospace" font-size="9" fill="#8B949E">Investigation</text>
  </g>
  <line x1="955" y1="105" x2="990" y2="105" stroke="#8B949E" stroke-width="2" marker-end="url(#arr)"/>

  <!-- Step 5 -->
  <g transform="translate(990, 40)" filter="url(#shadow)">
    <rect width="180" height="130" rx="10" fill="#161B22" stroke="#39FF88" stroke-width="2"/>
    <rect width="180" height="6" rx="3" fill="#39FF88"/>
    <circle cx="30" cy="30" r="16" fill="#39FF88"/>
    <text x="30" y="36" text-anchor="middle" font-family="ui-monospace, monospace" font-size="16" font-weight="700" fill="#0D1117">5</text>
    <text x="100" y="60" text-anchor="middle" font-family="ui-monospace, monospace" font-size="15" font-weight="700" fill="#39FF88">RESPONSE</text>
    <text x="100" y="82" text-anchor="middle" font-family="ui-monospace, monospace" font-size="11" fill="#E6EDF3">Réponse</text>
    <text x="100" y="102" text-anchor="middle" font-family="ui-monospace, monospace" font-size="9" fill="#8B949E">Isolation · Correction</text>
    <text x="100" y="116" text-anchor="middle" font-family="ui-monospace, monospace" font-size="9" fill="#8B949E">Remédiation</text>
  </g>

  <!-- Legend -->
  <g transform="translate(30, 220)">
    <text font-family="ui-monospace, monospace" font-size="11" fill="#8B949E">Légende :</text>
    <rect x="80" y="-8" width="12" height="12" rx="2" fill="#58A6FF"/><text x="98" y="2" font-size="10" fill="#8B949E">Infrastructure</text>
    <rect x="190" y="-8" width="12" height="12" rx="2" fill="#79C0FF"/><text x="208" y="2" font-size="10" fill="#8B949E">Collection</text>
    <rect x="300" y="-8" width="12" height="12" rx="2" fill="#F0883E"/><text x="318" y="2" font-size="10" fill="#8B949E">Détection</text>
    <rect x="410" y="-8" width="12" height="12" rx="2" fill="#FFD866"/><text x="428" y="2" font-size="10" fill="#8B949E">Analyse</text>
    <rect x="510" y="-8" width="12" height="12" rx="2" fill="#39FF88"/><text x="528" y="2" font-size="10" fill="#8B949E">Réponse</text>
    <circle cx="620" cy="-2" r="5" fill="#F85149"/><text x="632" y="2" font-size="10" fill="#8B949E">Alerte critique</text>
  </g>
</svg>

</div>

---

<div align="center">

### <samp>› Architecture réseau &amp; sécurité</samp>
<sub>Une infrastructure connectée et protégée</sub>

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 320" width="100%" height="320" role="img" aria-label="Architecture réseau">
  <defs>
    <linearGradient id="aBg" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0%" stop-color="#0D1117"/>
      <stop offset="100%" stop-color="#161B22"/>
    </linearGradient>
    <marker id="aArr" viewBox="0 0 10 10" refX="8" refY="5" markerWidth="6" markerHeight="6" orient="auto">
      <path d="M 0 0 L 10 5 L 0 10 z" fill="#8B949E"/>
    </marker>
  </defs>
  <rect width="1200" height="320" fill="url(#aBg)" rx="12" stroke="#30363D"/>
  
  <!-- Users -->
  <g transform="translate(30, 40)">
    <rect width="150" height="90" rx="8" fill="#161B22" stroke="#58A6FF" stroke-width="1.5"/>
    <rect width="150" height="4" rx="2" fill="#58A6FF"/>
    <text x="75" y="30" text-anchor="middle" font-family="ui-monospace, monospace" font-size="11" font-weight="700" fill="#58A6FF">UTILISATEURS</text>
    <text x="75" y="52" text-anchor="middle" font-family="ui-monospace, monospace" font-size="10" fill="#E6EDF3">Postes · Mobiles</text>
    <text x="75" y="72" text-anchor="middle" font-family="ui-monospace, monospace" font-size="9" fill="#8B949E">Accès distants</text>
  </g>
  
  <!-- Internet -->
  <g transform="translate(230, 50)">
    <circle cx="30" cy="30" r="30" fill="#161B22" stroke="#79C0FF" stroke-width="2"/>
    <text x="30" y="35" text-anchor="middle" font-family="ui-monospace, monospace" font-size="10" font-weight="700" fill="#79C0FF">WEB</text>
  </g>
  
  <!-- Firewall -->
  <g transform="translate(330, 40)">
    <rect width="180" height="90" rx="8" fill="#161B22" stroke="#F85149" stroke-width="1.5"/>
    <rect width="180" height="4" rx="2" fill="#F85149"/>
    <text x="90" y="30" text-anchor="middle" font-family="ui-monospace, monospace" font-size="11" font-weight="700" fill="#F85149">DMZ · FIREWALL</text>
    <text x="90" y="52" text-anchor="middle" font-family="ui-monospace, monospace" font-size="10" fill="#E6EDF3">WAF · IDS/IPS</text>
    <text x="90" y="72" text-anchor="middle" font-family="ui-monospace, monospace" font-size="9" fill="#8B949E">Web · Mail · DNS</text>
  </g>

  <!-- Internal -->
  <g transform="translate(560, 40)">
    <rect width="200" height="90" rx="8" fill="#161B22" stroke="#3FB950" stroke-width="1.5"/>
    <rect width="200" height="4" rx="2" fill="#3FB950"/>
    <text x="100" y="30" text-anchor="middle" font-family="ui-monospace, monospace" font-size="11" font-weight="700" fill="#3FB950">RÉSEAU INTERNE</text>
    <text x="100" y="52" text-anchor="middle" font-family="ui-monospace, monospace" font-size="10" fill="#E6EDF3">Serveurs · Applications</text>
    <text x="100" y="72" text-anchor="middle" font-family="ui-monospace, monospace" font-size="9" fill="#8B949E">Switch · Routeur</text>
  </g>

  <!-- Supervision -->
  <g transform="translate(810, 40)">
    <rect width="180" height="90" rx="8" fill="#161B22" stroke="#FFD866" stroke-width="1.5"/>
    <rect width="180" height="4" rx="2" fill="#FFD866"/>
    <text x="90" y="30" text-anchor="middle" font-family="ui-monospace, monospace" font-size="11" font-weight="700" fill="#FFD866">SUPERVISION</text>
    <text x="90" y="52" text-anchor="middle" font-family="ui-monospace, monospace" font-size="10" fill="#E6EDF3">SIEM · IDS/IPS</text>
    <text x="90" y="72" text-anchor="middle" font-family="ui-monospace, monospace" font-size="9" fill="#8B949E">Monitoring · Logs</text>
  </g>

  <!-- Arrows -->
  <line x1="185" y1="85" x2="225" y2="85" stroke="#8B949E" stroke-width="1.5" marker-end="url(#aArr)"/>
  <line x1="285" y1="85" x2="325" y2="85" stroke="#8B949E" stroke-width="1.5" marker-end="url(#aArr)"/>
  <line x1="515" y1="85" x2="555" y2="85" stroke="#8B949E" stroke-width="1.5" marker-end="url(#aArr)"/>
  <line x1="765" y1="85" x2="805" y2="85" stroke="#8B949E" stroke-width="1.5" marker-end="url(#aArr)"/>

  <!-- Bottom bar -->
  <rect x="30" y="200" width="1140" height="50" rx="8" fill="#1C2128" stroke="#79C0FF" stroke-width="1.5"/>
  <rect x="30" y="200" width="6" height="50" rx="2" fill="#79C0FF"/>
  <text x="600" y="222" text-anchor="middle" font-family="ui-monospace, monospace" font-size="12" font-weight="700" fill="#79C0FF">COLLECTE DES JOURNAUX ET ÉVÉNEMENTS</text>
  <text x="600" y="240" text-anchor="middle" font-family="ui-monospace, monospace" font-size="9" fill="#8B949E">Flux centralisé · Corrélation · Analyse temps réel</text>
  
  <line x1="420" y1="130" x2="420" y2="195" stroke="#79C0FF" stroke-width="1.5" stroke-dasharray="4 3"/>
  <line x1="660" y1="130" x2="660" y2="195" stroke="#79C0FF" stroke-width="1.5" stroke-dasharray="4 3"/>
  <line x1="900" y1="130" x2="900" y2="195" stroke="#79C0FF" stroke-width="1.5" stroke-dasharray="4 3"/>
</svg>

</div>

---

<div align="center">

### <samp>› Pipeline Machine Learning</samp>
<sub>Des données aux prédictions</sub>

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1200 260" width="100%" height="260" role="img" aria-label="Pipeline Machine Learning">
  <defs>
    <linearGradient id="mlBg" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0%" stop-color="#0D1117"/>
      <stop offset="100%" stop-color="#161B22"/>
    </linearGradient>
    <marker id="mlArr" viewBox="0 0 10 10" refX="8" refY="5" markerWidth="6" markerHeight="6" orient="auto">
      <path d="M 0 0 L 10 5 L 0 10 z" fill="#8B949E"/>
    </marker>
  </defs>
  <rect width="1200" height="260" fill="url(#mlBg)" rx="12" stroke="#30363D"/>
  
  <!-- Step 1 -->
  <g transform="translate(30, 50)">
    <rect width="200" height="120" rx="10" fill="#161B22" stroke="#A371F7" stroke-width="2"/>
    <rect width="200" height="5" rx="2" fill="#A371F7"/>
    <circle cx="30" cy="30" r="16" fill="#A371F7"/>
    <text x="30" y="36" text-anchor="middle" font-family="ui-monospace, monospace" font-size="16" font-weight="700" fill="#0D1117">1</text>
    <text x="110" y="60" text-anchor="middle" font-family="ui-monospace, monospace" font-size="13" font-weight="700" fill="#A371F7">PRÉPARATION</text>
    <text x="110" y="82" text-anchor="middle" font-family="ui-monospace, monospace" font-size="10" fill="#E6EDF3">des données</text>
    <text x="110" y="102" text-anchor="middle" font-family="ui-monospace, monospace" font-size="9" fill="#8B949E">Nettoyage · Filtres</text>
  </g>
  <line x1="235" y1="110" x2="270" y2="110" stroke="#8B949E" stroke-width="2" marker-end="url(#mlArr)"/>

  <!-- Step 2 -->
  <g transform="translate(270, 50)">
    <rect width="200" height="120" rx="10" fill="#161B22" stroke="#79C0FF" stroke-width="2"/>
    <rect width="200" height="5" rx="2" fill="#79C0FF"/>
    <circle cx="30" cy="30" r="16" fill="#79C0FF"/>
    <text x="30" y="36" text-anchor="middle" font-family="ui-monospace, monospace" font-size="16" font-weight="700" fill="#0D1117">2</text>
    <text x="110" y="60" text-anchor="middle" font-family="ui-monospace, monospace" font-size="13" font-weight="700" fill="#79C0FF">EXTRACTION</text>
    <text x="110" y="82" text-anchor="middle" font-family="ui-monospace, monospace" font-size="10" fill="#E6EDF3">Features</text>
    <text x="110" y="102" text-anchor="middle" font-family="ui-monospace, monospace" font-size="9" fill="#8B949E">Sélection · Scaling</text>
  </g>
  <line x1="475" y1="110" x2="510" y2="110" stroke="#8B949E" stroke-width="2" marker-end="url(#mlArr)"/>

  <!-- Step 3 -->
  <g transform="translate(510, 50)">
    <rect width="200" height="120" rx="10" fill="#161B22" stroke="#F0883E" stroke-width="2"/>
    <rect width="200" height="5" rx="2" fill="#F0883E"/>
    <circle cx="30" cy="30" r="16" fill="#F0883E"/>
    <text x="30" y="36" text-anchor="middle" font-family="ui-monospace, monospace" font-size="16" font-weight="700" fill="#0D1117">3</text>
    <text x="110" y="60" text-anchor="middle" font-family="ui-monospace, monospace" font-size="13" font-weight="700" fill="#F0883E">ENTRAÎNEMENT</text>
    <text x="110" y="82" text-anchor="middle" font-family="ui-monospace, monospace" font-size="10" fill="#E6EDF3">Modèles</text>
    <text x="110" y="102" text-anchor="middle" font-family="ui-monospace, monospace" font-size="9" fill="#8B949E">Validation · Tuning</text>
  </g>
  <line x1="715" y1="110" x2="750" y2="110" stroke="#8B949E" stroke-width="2" marker-end="url(#mlArr)"/>

  <!-- Step 4 -->
  <g transform="translate(750, 50)">
    <rect width="200" height="120" rx="10" fill="#161B22" stroke="#FFD866" stroke-width="2"/>
    <rect width="200" height="5" rx="2" fill="#FFD866"/>
    <circle cx="30" cy="30" r="16" fill="#FFD866"/>
    <text x="30" y="36" text-anchor="middle" font-family="ui-monospace, monospace" font-size="16" font-weight="700" fill="#0D1117">4</text>
    <text x="110" y="60" text-anchor="middle" font-family="ui-monospace, monospace" font-size="13" font-weight="700" fill="#FFD866">DÉTECTION</text>
    <text x="110" y="82" text-anchor="middle" font-family="ui-monospace, monospace" font-size="10" fill="#E6EDF3">des anomalies</text>
    <text x="110" y="102" text-anchor="middle" font-family="ui-monospace, monospace" font-size="9" fill="#8B949E">Scores · Seuils</text>
  </g>
  <line x1="955" y1="110" x2="990" y2="110" stroke="#8B949E" stroke-width="2" marker-end="url(#mlArr)"/>

  <!-- Step 5 -->
  <g transform="translate(990, 50)">
    <rect width="180" height="120" rx="10" fill="#161B22" stroke="#39FF88" stroke-width="2"/>
    <rect width="180" height="5" rx="2" fill="#39FF88"/>
    <circle cx="30" cy="30" r="16" fill="#39FF88"/>
    <text x="30" y="36" text-anchor="middle" font-family="ui-monospace, monospace" font-size="16" font-weight="700" fill="#0D1117">5</text>
    <text x="100" y="60" text-anchor="middle" font-family="ui-monospace, monospace" font-size="13" font-weight="700" fill="#39FF88">ÉVALUATION</text>
    <text x="100" y="82" text-anchor="middle" font-family="ui-monospace, monospace" font-size="10" fill="#E6EDF3">Métriques</text>
    <text x="100" y="102" text-anchor="middle" font-family="ui-monospace, monospace" font-size="9" fill="#8B949E">F1 · Précision</text>
  </g>
</svg>

</div>

---

### <samp>› Projets &amp; Réalisations</samp>

<table width="100%">
<tr>
<td width="50%" valign="top" style="background-color:#161B22; border: 1px solid #A371F7; border-radius: 8px; padding: 15px;">
<h4 style="color:#A371F7; margin:0;">🧠 Banking Anomaly Detection</h4>
<sub style="color:#8B949E;">IA · Détection de fraude</sub><br/><br/>
<sub>Détection des transactions anormales bancaires avec Machine Learning.</sub><br/><br/>
<sub><b>Stack</b> · Python · Flask · ML</sub><br/>
<sub><b>Métrique</b> · F1-score: <code>0.9632</code></sub>
</td>
<td width="50%" valign="top" style="background-color:#161B22; border: 1px solid #39FF88; border-radius: 8px; padding: 15px;">
<h4 style="color:#39FF88; margin:0;">🛡️ NeuroSecure</h4>
<sub style="color:#8B949E;">Sécurité web · IA</sub><br/><br/>
<sub>Système de protection des applications web (WAF, IDS, OTP).</sub><br/><br/>
<sub><b>Stack</b> · Flask · WAF · XGBoost</sub><br/>
<sub><b>Fonctions</b> · SQLi · XSS · Blocage IP</sub>
</td>
</tr>
<tr>
<td width="50%" valign="top" style="background-color:#161B22; border: 1px solid #58A6FF; border-radius: 8px; padding: 15px;">
<h4 style="color:#58A6FF; margin:0;">🏭 Menara CyberShield</h4>
<sub style="color:#8B949E;">Cybersécurité industrielle</sub><br/><br/>
<sub>Plateforme industrielle et gestion opérationnelle.</sub><br/><br/>
<sub><b>Stack</b> · Python · PySide6</sub><br/>
<sub><b>Fonctions</b> · Gestion stock · Suivi camions</sub>
</td>
<td width="50%" valign="top" style="background-color:#161B22; border: 1px solid #F0883E; border-radius: 8px; padding: 15px;">
<h4 style="color:#F0883E; margin:0;">⚙️ Plateforme Multi-Modules</h4>
<sub style="color:#8B949E;">Sécurité modulaire</sub><br/><br/>
<sub>Plateforme full-stack de cybersécurité avec 10 modules.</sub><br/><br/>
<sub><b>Stack</b> · Python · Flask</sub><br/>
<sub><b>Fonctions</b> · Chatbot IA · AES-256</sub>
</td>
</tr>
<tr>
<td width="50%" valign="top" style="background-color:#161B22; border: 1px solid #FFD866; border-radius: 8px; padding: 15px;">
<h4 style="color:#FFD866; margin:0;">🕵️ CyberGuard</h4>
<sub style="color:#8B949E;">Accès &amp; anti-intrusion</sub><br/><br/>
<sub>Prototype web de gestion d'accès et sécurité.</sub><br/><br/>
<sub><b>Fonctions</b> · Scan réseau · Audit logs · Auth</sub>
</td>
<td width="50%" valign="top" style="background-color:#161B22; border: 1px solid #79C0FF; border-radius: 8px; padding: 15px;">
<h4 style="color:#79C0FF; margin:0;">📊 Supervision Zabbix + IA</h4>
<sub style="color:#8B949E;">Monitoring intelligent</sub><br/><br/>
<sub>Lab de 5 VMs VirtualBox avec supervision et analyse intelligente.</sub><br/><br/>
<sub><b>Stack</b> · Zabbix · ML · Flask · React</sub>
</td>
</tr>
</table>

---

### <samp>› Expérience &amp; Formation</samp>

<table width="100%">
<tr>
<td width="50%" valign="top" style="background-color:#161B22; border: 1px solid #30363D; border-radius: 8px; padding: 15px;">
<h4 style="color:#58A6FF; margin:0;">💼 Expérience Professionnelle</h4>
<br/>
<b>Stage Technique — MORITSOFT</b><br/>
<sub style="color:#8B949E;">Avr – Jun 2026</sub><br/>
<sub>Protection applicative, détection d'intrusion, analyse comportementale.</sub><br/><br/>
<b>Stage d'Initiation — Ménara Préfa</b><br/>
<sub style="color:#8B949E;">Juin – Juil 2025</sub><br/>
<sub>Cybersécurité industrielle, gestion opérationnelle (Python/PySide6).</sub>
</td>
<td width="50%" valign="top" style="background-color:#161B22; border: 1px solid #30363D; border-radius: 8px; padding: 15px;">
<h4 style="color:#39FF88; margin:0;">🎓 Parcours Académique</h4>
<br/>
<b>Bachelor Réseaux, Cybersécurité &amp; Cloud</b><br/>
<sub style="color:#8B949E;">2026 – 2027 (en cours)</sub><br/>
<sub>ESTK · Université Cadi Ayyad</sub><br/><br/>
<b>DUT Réseaux, Cybersécurité &amp; IA</b><br/>
<sub style="color:#8B949E;">2024 – 2026 (Mention Bien)</sub><br/>
<sub>ESTK · Université Cadi Ayyad</sub>
</td>
</tr>
</table>

---

### <samp>› Contact &amp; Langues</samp>

<table width="100%">
<tr>
<td width="33%" valign="top" style="background-color:#161B22; border: 1px solid #A371F7; border-radius: 8px; padding: 15px;">
<h4 style="color:#A371F7; margin:0;">🌍 Langues</h4>
<br/>
<sub>🇲🇦 Arabe (Maternelle)</sub><br/>
<sub>🇫🇷 Français (C2)</sub><br/>
<sub>🇬🇧 Anglais (B2)</sub>
</td>
<td width="33%" valign="top" align="center" style="background-color:#161B22; border: 1px solid #39FF88; border-radius: 8px; padding: 15px;">
<h4 style="color:#39FF88; margin:0;">📬 Me Contacter</h4>
<br/>
<a href="https://github.com/waalidcyber"><img src="https://img.shields.io/badge/GitHub-waalidcyber-0D1117?style=for-the-badge&logo=github&logoColor=39FF88" alt="GitHub"/></a><br/><br/>
<a href="https://www.linkedin.com/in/walid-sabri-b01412358/"><img src="https://img.shields.io/badge/LinkedIn-Walid%20Sabri-0D1117?style=for-the-badge&logo=linkedin&logoColor=58A6FF" alt="LinkedIn"/></a><br/><br/>
<a href="mailto:w.sabri3107@uca.ac.ma"><img src="https://img.shields.io/badge/Email-w.sabri3107@uca.ac.ma-0D1117?style=for-the-badge&logo=gmail&logoColor=39FF88" alt="Email"/></a>
</td>
<td width="33%" valign="top" align="center" style="background-color:#161B22; border: 1px solid #FFD866; border-radius: 8px; padding: 15px;">
<h4 style="color:#FFD866; margin:0;">🚀 Disponibilité</h4>
<br/>
<sub>Disponible pour un <b>stage</b> en cybersécurité, sécurité des réseaux ou supervision.</sub><br/><br/>
<sub style="color:#39FF88;">● OPEN TO WORK</sub>
</td>
</tr>
</table>

---

<div align="center">
<sub><i>DES DONNÉES À LA SÉCURITÉ — DE LA THÉORIE À L'IMPACT</i></sub>
</div>
