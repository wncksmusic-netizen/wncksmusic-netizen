<svg xmlns="http://www.w3.org/2000/svg" width="920" height="400" viewBox="0 0 920 400" role="img" aria-labelledby="card-title card-description">
  <title id="card-title">김주찬 · Front-End Developer</title>
  <desc id="card-description">빠른 사용자 경험과 확장 가능한 웹 구조를 고민합니다.</desc>
  <defs>
    <linearGradient id="card-background" x1="0" y1="0" x2="1" y2="1">
      <stop offset="0" stop-color="#04111f"><animate attributeName="stop-color" values="#04111f;#082a40;#04111f" dur="10s" repeatCount="indefinite"/></stop>
      <stop offset="1" stop-color="#082a40"/>
    </linearGradient>
    <linearGradient id="accent-line" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0" stop-color="#38bdf8"/>
      <stop offset="1" stop-color="#22d3ee"/>
    </linearGradient>
    <linearGradient id="shine-gradient" x1="0" y1="0" x2="1" y2="0">
      <stop offset="0" stop-color="#ffffff" stop-opacity="0"/>
      <stop offset=".5" stop-color="#ffffff" stop-opacity=".07"/>
      <stop offset="1" stop-color="#ffffff" stop-opacity="0"/>
    </linearGradient>
    <pattern id="grid" width="24" height="24" patternUnits="userSpaceOnUse">
      <path d="M 24 0 L 0 0 0 24" fill="none" stroke="#6799b3" stroke-opacity=".08" stroke-width="1"/>
    </pattern>
    <clipPath id="card-clip"><rect width="920" height="400" rx="24"/></clipPath>
  </defs>
  <style>
    :root { --text: #f0f9ff; --muted: #9bc4da; --accent: #38bdf8; --accent-2: #22d3ee; --surface: #0a2132; --surface-border: #184a67; --chip: #0b2c42; --chip-border: #24749a; }
    text { font-family: Inter, Pretendard, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif; }
    .eyebrow { fill: var(--accent); font-size: 12px; font-weight: 700; letter-spacing: 2.4px; }
    .name { fill: var(--text); font-size: 33px; font-weight: 750; letter-spacing: -.5px; }
    .english-name { fill: var(--muted); font-size: 14px; font-weight: 500; }
    .role { fill: var(--text); font-size: 19px; font-weight: 650; }
    .description { fill: var(--muted); font-size: 15px; font-weight: 450; }
    .section-label { fill: var(--muted); font-size: 11px; font-weight: 700; letter-spacing: 1.8px; }
    .skill-text { fill: var(--text); font-size: 12px; font-weight: 600; }
    .growth-text { fill: var(--text); font-size: 14px; font-weight: 600; }
    .path-line { stroke: var(--accent); stroke-width: 1.5; stroke-opacity: .55; stroke-dasharray: 4 6; }
    
      .ambient { animation: float 8s ease-in-out infinite alternate; }
      .role-cursor { animation: blink 1s steps(1) infinite; }
      .shine { animation: sweep 5s ease-in-out infinite; }
      .path-line { animation: dash 2.4s linear infinite; }
      .skill, .growth { opacity: 0; animation: reveal .55s ease forwards; }
      .skill-1, .growth-1 { animation-delay: .15s; }
      .skill-2, .growth-2 { animation-delay: .28s; }
      .skill-3, .growth-3 { animation-delay: .41s; }
      .skill-4, .growth-4 { animation-delay: .54s; }
      .skill-5 { animation-delay: .67s; }
      .skill-6 { animation-delay: .80s; }
      .skill-7 { animation-delay: .93s; }
      .skill-8 { animation-delay: 1.06s; }
      @keyframes float { from { transform: translate(-10px, -7px); } to { transform: translate(12px, 10px); } }
      @keyframes blink { 0%, 48% { opacity: 1; } 49%, 100% { opacity: 0; } }
      @keyframes sweep { 0%, 15% { transform: translateX(-260px); } 65%, 100% { transform: translateX(940px); } }
      @keyframes dash { to { stroke-dashoffset: -20; } }
      @keyframes reveal { from { opacity: 0; } to { opacity: 1; } }
      @media (prefers-reduced-motion: reduce) {
        * { animation: none !important; }
        .skill, .growth { opacity: 1; }
      }
  </style>
  <g clip-path="url(#card-clip)">
    <rect width="920" height="400" rx="24" fill="url(#card-background)"/>
    <rect width="920" height="400" fill="url(#grid)"/>
    <circle class="ambient" cx="826" cy="-18" r="150" fill="#38bdf8" fill-opacity=".10"/>
    <circle class="ambient" cx="72" cy="414" r="118" fill="#22d3ee" fill-opacity=".08"/>
    <rect class="shine" x="-260" y="0" width="220" height="400" fill="url(#shine-gradient)" transform="skewX(-18)"/>

    <g transform="translate(52 45)">
      <rect width="32" height="5" rx="2.5" fill="url(#accent-line)"/>
      <text class="eyebrow" x="0" y="32">PROFILE / JUCHAN</text>
      <text class="name" x="0" y="78">김주찬</text>
      <text class="english-name" x="129" y="76">· Kim Juchan</text>
      <text class="role" x="0" y="116">Front-End Developer</text>
      <rect class="role-cursor" x="213.20000000000002" y="98" width="2" height="22" rx="1" fill="var(--accent)"/>
      <text class="description" x="0" y="154">빠른 사용자 경험과 확장 가능한 웹 구조를 고민합니다.</text>
      <text class="section-label" x="0" y="201">TECH STACK</text>
    </g>

    
      <g class="skill skill-1" transform="translate(52 267)">
        <rect width="58" height="31" rx="15.5" fill="var(--chip)" stroke="var(--chip-border)"/>
        <text x="29" y="16" text-anchor="middle" dominant-baseline="middle" class="skill-text">Vue</text>
      </g>
      <g class="skill skill-2" transform="translate(120 267)">
        <rect width="58.8" height="31" rx="15.5" fill="var(--chip)" stroke="var(--chip-border)"/>
        <text x="29.4" y="16" text-anchor="middle" dominant-baseline="middle" class="skill-text">Nuxt</text>
      </g>
      <g class="skill skill-3" transform="translate(188.8 267)">
        <rect width="108" height="31" rx="15.5" fill="var(--chip)" stroke="var(--chip-border)"/>
        <text x="54" y="16" text-anchor="middle" dominant-baseline="middle" class="skill-text">TypeScript</text>
      </g>
      <g class="skill skill-4" transform="translate(306.8 267)">
        <rect width="67" height="31" rx="15.5" fill="var(--chip)" stroke="var(--chip-border)"/>
        <text x="33.5" y="16" text-anchor="middle" dominant-baseline="middle" class="skill-text">Pinia</text>
      </g>
      <g class="skill skill-5" transform="translate(383.8 267)">
        <rect width="124.39999999999999" height="31" rx="15.5" fill="var(--chip)" stroke="var(--chip-border)"/>
        <text x="62.199999999999996" y="16" text-anchor="middle" dominant-baseline="middle" class="skill-text">Tailwind CSS</text>
      </g>
      <g class="skill skill-6" transform="translate(52 310)">
        <rect width="83.39999999999999" height="31" rx="15.5" fill="var(--chip)" stroke="var(--chip-border)"/>
        <text x="41.699999999999996" y="16" text-anchor="middle" dominant-baseline="middle" class="skill-text">Node.js</text>
      </g>
      <g class="skill skill-7" transform="translate(145.39999999999998 310)">
        <rect width="75.19999999999999" height="31" rx="15.5" fill="var(--chip)" stroke="var(--chip-border)"/>
        <text x="37.599999999999994" y="16" text-anchor="middle" dominant-baseline="middle" class="skill-text">NestJS</text>
      </g>

    <g transform="translate(626 48)">
      <rect width="246" height="304" rx="18" fill="var(--surface)" fill-opacity=".72" stroke="var(--surface-border)"/>
      <text class="section-label" x="25" y="38">GROWTH PATH</text>
      <text x="25" y="65" fill="var(--text)" font-size="18" font-weight="700">Building forward</text>
      <g transform="translate(25 0)">
      <g class="growth growth-1">
        <circle cx="15" cy="139" r="8" fill="var(--surface)" stroke="var(--accent)" stroke-width="2"/>
        <circle cx="15" cy="139" r="3" fill="var(--accent)"/>
        <text x="35" y="140" dominant-baseline="middle" class="growth-text">Front-End</text>
        <path d="M 15 153 V 187" class="path-line"/>
      </g>
      <g class="growth growth-2">
        <circle cx="15" cy="196" r="8" fill="var(--surface)" stroke="var(--accent)" stroke-width="2"/>
        <circle cx="15" cy="196" r="3" fill="var(--accent)"/>
        <text x="35" y="197" dominant-baseline="middle" class="growth-text">Full-stack</text>
        <path d="M 15 210 V 244" class="path-line"/>
      </g>
      <g class="growth growth-3">
        <circle cx="15" cy="253" r="8" fill="var(--surface)" stroke="var(--accent)" stroke-width="2"/>
        <circle cx="15" cy="253" r="3" fill="var(--accent)"/>
        <text x="35" y="254" dominant-baseline="middle" class="growth-text">DevOps</text>
        
      </g></g>
      <rect x="25" y="278" width="196" height="2" rx="1" fill="url(#accent-line)" opacity=".75"/>
    </g>

    <g transform="translate(52 371)">
      <circle cx="4" cy="-4" r="4" fill="var(--accent)"/>
      <text x="16" y="0" fill="var(--muted)" font-size="11" font-weight="600">GITHUB PROFILE CARD · SVG</text>
    </g>
  </g>
  <rect x=".75" y=".75" width="918.5" height="398.5" rx="23.25" fill="none" stroke="#184a67" stroke-width="1.5"/>
<script xmlns=""/></svg>
