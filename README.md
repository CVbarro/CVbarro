<!--
  César Barros — Engineering Portfolio
  Design: Technical Editorial · Clean · No terminal aesthetics
  Palette: #090909 · #E63946 · #FFD700 · #F2F2F2 · #8A8A8A
-->

<!-- ─── HERO ──────────────────────────────────────────────────────── -->

<div align="center">
<svg width="860" height="240" viewBox="0 0 860 240" xmlns="http://www.w3.org/2000/svg">
<defs>
  <linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
    <stop offset="0%" stop-color="#090909"/>
    <stop offset="100%" stop-color="#0e0404"/>
  </linearGradient>
  <linearGradient id="rl" x1="0" y1="0" x2="1" y2="0">
    <stop offset="0%" stop-color="#090909" stop-opacity="0"/>
    <stop offset="18%" stop-color="#E63946"/>
    <stop offset="82%" stop-color="#E63946"/>
    <stop offset="100%" stop-color="#090909" stop-opacity="0"/>
  </linearGradient>
  <pattern id="dots" width="24" height="24" patternUnits="userSpaceOnUse">
    <circle cx="12" cy="12" r="0.7" fill="#E63946" opacity="0.09"/>
  </pattern>
  <filter id="gw"><feGaussianBlur stdDeviation="2.5" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
  <filter id="gs"><feGaussianBlur stdDeviation="1" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter>
</defs>

<rect width="860" height="240" fill="url(#bg)"/>
<rect width="860" height="240" fill="url(#dots)"/>

<!-- accent lines -->
<rect x="0" y="0"   width="860" height="1.5" fill="url(#rl)"/>
<rect x="0" y="238" width="860" height="1.5" fill="url(#rl)"/>

<!-- vertical margin rules -->
<line x1="56" y1="0" x2="56" y2="240" stroke="#E63946" stroke-width="0.3" opacity="0.1"/>
<line x1="804" y1="0" x2="804" y2="240" stroke="#E63946" stroke-width="0.3" opacity="0.1"/>

<!-- corner marks -->
<line x1="20" y1="20" x2="42" y2="20" stroke="#E63946" stroke-width="1" opacity="0.35"/>
<line x1="20" y1="20" x2="20" y2="42" stroke="#E63946" stroke-width="1" opacity="0.35"/>
<line x1="840" y1="20" x2="818" y2="20" stroke="#E63946" stroke-width="1" opacity="0.35"/>
<line x1="840" y1="20" x2="840" y2="42" stroke="#E63946" stroke-width="1" opacity="0.35"/>
<line x1="20" y1="220" x2="42" y2="220" stroke="#E63946" stroke-width="1" opacity="0.35"/>
<line x1="20" y1="220" x2="20" y2="198" stroke="#E63946" stroke-width="1" opacity="0.35"/>
<line x1="840" y1="220" x2="818" y2="220" stroke="#E63946" stroke-width="1" opacity="0.35"/>
<line x1="840" y1="220" x2="840" y2="198" stroke="#E63946" stroke-width="1" opacity="0.35"/>

<!-- ref marks -->
<text x="20" y="14" font-family="Share Tech Mono,monospace" font-size="7.5" fill="#E63946" opacity="0.28" letter-spacing="1">A·01</text>
<text x="840" y="14" font-family="Share Tech Mono,monospace" font-size="7.5" fill="#E63946" opacity="0.28" text-anchor="end" letter-spacing="1">REV·2025</text>

<!-- left data panel -->
<text x="68" y="96"  font-family="Share Tech Mono,monospace" font-size="7" fill="#8A8A8A" letter-spacing="1.5">CLASS</text>
<text x="68" y="112" font-family="Share Tech Mono,monospace" font-size="10" fill="#F2F2F2" opacity="0.85">Backend Engineer</text>
<text x="68" y="132" font-family="Share Tech Mono,monospace" font-size="7" fill="#8A8A8A" letter-spacing="1.5">ORIGIN</text>
<text x="68" y="148" font-family="Share Tech Mono,monospace" font-size="10" fill="#F2F2F2" opacity="0.85">Brazil</text>
<text x="68" y="168" font-family="Share Tech Mono,monospace" font-size="7" fill="#8A8A8A" letter-spacing="1.5">AVAILABILITY</text>
<text x="68" y="184" font-family="Share Tech Mono,monospace" font-size="10" fill="#FFD700" opacity="0.9">Open to work</text>
<circle cx="178" cy="181" r="3" fill="#FFD700" opacity="0.75" filter="url(#gs)">
  <animate attributeName="opacity" values="0.75;0.2;0.75" dur="2.4s" repeatCount="indefinite"/>
</circle>

<!-- right data panel -->
<text x="792" y="96"  font-family="Share Tech Mono,monospace" font-size="7" fill="#8A8A8A" letter-spacing="1.5" text-anchor="end">FOCUS</text>
<text x="792" y="112" font-family="Share Tech Mono,monospace" font-size="10" fill="#F2F2F2" opacity="0.85" text-anchor="end">REST APIs · Systems</text>
<text x="792" y="132" font-family="Share Tech Mono,monospace" font-size="7" fill="#8A8A8A" letter-spacing="1.5" text-anchor="end">CORE STACK</text>
<text x="792" y="148" font-family="Share Tech Mono,monospace" font-size="10" fill="#F2F2F2" opacity="0.75" text-anchor="end">Java · Spring · Docker</text>
<text x="792" y="168" font-family="Share Tech Mono,monospace" font-size="7" fill="#8A8A8A" letter-spacing="1.5" text-anchor="end">RESEARCH</text>
<text x="792" y="184" font-family="Share Tech Mono,monospace" font-size="10" fill="#F2F2F2" opacity="0.5" text-anchor="end">C++ · Go · Kotlin</text>

<!-- name -->
<text x="430" y="126" font-family="Share Tech Mono,monospace" font-size="48" font-weight="bold" fill="#F2F2F2" text-anchor="middle" filter="url(#gw)" letter-spacing="5">CÉSAR BARROS</text>

<!-- rule -->
<rect x="210" y="138" width="440" height="1" fill="url(#rl)" opacity="0.8"/>

<!-- subtitle -->
<text x="430" y="160" font-family="Share Tech Mono,monospace" font-size="11" fill="#E63946" text-anchor="middle" letter-spacing="3.5" filter="url(#gs)">BACKEND ENGINEER  ·  API ARCHITECT</text>

<!-- caption -->
<text x="430" y="226" font-family="Share Tech Mono,monospace" font-size="7.5" fill="#F2F2F2" text-anchor="middle" opacity="0.18" letter-spacing="1.5">DESIGNING SYSTEMS BUILT TO SURVIVE REAL-WORLD TRAFFIC</text>
</svg>
</div>

<br/>

<!-- ─── DIVIDER ──────────────────────────────────────────────────── -->
<div align="center"><svg width="860" height="18" viewBox="0 0 860 18" xmlns="http://www.w3.org/2000/svg"><defs><linearGradient id="d1" x1="0" y1="0" x2="1" y2="0"><stop offset="0%" stop-color="#090909" stop-opacity="0"/><stop offset="15%" stop-color="#E63946" stop-opacity="0.7"/><stop offset="50%" stop-color="#FFD700" stop-opacity="0.9"/><stop offset="85%" stop-color="#E63946" stop-opacity="0.7"/><stop offset="100%" stop-color="#090909" stop-opacity="0"/></linearGradient><filter id="fd"><feGaussianBlur stdDeviation="1" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter></defs><rect x="0" y="8" width="860" height="1" fill="url(#d1)" opacity="0.15"/><rect x="0" y="9" width="860" height="1" fill="url(#d1)" filter="url(#fd)"/><rect x="0" y="8" width="50" height="2" fill="url(#d1)" opacity="0.7" filter="url(#fd)"><animateTransform attributeName="transform" type="translate" from="-50 0" to="910 0" dur="3s" repeatCount="indefinite"/></rect><rect x="425" y="5" width="10" height="8" rx="1" fill="#090909"/><line x1="428" y1="9" x2="432" y2="9" stroke="#FFD700" stroke-width="1" opacity="0.8" filter="url(#fd)"/></svg></div>

<br/>

<!-- ─── ENGINEERING APPROACH ─────────────────────────────────────── -->

<div align="center">
<svg width="860" height="88" viewBox="0 0 860 88" xmlns="http://www.w3.org/2000/svg">
<rect width="860" height="88" fill="#090909"/>
<rect x="56" y="16" width="2" height="56" fill="#E63946" opacity="0.45"/>
<text x="72" y="34" font-family="Share Tech Mono,monospace" font-size="7.5" fill="#8A8A8A" letter-spacing="2">ENGINEERING APPROACH</text>
<text x="72" y="54" font-family="Share Tech Mono,monospace" font-size="13" fill="#F2F2F2" opacity="0.92">What breaks first?  How does it recover?</text>
<text x="72" y="72" font-family="Share Tech Mono,monospace" font-size="13" fill="#F2F2F2" opacity="0.5">Who maintains this in 12 months?</text>
</svg>
</div>

<br/>

<!-- ─── DIVIDER ──────────────────────────────────────────────────── -->
<div align="center"><svg width="860" height="18" viewBox="0 0 860 18" xmlns="http://www.w3.org/2000/svg"><defs><linearGradient id="d2" x1="0" y1="0" x2="1" y2="0"><stop offset="0%" stop-color="#090909" stop-opacity="0"/><stop offset="15%" stop-color="#E63946" stop-opacity="0.7"/><stop offset="50%" stop-color="#FFD700" stop-opacity="0.9"/><stop offset="85%" stop-color="#E63946" stop-opacity="0.7"/><stop offset="100%" stop-color="#090909" stop-opacity="0"/></linearGradient><filter id="fd2"><feGaussianBlur stdDeviation="1" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter></defs><rect x="0" y="8" width="860" height="1" fill="url(#d2)" opacity="0.15"/><rect x="0" y="9" width="860" height="1" fill="url(#d2)" filter="url(#fd2)"/><rect x="0" y="8" width="50" height="2" fill="url(#d2)" opacity="0.7" filter="url(#fd2)"><animateTransform attributeName="transform" type="translate" from="-50 0" to="910 0" dur="3s" repeatCount="indefinite"/></rect><rect x="425" y="5" width="10" height="8" rx="1" fill="#090909"/><line x1="428" y1="9" x2="432" y2="9" stroke="#FFD700" stroke-width="1" opacity="0.8" filter="url(#fd2)"/></svg></div>

<br/>

<!-- ─── CORE STACK ───────────────────────────────────────────────── -->

<div align="center">
<table border="0" cellspacing="0" cellpadding="16">
<tr valign="top">
<td width="260" align="left">

**BACKEND**
<sub>Services that hold up at 3 a.m.</sub>

<br/>

![Java](https://img.shields.io/badge/Java-090909?style=for-the-badge&logo=openjdk&logoColor=E63946)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-090909?style=for-the-badge&logo=springboot&logoColor=F2F2F2)
![Python](https://img.shields.io/badge/Python-090909?style=for-the-badge&logo=python&logoColor=FFD700)
![REST](https://img.shields.io/badge/REST_API-090909?style=for-the-badge&logoColor=F2F2F2)

</td>
<td width="260" align="left">

**INFRASTRUCTURE**
<sub>The boring layer that must never blink.</sub>

<br/>

![Docker](https://img.shields.io/badge/Docker-090909?style=for-the-badge&logo=docker&logoColor=F2F2F2)
![MySQL](https://img.shields.io/badge/MySQL-090909?style=for-the-badge&logo=mysql&logoColor=FFD700)
![Git](https://img.shields.io/badge/Git-090909?style=for-the-badge&logo=git&logoColor=E63946)

</td>
<td width="260" align="left">

**RESEARCH**
<sub>What I am building fluency in next.</sub>

<br/>

![C++](https://img.shields.io/badge/C++-090909?style=for-the-badge&logo=cplusplus&logoColor=F2F2F2)
![Go](https://img.shields.io/badge/Go-090909?style=for-the-badge&logo=go&logoColor=FFD700)
![Kotlin](https://img.shields.io/badge/Kotlin-090909?style=for-the-badge&logo=kotlin&logoColor=F2F2F2)

</td>
</tr>
</table>
</div>

<br/>

<!-- ─── DIVIDER ──────────────────────────────────────────────────── -->
<div align="center"><svg width="860" height="18" viewBox="0 0 860 18" xmlns="http://www.w3.org/2000/svg"><defs><linearGradient id="d3" x1="0" y1="0" x2="1" y2="0"><stop offset="0%" stop-color="#090909" stop-opacity="0"/><stop offset="15%" stop-color="#E63946" stop-opacity="0.7"/><stop offset="50%" stop-color="#FFD700" stop-opacity="0.9"/><stop offset="85%" stop-color="#E63946" stop-opacity="0.7"/><stop offset="100%" stop-color="#090909" stop-opacity="0"/></linearGradient><filter id="fd3"><feGaussianBlur stdDeviation="1" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter></defs><rect x="0" y="8" width="860" height="1" fill="url(#d3)" opacity="0.15"/><rect x="0" y="9" width="860" height="1" fill="url(#d3)" filter="url(#fd3)"/><rect x="0" y="8" width="50" height="2" fill="url(#d3)" opacity="0.7" filter="url(#fd3)"><animateTransform attributeName="transform" type="translate" from="-50 0" to="910 0" dur="3s" repeatCount="indefinite"/></rect><rect x="425" y="5" width="10" height="8" rx="1" fill="#090909"/><line x1="428" y1="9" x2="432" y2="9" stroke="#FFD700" stroke-width="1" opacity="0.8" filter="url(#fd3)"/></svg></div>

<br/>

<!-- ─── ENGINEERING PRINCIPLES ───────────────────────────────────── -->

<div align="center">
<svg width="860" height="92" viewBox="0 0 860 92" xmlns="http://www.w3.org/2000/svg">
<defs><filter id="fp"><feGaussianBlur stdDeviation="1" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter></defs>
<rect width="860" height="92" fill="#090909"/>
<rect x="0" y="0" width="860" height="1" fill="#E63946" opacity="0.08"/>
<rect x="0" y="91" width="860" height="1" fill="#E63946" opacity="0.08"/>
<text x="430" y="20" font-family="Share Tech Mono,monospace" font-size="7.5" fill="#8A8A8A" text-anchor="middle" letter-spacing="2">ENGINEERING PRINCIPLES</text>
<circle cx="68"  cy="44" r="2.2" fill="#FFD700" opacity="0.7" filter="url(#fp)"/>
<text x="80"  y="48" font-family="Share Tech Mono,monospace" font-size="10.5" fill="#F2F2F2" opacity="0.85">Simplicity</text>
<circle cx="220" cy="44" r="2.2" fill="#FFD700" opacity="0.7" filter="url(#fp)"/>
<text x="232" y="48" font-family="Share Tech Mono,monospace" font-size="10.5" fill="#F2F2F2" opacity="0.85">Observability</text>
<circle cx="408" cy="44" r="2.2" fill="#FFD700" opacity="0.7" filter="url(#fp)"/>
<text x="420" y="48" font-family="Share Tech Mono,monospace" font-size="10.5" fill="#F2F2F2" opacity="0.85">Scalability</text>
<circle cx="578" cy="44" r="2.2" fill="#FFD700" opacity="0.7" filter="url(#fp)"/>
<text x="590" y="48" font-family="Share Tech Mono,monospace" font-size="10.5" fill="#F2F2F2" opacity="0.85">Maintainability</text>
<circle cx="68"  cy="70" r="2.2" fill="#FFD700" opacity="0.45" filter="url(#fp)"/>
<text x="80"  y="74" font-family="Share Tech Mono,monospace" font-size="10.5" fill="#F2F2F2" opacity="0.45">Testing</text>
<circle cx="220" cy="70" r="2.2" fill="#FFD700" opacity="0.45" filter="url(#fp)"/>
<text x="232" y="74" font-family="Share Tech Mono,monospace" font-size="10.5" fill="#F2F2F2" opacity="0.45">Documentation</text>
<circle cx="408" cy="70" r="2.2" fill="#FFD700" opacity="0.45" filter="url(#fp)"/>
<text x="420" y="74" font-family="Share Tech Mono,monospace" font-size="10.5" fill="#F2F2F2" opacity="0.45">Automation</text>
<circle cx="578" cy="70" r="2.2" fill="#FFD700" opacity="0.45" filter="url(#fp)"/>
<text x="590" y="74" font-family="Share Tech Mono,monospace" font-size="10.5" fill="#F2F2F2" opacity="0.45">Performance</text>
</svg>
</div>

<br/>

<!-- ─── DIVIDER ──────────────────────────────────────────────────── -->
<div align="center"><svg width="860" height="18" viewBox="0 0 860 18" xmlns="http://www.w3.org/2000/svg"><defs><linearGradient id="d4" x1="0" y1="0" x2="1" y2="0"><stop offset="0%" stop-color="#090909" stop-opacity="0"/><stop offset="15%" stop-color="#E63946" stop-opacity="0.7"/><stop offset="50%" stop-color="#FFD700" stop-opacity="0.9"/><stop offset="85%" stop-color="#E63946" stop-opacity="0.7"/><stop offset="100%" stop-color="#090909" stop-opacity="0"/></linearGradient><filter id="fd4"><feGaussianBlur stdDeviation="1" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter></defs><rect x="0" y="8" width="860" height="1" fill="url(#d4)" opacity="0.15"/><rect x="0" y="9" width="860" height="1" fill="url(#d4)" filter="url(#fd4)"/><rect x="0" y="8" width="50" height="2" fill="url(#d4)" opacity="0.7" filter="url(#fd4)"><animateTransform attributeName="transform" type="translate" from="-50 0" to="910 0" dur="3s" repeatCount="indefinite"/></rect><rect x="425" y="5" width="10" height="8" rx="1" fill="#090909"/><line x1="428" y1="9" x2="432" y2="9" stroke="#FFD700" stroke-width="1" opacity="0.8" filter="url(#fd4)"/></svg></div>

<br/>

<!-- ─── TIMELINE ─────────────────────────────────────────────────── -->

<div align="center">
<svg width="860" height="108" viewBox="0 0 860 108" xmlns="http://www.w3.org/2000/svg">
<defs><filter id="ft"><feGaussianBlur stdDeviation="1.2" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter></defs>
<rect width="860" height="108" fill="#090909"/>
<rect x="0" y="0" width="860" height="1" fill="#E63946" opacity="0.08"/>
<rect x="0" y="107" width="860" height="1" fill="#E63946" opacity="0.08"/>
<text x="56" y="22" font-family="Share Tech Mono,monospace" font-size="7.5" fill="#8A8A8A" letter-spacing="2">TIMELINE</text>
<!-- spine -->
<line x1="76" y1="62" x2="800" y2="62" stroke="#E63946" stroke-width="0.6" opacity="0.18"/>
<!-- ticks -->
<line x1="110" y1="54" x2="110" y2="70" stroke="#E63946" stroke-width="0.8" opacity="0.45"/>
<line x1="258" y1="54" x2="258" y2="70" stroke="#E63946" stroke-width="0.8" opacity="0.45"/>
<line x1="406" y1="54" x2="406" y2="70" stroke="#E63946" stroke-width="1"   opacity="0.65"/>
<line x1="554" y1="54" x2="554" y2="70" stroke="#FFD700" stroke-width="1"   opacity="0.65" filter="url(#ft)"/>
<line x1="702" y1="54" x2="702" y2="70" stroke="#FFD700" stroke-width="1"   opacity="0.65" filter="url(#ft)"/>
<line x1="790" y1="54" x2="790" y2="70" stroke="#E63946" stroke-width="0.6" opacity="0.25"/>
<!-- nodes -->
<circle cx="110" cy="62" r="4"   fill="#E63946" opacity="0.7"/>
<circle cx="258" cy="62" r="4"   fill="#E63946" opacity="0.7"/>
<circle cx="406" cy="62" r="5"   fill="#E63946" filter="url(#ft)"/>
<circle cx="554" cy="62" r="5"   fill="#FFD700" filter="url(#ft)"/>
<circle cx="702" cy="62" r="5"   fill="#FFD700" filter="url(#ft)"/>
<circle cx="790" cy="62" r="3.5" fill="#E63946" opacity="0.28"/>
<!-- labels top -->
<text x="110" y="44" font-family="Share Tech Mono,monospace" font-size="8"   fill="#E63946"  text-anchor="middle" opacity="0.7">2021</text>
<text x="110" y="33" font-family="Share Tech Mono,monospace" font-size="7.5" fill="#F2F2F2"  text-anchor="middle" opacity="0.55">Python</text>
<text x="258" y="44" font-family="Share Tech Mono,monospace" font-size="8"   fill="#E63946"  text-anchor="middle" opacity="0.7">2022</text>
<text x="258" y="33" font-family="Share Tech Mono,monospace" font-size="7.5" fill="#F2F2F2"  text-anchor="middle" opacity="0.55">Java · SQL</text>
<text x="406" y="44" font-family="Share Tech Mono,monospace" font-size="8"   fill="#E63946"  text-anchor="middle" opacity="0.9">2023</text>
<text x="406" y="33" font-family="Share Tech Mono,monospace" font-size="7.5" fill="#F2F2F2"  text-anchor="middle" opacity="0.75">Spring Boot</text>
<!-- labels bottom -->
<text x="554" y="82" font-family="Share Tech Mono,monospace" font-size="8"   fill="#FFD700"  text-anchor="middle" opacity="0.9">2024</text>
<text x="554" y="95" font-family="Share Tech Mono,monospace" font-size="7.5" fill="#F2F2F2"  text-anchor="middle" opacity="0.75">Docker · APIs</text>
<text x="702" y="82" font-family="Share Tech Mono,monospace" font-size="8"   fill="#FFD700"  text-anchor="middle" opacity="0.9">2025</text>
<text x="702" y="95" font-family="Share Tech Mono,monospace" font-size="7.5" fill="#F2F2F2"  text-anchor="middle" opacity="0.75">Microservices</text>
<text x="790" y="82" font-family="Share Tech Mono,monospace" font-size="8"   fill="#8A8A8A"  text-anchor="middle" opacity="0.6">2026</text>
<text x="790" y="95" font-family="Share Tech Mono,monospace" font-size="7.5" fill="#F2F2F2"  text-anchor="middle" opacity="0.35">C++ · Systems</text>
</svg>
</div>

<br/>

<!-- ─── DIVIDER ──────────────────────────────────────────────────── -->
<div align="center"><svg width="860" height="18" viewBox="0 0 860 18" xmlns="http://www.w3.org/2000/svg"><defs><linearGradient id="d5" x1="0" y1="0" x2="1" y2="0"><stop offset="0%" stop-color="#090909" stop-opacity="0"/><stop offset="15%" stop-color="#E63946" stop-opacity="0.7"/><stop offset="50%" stop-color="#FFD700" stop-opacity="0.9"/><stop offset="85%" stop-color="#E63946" stop-opacity="0.7"/><stop offset="100%" stop-color="#090909" stop-opacity="0"/></linearGradient><filter id="fd5"><feGaussianBlur stdDeviation="1" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter></defs><rect x="0" y="8" width="860" height="1" fill="url(#d5)" opacity="0.15"/><rect x="0" y="9" width="860" height="1" fill="url(#d5)" filter="url(#fd5)"/><rect x="0" y="8" width="50" height="2" fill="url(#d5)" opacity="0.7" filter="url(#fd5)"><animateTransform attributeName="transform" type="translate" from="-50 0" to="910 0" dur="3s" repeatCount="indefinite"/></rect><rect x="425" y="5" width="10" height="8" rx="1" fill="#090909"/><line x1="428" y1="9" x2="432" y2="9" stroke="#FFD700" stroke-width="1" opacity="0.8" filter="url(#fd5)"/></svg></div>

<br/>

<!-- ─── METRICS ──────────────────────────────────────────────────── -->

<div align="center">
  <img height="158" src="https://github-readme-stats.vercel.app/api?username=CVbarro&show_icons=true&hide_border=true&count_private=true&hide_title=true&bg_color=090909&icon_color=E63946&text_color=8A8A8A&ring_color=FFD700&rank_icon=github"/>
  <img height="158" src="https://github-readme-stats.vercel.app/api/top-langs/?username=CVbarro&layout=compact&hide_border=true&bg_color=090909&title_color=E63946&text_color=8A8A8A&langs_count=8"/>
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=CVbarro&hide_border=true&background=090909&stroke=E63946&ring=FFD700&fire=E63946&currStreakLabel=FFD700&sideLabels=8A8A8A&dates=444444&sideNums=E63946&currStreakNum=FFD700"/>
</div>

<br/>

<!-- ─── DIVIDER ──────────────────────────────────────────────────── -->
<div align="center"><svg width="860" height="18" viewBox="0 0 860 18" xmlns="http://www.w3.org/2000/svg"><defs><linearGradient id="d6" x1="0" y1="0" x2="1" y2="0"><stop offset="0%" stop-color="#090909" stop-opacity="0"/><stop offset="15%" stop-color="#E63946" stop-opacity="0.7"/><stop offset="50%" stop-color="#FFD700" stop-opacity="0.9"/><stop offset="85%" stop-color="#E63946" stop-opacity="0.7"/><stop offset="100%" stop-color="#090909" stop-opacity="0"/></linearGradient><filter id="fd6"><feGaussianBlur stdDeviation="1" result="b"/><feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge></filter></defs><rect x="0" y="8" width="860" height="1" fill="url(#d6)" opacity="0.15"/><rect x="0" y="9" width="860" height="1" fill="url(#d6)" filter="url(#fd6)"/><rect x="0" y="8" width="50" height="2" fill="url(#d6)" opacity="0.7" filter="url(#fd6)"><animateTransform attributeName="transform" type="translate" from="-50 0" to="910 0" dur="3s" repeatCount="indefinite"/></rect><rect x="425" y="5" width="10" height="8" rx="1" fill="#090909"/><line x1="428" y1="9" x2="432" y2="9" stroke="#FFD700" stroke-width="1" opacity="0.8" filter="url(#fd6)"/></svg></div>

<br/>

<!-- ─── SNAKE ───────────────────────────────────────────────────── -->

<div align="center">
  <img src="https://raw.githubusercontent.com/CVbarro/CVbarro/output/github-contribution-grid-snake-dark.svg"/>
</div>

<br/>

<!-- ─── FOOTER ──────────────────────────────────────────────────── -->

<div align="center">
<svg width="860" height="44" viewBox="0 0 860 44" xmlns="http://www.w3.org/2000/svg">
<defs>
  <linearGradient id="fb" x1="0" y1="0" x2="0" y2="1"><stop offset="0%" stop-color="#090909"/><stop offset="100%" stop-color="#0d0202"/></linearGradient>
  <linearGradient id="fl" x1="0" y1="0" x2="1" y2="0"><stop offset="0%" stop-color="#090909" stop-opacity="0"/><stop offset="18%" stop-color="#E63946" stop-opacity="0.6"/><stop offset="82%" stop-color="#E63946" stop-opacity="0.6"/><stop offset="100%" stop-color="#090909" stop-opacity="0"/></linearGradient>
</defs>
<rect width="860" height="44" fill="url(#fb)"/>
<rect x="0" y="0" width="860" height="1.5" fill="url(#fl)"/>
<text x="430" y="28" font-family="Share Tech Mono,monospace" font-size="9" fill="#F2F2F2" text-anchor="middle" opacity="0.2" letter-spacing="2">CVBARRO  ·  BACKEND ENGINEER  ·  BRAZIL  ·  2025</text>
</svg>
</div>
