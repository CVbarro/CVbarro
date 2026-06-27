<!--
  CVBARRO — Engineering Portfolio
  Design Language: Technical Instrumentation
  Palette: #0A0A0A · #E63946 · #FFD700 · #E0E0E0
-->

<!-- ═══════════════════════════════════════════════════════════
     HERO — Technical Blueprint Panel
     ═══════════════════════════════════════════════════════════ -->

<div align="center">
<svg width="860" height="280" viewBox="0 0 860 280" xmlns="http://www.w3.org/2000/svg">
<defs>
  <linearGradient id="hBg" x1="0" y1="0" x2="1" y2="1">
    <stop offset="0%" stop-color="#0A0A0A"/>
    <stop offset="100%" stop-color="#0f0505"/>
  </linearGradient>
  <linearGradient id="hRed" x1="0" y1="0" x2="1" y2="0">
    <stop offset="0%" stop-color="#0A0A0A" stop-opacity="0"/>
    <stop offset="20%" stop-color="#E63946"/>
    <stop offset="80%" stop-color="#E63946"/>
    <stop offset="100%" stop-color="#0A0A0A" stop-opacity="0"/>
  </linearGradient>
  <filter id="fGlow">
    <feGaussianBlur stdDeviation="2.5" result="b"/>
    <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
  </filter>
  <filter id="fSoft">
    <feGaussianBlur stdDeviation="1.2" result="b"/>
    <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
  </filter>
  <!-- Blueprint grid -->
  <pattern id="bpGrid" width="40" height="40" patternUnits="userSpaceOnUse">
    <path d="M40 0H0V40" fill="none" stroke="#E63946" stroke-width="0.15" opacity="0.08"/>
  </pattern>
  <pattern id="bpDot" width="20" height="20" patternUnits="userSpaceOnUse">
    <circle cx="10" cy="10" r="0.6" fill="#E63946" opacity="0.12"/>
  </pattern>
</defs>

<!-- Background -->
<rect width="860" height="280" fill="url(#hBg)"/>
<rect width="860" height="280" fill="url(#bpGrid)"/>
<rect width="860" height="280" fill="url(#bpDot)"/>

<!-- Top accent line -->
<rect x="0" y="0" width="860" height="2" fill="url(#hRed)"/>
<!-- Bottom accent line -->
<rect x="0" y="278" width="860" height="2" fill="url(#hRed)"/>

<!-- Left margin construction lines -->
<line x1="52" y1="0" x2="52" y2="280" stroke="#E63946" stroke-width="0.4" opacity="0.12"/>
<!-- Right margin -->
<line x1="808" y1="0" x2="808" y2="280" stroke="#E63946" stroke-width="0.4" opacity="0.12"/>
<!-- Horizontal rule top -->
<line x1="52" y1="52" x2="808" y2="52" stroke="#E63946" stroke-width="0.4" opacity="0.12"/>
<!-- Horizontal rule bottom -->
<line x1="52" y1="228" x2="808" y2="228" stroke="#E63946" stroke-width="0.4" opacity="0.12"/>

<!-- Left data panel -->
<rect x="52" y="72" width="130" height="130" fill="none" stroke="#E63946" stroke-width="0.6" opacity="0.25"/>
<line x1="52" y1="90" x2="182" y2="90" stroke="#E63946" stroke-width="0.4" opacity="0.18"/>
<text x="60" y="85" font-family="'Share Tech Mono',monospace" font-size="7.5" fill="#E63946" opacity="0.5" letter-spacing="1.5">ENGINEER</text>
<text x="60" y="108" font-family="'Share Tech Mono',monospace" font-size="7" fill="#E0E0E0" opacity="0.45">CLASS</text>
<text x="60" y="120" font-family="'Share Tech Mono',monospace" font-size="8.5" fill="#E0E0E0" opacity="0.85">Backend</text>
<text x="60" y="138" font-family="'Share Tech Mono',monospace" font-size="7" fill="#E0E0E0" opacity="0.45">ORIGIN</text>
<text x="60" y="150" font-family="'Share Tech Mono',monospace" font-size="8.5" fill="#E0E0E0" opacity="0.85">Brazil</text>
<text x="60" y="168" font-family="'Share Tech Mono',monospace" font-size="7" fill="#E0E0E0" opacity="0.45">AVAILABILITY</text>
<text x="60" y="180" font-family="'Share Tech Mono',monospace" font-size="8.5" fill="#FFD700" opacity="0.9">Open</text>

<!-- Status dot -->
<circle cx="170" cy="179" r="3.5" fill="#FFD700" opacity="0.85" filter="url(#fSoft)">
  <animate attributeName="opacity" values="0.85;0.3;0.85" dur="2.4s" repeatCount="indefinite"/>
</circle>

<!-- Right data panel -->
<rect x="678" y="72" width="130" height="130" fill="none" stroke="#E63946" stroke-width="0.6" opacity="0.25"/>
<line x1="678" y1="90" x2="808" y2="90" stroke="#E63946" stroke-width="0.4" opacity="0.18"/>
<text x="686" y="85" font-family="'Share Tech Mono',monospace" font-size="7.5" fill="#E63946" opacity="0.5" letter-spacing="1.5">STACK</text>
<text x="686" y="110" font-family="'Share Tech Mono',monospace" font-size="8" fill="#E0E0E0" opacity="0.75">Java · Spring</text>
<text x="686" y="126" font-family="'Share Tech Mono',monospace" font-size="8" fill="#E0E0E0" opacity="0.75">Python</text>
<text x="686" y="142" font-family="'Share Tech Mono',monospace" font-size="8" fill="#E0E0E0" opacity="0.75">Docker · MySQL</text>
<text x="686" y="158" font-family="'Share Tech Mono',monospace" font-size="8" fill="#E0E0E0" opacity="0.55">Go · Kotlin · JS</text>
<text x="686" y="174" font-family="'Share Tech Mono',monospace" font-size="7.5" fill="#E63946" opacity="0.5">RESEARCH</text>
<text x="686" y="188" font-family="'Share Tech Mono',monospace" font-size="8" fill="#E0E0E0" opacity="0.55">C++</text>

<!-- Center: name -->
<text x="430" y="148" font-family="'Share Tech Mono',monospace" font-size="48" font-weight="bold" fill="#E0E0E0" text-anchor="middle" filter="url(#fGlow)" letter-spacing="5">CÉSAR BARROS</text>

<!-- Underline -->
<rect x="220" y="160" width="420" height="1.5" fill="url(#hRed)"/>

<!-- Subtitle -->
<text x="430" y="182" font-family="'Share Tech Mono',monospace" font-size="11.5" fill="#E63946" text-anchor="middle" letter-spacing="3.5" filter="url(#fSoft)">BACKEND ENGINEER  ·  API ARCHITECT</text>

<!-- Corner marks TL -->
<line x1="16" y1="16" x2="36" y2="16" stroke="#E63946" stroke-width="1.2" opacity="0.5"/>
<line x1="16" y1="16" x2="16" y2="36" stroke="#E63946" stroke-width="1.2" opacity="0.5"/>
<!-- TR -->
<line x1="844" y1="16" x2="824" y2="16" stroke="#E63946" stroke-width="1.2" opacity="0.5"/>
<line x1="844" y1="16" x2="844" y2="36" stroke="#E63946" stroke-width="1.2" opacity="0.5"/>
<!-- BL -->
<line x1="16" y1="264" x2="36" y2="264" stroke="#E63946" stroke-width="1.2" opacity="0.5"/>
<line x1="16" y1="264" x2="16" y2="244" stroke="#E63946" stroke-width="1.2" opacity="0.5"/>
<!-- BR -->
<line x1="844" y1="264" x2="824" y2="264" stroke="#E63946" stroke-width="1.2" opacity="0.5"/>
<line x1="844" y1="264" x2="844" y2="244" stroke="#E63946" stroke-width="1.2" opacity="0.5"/>

<!-- Bottom label -->
<text x="430" y="248" font-family="'Share Tech Mono',monospace" font-size="8" fill="#E63946" text-anchor="middle" opacity="0.28" letter-spacing="2">DESIGNING SYSTEMS BUILT TO SURVIVE REAL-WORLD TRAFFIC</text>

<!-- Reference marks (blueprint style) -->
<text x="16" y="13" font-family="'Share Tech Mono',monospace" font-size="7" fill="#E63946" opacity="0.3">A-01</text>
<text x="844" y="13" font-family="'Share Tech Mono',monospace" font-size="7" fill="#E63946" opacity="0.3" text-anchor="end">REV.2025</text>
</svg>
</div>

<!-- Contact -->
<div align="center">
  <a href="https://www.linkedin.com/public-profile/settings?trk=d_flagship3_profile_self_view_public_profile"><img src="https://img.shields.io/badge/LinkedIn-0a0a0a?style=flat-square&logo=linkedin&logoColor=E63946"/></a>&nbsp;
  <a href="https://www.instagram.com/ounicocesar/"><img src="https://img.shields.io/badge/Instagram-0a0a0a?style=flat-square&logo=instagram&logoColor=FFD700"/></a>&nbsp;
  <a href="mailto:cesarvianabarros@gmail.com"><img src="https://img.shields.io/badge/Gmail-0a0a0a?style=flat-square&logo=gmail&logoColor=E63946"/></a>&nbsp;
  <img src="https://komarev.com/ghpvc/?username=CVbarro&style=flat-square&color=E63946&labelColor=0a0a0a&label=visitors"/>
</div>

<br/><br/>

<!-- ═══════════════════════════════════════════════════════════
     DIVIDER — Blueprint rule
     ═══════════════════════════════════════════════════════════ -->
<div align="center"><svg width="860" height="16" viewBox="0 0 860 16" xmlns="http://www.w3.org/2000/svg"><defs><linearGradient id="dr1" x1="0" y1="0" x2="1" y2="0"><stop offset="0%" stop-color="#0A0A0A" stop-opacity="0"/><stop offset="15%" stop-color="#E63946" stop-opacity="0.6"/><stop offset="50%" stop-color="#FFD700" stop-opacity="0.8"/><stop offset="85%" stop-color="#E63946" stop-opacity="0.6"/><stop offset="100%" stop-color="#0A0A0A" stop-opacity="0"/></linearGradient><filter id="df1"><feGaussianBlur stdDeviation="1" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter></defs><rect x="0" y="7" width="860" height="1" fill="url(#dr1)" opacity="0.18"/><rect x="0" y="8" width="860" height="1" fill="url(#dr1)" filter="url(#df1)"/><rect x="0" y="8" width="55" height="1" fill="url(#dr1)" opacity="0.8" filter="url(#df1)"><animateTransform attributeName="transform" type="translate" from="-55 0" to="915 0" dur="3s" repeatCount="indefinite"/></rect><rect x="424" y="4" width="12" height="8" rx="1" fill="#0A0A0A"/><line x1="427" y1="8" x2="433" y2="8" stroke="#FFD700" stroke-width="1" opacity="0.8" filter="url(#df1)"/></svg></div>

<br/>

<!-- ═══════════════════════════════════════════════════════════
     ENGINEERING APPROACH
     ═══════════════════════════════════════════════════════════ -->

<div align="center">
<svg width="860" height="100" viewBox="0 0 860 100" xmlns="http://www.w3.org/2000/svg">
<defs><filter id="fs2"><feGaussianBlur stdDeviation="1" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter></defs>
<rect width="860" height="100" fill="#0A0A0A"/>
<!-- Left vertical accent -->
<rect x="52" y="16" width="2" height="68" fill="#E63946" opacity="0.5"/>
<!-- Approach text -->
<text x="72" y="38" font-family="'Share Tech Mono',monospace" font-size="8" fill="#E63946" opacity="0.45" letter-spacing="2">ENGINEERING APPROACH</text>
<text x="72" y="58" font-family="'Share Tech Mono',monospace" font-size="12" fill="#E0E0E0" opacity="0.9">What breaks first?  How does it recover?</text>
<text x="72" y="76" font-family="'Share Tech Mono',monospace" font-size="12" fill="#E0E0E0" opacity="0.55">Who maintains this in 12 months?</text>
<!-- Right indicator -->
<rect x="790" y="36" width="18" height="2" fill="#FFD700" opacity="0.4" filter="url(#fs2)"/>
<rect x="790" y="46" width="12" height="2" fill="#FFD700" opacity="0.25"/>
<rect x="790" y="56" width="16" height="2" fill="#FFD700" opacity="0.35"/>
</svg>
</div>

<br/>

<!-- DIVIDER -->
<div align="center"><svg width="860" height="16" viewBox="0 0 860 16" xmlns="http://www.w3.org/2000/svg"><defs><linearGradient id="dr2" x1="0" y1="0" x2="1" y2="0"><stop offset="0%" stop-color="#0A0A0A" stop-opacity="0"/><stop offset="15%" stop-color="#E63946" stop-opacity="0.6"/><stop offset="50%" stop-color="#FFD700" stop-opacity="0.8"/><stop offset="85%" stop-color="#E63946" stop-opacity="0.6"/><stop offset="100%" stop-color="#0A0A0A" stop-opacity="0"/></linearGradient><filter id="df2"><feGaussianBlur stdDeviation="1" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter></defs><rect x="0" y="7" width="860" height="1" fill="url(#dr2)" opacity="0.18"/><rect x="0" y="8" width="860" height="1" fill="url(#dr2)" filter="url(#df2)"/><rect x="0" y="8" width="55" height="1" fill="url(#dr2)" opacity="0.8" filter="url(#df2)"><animateTransform attributeName="transform" type="translate" from="-55 0" to="915 0" dur="3s" repeatCount="indefinite"/></rect><rect x="424" y="4" width="12" height="8" rx="1" fill="#0A0A0A"/><line x1="427" y1="8" x2="433" y2="8" stroke="#FFD700" stroke-width="1" opacity="0.8" filter="url(#df2)"/></svg></div>

<br/>

<!-- ═══════════════════════════════════════════════════════════
     SYSTEM ARCHITECTURE — API Flow Diagram
     ═══════════════════════════════════════════════════════════ -->

<div align="center">
<svg width="860" height="200" viewBox="0 0 860 200" xmlns="http://www.w3.org/2000/svg">
<defs>
  <marker id="arr" markerWidth="6" markerHeight="6" refX="5" refY="3" orient="auto">
    <path d="M0,0 L0,6 L6,3 Z" fill="#E63946" opacity="0.6"/>
  </marker>
  <marker id="arrG" markerWidth="6" markerHeight="6" refX="5" refY="3" orient="auto">
    <path d="M0,0 L0,6 L6,3 Z" fill="#FFD700" opacity="0.5"/>
  </marker>
  <filter id="fs3"><feGaussianBlur stdDeviation="1.2" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
</defs>
<rect width="860" height="200" fill="#0A0A0A"/>
<rect x="0" y="0" width="860" height="1" fill="#E63946" opacity="0.12"/>
<rect x="0" y="199" width="860" height="1" fill="#E63946" opacity="0.12"/>

<!-- Label -->
<text x="52" y="22" font-family="'Share Tech Mono',monospace" font-size="8" fill="#E63946" opacity="0.4" letter-spacing="2">SYSTEM TOPOLOGY</text>

<!-- Node: Client -->
<rect x="40" y="72" width="90" height="40" rx="2" fill="#0A0A0A" stroke="#E63946" stroke-width="0.8" opacity="0.8"/>
<text x="85" y="88" font-family="'Share Tech Mono',monospace" font-size="8" fill="#E0E0E0" text-anchor="middle" opacity="0.7">CLIENT</text>
<text x="85" y="102" font-family="'Share Tech Mono',monospace" font-size="7" fill="#E63946" text-anchor="middle" opacity="0.5">HTTP/REST</text>

<!-- Arrow Client → API -->
<line x1="130" y1="92" x2="188" y2="92" stroke="#E63946" stroke-width="0.8" opacity="0.5" marker-end="url(#arr)"/>
<text x="159" y="87" font-family="'Share Tech Mono',monospace" font-size="6.5" fill="#E63946" text-anchor="middle" opacity="0.35">JSON</text>

<!-- Node: API Gateway -->
<rect x="190" y="60" width="100" height="64" rx="2" fill="#0A0A0A" stroke="#E63946" stroke-width="1.2" opacity="0.9" filter="url(#fs3)"/>
<rect x="190" y="60" width="100" height="10" rx="2" fill="#E63946" opacity="0.15"/>
<text x="240" y="82" font-family="'Share Tech Mono',monospace" font-size="8" fill="#E63946" text-anchor="middle" opacity="0.9">SPRING</text>
<text x="240" y="95" font-family="'Share Tech Mono',monospace" font-size="7.5" fill="#E0E0E0" text-anchor="middle" opacity="0.75">REST API</text>
<text x="240" y="108" font-family="'Share Tech Mono',monospace" font-size="6.5" fill="#E0E0E0" text-anchor="middle" opacity="0.4">Java · JWT</text>

<!-- Arrow API → Auth -->
<line x1="290" y1="78" x2="348" y2="58" stroke="#E63946" stroke-width="0.7" opacity="0.4" marker-end="url(#arr)" stroke-dasharray="4,2"/>

<!-- Node: Auth -->
<rect x="350" y="38" width="90" height="38" rx="2" fill="#0A0A0A" stroke="#E63946" stroke-width="0.7" opacity="0.6"/>
<text x="395" y="54" font-family="'Share Tech Mono',monospace" font-size="7.5" fill="#E0E0E0" text-anchor="middle" opacity="0.65">AUTH</text>
<text x="395" y="67" font-family="'Share Tech Mono',monospace" font-size="6.5" fill="#E63946" text-anchor="middle" opacity="0.45">JWT · OAuth</text>

<!-- Arrow API → Service -->
<line x1="290" y1="92" x2="348" y2="92" stroke="#E63946" stroke-width="0.8" opacity="0.5" marker-end="url(#arr)"/>

<!-- Node: Business Logic -->
<rect x="350" y="72" width="100" height="40" rx="2" fill="#0A0A0A" stroke="#E63946" stroke-width="0.9" opacity="0.75"/>
<text x="400" y="89" font-family="'Share Tech Mono',monospace" font-size="7.5" fill="#E0E0E0" text-anchor="middle" opacity="0.75">SERVICES</text>
<text x="400" y="102" font-family="'Share Tech Mono',monospace" font-size="6.5" fill="#E63946" text-anchor="middle" opacity="0.45">Business Logic</text>

<!-- Arrow API → Cache -->
<line x1="290" y1="108" x2="348" y2="130" stroke="#E63946" stroke-width="0.7" opacity="0.4" marker-end="url(#arr)" stroke-dasharray="4,2"/>

<!-- Node: Cache -->
<rect x="350" y="118" width="90" height="38" rx="2" fill="#0A0A0A" stroke="#FFD700" stroke-width="0.7" opacity="0.45"/>
<text x="395" y="134" font-family="'Share Tech Mono',monospace" font-size="7.5" fill="#E0E0E0" text-anchor="middle" opacity="0.55">CACHE</text>
<text x="395" y="147" font-family="'Share Tech Mono',monospace" font-size="6.5" fill="#FFD700" text-anchor="middle" opacity="0.4">Redis</text>

<!-- Arrow Service → DB -->
<line x1="450" y1="92" x2="508" y2="92" stroke="#FFD700" stroke-width="0.8" opacity="0.4" marker-end="url(#arrG)"/>

<!-- Node: Database -->
<rect x="510" y="60" width="100" height="64" rx="2" fill="#0A0A0A" stroke="#FFD700" stroke-width="1" opacity="0.7" filter="url(#fs3)"/>
<rect x="510" y="60" width="100" height="10" rx="2" fill="#FFD700" opacity="0.08"/>
<text x="560" y="82" font-family="'Share Tech Mono',monospace" font-size="8" fill="#FFD700" text-anchor="middle" opacity="0.9">DATABASE</text>
<text x="560" y="95" font-family="'Share Tech Mono',monospace" font-size="7.5" fill="#E0E0E0" text-anchor="middle" opacity="0.7">MySQL</text>
<text x="560" y="108" font-family="'Share Tech Mono',monospace" font-size="6.5" fill="#E0E0E0" text-anchor="middle" opacity="0.4">Docker</text>

<!-- Arrow DB → Monitor -->
<line x1="610" y1="92" x2="668" y2="92" stroke="#FFD700" stroke-width="0.7" opacity="0.35" marker-end="url(#arrG)" stroke-dasharray="4,2"/>

<!-- Node: Monitoring -->
<rect x="670" y="72" width="100" height="40" rx="2" fill="#0A0A0A" stroke="#E63946" stroke-width="0.6" opacity="0.5"/>
<text x="720" y="89" font-family="'Share Tech Mono',monospace" font-size="7.5" fill="#E0E0E0" text-anchor="middle" opacity="0.55">MONITORING</text>
<text x="720" y="102" font-family="'Share Tech Mono',monospace" font-size="6.5" fill="#E63946" text-anchor="middle" opacity="0.4">Logs · Metrics</text>

<!-- Legend -->
<line x1="52" y1="172" x2="80" y2="172" stroke="#E63946" stroke-width="0.8" opacity="0.5"/>
<text x="86" y="176" font-family="'Share Tech Mono',monospace" font-size="7" fill="#E63946" opacity="0.4">primary flow</text>
<line x1="180" y1="172" x2="208" y2="172" stroke="#E63946" stroke-width="0.7" opacity="0.4" stroke-dasharray="4,2"/>
<text x="214" y="176" font-family="'Share Tech Mono',monospace" font-size="7" fill="#E63946" opacity="0.4">secondary</text>
<line x1="310" y1="172" x2="338" y2="172" stroke="#FFD700" stroke-width="0.8" opacity="0.4"/>
<text x="344" y="176" font-family="'Share Tech Mono',monospace" font-size="7" fill="#FFD700" opacity="0.4">data layer</text>
</svg>
</div>

<br/>

<!-- DIVIDER -->
<div align="center"><svg width="860" height="16" viewBox="0 0 860 16" xmlns="http://www.w3.org/2000/svg"><defs><linearGradient id="dr3" x1="0" y1="0" x2="1" y2="0"><stop offset="0%" stop-color="#0A0A0A" stop-opacity="0"/><stop offset="15%" stop-color="#E63946" stop-opacity="0.6"/><stop offset="50%" stop-color="#FFD700" stop-opacity="0.8"/><stop offset="85%" stop-color="#E63946" stop-opacity="0.6"/><stop offset="100%" stop-color="#0A0A0A" stop-opacity="0"/></linearGradient><filter id="df3"><feGaussianBlur stdDeviation="1" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter></defs><rect x="0" y="7" width="860" height="1" fill="url(#dr3)" opacity="0.18"/><rect x="0" y="8" width="860" height="1" fill="url(#dr3)" filter="url(#df3)"/><rect x="0" y="8" width="55" height="1" fill="url(#dr3)" opacity="0.8" filter="url(#df3)"><animateTransform attributeName="transform" type="translate" from="-55 0" to="915 0" dur="3s" repeatCount="indefinite"/></rect><rect x="424" y="4" width="12" height="8" rx="1" fill="#0A0A0A"/><line x1="427" y1="8" x2="433" y2="8" stroke="#FFD700" stroke-width="1" opacity="0.8" filter="url(#df3)"/></svg></div>

<br/>

<!-- ═══════════════════════════════════════════════════════════
     COMPETENCY MATRIX
     ═══════════════════════════════════════════════════════════ -->

<div align="center">
<svg width="860" height="210" viewBox="0 0 860 210" xmlns="http://www.w3.org/2000/svg">
<defs>
  <linearGradient id="bRed" x1="0" y1="0" x2="1" y2="0">
    <stop offset="0%" stop-color="#E63946"/>
    <stop offset="100%" stop-color="#6b0f17"/>
  </linearGradient>
  <linearGradient id="bGold" x1="0" y1="0" x2="1" y2="0">
    <stop offset="0%" stop-color="#FFD700"/>
    <stop offset="100%" stop-color="#7a6200"/>
  </linearGradient>
  <linearGradient id="bGrey" x1="0" y1="0" x2="1" y2="0">
    <stop offset="0%" stop-color="#444444"/>
    <stop offset="100%" stop-color="#222222"/>
  </linearGradient>
  <filter id="fs4"><feGaussianBlur stdDeviation="0.8" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
</defs>
<rect width="860" height="210" fill="#0A0A0A"/>
<rect x="0" y="0" width="860" height="1" fill="#E63946" opacity="0.12"/>
<rect x="0" y="209" width="860" height="1" fill="#E63946" opacity="0.12"/>

<!-- Header -->
<text x="52" y="22" font-family="'Share Tech Mono',monospace" font-size="8" fill="#E63946" opacity="0.4" letter-spacing="2">COMPETENCY MATRIX</text>

<!-- COL 1 — Backend -->
<text x="52" y="44" font-family="'Share Tech Mono',monospace" font-size="7.5" fill="#E63946" opacity="0.55" letter-spacing="1">BACKEND</text>
<!-- Java -->
<text x="52" y="62" font-family="'Share Tech Mono',monospace" font-size="9" fill="#E0E0E0" opacity="0.85">Java</text>
<rect x="52" y="65" width="170" height="4" rx="1" fill="#1a1a1a"/>
<rect x="52" y="65" width="160" height="4" rx="1" fill="url(#bRed)" filter="url(#fs4)"/>
<!-- Spring Boot -->
<text x="52" y="84" font-family="'Share Tech Mono',monospace" font-size="9" fill="#E0E0E0" opacity="0.85">Spring Boot</text>
<rect x="52" y="87" width="170" height="4" rx="1" fill="#1a1a1a"/>
<rect x="52" y="87" width="152" height="4" rx="1" fill="url(#bRed)" filter="url(#fs4)"/>
<!-- Python -->
<text x="52" y="106" font-family="'Share Tech Mono',monospace" font-size="9" fill="#E0E0E0" opacity="0.85">Python</text>
<rect x="52" y="109" width="170" height="4" rx="1" fill="#1a1a1a"/>
<rect x="52" y="109" width="138" height="4" rx="1" fill="url(#bRed)" filter="url(#fs4)"/>
<!-- REST APIs -->
<text x="52" y="128" font-family="'Share Tech Mono',monospace" font-size="9" fill="#E0E0E0" opacity="0.85">REST APIs</text>
<rect x="52" y="131" width="170" height="4" rx="1" fill="#1a1a1a"/>
<rect x="52" y="131" width="165" height="4" rx="1" fill="url(#bRed)" filter="url(#fs4)"/>

<!-- COL 2 — Infra -->
<text x="270" y="44" font-family="'Share Tech Mono',monospace" font-size="7.5" fill="#FFD700" opacity="0.55" letter-spacing="1">INFRASTRUCTURE</text>
<text x="270" y="62" font-family="'Share Tech Mono',monospace" font-size="9" fill="#E0E0E0" opacity="0.85">MySQL</text>
<rect x="270" y="65" width="170" height="4" rx="1" fill="#1a1a1a"/>
<rect x="270" y="65" width="145" height="4" rx="1" fill="url(#bGold)" filter="url(#fs4)"/>
<text x="270" y="84" font-family="'Share Tech Mono',monospace" font-size="9" fill="#E0E0E0" opacity="0.85">Docker</text>
<rect x="270" y="87" width="170" height="4" rx="1" fill="#1a1a1a"/>
<rect x="270" y="87" width="152" height="4" rx="1" fill="url(#bGold)" filter="url(#fs4)"/>
<text x="270" y="106" font-family="'Share Tech Mono',monospace" font-size="9" fill="#E0E0E0" opacity="0.85">Git</text>
<rect x="270" y="109" width="170" height="4" rx="1" fill="#1a1a1a"/>
<rect x="270" y="109" width="165" height="4" rx="1" fill="url(#bGold)" filter="url(#fs4)"/>

<!-- COL 3 — Frontend -->
<text x="488" y="44" font-family="'Share Tech Mono',monospace" font-size="7.5" fill="#E0E0E0" opacity="0.35" letter-spacing="1">FRONTEND</text>
<text x="488" y="62" font-family="'Share Tech Mono',monospace" font-size="9" fill="#E0E0E0" opacity="0.65">React</text>
<rect x="488" y="65" width="170" height="4" rx="1" fill="#1a1a1a"/>
<rect x="488" y="65" width="88" height="4" rx="1" fill="url(#bGrey)" filter="url(#fs4)"/>
<text x="488" y="84" font-family="'Share Tech Mono',monospace" font-size="9" fill="#E0E0E0" opacity="0.65">JavaScript</text>
<rect x="488" y="87" width="170" height="4" rx="1" fill="#1a1a1a"/>
<rect x="488" y="87" width="105" height="4" rx="1" fill="url(#bGrey)" filter="url(#fs4)"/>
<text x="488" y="106" font-family="'Share Tech Mono',monospace" font-size="9" fill="#E0E0E0" opacity="0.65">HTML · CSS</text>
<rect x="488" y="109" width="170" height="4" rx="1" fill="#1a1a1a"/>
<rect x="488" y="109" width="118" height="4" rx="1" fill="url(#bGrey)" filter="url(#fs4)"/>

<!-- COL 4 — Research -->
<text x="706" y="44" font-family="'Share Tech Mono',monospace" font-size="7.5" fill="#E63946" opacity="0.35" letter-spacing="1">RESEARCH</text>
<text x="706" y="62" font-family="'Share Tech Mono',monospace" font-size="9" fill="#E0E0E0" opacity="0.5">Kotlin</text>
<rect x="706" y="65" width="130" height="4" rx="1" fill="#1a1a1a"/>
<rect x="706" y="65" width="72" height="4" rx="1" fill="url(#bGrey)" filter="url(#fs4)"/>
<text x="706" y="84" font-family="'Share Tech Mono',monospace" font-size="9" fill="#E0E0E0" opacity="0.5">Go</text>
<rect x="706" y="87" width="130" height="4" rx="1" fill="#1a1a1a"/>
<rect x="706" y="87" width="58" height="4" rx="1" fill="url(#bGrey)" filter="url(#fs4)"/>
<text x="706" y="106" font-family="'Share Tech Mono',monospace" font-size="9" fill="#E0E0E0" opacity="0.5">C++</text>
<rect x="706" y="109" width="130" height="4" rx="1" fill="#1a1a1a"/>
<rect x="706" y="109" width="36" height="4" rx="1" fill="#E63946" opacity="0.3"/>
<text x="706" y="120" font-family="'Share Tech Mono',monospace" font-size="6.5" fill="#E63946" opacity="0.35">in progress</text>

<!-- Legend -->
<rect x="52" y="178" width="8" height="4" rx="1" fill="url(#bRed)"/>
<text x="66" y="183" font-family="'Share Tech Mono',monospace" font-size="7" fill="#E63946" opacity="0.4">primary</text>
<rect x="140" y="178" width="8" height="4" rx="1" fill="url(#bGold)"/>
<text x="154" y="183" font-family="'Share Tech Mono',monospace" font-size="7" fill="#FFD700" opacity="0.4">infrastructure</text>
<rect x="260" y="178" width="8" height="4" rx="1" fill="url(#bGrey)"/>
<text x="274" y="183" font-family="'Share Tech Mono',monospace" font-size="7" fill="#E0E0E0" opacity="0.3">secondary</text>
</svg>
</div>

<br/>

<!-- DIVIDER -->
<div align="center"><svg width="860" height="16" viewBox="0 0 860 16" xmlns="http://www.w3.org/2000/svg"><defs><linearGradient id="dr4" x1="0" y1="0" x2="1" y2="0"><stop offset="0%" stop-color="#0A0A0A" stop-opacity="0"/><stop offset="15%" stop-color="#E63946" stop-opacity="0.6"/><stop offset="50%" stop-color="#FFD700" stop-opacity="0.8"/><stop offset="85%" stop-color="#E63946" stop-opacity="0.6"/><stop offset="100%" stop-color="#0A0A0A" stop-opacity="0"/></linearGradient><filter id="df4"><feGaussianBlur stdDeviation="1" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter></defs><rect x="0" y="7" width="860" height="1" fill="url(#dr4)" opacity="0.18"/><rect x="0" y="8" width="860" height="1" fill="url(#dr4)" filter="url(#df4)"/><rect x="0" y="8" width="55" height="1" fill="url(#dr4)" opacity="0.8" filter="url(#df4)"><animateTransform attributeName="transform" type="translate" from="-55 0" to="915 0" dur="3s" repeatCount="indefinite"/></rect><rect x="424" y="4" width="12" height="8" rx="1" fill="#0A0A0A"/><line x1="427" y1="8" x2="433" y2="8" stroke="#FFD700" stroke-width="1" opacity="0.8" filter="url(#df4)"/></svg></div>

<br/>

<!-- ═══════════════════════════════════════════════════════════
     ENGINEERING PRINCIPLES
     ═══════════════════════════════════════════════════════════ -->

<div align="center">
<svg width="860" height="80" viewBox="0 0 860 80" xmlns="http://www.w3.org/2000/svg">
<defs><filter id="fs5"><feGaussianBlur stdDeviation="1" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter></defs>
<rect width="860" height="80" fill="#0A0A0A"/>
<rect x="0" y="0" width="860" height="1" fill="#E63946" opacity="0.1"/>
<rect x="0" y="79" width="860" height="1" fill="#E63946" opacity="0.1"/>
<text x="430" y="18" font-family="'Share Tech Mono',monospace" font-size="7.5" fill="#E63946" text-anchor="middle" opacity="0.35" letter-spacing="2">ENGINEERING PRINCIPLES</text>
<!-- Row 1 -->
<circle cx="62" cy="36" r="2" fill="#FFD700" opacity="0.7" filter="url(#fs5)"/>
<text x="72" y="40" font-family="'Share Tech Mono',monospace" font-size="9.5" fill="#E0E0E0" opacity="0.75">Simplicity</text>
<circle cx="192" cy="36" r="2" fill="#FFD700" opacity="0.7" filter="url(#fs5)"/>
<text x="202" y="40" font-family="'Share Tech Mono',monospace" font-size="9.5" fill="#E0E0E0" opacity="0.75">Observability</text>
<circle cx="352" cy="36" r="2" fill="#FFD700" opacity="0.7" filter="url(#fs5)"/>
<text x="362" y="40" font-family="'Share Tech Mono',monospace" font-size="9.5" fill="#E0E0E0" opacity="0.75">Scalability</text>
<circle cx="502" cy="36" r="2" fill="#FFD700" opacity="0.7" filter="url(#fs5)"/>
<text x="512" y="40" font-family="'Share Tech Mono',monospace" font-size="9.5" fill="#E0E0E0" opacity="0.75">Maintainability</text>
<!-- Row 2 -->
<circle cx="62" cy="60" r="2" fill="#FFD700" opacity="0.5" filter="url(#fs5)"/>
<text x="72" y="64" font-family="'Share Tech Mono',monospace" font-size="9.5" fill="#E0E0E0" opacity="0.5">Testing</text>
<circle cx="192" cy="60" r="2" fill="#FFD700" opacity="0.5" filter="url(#fs5)"/>
<text x="202" y="64" font-family="'Share Tech Mono',monospace" font-size="9.5" fill="#E0E0E0" opacity="0.5">Documentation</text>
<circle cx="352" cy="60" r="2" fill="#FFD700" opacity="0.5" filter="url(#fs5)"/>
<text x="362" y="64" font-family="'Share Tech Mono',monospace" font-size="9.5" fill="#E0E0E0" opacity="0.5">Automation</text>
<circle cx="502" cy="60" r="2" fill="#FFD700" opacity="0.5" filter="url(#fs5)"/>
<text x="512" y="64" font-family="'Share Tech Mono',monospace" font-size="9.5" fill="#E0E0E0" opacity="0.5">Performance</text>
</svg>
</div>

<br/>

<!-- DIVIDER -->
<div align="center"><svg width="860" height="16" viewBox="0 0 860 16" xmlns="http://www.w3.org/2000/svg"><defs><linearGradient id="dr5" x1="0" y1="0" x2="1" y2="0"><stop offset="0%" stop-color="#0A0A0A" stop-opacity="0"/><stop offset="15%" stop-color="#E63946" stop-opacity="0.6"/><stop offset="50%" stop-color="#FFD700" stop-opacity="0.8"/><stop offset="85%" stop-color="#E63946" stop-opacity="0.6"/><stop offset="100%" stop-color="#0A0A0A" stop-opacity="0"/></linearGradient><filter id="df5"><feGaussianBlur stdDeviation="1" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter></defs><rect x="0" y="7" width="860" height="1" fill="url(#dr5)" opacity="0.18"/><rect x="0" y="8" width="860" height="1" fill="url(#dr5)" filter="url(#df5)"/><rect x="0" y="8" width="55" height="1" fill="url(#dr5)" opacity="0.8" filter="url(#df5)"><animateTransform attributeName="transform" type="translate" from="-55 0" to="915 0" dur="3s" repeatCount="indefinite"/></rect><rect x="424" y="4" width="12" height="8" rx="1" fill="#0A0A0A"/><line x1="427" y1="8" x2="433" y2="8" stroke="#FFD700" stroke-width="1" opacity="0.8" filter="url(#df5)"/></svg></div>

<br/>

<!-- ═══════════════════════════════════════════════════════════
     DEVELOPMENT TIMELINE
     ═══════════════════════════════════════════════════════════ -->

<div align="center">
<svg width="860" height="110" viewBox="0 0 860 110" xmlns="http://www.w3.org/2000/svg">
<defs><filter id="fs6"><feGaussianBlur stdDeviation="1.2" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter></defs>
<rect width="860" height="110" fill="#0A0A0A"/>
<rect x="0" y="0" width="860" height="1" fill="#E63946" opacity="0.1"/>
<rect x="0" y="109" width="860" height="1" fill="#E63946" opacity="0.1"/>
<text x="52" y="22" font-family="'Share Tech Mono',monospace" font-size="7.5" fill="#E63946" opacity="0.35" letter-spacing="2">DEVELOPMENT TIMELINE</text>
<!-- Spine -->
<line x1="72" y1="62" x2="808" y2="62" stroke="#E63946" stroke-width="0.6" opacity="0.2"/>
<!-- Tick marks -->
<line x1="100" y1="56" x2="100" y2="68" stroke="#E63946" stroke-width="0.8" opacity="0.5"/>
<line x1="240" y1="56" x2="240" y2="68" stroke="#E63946" stroke-width="0.8" opacity="0.5"/>
<line x1="380" y1="56" x2="380" y2="68" stroke="#E63946" stroke-width="0.8" opacity="0.6"/>
<line x1="520" y1="56" x2="520" y2="68" stroke="#FFD700" stroke-width="1" opacity="0.6" filter="url(#fs6)"/>
<line x1="660" y1="56" x2="660" y2="68" stroke="#FFD700" stroke-width="1" opacity="0.6" filter="url(#fs6)"/>
<line x1="790" y1="56" x2="790" y2="68" stroke="#E63946" stroke-width="0.6" opacity="0.3"/>
<!-- Nodes -->
<circle cx="100" cy="62" r="4" fill="#E63946" opacity="0.75"/>
<circle cx="240" cy="62" r="4" fill="#E63946" opacity="0.75"/>
<circle cx="380" cy="62" r="5" fill="#E63946" filter="url(#fs6)"/>
<circle cx="520" cy="62" r="5" fill="#FFD700" filter="url(#fs6)"/>
<circle cx="660" cy="62" r="5" fill="#FFD700" filter="url(#fs6)"/>
<circle cx="790" cy="62" r="3.5" fill="#E63946" opacity="0.3"/>
<!-- Labels top -->
<text x="100" y="46" font-family="'Share Tech Mono',monospace" font-size="7.5" fill="#E63946" text-anchor="middle" opacity="0.7">2021</text>
<text x="100" y="36" font-family="'Share Tech Mono',monospace" font-size="7" fill="#E0E0E0" text-anchor="middle" opacity="0.55">Python</text>
<text x="240" y="46" font-family="'Share Tech Mono',monospace" font-size="7.5" fill="#E63946" text-anchor="middle" opacity="0.7">2022</text>
<text x="240" y="36" font-family="'Share Tech Mono',monospace" font-size="7" fill="#E0E0E0" text-anchor="middle" opacity="0.55">Java · SQL</text>
<text x="380" y="46" font-family="'Share Tech Mono',monospace" font-size="7.5" fill="#E63946" text-anchor="middle" opacity="0.85">2023</text>
<text x="380" y="36" font-family="'Share Tech Mono',monospace" font-size="7" fill="#E0E0E0" text-anchor="middle" opacity="0.7">Spring Boot</text>
<!-- Labels bottom -->
<text x="520" y="80" font-family="'Share Tech Mono',monospace" font-size="7.5" fill="#FFD700" text-anchor="middle" opacity="0.85">2024</text>
<text x="520" y="92" font-family="'Share Tech Mono',monospace" font-size="7" fill="#E0E0E0" text-anchor="middle" opacity="0.7">Docker · APIs</text>
<text x="660" y="80" font-family="'Share Tech Mono',monospace" font-size="7.5" fill="#FFD700" text-anchor="middle" opacity="0.85">2025</text>
<text x="660" y="92" font-family="'Share Tech Mono',monospace" font-size="7" fill="#E0E0E0" text-anchor="middle" opacity="0.7">Microservices</text>
<text x="790" y="80" font-family="'Share Tech Mono',monospace" font-size="7.5" fill="#E63946" text-anchor="middle" opacity="0.4">2026</text>
<text x="790" y="92" font-family="'Share Tech Mono',monospace" font-size="7" fill="#E0E0E0" text-anchor="middle" opacity="0.35">C++ · Systems</text>
</svg>
</div>

<br/>

<!-- DIVIDER -->
<div align="center"><svg width="860" height="16" viewBox="0 0 860 16" xmlns="http://www.w3.org/2000/svg"><defs><linearGradient id="dr6" x1="0" y1="0" x2="1" y2="0"><stop offset="0%" stop-color="#0A0A0A" stop-opacity="0"/><stop offset="15%" stop-color="#E63946" stop-opacity="0.6"/><stop offset="50%" stop-color="#FFD700" stop-opacity="0.8"/><stop offset="85%" stop-color="#E63946" stop-opacity="0.6"/><stop offset="100%" stop-color="#0A0A0A" stop-opacity="0"/></linearGradient><filter id="df6"><feGaussianBlur stdDeviation="1" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter></defs><rect x="0" y="7" width="860" height="1" fill="url(#dr6)" opacity="0.18"/><rect x="0" y="8" width="860" height="1" fill="url(#dr6)" filter="url(#df6)"/><rect x="0" y="8" width="55" height="1" fill="url(#dr6)" opacity="0.8" filter="url(#df6)"><animateTransform attributeName="transform" type="translate" from="-55 0" to="915 0" dur="3s" repeatCount="indefinite"/></rect><rect x="424" y="4" width="12" height="8" rx="1" fill="#0A0A0A"/><line x1="427" y1="8" x2="433" y2="8" stroke="#FFD700" stroke-width="1" opacity="0.8" filter="url(#df6)"/></svg></div>

<br/>

<!-- ═══════════════════════════════════════════════════════════
     METRICS
     ═══════════════════════════════════════════════════════════ -->

<div align="center">
  <img height="158" src="https://github-readme-stats.vercel.app/api?username=CVbarro&show_icons=true&hide_border=true&count_private=true&bg_color=0a0a0a&title_color=e63946&icon_color=ffd700&text_color=e0e0e0&ring_color=e63946&rank_icon=github"/>
  <img height="158" src="https://github-readme-stats.vercel.app/api/top-langs/?username=CVbarro&layout=compact&hide_border=true&bg_color=0a0a0a&title_color=e63946&text_color=e0e0e0&langs_count=8"/>
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=CVbarro&hide_border=true&background=0a0a0a&stroke=e63946&ring=ffd700&fire=e63946&currStreakLabel=ffd700&sideLabels=e0e0e0&dates=444444&sideNums=e63946&currStreakNum=ffd700"/>
</div>

<!-- DIVIDER -->
<div align="center"><svg width="860" height="16" viewBox="0 0 860 16" xmlns="http://www.w3.org/2000/svg"><defs><linearGradient id="dr7" x1="0" y1="0" x2="1" y2="0"><stop offset="0%" stop-color="#0A0A0A" stop-opacity="0"/><stop offset="15%" stop-color="#E63946" stop-opacity="0.6"/><stop offset="50%" stop-color="#FFD700" stop-opacity="0.8"/><stop offset="85%" stop-color="#E63946" stop-opacity="0.6"/><stop offset="100%" stop-color="#0A0A0A" stop-opacity="0"/></linearGradient><filter id="df7"><feGaussianBlur stdDeviation="1" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter></defs><rect x="0" y="7" width="860" height="1" fill="url(#dr7)" opacity="0.18"/><rect x="0" y="8" width="860" height="1" fill="url(#dr7)" filter="url(#df7)"/><rect x="0" y="8" width="55" height="1" fill="url(#dr7)" opacity="0.8" filter="url(#df7)"><animateTransform attributeName="transform" type="translate" from="-55 0" to="915 0" dur="3s" repeatCount="indefinite"/></rect><rect x="424" y="4" width="12" height="8" rx="1" fill="#0A0A0A"/><line x1="427" y1="8" x2="433" y2="8" stroke="#FFD700" stroke-width="1" opacity="0.8" filter="url(#df7)"/></svg></div>

<br/>

<!-- Snake -->
<div align="center">
  <img src="https://raw.githubusercontent.com/CVbarro/CVbarro/output/github-contribution-grid-snake-dark.svg"/>
</div>

<br/>

<!-- ═══════════════════════════════════════════════════════════
     FOOTER
     ═══════════════════════════════════════════════════════════ -->

<div align="center">
<svg width="860" height="48" viewBox="0 0 860 48" xmlns="http://www.w3.org/2000/svg">
<defs>
  <linearGradient id="ftBg" x1="0" y1="0" x2="0" y2="1">
    <stop offset="0%" stop-color="#0A0A0A"/>
    <stop offset="100%" stop-color="#0d0101"/>
  </linearGradient>
  <linearGradient id="ftL" x1="0" y1="0" x2="1" y2="0">
    <stop offset="0%" stop-color="#0A0A0A" stop-opacity="0"/>
    <stop offset="20%" stop-color="#E63946" stop-opacity="0.6"/>
    <stop offset="80%" stop-color="#E63946" stop-opacity="0.6"/>
    <stop offset="100%" stop-color="#0A0A0A" stop-opacity="0"/>
  </linearGradient>
</defs>
<rect width="860" height="48" fill="url(#ftBg)"/>
<rect x="0" y="0" width="860" height="1.5" fill="url(#ftL)"/>
<text x="430" y="30" font-family="'Share Tech Mono',monospace" font-size="9" fill="#E63946" text-anchor="middle" opacity="0.25" letter-spacing="2">CVBARRO  ·  BACKEND ENGINEER  ·  BRAZIL  ·  2025</text>
</svg>
</div>
