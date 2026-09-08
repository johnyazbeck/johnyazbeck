<svg xmlns="http://www.w3.org/2000/svg" width="1200" height="2800" viewBox="0 0 1200 2800">

<defs>
  <linearGradient id="bg" x1="0" y1="0" x2="1" y2="1">
    <stop offset="0" stop-color="#0d1117"/>
    <stop offset="0.55" stop-color="#111827"/>
    <stop offset="1" stop-color="#0b1220"/>
  </linearGradient>

  <linearGradient id="hero" x1="0" y1="0" x2="1" y2="0">
    <stop offset="0" stop-color="#e32636"/>
    <stop offset="0.5" stop-color="#f2c94c"/>
    <stop offset="1" stop-color="#2d9cdb"/>
  </linearGradient>

  <linearGradient id="cyan" x1="0" y1="0" x2="1" y2="1">
    <stop offset="0" stop-color="#2d9cdb"/>
    <stop offset="1" stop-color="#7c5cff"/>
  </linearGradient>

  <pattern id="grid" width="40" height="40" patternUnits="userSpaceOnUse">
    <path d="M40 0H0V40" fill="none" stroke="#263142" stroke-width="1"/>
  </pattern>

  <filter id="glowRed">
    <feGaussianBlur stdDeviation="8" result="b"/>
    <feMerge>
      <feMergeNode in="b"/>
      <feMergeNode in="SourceGraphic"/>
    </feMerge>
  </filter>

  <filter id="glowBlue">
    <feGaussianBlur stdDeviation="10" result="b"/>
    <feMerge>
      <feMergeNode in="b"/>
      <feMergeNode in="SourceGraphic"/>
    </feMerge>
  </filter>

  <style>
    .title{
      font:900 78px Arial,Helvetica,sans-serif;
      letter-spacing:-3px;
      fill:#f0f6fc
    }

    .h2{
      font:900 38px Arial,Helvetica,sans-serif;
      letter-spacing:-1px;
      fill:#f0f6fc
    }

    .h3{
      font:700 20px Arial,Helvetica,sans-serif;
      fill:#f0f6fc
    }

    .body{
      font:500 17px Arial,Helvetica,sans-serif;
      fill:#c9d1d9
    }

    .small{
      font:700 12px monospace;
      letter-spacing:1.5px;
      fill:#8b949e
    }

    .mono{
      font:700 14px monospace;
      letter-spacing:1px;
      fill:#e6edf3
    }

    .tag{
      font:700 14px Arial,Helvetica,sans-serif;
      fill:#0d1117
    }

    .white{fill:#f0f6fc}
    .muted{fill:#8b949e}
    .red{fill:#e32636}
    .yellow{fill:#f2c94c}
    .blue{fill:#2d9cdb}
    .green{fill:#2ea043}
  </style>
</defs>


<!-- ========================================================= -->
<!-- BACKGROUND -->
<!-- ========================================================= -->

<rect width="1200" height="2800" fill="url(#bg)"/>
<rect width="1200" height="2800" fill="url(#grid)" opacity=".75"/>

<rect
  x="4"
  y="4"
  width="1192"
  height="2792"
  rx="4"
  fill="none"
  stroke="#e32636"
  stroke-width="4"
/>


<!-- ========================================================= -->
<!-- REGISTRATION MARKS -->
<!-- ========================================================= -->

<g stroke="#e32636" stroke-width="3" fill="none">
  <path d="M20 44V20H44"/>
  <path d="M1156 20h24v24"/>
  <path d="M20 2756v24h24"/>
  <path d="M1156 2780h24v-24"/>
</g>


<!-- ========================================================= -->
<!-- HEADER -->
<!-- ========================================================= -->

<g transform="translate(60 60)">

  <!-- Color bars -->
  <rect x="0" y="0" width="80" height="14" rx="2" fill="#e32636"/>
  <rect x="95" y="0" width="26" height="14" fill="#f2c94c"/>
  <rect x="135" y="0" width="50" height="14" fill="#2d9cdb"/>

  <!-- Name -->
  <text x="0" y="92" class="title">JOHN</text>
  <text x="0" y="160" class="title">YAZBECK</text>

  <!-- Role banner -->
  <rect x="0" y="188" width="575" height="48" rx="4" fill="url(#hero)"/>

  <text
    x="18"
    y="219"
    font-family="monospace"
    font-size="14"
    font-weight="700"
    fill="#0d1117"
  >
    SOFTWARE ENGINEER
  </text>

  <text
    x="190"
    y="219"
    font-size="13"
    font-weight="900"
    fill="#0d1117"
  >■</text>

  <text
    x="212"
    y="219"
    font-family="monospace"
    font-size="14"
    font-weight="700"
    fill="#0d1117"
  >
    FULL-STACK
  </text>

  <text
    x="338"
    y="219"
    font-size="13"
    font-weight="900"
    fill="#0d1117"
  >■</text>

  <text
    x="360"
    y="219"
    font-family="monospace"
    font-size="14"
    font-weight="700"
    fill="#0d1117"
  >
    CTF HUNTER
  </text>


  <!-- Geometric art -->
  <g transform="translate(770,-5)">

    <circle
      cx="180"
      cy="105"
      r="105"
      fill="#e32636"
      opacity=".75"
      filter="url(#glowRed)"
    />

    <rect
      x="35"
      y="155"
      width="155"
      height="155"
      fill="#2d9cdb"
      opacity=".7"
    />

    <path
      d="M0 230L170 60
         M-10 260L200 50
         M35 290L230 95"
      stroke="#f2c94c"
      stroke-width="10"
      opacity=".8"
    />

    <circle
      cx="180"
      cy="105"
      r="48"
      fill="none"
      stroke="#f0f6fc"
      stroke-width="2"
      opacity=".8"
    />

  </g>


  <!-- Manifest -->
  <g transform="translate(0 285)">

    <line
      x1="0"
      y1="0"
      x2="650"
      y2="0"
      stroke="#30363d"
      stroke-width="2"
    />

    <text x="0" y="28" class="small red">01</text>
    <text x="45" y="28" class="mono">
      BUILDING SCALABLE SYSTEMS
    </text>

    <line
      x1="0"
      y1="45"
      x2="650"
      y2="45"
      stroke="#30363d"
    />

    <text x="0" y="73" class="small yellow">02</text>
    <text x="45" y="73" class="mono">
      BREAKING THINGS LEGALLY
    </text>

    <line
      x1="0"
      y1="90"
      x2="650"
      y2="90"
      stroke="#30363d"
    />

    <text x="0" y="118" class="small blue">03</text>
    <text x="45" y="118" class="mono">
      MOBILE &amp; WEB CRAFTSMAN
    </text>

    <line
      x1="0"
      y1="135"
      x2="650"
      y2="135"
      stroke="#30363d"
    />

    <text x="0" y="163" class="small green">04</text>
    <text x="45" y="163" class="mono">
      LIFELONG LEARNER
    </text>

  </g>


  <!-- Telemetry -->
  <g transform="translate(850 330)">

    <g fill="#f0f6fc">
      <rect x="0" y="0" width="5" height="42"/>
      <rect x="11" y="0" width="13" height="42"/>
      <rect x="30" y="0" width="4" height="42"/>
      <rect x="40" y="0" width="9" height="42"/>
      <rect x="55" y="0" width="22" height="42"/>
      <rect x="83" y="0" width="7" height="42"/>
      <rect x="96" y="0" width="4" height="42"/>
      <rect x="106" y="0" width="17" height="42"/>
      <rect x="129" y="0" width="6" height="42"/>
    </g>

    <text x="0" y="66" class="small">
      REF_ID: JY-2026
    </text>

    <circle
      cx="8"
      cy="88"
      r="5"
      fill="#2d9cdb"
    />

    <text x="22" y="93" class="small">
      SYS_STATUS: ACTIVE
    </text>

    <text x="0" y="118" class="small">
      MODE: BUILDING
    </text>

  </g>

</g>


<!-- ========================================================= -->
<!-- OPERATIONS & OBJECTIVES -->
<!-- ========================================================= -->

<line
  x1="60"
  y1="560"
  x2="1140"
  y2="560"
  stroke="#30363d"
  stroke-width="4"
/>

<rect
  x="60"
  y="600"
  width="16"
  height="16"
  fill="#e32636"
/>

<text
  x="100"
  y="617"
  class="h2"
>
  OPERATIONS &amp; OBJECTIVES
</text>


<!-- ========================================================= -->
<!-- CURRENT SCOPE -->
<!-- ========================================================= -->

<rect
  x="60"
  y="665"
  width="515"
  height="480"
  rx="10"
  fill="#111827"
  stroke="#30363d"
/>

<text
  x="85"
  y="705"
  class="h3"
>
  CURRENT SCOPE
</text>

<line
  x1="85"
  y1="720"
  x2="550"
  y2="720"
  stroke="#30363d"
  stroke-width="2"
/>

<rect
  x="85"
  y="745"
  width="260"
  height="30"
  rx="4"
  fill="#e32636"
/>

<text
  x="96"
  y="766"
  font-family="Arial,Helvetica,sans-serif"
  font-size="14"
  font-weight="700"
  fill="#0d1117"
>
  SOFTWARE ENGINEERING GRADUATE
</text>

<text x="85" y="805" class="body">
  HELB Ilya Prigogine (Brussels) with a strong
</text>

<text x="85" y="830" class="body">
  foundation in computer science and hands-on
</text>

<text x="85" y="855" class="body">
  experience through academic projects and an
</text>

<text x="85" y="880" class="body">
  internship at MyGridEnergy.
</text>

<text x="85" y="915" class="body">
  Focused on backend development, software
</text>

<text x="85" y="940" class="body">
  architecture, and AI-powered applications.
</text>


<!-- MyGridEnergy timeline -->
<line
  x1="100"
  y1="980"
  x2="100"
  y2="1060"
  stroke="#e32636"
  stroke-width="3"
/>

<circle
  cx="100"
  cy="980"
  r="7"
  fill="#e32636"
/>

<text x="125" y="985" class="h3">
  MyGridEnergy
</text>

<text x="125" y="1008" class="small red">
  INTERNSHIP 2026
</text>

<text x="125" y="1032" class="body">
  Professional software development
</text>

<text x="125" y="1055" class="body">
  and real-world engineering experience.
</text>


<!-- ========================================================= -->
<!-- CTF ENGAGEMENTS -->
<!-- ========================================================= -->

<rect
  x="625"
  y="665"
  width="515"
  height="480"
  rx="10"
  fill="#111827"
  stroke="#30363d"
/>

<text
  x="650"
  y="705"
  class="h3"
>
  CTF ENGAGEMENTS
</text>

<line
  x1="650"
  y1="720"
  x2="1115"
  y2="720"
  stroke="#30363d"
  stroke-width="2"
/>

<g transform="translate(650 760)">

  <!-- CTF 1 -->
  <circle
    cx="16"
    cy="0"
    r="13"
    fill="#f2c94c"
  />

  <text
    x="8"
    y="6"
    font-size="15"
  >★</text>

  <text
    x="45"
    y="6"
    class="h3"
  >
    Federal Police CTF Belgium
  </text>

  <text
    x="430"
    y="6"
    class="small"
  >
    2024/25
  </text>

  <line
    x1="0"
    y1="35"
    x2="465"
    y2="35"
    stroke="#30363d"
  />


  <!-- CTF 2 -->
  <circle
    cx="16"
    cy="65"
    r="13"
    fill="#f2c94c"
  />

  <text
    x="8"
    y="71"
    font-size="15"
  >★</text>

  <text
    x="45"
    y="71"
    class="h3"
  >
    CyberCrusade CTF HELB
  </text>

  <text
    x="430"
    y="71"
    class="small"
  >
    2024/25
  </text>

  <line
    x1="0"
    y1="100"
    x2="465"
    y2="100"
    stroke="#30363d"
  />


  <!-- CTF 3 -->
  <circle
    cx="16"
    cy="130"
    r="13"
    fill="#2d9cdb"
  />

  <text
    x="8"
    y="136"
    font-size="15"
  >⚡</text>

  <text
    x="45"
    y="136"
    class="h3"
  >
    CyberWeek Wallonia (Pro)
  </text>

  <text
    x="430"
    y="136"
    class="small"
  >
    2024/25
  </text>

  <line
    x1="0"
    y1="165"
    x2="465"
    y2="165"
    stroke="#30363d"
  />


  <!-- CTF 4 -->
  <circle
    cx="16"
    cy="195"
    r="13"
    fill="#2d9cdb"
  />

  <text
    x="8"
    y="201"
    font-size="15"
  >⚡</text>

  <text
    x="45"
    y="201"
    class="h3"
  >
    HACK'N WOW
  </text>

  <text
    x="430"
    y="201"
    class="small"
  >
    2024/25
  </text>

  <line
    x1="0"
    y1="230"
    x2="465"
    y2="230"
    stroke="#30363d"
  />


  <!-- CTF 5 -->
  <circle
    cx="16"
    cy="260"
    r="13"
    fill="#e32636"
  />

  <text
    x="8"
    y="266"
    font-size="15"
  >◆</text>

  <text
    x="45"
    y="266"
    class="h3"
  >
    Odoo Hackathon — UI Without Text
  </text>

  <text
    x="430"
    y="266"
    class="small"
  >
    2025
  </text>

</g>


<!-- ========================================================= -->
<!-- TECHNICAL ARSENAL -->
<!-- ========================================================= -->

<line
  x1="60"
  y1="1210"
  x2="1140"
  y2="1210"
  stroke="#30363d"
  stroke-width="4"
/>

<rect
  x="60"
  y="1250"
  width="16"
  height="16"
  fill="#2d9cdb"
/>

<text
  x="100"
  y="1267"
  class="h2"
>
  TECHNICAL ARSENAL
</text>


<!-- Tech groups -->
<g transform="translate(60 1315)">

  <!-- Core languages -->
  <text x="0" y="0" class="small">
    CORE LANGUAGES
  </text>

  <g transform="translate(0 25)">

    <rect
      width="90"
      height="36"
      rx="6"
      fill="#e32636"
    />
    <text x="20" y="23" class="tag">JAVA</text>

    <rect
      x="102"
      width="80"
      height="36"
      rx="6"
      fill="#e32636"
    />
    <text x="126" y="23" class="tag">C#</text>

    <rect
      x="194"
      width="100"
      height="36"
      rx="6"
      fill="#e32636"
    />
    <text x="215" y="23" class="tag">PYTHON</text>

    <rect
      x="306"
      width="115"
      height="36"
      rx="6"
      fill="#f2c94c"
    />
    <text x="325" y="23" class="tag">JAVASCRIPT</text>

    <rect
      x="433"
      width="75"
      height="36"
      rx="6"
      fill="#2d9cdb"
    />
    <text x="452" y="23" class="tag">PHP</text>

    <rect
      x="520"
      width="80"
      height="36"
      rx="6"
      fill="#212936"
      stroke="#485260"
    />
    <text
      x="543"
      y="23"
      class="white"
      font-family="Arial"
      font-size="14"
      font-weight="700"
    >
      C++
    </text>

    <rect
      x="612"
      width="120"
      height="36"
      rx="6"
      fill="#212936"
      stroke="#485260"
    />
    <text
      x="626"
      y="23"
      class="white"
      font-family="Arial"
      font-size="14"
      font-weight="700"
    >
      HTML / CSS
    </text>

  </g>


  <!-- Frameworks -->
  <text
    x="0"
    y="105"
    class="small"
  >
    FRAMEWORKS &amp; LIBRARIES
  </text>

  <g transform="translate(0 130)">

    <rect
      width="105"
      height="36"
      rx="6"
      fill="#e32636"
    />
    <text x="15" y="23" class="tag">
      .NET MAUI
    </text>

    <rect
      x="117"
      width="125"
      height="36"
      rx="6"
      fill="#e32636"
    />
    <text x="130" y="23" class="tag">
      .NET FRAMEWORK
    </text>

    <rect
      x="254"
      width="135"
      height="36"
      rx="6"
      fill="#2d9cdb"
    />
    <text x="273" y="23" class="tag">
      REACT
    </text>

    <rect
      x="401"
      width="155"
      height="36"
      rx="6"
      fill="#2d9cdb"
    />
    <text x="415" y="23" class="tag">
      REACT NATIVE
    </text>

    <rect
      x="568"
      width="95"
      height="36"
      rx="6"
      fill="#1f6feb"
    />
    <text
      x="588"
      y="23"
      class="white"
      font-family="Arial"
      font-size="14"
      font-weight="700"
    >
      DJANGO
    </text>

    <rect
      x="675"
      width="125"
      height="36"
      rx="6"
      fill="#1f6feb"
    />
    <text
      x="688"
      y="23"
      class="white"
      font-family="Arial"
      font-size="14"
      font-weight="700"
    >
      SPRING BOOT
    </text>

    <rect
      x="812"
      width="95"
      height="36"
      rx="6"
      fill="#f2c94c"
    />
    <text x="827" y="23" class="tag">
      JAVAFX
    </text>

    <rect
      x="919"
      width="80"
      height="36"
      rx="6"
      fill="#2ea043"
    />
    <text x="938" y="23" class="tag">
      UNITY
    </text>

  </g>


  <!-- Databases -->
  <text
    x="0"
    y="210"
    class="small"
  >
    DATABASES / STORES
  </text>

  <g transform="translate(0 235)">

    <rect
      width="115"
      height="36"
      rx="6"
      fill="#2d9cdb"
    />
    <text x="17" y="23" class="tag">
      POSTGRESQL
    </text>

    <rect
      x="127"
      width="85"
      height="36"
      rx="6"
      fill="#1f6feb"
    />
    <text
      x="145"
      y="23"
      class="white"
      font-family="Arial"
      font-size="14"
      font-weight="700"
    >
      MYSQL
    </text>

    <rect
      x="224"
      width="105"
      height="36"
      rx="6"
      fill="#212936"
      stroke="#485260"
    />
    <text
      x="240"
      y="23"
      class="white"
      font-family="Arial"
      font-size="14"
      font-weight="700"
    >
      MONGODB
    </text>

    <rect
      x="341"
      width="90"
      height="36"
      rx="6"
      fill="#e32636"
    />
    <text x="360" y="23" class="tag">
      SQLITE
    </text>

    <rect
      x="443"
      width="95"
      height="36"
      rx="6"
      fill="#f2c94c"
    />
    <text x="458" y="23" class="tag">
      FIREBASE
    </text>

  </g>


  <!-- Tools -->
  <text
    x="600"
    y="210"
    class="small"
  >
    TOOLS &amp; PLATFORMS
  </text>

  <g transform="translate(600 235)">

    <rect
      width="70"
      height="36"
      rx="6"
      fill="#f2c94c"
    />
    <text x="20" y="23" class="tag">
      GIT
    </text>

    <rect
      x="82"
      width="90"
      height="36"
      rx="6"
      fill="#2d9cdb"
    />
    <text x="100" y="23" class="tag">
      GITHUB
    </text>

    <rect
      x="184"
      width="80"
      height="36"
      rx="6"
      fill="#2d9cdb"
    />
    <text x="202" y="23" class="tag">
      LINUX
    </text>

    <rect
      x="276"
      width="125"
      height="36"
      rx="6"
      fill="#e32636"
    />
    <text x="291" y="23" class="tag">
      ANDROID STUDIO
    </text>

    <rect
      x="413"
      width="80"
      height="36"
      rx="6"
      fill="#212936"
      stroke="#485260"
    />
    <text
      x="429"
      y="23"
      class="white"
      font-family="Arial"
      font-size="14"
      font-weight="700"
    >
      POSTMAN
    </text>

    <rect
      x="505"
      width="75"
      height="36"
      rx="6"
      fill="#2ea043"
    />
    <text x="522" y="23" class="tag">
      FIGMA
    </text>

    <rect
      x="592"
      width="75"
      height="36"
      rx="6"
      fill="#212936"
      stroke="#485260"
    />
    <text
      x="608"
      y="23"
      class="white"
      font-family="Arial"
      font-size="14"
      font-weight="700"
    >
      XAMPP
    </text>

  </g>

</g>


<!-- ========================================================= -->
<!-- PROJECTS & EDUCATION -->
<!-- ========================================================= -->

<line
  x1="60"
  y1="1710"
  x2="1140"
  y2="1710"
  stroke="#30363d"
  stroke-width="4"
/>

<rect
  x="60"
  y="1750"
  width="16"
  height="16"
  fill="#f2c94c"
/>

<text
  x="100"
  y="1767"
  class="h2"
>
  PROJECTS &amp; EDUCATION
</text>


<!-- ========================================================= -->
<!-- FEATURED PROJECTS -->
<!-- ========================================================= -->

<g transform="translate(60 1815)">

  <rect
    width="520"
    height="710"
    rx="10"
    fill="#111827"
    stroke="#30363d"
  />

  <text
    x="25"
    y="42"
    class="h3"
  >
    FEATURED PROJECTS
  </text>

  <g transform="translate(25 75)">

    <!-- Ice Cream Simulator -->
    <circle
      cx="7"
      cy="0"
      r="7"
      fill="#f2c94c"
    />

    <text
      x="25"
      y="6"
      class="h3"
    >
      Ice Cream Simulator
    </text>

    <text
      x="25"
      y="28"
      class="small yellow"
    >
      .NET MAUI + ARDUINO
    </text>

    <text
      x="25"
      y="52"
      class="body"
    >
      Cross-platform simulator with real-time
    </text>

    <text
      x="25"
      y="75"
      class="body"
    >
      temperature &amp; humidity monitoring.
    </text>


    <!-- Duo-Codeur -->
    <circle
      cx="7"
      cy="105"
      r="7"
      fill="#2d9cdb"
    />

    <text
      x="25"
      y="111"
      class="h3"
    >
      Duo-Codeur
    </text>

    <text
      x="25"
      y="133"
      class="small blue"
    >
      REACT NATIVE + EXPO GO
    </text>

    <text
      x="25"
      y="157"
      class="body"
    >
      Gamified coding-learning mobile app
    </text>

    <text
      x="25"
      y="180"
      class="body"
    >
      with external API integration.
    </text>


    <!-- Stocks & Commands -->
    <circle
      cx="7"
      cy="210"
      r="7"
      fill="#e32636"
    />

    <text
      x="25"
      y="216"
      class="h3"
    >
      Stocks &amp; Commands
    </text>

    <text
      x="25"
      y="238"
      class="small red"
    >
      JAVA + SPRING BOOT
    </text>

    <text
      x="25"
      y="262"
      class="body"
    >
      Inventory and order management backend
    </text>

    <text
      x="25"
      y="285"
      class="body"
    >
      with REST APIs and Maven.
    </text>


    <!-- Biblioplane -->
    <circle
      cx="7"
      cy="315"
      r="7"
      fill="#2ea043"
    />

    <text
      x="25"
      y="321"
      class="h3"
    >
      Biblioplane
    </text>

    <text
      x="25"
      y="343"
      class="small green"
    >
      ANDROID + FIREBASE
    </text>

    <text
      x="25"
      y="367"
      class="body"
    >
      Campus library locator with maps, books
    </text>

    <text
      x="25"
      y="390"
      class="body"
    >
      and user ratings.
    </text>


    <!-- Collaborative Canvas -->
    <circle
      cx="7"
      cy="420"
      r="7"
      fill="#7c5cff"
    />

    <text
      x="25"
      y="426"
      class="h3"
    >
      Collaborative Canvas
    </text>

    <text
      x="25"
      y="448"
      class="small"
      fill="#7c5cff"
    >
      DJANGO + JAVASCRIPT
    </text>

    <text
      x="25"
      y="472"
      class="body"
    >
      Collaborative canvas web application
    </text>

    <text
      x="25"
      y="495"
      class="body"
    >
      with multi-user interaction.
    </text>


    <!-- Invoice System -->
    <circle
      cx="7"
      cy="525"
      r="7"
      fill="#e32636"
    />

    <text
      x="25"
      y="531"
      class="h3"
    >
      Invoice System
    </text>

    <text
      x="25"
      y="553"
      class="small red"
    >
      C# + .NET FRAMEWORK
    </text>

    <text
      x="25"
      y="577"
      class="body"
    >
      Client, article and billing management
    </text>

    <text
      x="25"
      y="600"
      class="body"
    >
      with automated calculations.
    </text>


    <!-- Sentier des Planètes -->
    <circle
      cx="7"
      cy="630"
      r="7"
      fill="#2d9cdb"
    />

    <text
      x="25"
      y="636"
      class="h3"
    >
      Sentier des Planètes
    </text>

    <text
      x="25"
      y="658"
      class="small blue"
    >
      AR + MOBILE DEVELOPMENT
    </text>

  </g>

</g>


<!-- ========================================================= -->
<!-- ACADEMIC & PROFESSIONAL -->
<!-- ========================================================= -->

<g transform="translate(620 1815)">

  <rect
    width="520"
    height="710"
    rx="10"
    fill="#111827"
    stroke="#30363d"
  />

  <text
    x="25"
    y="42"
    class="h3"
  >
    ACADEMIC &amp; PROFESSIONAL
  </text>

  <g transform="translate(25 75)">


    <!-- Currently Seeking -->
    <circle
      cx="7"
      cy="0"
      r="7"
      fill="#2ea043"
    />

    <text
      x="25"
      y="6"
      class="h3"
    >
      Currently Seeking
    </text>

    <text
      x="25"
      y="28"
      class="small green"
    >
      MASTER'S + WORK
    </text>

    <text
      x="25"
      y="52"
      class="body"
    >
      Looking to combine advanced studies with
    </text>

    <text
      x="25"
      y="75"
      class="body"
    >
      hands-on professional experience.
    </text>


    <!-- Bachelor -->
    <circle
      cx="7"
      cy="125"
      r="7"
      fill="#f2c94c"
    />

    <text
      x="25"
      y="131"
      class="h3"
    >
      Bachelor of Science in Information Technology
    </text>

    <text
      x="25"
      y="153"
      class="small yellow"
    >
      HELB ILYA PRIGOGINE · GRADUATED 2026
    </text>

    <text
      x="25"
      y="177"
      class="body"
    >
      Software architecture, data structures
    </text>

    <text
      x="25"
      y="200"
      class="body"
    >
      and security fundamentals.
    </text>


    <!-- Internship -->
    <circle
      cx="7"
      cy="250"
      r="7"
      fill="#e32636"
    />

    <text
      x="25"
      y="256"
      class="h3"
    >
      Internship @ MyGridEnergy
    </text>

    <text
      x="25"
      y="278"
      class="small red"
    >
      2026
    </text>

    <text
      x="25"
      y="302"
      class="body"
    >
      Hands-on software development in a
    </text>

    <text
      x="25"
      y="325"
      class="body"
    >
      professional engineering environment.
    </text>


    <!-- Upper Secondary -->
    <circle
      cx="7"
      cy="375"
      r="7"
      fill="#2d9cdb"
    />

    <text
      x="25"
      y="381"
      class="h3"
    >
      Upper Secondary Education
    </text>

    <text
      x="25"
      y="403"
      class="small blue"
    >
      ECONOMICS &amp; SOCIOLOGY · 2022
    </text>

    <text
      x="25"
      y="427"
      class="body"
    >
      Analytical thinking and problem-solving
    </text>

    <text
      x="25"
      y="450"
      class="body"
    >
      foundation.
    </text>

  </g>

</g>


<!-- ========================================================= -->
<!-- ICT KNOWLEDGE BASE / PROJECT MANAGEMENT -->
<!-- ========================================================= -->

<!-- Small project-management marker below project list -->
<g transform="translate(85 2460)">

  <rect
    x="0"
    y="0"
    width="470"
    height="45"
    rx="6"
    fill="#0d1117"
    stroke="#2ea043"
  />

  <circle
    cx="18"
    cy="22"
    r="6"
    fill="#2ea043"
  />

  <text
    x="35"
    y="20"
    class="small green"
  >
    ICT KNOWLEDGE BASE
  </text>

  <text
    x="35"
    y="37"
    font-family="Arial"
    font-size="12"
    fill="#8b949e"
  >
    SCRUM MASTER · AGILE · TEAM COORDINATION
  </text>

</g>


<!-- ========================================================= -->
<!-- FOOTER -->
<!-- ========================================================= -->

<rect
  x="60"
  y="2570"
  width="1080"
  height="170"
  rx="10"
  fill="#161b22"
  stroke="#30363d"
/>

<rect
  x="60"
  y="2570"
  width="8"
  height="170"
  fill="url(#hero)"
/>


<g transform="translate(95 2605)">

  <text
    x="0"
    y="0"
    class="mono"
  >
    SYS_COMM: johnayazbeck@hotmail.com
  </text>

  <text
    x="0"
    y="32"
    class="mono"
  >
    NETWORK: linkedin.com/in/yazbeckjohn
  </text>

  <text
    x="0"
    y="64"
    class="mono"
  >
    LOCATION: BRUSSELS, BELGIUM
  </text>

  <text
    x="0"
    y="96"
    class="mono"
  >
    VIDEO: youtube.com/@JohnCoding
  </text>

  <text
    x="0"
    y="128"
    class="small"
  >
    STATUS: AVAILABLE FOR THE NEXT CHALLENGE
  </text>

</g>


<!-- Footer quote -->
<text
  x="1100"
  y="2635"
  text-anchor="end"
  font-family="Arial"
  font-size="18"
  font-style="italic"
  fill="#8b949e"
>
  “Building systems that scale,
</text>

<text
  x="1100"
  y="2663"
  text-anchor="end"
  font-family="Arial"
  font-size="18"
  font-style="italic"
  fill="#8b949e"
>
  breaking challenges that don't,
</text>

<text
  x="1100"
  y="2691"
  text-anchor="end"
  font-family="Arial"
  font-size="18"
  font-style="italic"
  fill="#8b949e"
>
  and always pushing the limits.”
</text>


<!-- ========================================================= -->
<!-- BOTTOM ACCENT -->
<!-- ========================================================= -->

<rect
  x="60"
  y="2760"
  width="300"
  height="6"
  fill="#e32636"
/>

<rect
  x="375"
  y="2760"
  width="180"
  height="6"
  fill="#f2c94c"
/>

<rect
  x="570"
  y="2760"
  width="250"
  height="6"
  fill="#2d9cdb"
/>

<rect
  x="835"
  y="2760"
  width="305"
  height="6"
  fill="#2ea043"
/>

</svg>
