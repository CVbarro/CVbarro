<!--
╔══════════════════════════════════════════════════════════════════╗
║  CVBARRO.OS — Engineering Portfolio                              ║
║  Design System: Engineering Console                              ║
║  Palette: #0a0a0a · #e63946 · #ffd700 · #e0e0e0                 ║
║  All SVGs custom-built. Zero third-party visual components.      ║
╚══════════════════════════════════════════════════════════════════╝
-->

<!-- ░░░░░░░░░░░░░░░░░  BOOT SEQUENCE  ░░░░░░░░░░░░░░░░░░░░░░░░░░ -->

<div align="center">

```console
╔═══════════════════════════════════════════════════════════╗
║         CVBARRO.OS  ·  v2.0  ·  ENGINEERING CONSOLE      ║
╠═══════════════════════════════════════════════════════════╣
║  [ SYS ] Kernel boot sequence................ COMPLETE   ║
║  [ NET ] Network stack initialized........... ONLINE     ║
║  [ ENV ] Build environment loaded............ READY      ║
║  [ API ] REST interface layer................ ACTIVE     ║
║  [ DB  ] Database connections verified....... STABLE     ║
╠═══════════════════════════════════════════════════════════╣
║  [ RDY ] Engineering console ready.                       ║
║          Welcome, operator.                               ║
╚═══════════════════════════════════════════════════════════╝
```

</div>

<!-- ░░░░░░░░░░░░░░░░░  HERO BANNER  ░░░░░░░░░░░░░░░░░░░░░░░░░░░░ -->

<div align="center">
<svg width="860" height="260" viewBox="0 0 860 260" xmlns="http://www.w3.org/2000/svg">
<defs>
  <linearGradient id="bgH" x1="0" y1="0" x2="1" y2="1"><stop offset="0%" stop-color="#0a0a0a"/><stop offset="45%" stop-color="#130000"/><stop offset="100%" stop-color="#0a0a0a"/></linearGradient>
  <linearGradient id="lR" x1="0" y1="0" x2="1" y2="0"><stop offset="0%" stop-color="#0a0a0a" stop-opacity="0"/><stop offset="15%" stop-color="#e63946"/><stop offset="85%" stop-color="#e63946"/><stop offset="100%" stop-color="#0a0a0a" stop-opacity="0"/></linearGradient>
  <filter id="gw"><feGaussianBlur stdDeviation="3" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
  <filter id="gs"><feGaussianBlur stdDeviation="1.5" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
  <pattern id="pg" width="43" height="43" patternUnits="userSpaceOnUse"><path d="M43 0L0 0 0 43" fill="none" stroke="#e63946" stroke-width="0.18" opacity="0.09"/></pattern>
</defs>
<rect width="860" height="260" fill="url(#bgH)"/>
<rect width="860" height="260" fill="url(#pg)"/>
<!-- top/bottom accent -->
<rect x="0" y="0" width="860" height="2" fill="url(#lR)"/>
<rect x="0" y="258" width="860" height="2" fill="url(#lR)"/>
<!-- corner brackets -->
<polyline points="28,18 16,18 16,50" fill="none" stroke="#e63946" stroke-width="1.5" filter="url(#gs)"/>
<polyline points="832,18 844,18 844,50" fill="none" stroke="#e63946" stroke-width="1.5" filter="url(#gs)"/>
<polyline points="28,242 16,242 16,210" fill="none" stroke="#e63946" stroke-width="1.5" filter="url(#gs)"/>
<polyline points="832,242 844,242 844,210" fill="none" stroke="#e63946" stroke-width="1.5" filter="url(#gs)"/>
<!-- system label + pulsing dot -->
<text x="22" y="13" font-family="Share Tech Mono,monospace" font-size="8.5" fill="#e63946" opacity="0.4">CVBARRO.OS // ENGINEERING CONSOLE</text>
<text x="838" y="13" font-family="Share Tech Mono,monospace" font-size="8.5" fill="#e63946" opacity="0.4" text-anchor="end">STATUS: ONLINE</text>
<circle cx="846" cy="9" r="3" fill="#e63946" filter="url(#gs)"><animate attributeName="opacity" values="1;0.15;1" dur="1.8s" repeatCount="indefinite"/></circle>

<!-- LEFT PANEL -->
<rect x="16" y="62" width="110" height="136" fill="#0d0d0d" stroke="#e63946" stroke-width="0.5" opacity="0.7"/>
<text x="71" y="77" font-family="Share Tech Mono,monospace" font-size="7.5" fill="#ffd700" text-anchor="middle" opacity="0.7">SYS INFO</text>
<line x1="22" y1="81" x2="120" y2="81" stroke="#e63946" stroke-width="0.4" opacity="0.4"/>
<text x="22" y="96"  font-family="Share Tech Mono,monospace" font-size="7" fill="#e63946" opacity="0.55">VERSION</text>
<text x="120" y="96"  font-family="Share Tech Mono,monospace" font-size="7" fill="#e0e0e0" text-anchor="end" opacity="0.9">v2.0.77</text>
<text x="22" y="112" font-family="Share Tech Mono,monospace" font-size="7" fill="#e63946" opacity="0.55">BUILD</text>
<text x="120" y="112" font-family="Share Tech Mono,monospace" font-size="7" fill="#e0e0e0" text-anchor="end" opacity="0.9">2025.06</text>
<text x="22" y="128" font-family="Share Tech Mono,monospace" font-size="7" fill="#e63946" opacity="0.55">NODE</text>
<text x="120" y="128" font-family="Share Tech Mono,monospace" font-size="7" fill="#ffd700" text-anchor="end" opacity="0.9">ONLINE</text>
<text x="22" y="144" font-family="Share Tech Mono,monospace" font-size="7" fill="#e63946" opacity="0.55">CLASS</text>
<text x="120" y="144" font-family="Share Tech Mono,monospace" font-size="7" fill="#e0e0e0" text-anchor="end" opacity="0.9">BACKEND</text>
<text x="22" y="160" font-family="Share Tech Mono,monospace" font-size="7" fill="#e63946" opacity="0.55">ORIGIN</text>
<text x="120" y="160" font-family="Share Tech Mono,monospace" font-size="7" fill="#e0e0e0" text-anchor="end" opacity="0.9">BRAZIL</text>
<text x="22" y="176" font-family="Share Tech Mono,monospace" font-size="7" fill="#e63946" opacity="0.55">CONTRACT</text>
<text x="120" y="176" font-family="Share Tech Mono,monospace" font-size="7" fill="#ffd700" text-anchor="end" opacity="0.9">OPEN</text>

<!-- RIGHT PANEL -->
<rect x="734" y="62" width="110" height="136" fill="#0d0d0d" stroke="#e63946" stroke-width="0.5" opacity="0.7"/>
<text x="789" y="77" font-family="Share Tech Mono,monospace" font-size="7.5" fill="#ffd700" text-anchor="middle" opacity="0.7">RUNTIME</text>
<line x1="740" y1="81" x2="838" y2="81" stroke="#e63946" stroke-width="0.4" opacity="0.4"/>
<text x="740" y="96"  font-family="Share Tech Mono,monospace" font-size="7" fill="#e63946" opacity="0.55">API</text>
<text x="838" y="96"  font-family="Share Tech Mono,monospace" font-size="7" fill="#ffd700" text-anchor="end" opacity="0.9">READY</text>
<text x="740" y="112" font-family="Share Tech Mono,monospace" font-size="7" fill="#e63946" opacity="0.55">DB</text>
<text x="838" y="112" font-family="Share Tech Mono,monospace" font-size="7" fill="#ffd700" text-anchor="end" opacity="0.9">STABLE</text>
<text x="740" y="128" font-family="Share Tech Mono,monospace" font-size="7" fill="#e63946" opacity="0.55">DOCKER</text>
<text x="838" y="128" font-family="Share Tech Mono,monospace" font-size="7" fill="#ffd700" text-anchor="end" opacity="0.9">ACTIVE</text>
<text x="740" y="144" font-family="Share Tech Mono,monospace" font-size="7" fill="#e63946" opacity="0.55">FOCUS</text>
<text x="838" y="144" font-family="Share Tech Mono,monospace" font-size="7" fill="#e0e0e0" text-anchor="end" opacity="0.9">REST API</text>
<text x="740" y="160" font-family="Share Tech Mono,monospace" font-size="7" fill="#e63946" opacity="0.55">RESEARCH</text>
<text x="838" y="160" font-family="Share Tech Mono,monospace" font-size="7" fill="#e0e0e0" text-anchor="end" opacity="0.9">C++</text>
<text x="740" y="176" font-family="Share Tech Mono,monospace" font-size="7" fill="#e63946" opacity="0.55">STATUS</text>
<text x="838" y="176" font-family="Share Tech Mono,monospace" font-size="7" fill="#ffd700" text-anchor="end" opacity="0.9">ACTIVE</text>

<!-- MAIN NAME -->
<text x="430" y="138" font-family="Share Tech Mono,monospace" font-size="50" font-weight="bold" fill="#e0e0e0" text-anchor="middle" filter="url(#gw)" letter-spacing="7">CÉSAR BARROS</text>
<rect x="186" y="148" width="488" height="1.5" fill="url(#lR)"/>

<!-- gold dots + subtitle -->
<circle cx="168" cy="174" r="2.5" fill="#ffd700" opacity="0.85" filter="url(#gs)"/>
<circle cx="692" cy="174" r="2.5" fill="#ffd700" opacity="0.85" filter="url(#gs)"/>
<text x="430" y="179" font-family="Share Tech Mono,monospace" font-size="12" fill="#e63946" text-anchor="middle" letter-spacing="4" filter="url(#gs)">BACKEND ENGINEER  ·  API ARCHITECT  ·  BRAZIL</text>

<!-- bottom label -->
<text x="430" y="248" font-family="Share Tech Mono,monospace" font-size="8.5" fill="#e63946" text-anchor="middle" opacity="0.28">DESIGNING SYSTEMS BUILT TO SURVIVE REAL-WORLD TRAFFIC</text>
</svg>
</div>

<!-- CONTACT -->
<div align="center">
  <a href="https://www.linkedin.com/public-profile/settings?trk=d_flagship3_profile_self_view_public_profile"><img src="https://img.shields.io/badge/LinkedIn-0a0a0a?style=for-the-badge&logo=linkedin&logoColor=e63946"/></a>&nbsp;
  <a href="https://www.instagram.com/ounicocesar/"><img src="https://img.shields.io/badge/Instagram-0a0a0a?style=for-the-badge&logo=instagram&logoColor=ffd700"/></a>&nbsp;
  <a href="mailto:cesarvianabarros@gmail.com"><img src="https://img.shields.io/badge/Gmail-0a0a0a?style=for-the-badge&logo=gmail&logoColor=e63946"/></a>&nbsp;
  <img src="https://komarev.com/ghpvc/?username=CVbarro&style=for-the-badge&color=e63946&labelColor=0a0a0a&label=VISITORS"/>
</div>

<br/>

<!-- DIVIDER -->
<div align="center"><svg width="860" height="22" viewBox="0 0 860 22" xmlns="http://www.w3.org/2000/svg"><defs><linearGradient id="dv1" x1="0" y1="0" x2="1" y2="0"><stop offset="0%" stop-color="#0a0a0a" stop-opacity="0"/><stop offset="12%" stop-color="#e63946"/><stop offset="50%" stop-color="#ffd700"/><stop offset="88%" stop-color="#e63946"/><stop offset="100%" stop-color="#0a0a0a" stop-opacity="0"/></linearGradient><filter id="fd1"><feGaussianBlur stdDeviation="1.5" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter></defs><rect x="0" y="10" width="860" height="1" fill="url(#dv1)" opacity="0.2"/><rect x="0" y="11" width="860" height="1" fill="url(#dv1)" filter="url(#fd1)"/><rect x="0" y="12" width="860" height="1" fill="url(#dv1)" opacity="0.2"/><rect x="0" y="8" width="55" height="5" fill="url(#dv1)" opacity="0.65" filter="url(#fd1)"><animateTransform attributeName="transform" type="translate" from="-55 0" to="915 0" dur="2.8s" repeatCount="indefinite"/></rect><polygon points="430,5 437,11 430,17 423,11" fill="#ffd700" filter="url(#fd1)" opacity="0.9"><animate attributeName="opacity" values="0.35;1;0.35" dur="2s" repeatCount="indefinite"/></polygon></svg></div>

<br/>

<!-- ░░░░░░░░░░░░░░░░░  ENGINEERING PHILOSOPHY  ░░░░░░░░░░░░░░░░░ -->

> I design software around three constraints:
> *What breaks first? How does it recover? Who maintains this in 12 months?*
>
> Simplicity is a feature. Observability is not optional.
> Performance is measured, not assumed. Documentation ships with the code.

<br/>

<!-- ░░░░░░░░░░░░░░░░░  ENGINEERING PRINCIPLES  ░░░░░░░░░░░░░░░░░ -->

<div align="center">
<svg width="860" height="72" viewBox="0 0 860 72" xmlns="http://www.w3.org/2000/svg">
<defs><filter id="gsp"><feGaussianBlur stdDeviation="1.2" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter></defs>
<rect width="860" height="72" fill="#0a0a0a"/>
<rect x="0" y="0" width="860" height="1" fill="#e63946" opacity="0.3"/>
<rect x="0" y="71" width="860" height="1" fill="#e63946" opacity="0.3"/>
<!-- label -->
<text x="430" y="16" font-family="Share Tech Mono,monospace" font-size="8.5" fill="#e63946" text-anchor="middle" opacity="0.5" letter-spacing="3">ENGINEERING PRINCIPLES</text>
<!-- principles row 1 -->
<text x="40"  y="36" font-family="Share Tech Mono,monospace" font-size="10" fill="#ffd700" filter="url(#gsp)">✓</text><text x="54"  y="36" font-family="Share Tech Mono,monospace" font-size="10" fill="#e0e0e0">Simplicity</text>
<text x="170" y="36" font-family="Share Tech Mono,monospace" font-size="10" fill="#ffd700" filter="url(#gsp)">✓</text><text x="184" y="36" font-family="Share Tech Mono,monospace" font-size="10" fill="#e0e0e0">Scalability</text>
<text x="310" y="36" font-family="Share Tech Mono,monospace" font-size="10" fill="#ffd700" filter="url(#gsp)">✓</text><text x="324" y="36" font-family="Share Tech Mono,monospace" font-size="10" fill="#e0e0e0">Observability</text>
<text x="470" y="36" font-family="Share Tech Mono,monospace" font-size="10" fill="#ffd700" filter="url(#gsp)">✓</text><text x="484" y="36" font-family="Share Tech Mono,monospace" font-size="10" fill="#e0e0e0">Maintainability</text>
<!-- principles row 2 -->
<text x="40"  y="58" font-family="Share Tech Mono,monospace" font-size="10" fill="#ffd700" filter="url(#gsp)">✓</text><text x="54"  y="58" font-family="Share Tech Mono,monospace" font-size="10" fill="#e0e0e0">Testing</text>
<text x="170" y="58" font-family="Share Tech Mono,monospace" font-size="10" fill="#ffd700" filter="url(#gsp)">✓</text><text x="184" y="58" font-family="Share Tech Mono,monospace" font-size="10" fill="#e0e0e0">Documentation</text>
<text x="310" y="58" font-family="Share Tech Mono,monospace" font-size="10" fill="#ffd700" filter="url(#gsp)">✓</text><text x="324" y="58" font-family="Share Tech Mono,monospace" font-size="10" fill="#e0e0e0">Automation</text>
<text x="470" y="58" font-family="Share Tech Mono,monospace" font-size="10" fill="#ffd700" filter="url(#gsp)">✓</text><text x="484" y="58" font-family="Share Tech Mono,monospace" font-size="10" fill="#e0e0e0">Performance</text>
</svg>
</div>

<br/>

<!-- DIVIDER -->
<div align="center"><svg width="860" height="22" viewBox="0 0 860 22" xmlns="http://www.w3.org/2000/svg"><defs><linearGradient id="dv2" x1="0" y1="0" x2="1" y2="0"><stop offset="0%" stop-color="#0a0a0a" stop-opacity="0"/><stop offset="12%" stop-color="#e63946"/><stop offset="50%" stop-color="#ffd700"/><stop offset="88%" stop-color="#e63946"/><stop offset="100%" stop-color="#0a0a0a" stop-opacity="0"/></linearGradient><filter id="fd2"><feGaussianBlur stdDeviation="1.5" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter></defs><rect x="0" y="10" width="860" height="1" fill="url(#dv2)" opacity="0.2"/><rect x="0" y="11" width="860" height="1" fill="url(#dv2)" filter="url(#fd2)"/><rect x="0" y="12" width="860" height="1" fill="url(#dv2)" opacity="0.2"/><rect x="0" y="8" width="55" height="5" fill="url(#dv2)" opacity="0.65" filter="url(#fd2)"><animateTransform attributeName="transform" type="translate" from="-55 0" to="915 0" dur="2.8s" repeatCount="indefinite"/></rect><polygon points="430,5 437,11 430,17 423,11" fill="#ffd700" filter="url(#fd2)" opacity="0.9"><animate attributeName="opacity" values="0.35;1;0.35" dur="2.4s" repeatCount="indefinite"/></polygon></svg></div>

<br/>

<!-- ░░░░░░░░░░░░░░░░░  CORE ARCHITECTURE  ░░░░░░░░░░░░░░░░░░░░░░ -->

<div align="center">
<svg width="860" height="230" viewBox="0 0 860 230" xmlns="http://www.w3.org/2000/svg">
<defs>
  <filter id="gsb"><feGaussianBlur stdDeviation="1.2" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
  <linearGradient id="barR" x1="0" y1="0" x2="1" y2="0"><stop offset="0%" stop-color="#e63946"/><stop offset="100%" stop-color="#7a0a12"/></linearGradient>
  <linearGradient id="barG" x1="0" y1="0" x2="1" y2="0"><stop offset="0%" stop-color="#ffd700"/><stop offset="100%" stop-color="#7a6400"/></linearGradient>
</defs>
<rect width="860" height="230" fill="#0a0a0a"/>
<rect x="0" y="0" width="860" height="1" fill="#e63946" opacity="0.3"/>
<rect x="0" y="229" width="860" height="1" fill="#e63946" opacity="0.3"/>

<!-- Section label -->
<text x="430" y="20" font-family="Share Tech Mono,monospace" font-size="8.5" fill="#e63946" text-anchor="middle" opacity="0.5" letter-spacing="3">CORE ARCHITECTURE</text>
<line x1="30" y1="28" x2="390" y2="28" stroke="#e63946" stroke-width="0.4" opacity="0.25"/>
<line x1="470" y1="28" x2="830" y2="28" stroke="#e63946" stroke-width="0.4" opacity="0.25"/>

<!-- COL 1: BACKEND -->
<text x="30" y="46" font-family="Share Tech Mono,monospace" font-size="8" fill="#ffd700" opacity="0.7" letter-spacing="2">BACKEND</text>

<text x="30" y="66" font-family="Share Tech Mono,monospace" font-size="9.5" fill="#e0e0e0">Java</text>
<rect x="30" y="70" width="185" height="5" rx="1" fill="#1a1a1a"/>
<rect x="30" y="70" width="178" height="5" rx="1" fill="url(#barR)" filter="url(#gsb)"/>

<text x="30" y="92" font-family="Share Tech Mono,monospace" font-size="9.5" fill="#e0e0e0">Spring Boot</text>
<rect x="30" y="96" width="185" height="5" rx="1" fill="#1a1a1a"/>
<rect x="30" y="96" width="170" height="5" rx="1" fill="url(#barR)" filter="url(#gsb)"/>

<text x="30" y="118" font-family="Share Tech Mono,monospace" font-size="9.5" fill="#e0e0e0">Python</text>
<rect x="30" y="122" width="185" height="5" rx="1" fill="#1a1a1a"/>
<rect x="30" y="122" width="148" height="5" rx="1" fill="url(#barR)" filter="url(#gsb)"/>

<text x="30" y="144" font-family="Share Tech Mono,monospace" font-size="9.5" fill="#e0e0e0">REST APIs</text>
<rect x="30" y="148" width="185" height="5" rx="1" fill="#1a1a1a"/>
<rect x="30" y="148" width="180" height="5" rx="1" fill="url(#barR)" filter="url(#gsb)"/>

<!-- COL 2: INFRASTRUCTURE -->
<text x="248" y="46" font-family="Share Tech Mono,monospace" font-size="8" fill="#ffd700" opacity="0.7" letter-spacing="2">INFRASTRUCTURE</text>

<text x="248" y="66" font-family="Share Tech Mono,monospace" font-size="9.5" fill="#e0e0e0">MySQL</text>
<rect x="248" y="70" width="185" height="5" rx="1" fill="#1a1a1a"/>
<rect x="248" y="70" width="162" height="5" rx="1" fill="url(#barG)" filter="url(#gsb)"/>

<text x="248" y="92" font-family="Share Tech Mono,monospace" font-size="9.5" fill="#e0e0e0">Docker</text>
<rect x="248" y="96" width="185" height="5" rx="1" fill="#1a1a1a"/>
<rect x="248" y="96" width="170" height="5" rx="1" fill="url(#barG)" filter="url(#gsb)"/>

<text x="248" y="118" font-family="Share Tech Mono,monospace" font-size="9.5" fill="#e0e0e0">Git</text>
<rect x="248" y="122" width="185" height="5" rx="1" fill="#1a1a1a"/>
<rect x="248" y="122" width="182" height="5" rx="1" fill="url(#barG)" filter="url(#gsb)"/>

<!-- COL 3: RESEARCH -->
<text x="466" y="46" font-family="Share Tech Mono,monospace" font-size="8" fill="#ffd700" opacity="0.7" letter-spacing="2">RESEARCH</text>

<text x="466" y="66" font-family="Share Tech Mono,monospace" font-size="9.5" fill="#e0e0e0">Kotlin</text>
<rect x="466" y="70" width="185" height="5" rx="1" fill="#1a1a1a"/>
<rect x="466" y="70" width="110" height="5" rx="1" fill="#444" opacity="0.8"/>

<text x="466" y="92" font-family="Share Tech Mono,monospace" font-size="9.5" fill="#e0e0e0">Go</text>
<rect x="466" y="96" width="185" height="5" rx="1" fill="#1a1a1a"/>
<rect x="466" y="96" width="95" height="5" rx="1" fill="#444" opacity="0.8"/>

<text x="466" y="118" font-family="Share Tech Mono,monospace" font-size="9.5" fill="#e0e0e0">JavaScript</text>
<rect x="466" y="122" width="185" height="5" rx="1" fill="#1a1a1a"/>
<rect x="466" y="122" width="120" height="5" rx="1" fill="#444" opacity="0.8"/>

<text x="466" y="144" font-family="Share Tech Mono,monospace" font-size="9.5" fill="#e0e0e0">C++ <tspan font-size="8" fill="#e63946" opacity="0.6">[LEARNING]</tspan></text>
<rect x="466" y="148" width="185" height="5" rx="1" fill="#1a1a1a"/>
<rect x="466" y="148" width="60" height="5" rx="1" fill="#e63946" opacity="0.4"/>

<!-- FRONTEND row -->
<text x="684" y="46" font-family="Share Tech Mono,monospace" font-size="8" fill="#ffd700" opacity="0.7" letter-spacing="2">FRONTEND</text>

<text x="684" y="66" font-family="Share Tech Mono,monospace" font-size="9.5" fill="#e0e0e0">React</text>
<rect x="684" y="70" width="150" height="5" rx="1" fill="#1a1a1a"/>
<rect x="684" y="70" width="90" height="5" rx="1" fill="#444" opacity="0.8"/>

<text x="684" y="92" font-family="Share Tech Mono,monospace" font-size="9.5" fill="#e0e0e0">HTML · CSS</text>
<rect x="684" y="96" width="150" height="5" rx="1" fill="#1a1a1a"/>
<rect x="684" y="96" width="115" height="5" rx="1" fill="#444" opacity="0.8"/>

<!-- legend -->
<rect x="30" y="192" width="10" height="5" rx="1" fill="url(#barR)"/>
<text x="46" y="198" font-family="Share Tech Mono,monospace" font-size="8" fill="#e63946" opacity="0.6">PRIMARY STACK</text>
<rect x="180" y="192" width="10" height="5" rx="1" fill="url(#barG)"/>
<text x="196" y="198" font-family="Share Tech Mono,monospace" font-size="8" fill="#ffd700" opacity="0.6">INFRASTRUCTURE</text>
<rect x="360" y="192" width="10" height="5" rx="1" fill="#444"/>
<text x="376" y="198" font-family="Share Tech Mono,monospace" font-size="8" fill="#e0e0e0" opacity="0.5">EXPERIMENTAL</text>
</svg>
</div>

<br/>

<!-- DIVIDER -->
<div align="center"><svg width="860" height="22" viewBox="0 0 860 22" xmlns="http://www.w3.org/2000/svg"><defs><linearGradient id="dv3" x1="0" y1="0" x2="1" y2="0"><stop offset="0%" stop-color="#0a0a0a" stop-opacity="0"/><stop offset="12%" stop-color="#e63946"/><stop offset="50%" stop-color="#ffd700"/><stop offset="88%" stop-color="#e63946"/><stop offset="100%" stop-color="#0a0a0a" stop-opacity="0"/></linearGradient><filter id="fd3"><feGaussianBlur stdDeviation="1.5" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter></defs><rect x="0" y="10" width="860" height="1" fill="url(#dv3)" opacity="0.2"/><rect x="0" y="11" width="860" height="1" fill="url(#dv3)" filter="url(#fd3)"/><rect x="0" y="12" width="860" height="1" fill="url(#dv3)" opacity="0.2"/><rect x="0" y="8" width="55" height="5" fill="url(#dv3)" opacity="0.65" filter="url(#fd3)"><animateTransform attributeName="transform" type="translate" from="-55 0" to="915 0" dur="2.8s" repeatCount="indefinite"/></rect><polygon points="430,5 437,11 430,17 423,11" fill="#ffd700" filter="url(#fd3)" opacity="0.9"><animate attributeName="opacity" values="0.35;1;0.35" dur="2.8s" repeatCount="indefinite"/></polygon></svg></div>

<br/>

<!-- ░░░░░░░░░░░░░░░░░  TIMELINE  ░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░ -->

<div align="center">
<svg width="860" height="120" viewBox="0 0 860 120" xmlns="http://www.w3.org/2000/svg">
<defs><filter id="gtl"><feGaussianBlur stdDeviation="1.2" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter></defs>
<rect width="860" height="120" fill="#0a0a0a"/>
<rect x="0" y="0" width="860" height="1" fill="#e63946" opacity="0.2"/>
<rect x="0" y="119" width="860" height="1" fill="#e63946" opacity="0.2"/>
<text x="430" y="18" font-family="Share Tech Mono,monospace" font-size="8.5" fill="#e63946" text-anchor="middle" opacity="0.5" letter-spacing="3">DEVELOPMENT TIMELINE</text>
<!-- timeline line -->
<line x1="60" y1="70" x2="800" y2="70" stroke="#e63946" stroke-width="0.8" opacity="0.3"/>
<!-- nodes -->
<circle cx="100" cy="70" r="4" fill="#e63946" filter="url(#gtl)"/>
<circle cx="230" cy="70" r="4" fill="#e63946" filter="url(#gtl)"/>
<circle cx="360" cy="70" r="4" fill="#e63946" filter="url(#gtl)"/>
<circle cx="490" cy="70" r="4" fill="#ffd700" filter="url(#gtl)"/>
<circle cx="620" cy="70" r="4" fill="#ffd700" filter="url(#gtl)"/>
<circle cx="760" cy="70" r="4" fill="#e63946" opacity="0.5"/>
<!-- labels top -->
<text x="100" y="52" font-family="Share Tech Mono,monospace" font-size="8" fill="#e63946" text-anchor="middle">2021</text>
<text x="100" y="42" font-family="Share Tech Mono,monospace" font-size="7.5" fill="#e0e0e0" text-anchor="middle" opacity="0.7">Python</text>
<text x="230" y="52" font-family="Share Tech Mono,monospace" font-size="8" fill="#e63946" text-anchor="middle">2022</text>
<text x="230" y="42" font-family="Share Tech Mono,monospace" font-size="7.5" fill="#e0e0e0" text-anchor="middle" opacity="0.7">Java · SQL</text>
<text x="360" y="52" font-family="Share Tech Mono,monospace" font-size="8" fill="#e63946" text-anchor="middle">2023</text>
<text x="360" y="42" font-family="Share Tech Mono,monospace" font-size="7.5" fill="#e0e0e0" text-anchor="middle" opacity="0.7">Spring Boot</text>
<!-- labels bottom -->
<text x="490" y="88" font-family="Share Tech Mono,monospace" font-size="8" fill="#ffd700" text-anchor="middle">2024</text>
<text x="490" y="98" font-family="Share Tech Mono,monospace" font-size="7.5" fill="#e0e0e0" text-anchor="middle" opacity="0.7">Docker · APIs</text>
<text x="620" y="88" font-family="Share Tech Mono,monospace" font-size="8" fill="#ffd700" text-anchor="middle">2025</text>
<text x="620" y="98" font-family="Share Tech Mono,monospace" font-size="7.5" fill="#e0e0e0" text-anchor="middle" opacity="0.7">Microservices</text>
<text x="760" y="88" font-family="Share Tech Mono,monospace" font-size="8" fill="#e63946" text-anchor="middle" opacity="0.6">2026</text>
<text x="760" y="98" font-family="Share Tech Mono,monospace" font-size="7.5" fill="#e0e0e0" text-anchor="middle" opacity="0.45">C++ · Systems</text>
</svg>
</div>

<br/>

<!-- DIVIDER -->
<div align="center"><svg width="860" height="22" viewBox="0 0 860 22" xmlns="http://www.w3.org/2000/svg"><defs><linearGradient id="dv4" x1="0" y1="0" x2="1" y2="0"><stop offset="0%" stop-color="#0a0a0a" stop-opacity="0"/><stop offset="12%" stop-color="#e63946"/><stop offset="50%" stop-color="#ffd700"/><stop offset="88%" stop-color="#e63946"/><stop offset="100%" stop-color="#0a0a0a" stop-opacity="0"/></linearGradient><filter id="fd4"><feGaussianBlur stdDeviation="1.5" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter></defs><rect x="0" y="10" width="860" height="1" fill="url(#dv4)" opacity="0.2"/><rect x="0" y="11" width="860" height="1" fill="url(#dv4)" filter="url(#fd4)"/><rect x="0" y="12" width="860" height="1" fill="url(#dv4)" opacity="0.2"/><rect x="0" y="8" width="55" height="5" fill="url(#dv4)" opacity="0.65" filter="url(#fd4)"><animateTransform attributeName="transform" type="translate" from="-55 0" to="915 0" dur="2.8s" repeatCount="indefinite"/></rect><polygon points="430,5 437,11 430,17 423,11" fill="#ffd700" filter="url(#fd4)" opacity="0.9"><animate attributeName="opacity" values="0.35;1;0.35" dur="3.2s" repeatCount="indefinite"/></polygon></svg></div>

<br/>

<!-- ░░░░░░░░░░░░░░░░░  SYSTEM METRICS  ░░░░░░░░░░░░░░░░░░░░░░░░░ -->

<div align="center">
  <img height="162" src="https://github-readme-stats.vercel.app/api?username=CVbarro&show_icons=true&hide_border=true&count_private=true&bg_color=0a0a0a&title_color=e63946&icon_color=ffd700&text_color=e0e0e0&ring_color=e63946&rank_icon=github"/>
  <img height="162" src="https://github-readme-stats.vercel.app/api/top-langs/?username=CVbarro&layout=compact&hide_border=true&bg_color=0a0a0a&title_color=e63946&text_color=e0e0e0&langs_count=8"/>
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=CVbarro&hide_border=true&background=0a0a0a&stroke=e63946&ring=ffd700&fire=e63946&currStreakLabel=ffd700&sideLabels=e0e0e0&dates=555555&sideNums=e63946&currStreakNum=ffd700"/>
</div>

<!-- DIVIDER -->
<div align="center"><svg width="860" height="22" viewBox="0 0 860 22" xmlns="http://www.w3.org/2000/svg"><defs><linearGradient id="dv5" x1="0" y1="0" x2="1" y2="0"><stop offset="0%" stop-color="#0a0a0a" stop-opacity="0"/><stop offset="12%" stop-color="#e63946"/><stop offset="50%" stop-color="#ffd700"/><stop offset="88%" stop-color="#e63946"/><stop offset="100%" stop-color="#0a0a0a" stop-opacity="0"/></linearGradient><filter id="fd5"><feGaussianBlur stdDeviation="1.5" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter></defs><rect x="0" y="10" width="860" height="1" fill="url(#dv5)" opacity="0.2"/><rect x="0" y="11" width="860" height="1" fill="url(#dv5)" filter="url(#fd5)"/><rect x="0" y="12" width="860" height="1" fill="url(#dv5)" opacity="0.2"/><rect x="0" y="8" width="55" height="5" fill="url(#dv5)" opacity="0.65" filter="url(#fd5)"><animateTransform attributeName="transform" type="translate" from="-55 0" to="915 0" dur="2.8s" repeatCount="indefinite"/></rect><polygon points="430,5 437,11 430,17 423,11" fill="#ffd700" filter="url(#fd5)" opacity="0.9"><animate attributeName="opacity" values="0.35;1;0.35" dur="2s" repeatCount="indefinite"/></polygon></svg></div>

<br/>

<!-- ░░░░░░░░░░░░░░░░░  CONTRIBUTION SNAKE  ░░░░░░░░░░░░░░░░░░░░░ -->

<div align="center">
  <img src="https://raw.githubusercontent.com/CVbarro/CVbarro/output/github-contribution-grid-snake-dark.svg"/>
</div>

<br/>

<!-- ░░░░░░░░░░░░░░░░░  SHUTDOWN  ░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░░ -->

<div align="center">

```console
> SYSTEM SHUTDOWN INITIATED

  Flushing memory buffers ............. done
  Closing network connections ......... done
  Saving operator session ............. done

  Console offline.   ◈  CVBARRO · 2025  ◈
```

</div>

<!-- FOOTER -->
<div align="center">
<svg width="860" height="50" viewBox="0 0 860 50" xmlns="http://www.w3.org/2000/svg">
<defs><linearGradient id="ftB" x1="0" y1="0" x2="0" y2="1"><stop offset="0%" stop-color="#0a0a0a"/><stop offset="100%" stop-color="#130000"/></linearGradient><linearGradient id="ftL" x1="0" y1="0" x2="1" y2="0"><stop offset="0%" stop-color="#0a0a0a" stop-opacity="0"/><stop offset="15%" stop-color="#e63946"/><stop offset="85%" stop-color="#e63946"/><stop offset="100%" stop-color="#0a0a0a" stop-opacity="0"/></linearGradient></defs>
<rect width="860" height="50" fill="url(#ftB)"/>
<rect x="0" y="0" width="860" height="1.5" fill="url(#ftL)"/>
<text x="430" y="32" font-family="Share Tech Mono,monospace" font-size="9.5" fill="#e63946" text-anchor="middle" opacity="0.3">CVBARRO.OS  ·  ENGINEERING CONSOLE  ·  BRAZIL  ·  2025</text>
</svg>
</div>
