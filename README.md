<div align="center">

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                    IC DIE HERO BANNER                          -->
<!-- ═══════════════════════════════════════════════════════════════ -->

<svg width="100%" viewBox="0 0 900 220" xmlns="http://www.w3.org/2000/svg" style="border-radius:12px;display:block">
  <defs>
    <radialGradient id="bgG" cx="50%" cy="50%" r="70%">
      <stop offset="0%" stop-color="#0e1b2e"/>
      <stop offset="60%" stop-color="#070e1a"/>
      <stop offset="100%" stop-color="#020609"/>
    </radialGradient>
    <radialGradient id="gl1" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#388bfd" stop-opacity=".18"/>
      <stop offset="100%" stop-color="#388bfd" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="gl2" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#bc8cff" stop-opacity=".13"/>
      <stop offset="100%" stop-color="#bc8cff" stop-opacity="0"/>
    </radialGradient>
  </defs>
  <!-- Base -->
  <rect width="900" height="220" fill="url(#bgG)"/>
  <ellipse cx="450" cy="110" rx="320" ry="130" fill="url(#gl1)"/>
  <ellipse cx="200" cy="60"  rx="200" ry="100" fill="url(#gl2)"/>
  <ellipse cx="700" cy="160" rx="180" ry="90"  fill="url(#gl2)"/>
  <!-- Substrate grid -->
  <g stroke="#1a2a42" stroke-width=".5" opacity=".7">
    <line x1="0" y1="28"  x2="900" y2="28"/>  <line x1="0" y1="56"  x2="900" y2="56"/>
    <line x1="0" y1="84"  x2="900" y2="84"/>  <line x1="0" y1="112" x2="900" y2="112"/>
    <line x1="0" y1="140" x2="900" y2="140"/> <line x1="0" y1="168" x2="900" y2="168"/>
    <line x1="0" y1="196" x2="900" y2="196"/>
    <line x1="56"  y1="0" x2="56"  y2="220"/> <line x1="112" y1="0" x2="112" y2="220"/>
    <line x1="168" y1="0" x2="168" y2="220"/> <line x1="224" y1="0" x2="224" y2="220"/>
    <line x1="280" y1="0" x2="280" y2="220"/> <line x1="336" y1="0" x2="336" y2="220"/>
    <line x1="392" y1="0" x2="392" y2="220"/> <line x1="448" y1="0" x2="448" y2="220"/>
    <line x1="504" y1="0" x2="504" y2="220"/> <line x1="560" y1="0" x2="560" y2="220"/>
    <line x1="616" y1="0" x2="616" y2="220"/> <line x1="672" y1="0" x2="672" y2="220"/>
    <line x1="728" y1="0" x2="728" y2="220"/> <line x1="784" y1="0" x2="784" y2="220"/>
    <line x1="840" y1="0" x2="840" y2="220"/>
  </g>
  <!-- M1 power rails copper -->
  <g stroke="#c2622a" stroke-width="4" opacity=".25" fill="none">
    <line x1="0" y1="18"  x2="900" y2="18"/>  <line x1="0" y1="202" x2="900" y2="202"/>
    <line x1="18" y1="0"  x2="18"  y2="220"/> <line x1="882" y1="0" x2="882" y2="220"/>
  </g>
  <!-- M2 horizontal blue signal routes -->
  <g stroke="#388bfd" stroke-width="1.5" opacity=".35" fill="none">
    <polyline points="0,35 80,35 100,55 200,55"/>
    <polyline points="0,63 60,63 80,43 150,43 170,63 260,63"/>
    <polyline points="0,91 50,91 70,71 130,71 150,91 240,91 260,71 340,71"/>
    <polyline points="0,119 90,119 110,99 190,99 210,119 300,119"/>
    <polyline points="0,147 70,147 90,127 170,127 190,147 290,147 310,127 390,127"/>
    <polyline points="0,175 55,175 75,155 145,155 165,175 265,175"/>
    <polyline points="900,35 820,35 800,55 700,55"/>
    <polyline points="900,63 840,63 820,43 750,43 730,63 640,63"/>
    <polyline points="900,91 850,91 830,71 770,71 750,91 660,91 640,71 560,71"/>
    <polyline points="900,119 810,119 790,99 710,99 690,119 600,119"/>
    <polyline points="900,147 830,147 810,127 730,127 710,147 610,147 590,127 510,127"/>
    <polyline points="900,175 845,175 825,155 755,155 735,175 635,175"/>
  </g>
  <!-- M3 vertical purple signal routes -->
  <g stroke="#bc8cff" stroke-width="1.5" opacity=".3" fill="none">
    <polyline points="56,0 56,40 76,60 76,110 56,130 56,220"/>
    <polyline points="112,0 112,30 132,50 132,90 112,110 112,160 132,180 132,220"/>
    <polyline points="168,0 168,50 148,70 148,130 168,150 168,220"/>
    <polyline points="280,0 280,45 260,65 260,115 280,135 280,180 260,200 260,220"/>
    <polyline points="840,0 840,40 820,60 820,110 840,130 840,220"/>
    <polyline points="784,0 784,30 764,50 764,90 784,110 784,160 764,180 764,220"/>
    <polyline points="728,0 728,50 748,70 748,130 728,150 728,220"/>
    <polyline points="616,0 616,45 636,65 636,115 616,135 616,180 636,200 636,220"/>
  </g>
  <!-- Via dots blue -->
  <g fill="#388bfd" opacity=".7">
    <circle cx="80" cy="35" r="2.5"/><circle cx="100" cy="55" r="2.5"/>
    <circle cx="60" cy="63" r="2.5"/><circle cx="170" cy="63" r="2.5"/>
    <circle cx="50" cy="91" r="2.5"/><circle cx="150" cy="91" r="2.5"/><circle cx="260" cy="71" r="2.5"/>
    <circle cx="90" cy="119" r="2.5"/><circle cx="210" cy="119" r="2.5"/>
    <circle cx="70" cy="147" r="2.5"/><circle cx="190" cy="147" r="2.5"/><circle cx="310" cy="127" r="2.5"/>
    <circle cx="820" cy="35" r="2.5"/><circle cx="800" cy="55" r="2.5"/>
    <circle cx="840" cy="63" r="2.5"/><circle cx="730" cy="63" r="2.5"/>
    <circle cx="850" cy="91" r="2.5"/><circle cx="750" cy="91" r="2.5"/><circle cx="640" cy="71" r="2.5"/>
    <circle cx="810" cy="119" r="2.5"/><circle cx="690" cy="119" r="2.5"/>
    <circle cx="830" cy="147" r="2.5"/><circle cx="710" cy="147" r="2.5"/><circle cx="590" cy="127" r="2.5"/>
  </g>
  <!-- Via dots purple -->
  <g fill="#bc8cff" opacity=".6">
    <circle cx="56" cy="40" r="2"/><circle cx="76" cy="60" r="2"/><circle cx="76" cy="110" r="2"/>
    <circle cx="112" cy="30" r="2"/><circle cx="132" cy="50" r="2"/><circle cx="132" cy="90" r="2"/>
    <circle cx="168" cy="50" r="2"/><circle cx="148" cy="70" r="2"/><circle cx="148" cy="130" r="2"/>
    <circle cx="280" cy="45" r="2"/><circle cx="260" cy="65" r="2"/><circle cx="260" cy="115" r="2"/>
    <circle cx="840" cy="40" r="2"/><circle cx="820" cy="60" r="2"/><circle cx="820" cy="110" r="2"/>
    <circle cx="784" cy="30" r="2"/><circle cx="764" cy="50" r="2"/><circle cx="764" cy="90" r="2"/>
    <circle cx="728" cy="50" r="2"/><circle cx="748" cy="70" r="2"/><circle cx="748" cy="130" r="2"/>
    <circle cx="616" cy="45" r="2"/><circle cx="636" cy="65" r="2"/><circle cx="636" cy="115" r="2"/>
  </g>
  <!-- Via dots green -->
  <g fill="#3fb950" opacity=".55">
    <circle cx="200" cy="55" r="2"/><circle cx="150" cy="43" r="2"/>
    <circle cx="700" cy="55" r="2"/><circle cx="750" cy="43" r="2"/>
    <circle cx="55"  cy="175" r="2"/><circle cx="165" cy="175" r="2"/>
    <circle cx="845" cy="175" r="2"/><circle cx="735" cy="175" r="2"/>
  </g>
  <!-- Functional blocks LEFT -->
  <g opacity=".6">
    <rect x="26" y="38"  width="44" height="28" rx="2" fill="#0d1f38" stroke="#388bfd" stroke-width=".8"/>
    <text x="48" y="55"  text-anchor="middle" font-family="monospace" font-size="6" fill="#58a6ff" font-weight="700">APB</text>
    <text x="48" y="62"  text-anchor="middle" font-family="monospace" font-size="5"  fill="#388bfd">SLAVE</text>
    <rect x="26" y="78"  width="44" height="28" rx="2" fill="#140d28" stroke="#bc8cff" stroke-width=".8"/>
    <text x="48" y="95"  text-anchor="middle" font-family="monospace" font-size="6" fill="#bc8cff" font-weight="700">PULSE</text>
    <text x="48" y="102" text-anchor="middle" font-family="monospace" font-size="5"  fill="#9d7be8">SYNC</text>
    <rect x="26" y="118" width="44" height="28" rx="2" fill="#0a1f18" stroke="#3fb950" stroke-width=".8"/>
    <text x="48" y="135" text-anchor="middle" font-family="monospace" font-size="6" fill="#3fb950" font-weight="700">BAUD</text>
    <text x="48" y="142" text-anchor="middle" font-family="monospace" font-size="5"  fill="#3fb950">GEN</text>
    <rect x="26" y="158" width="44" height="28" rx="2" fill="#1a1000" stroke="#c2622a" stroke-width=".8"/>
    <text x="48" y="175" text-anchor="middle" font-family="monospace" font-size="6" fill="#e3a060" font-weight="700">REG</text>
    <text x="48" y="182" text-anchor="middle" font-family="monospace" font-size="5"  fill="#c2622a">MAP</text>
  </g>
  <!-- Functional blocks RIGHT -->
  <g opacity=".6">
    <rect x="830" y="38"  width="44" height="28" rx="2" fill="#0d1f38" stroke="#388bfd" stroke-width=".8"/>
    <text x="852" y="55"  text-anchor="middle" font-family="monospace" font-size="6" fill="#58a6ff" font-weight="700">UART</text>
    <text x="852" y="62"  text-anchor="middle" font-family="monospace" font-size="5"  fill="#388bfd">TX FSM</text>
    <rect x="830" y="78"  width="44" height="28" rx="2" fill="#140d28" stroke="#bc8cff" stroke-width=".8"/>
    <text x="852" y="95"  text-anchor="middle" font-family="monospace" font-size="6" fill="#bc8cff" font-weight="700">UART</text>
    <text x="852" y="102" text-anchor="middle" font-family="monospace" font-size="5"  fill="#9d7be8">RX FSM</text>
    <rect x="830" y="118" width="44" height="28" rx="2" fill="#0a1f18" stroke="#3fb950" stroke-width=".8"/>
    <text x="852" y="135" text-anchor="middle" font-family="monospace" font-size="6" fill="#3fb950" font-weight="700">CDC</text>
    <text x="852" y="142" text-anchor="middle" font-family="monospace" font-size="5"  fill="#3fb950">BRIDGE</text>
    <rect x="830" y="158" width="44" height="28" rx="2" fill="#1a1000" stroke="#c2622a" stroke-width=".8"/>
    <text x="852" y="175" text-anchor="middle" font-family="monospace" font-size="6" fill="#e3a060" font-weight="700">DFT</text>
    <text x="852" y="182" text-anchor="middle" font-family="monospace" font-size="5"  fill="#c2622a">SCAN</text>
  </g>
  <!-- Centre die frame -->
  <rect x="360" y="60" width="180" height="100" rx="4" fill="none" stroke="#388bfd" stroke-width=".8" stroke-dasharray="5,3" opacity=".4"/>
  <rect x="356" y="56" width="188" height="108" rx="6" fill="none" stroke="#388bfd" stroke-width=".4" opacity=".2"/>
  <!-- Scan-line overlay -->
  <g stroke="#000" stroke-width=".4" opacity=".15">
    <line x1="0" y1="4"   x2="900" y2="4"/>  <line x1="0" y1="8"   x2="900" y2="8"/>
    <line x1="0" y1="12"  x2="900" y2="12"/> <line x1="0" y1="16"  x2="900" y2="16"/>
    <line x1="0" y1="20"  x2="900" y2="20"/> <line x1="0" y1="24"  x2="900" y2="24"/>
    <line x1="0" y1="32"  x2="900" y2="32"/> <line x1="0" y1="36"  x2="900" y2="36"/>
    <line x1="0" y1="40"  x2="900" y2="40"/> <line x1="0" y1="44"  x2="900" y2="44"/>
    <line x1="0" y1="48"  x2="900" y2="48"/> <line x1="0" y1="52"  x2="900" y2="52"/>
    <line x1="0" y1="60"  x2="900" y2="60"/> <line x1="0" y1="64"  x2="900" y2="64"/>
    <line x1="0" y1="68"  x2="900" y2="68"/> <line x1="0" y1="72"  x2="900" y2="72"/>
    <line x1="0" y1="76"  x2="900" y2="76"/> <line x1="0" y1="80"  x2="900" y2="80"/>
    <line x1="0" y1="88"  x2="900" y2="88"/> <line x1="0" y1="92"  x2="900" y2="92"/>
    <line x1="0" y1="96"  x2="900" y2="96"/> <line x1="0" y1="100" x2="900" y2="100"/>
    <line x1="0" y1="104" x2="900" y2="104"/><line x1="0" y1="108" x2="900" y2="108"/>
    <line x1="0" y1="116" x2="900" y2="116"/><line x1="0" y1="120" x2="900" y2="120"/>
    <line x1="0" y1="124" x2="900" y2="124"/><line x1="0" y1="128" x2="900" y2="128"/>
    <line x1="0" y1="132" x2="900" y2="132"/><line x1="0" y1="136" x2="900" y2="136"/>
    <line x1="0" y1="144" x2="900" y2="144"/><line x1="0" y1="148" x2="900" y2="148"/>
    <line x1="0" y1="152" x2="900" y2="152"/><line x1="0" y1="156" x2="900" y2="156"/>
    <line x1="0" y1="160" x2="900" y2="160"/><line x1="0" y1="164" x2="900" y2="164"/>
    <line x1="0" y1="172" x2="900" y2="172"/><line x1="0" y1="176" x2="900" y2="176"/>
    <line x1="0" y1="180" x2="900" y2="180"/><line x1="0" y1="184" x2="900" y2="184"/>
    <line x1="0" y1="188" x2="900" y2="188"/><line x1="0" y1="192" x2="900" y2="192"/>
    <line x1="0" y1="200" x2="900" y2="200"/><line x1="0" y1="204" x2="900" y2="204"/>
    <line x1="0" y1="208" x2="900" y2="208"/><line x1="0" y1="212" x2="900" y2="212"/>
    <line x1="0" y1="216" x2="900" y2="216"/>
  </g>
  <!-- Corner text labels -->
  <text x="26"  y="11" font-family="monospace" font-size="7" fill="#388bfd" opacity=".5" font-weight="600">VDD · 3.3V · PCLK_IN</text>
  <text x="874" y="11" font-family="monospace" font-size="7" fill="#388bfd" opacity=".5" font-weight="600" text-anchor="end">REV 1.0 · INIYAVAN_S_CORE</text>
  <text x="26"  y="215" font-family="monospace" font-size="7" fill="#388bfd" opacity=".5" font-weight="600">KSRCT · Namakkal · TN-IND</text>
  <text x="874" y="215" font-family="monospace" font-size="7" fill="#388bfd" opacity=".5" font-weight="600" text-anchor="end">PROCESS: CMOS · YEAR: 2027</text>
  <!-- IC package pins top -->
  <g fill="#388bfd" opacity=".5">
    <rect x="330" y="0" width="5" height="9" rx="1"/>
    <rect x="345" y="0" width="5" height="9" rx="1"/>
    <rect x="360" y="0" width="5" height="9" rx="1"/>
  </g>
  <g fill="#bc8cff" opacity=".5">
    <rect x="375" y="0" width="5" height="9" rx="1"/>
    <rect x="390" y="0" width="5" height="9" rx="1"/>
  </g>
  <g fill="#3fb950" opacity=".5">
    <rect x="450" y="0" width="5" height="9" rx="1"/>
    <rect x="465" y="0" width="5" height="9" rx="1"/>
  </g>
  <g fill="#c2622a" opacity=".5">
    <rect x="520" y="0" width="5" height="9" rx="1"/>
    <rect x="535" y="0" width="5" height="9" rx="1"/>
    <rect x="550" y="0" width="5" height="9" rx="1"/>
  </g>
  <!-- IC package pins bottom -->
  <g fill="#3fb950" opacity=".45">
    <rect x="330" y="211" width="5" height="9" rx="1"/>
    <rect x="345" y="211" width="5" height="9" rx="1"/>
  </g>
  <g fill="#388bfd" opacity=".5">
    <rect x="390" y="211" width="5" height="9" rx="1"/>
    <rect x="405" y="211" width="5" height="9" rx="1"/>
    <rect x="420" y="211" width="5" height="9" rx="1"/>
  </g>
  <g fill="#bc8cff" opacity=".45">
    <rect x="480" y="211" width="5" height="9" rx="1"/>
    <rect x="495" y="211" width="5" height="9" rx="1"/>
  </g>
  <g fill="#c2622a" opacity=".45">
    <rect x="540" y="211" width="5" height="9" rx="1"/>
    <rect x="555" y="211" width="5" height="9" rx="1"/>
  </g>
  <!-- Centre name text -->
  <text x="450" y="101" text-anchor="middle" font-family="monospace" font-size="38" font-weight="800" fill="#e6edf3" letter-spacing="4" opacity=".97">INIYAVAN S</text>
  <!-- Gradient underline -->
  <line x1="270" y1="112" x2="630" y2="112" stroke="url(#nameUL)" stroke-width="1.5"/>
  <defs>
    <linearGradient id="nameUL" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%"   stop-color="#388bfd" stop-opacity="0"/>
      <stop offset="25%"  stop-color="#388bfd" stop-opacity="1"/>
      <stop offset="50%"  stop-color="#bc8cff" stop-opacity="1"/>
      <stop offset="75%"  stop-color="#3fb950" stop-opacity="1"/>
      <stop offset="100%" stop-color="#3fb950" stop-opacity="0"/>
    </linearGradient>
  </defs>
  <!-- Tagline -->
  <text x="450" y="130" text-anchor="middle" font-family="monospace" font-size="11" fill="#e6edf3" opacity=".65" letter-spacing="2.5">
    <tspan fill="#58a6ff" font-weight="700">RTL Design</tspan>
    <tspan fill="#e6edf3" opacity=".6">  →  Synthesis  →  </tspan>
    <tspan fill="#58a6ff" font-weight="700">Verification</tspan>
    <tspan fill="#e6edf3" opacity=".6">  →  Tape-Out</tspan>
  </text>
</svg>

</div>

---

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=2800&pause=900&color=70A5FD&center=true&vCenter=true&width=820&lines=%60define+INIYAVAN+%22VLSI+Design+Engineer%22;assign+passion+%3D+RTL+%7C+Verification+%7C+CDC;always+%40(posedge+CLK)+begin+learn%3B+build%3B+end;%2F%2F+C-DAC+1-TOPS+Tape-Out+Interview+Cleared+%E2%9C%94;module+iniyavan_s+%23(CGPA%3D8.18%2C+GRAD%3D2027);input+curiosity%2C+dedication%3B+output+innovation%3B)](https://git.io/typing-svg)

</div>

---

<!-- ═══════════════════════════════════════════════════════════════ -->
<!--                  CHIP FLOORPLAN BLOCK                          -->
<!-- ═══════════════════════════════════════════════════════════════ -->

```
╔══════════════════════════════════════════════════════════════════════════════════╗
║  ┌──────────────────────────────────────────────────────────────────────────┐   ║
║  │  MODULE : iniyavan_s_v1.0          DOMAIN : VLSI Design & Verification   │   ║
║  │  CLOCKS : PCLK (APB) + UART_CLK (Baud)     TYPE : Multi-Clock CDC Core   │   ║
║  │  STATUS : ✔ Synthesizable   ✔ CDC Clean   ✔ Func Verified   ✔ STA Pass   │   ║
║  └──────────────────────────────────────────────────────────────────────────┘   ║
║                                                                                  ║
║  PCLK ──▶┤  ┌────────────┐   ┌─────────────┐   ┌──────────────┐               ║
║           ├─►│ APB Slave  ├──►│  Reg Map     ├──►│ Pulse Sync   │──┐            ║
║           │  │ (PSEL/PENABLE│  │ CTRL/STATUS  │   │ 2-FF Guard   │  │ CDC        ║
║           │  │  PWRITE/PADDR│  │ BAUD_DIV/DATA│   │ Metastability│  │ Crossing   ║
║           │  └────────────┘   └─────────────┘   └──────────────┘  │            ║
║           │                                                          ▼            ║
║           │  ┌────────────────────────────────────────────────────────────┐      ║
║           │  │  UART_CLK Domain                                           │      ║
║           │  │  ┌─────────────┐   ┌─────────────┐   ┌─────────────┐      │      ║
║           │  │  │ Baud Rate   │   │ UART TX FSM  │   │ UART RX FSM │      │      ║
║           │  │  │ Generator   │──►│ START→DATA   │   │ Oversample  │      │      ║
║           │  │  │ 16x oversmp │   │ →PARITY→STOP │   │ Frame detect│      │      ║
║           │  │  └─────────────┘   └─────────────┘   └─────────────┘      │      ║
║           │  └────────────────────────────────────────────────────────────┘      ║
║           │                                                                       ║
║           └─► [ DFT ] LFSR · MISR · Scan Chain · STUMPS · Boundary Scan         ║
║                                                                                   ║
║  ENGINEER : Iniyavan S  │  ORG : KSRCT, Anna University  │  GRAD : Jun 2027      ║
╚══════════════════════════════════════════════════════════════════════════════════╝
```

---

## `// WHOAMI`

<img align="right" width="355" src="https://raw.githubusercontent.com/abhisheknaiidu/abhisheknaiidu/master/code.gif"/>

```verilog
// ================================================
//  Engineer   : Iniyavan S
//  Institute  : K.S. Rangasamy College of Technology
//  University : Anna University, Chennai
//  Domain     : VLSI Design & Technology
//  Email      : iniyavansoundar2002@gmail.com
//  GitHub     : github.com/INIYA-1010
// ================================================

module iniyavan_s #(
  parameter LOCATION  = "Namakkal, Tamil Nadu",
  parameter DEGREE    = "B.E Electronics Engineering",
  parameter SPEC      = "VLSI Design & Technology",
  parameter CGPA      = 8.18,
  parameter GRAD_YEAR = 2027
)(
  input  wire curiosity,
  input  wire dedication,
  output reg  [7:0] innovation
);

  // ── Technical Interests ──────────────────────
  localparam RTL_DESIGN         = 1'b1;
  localparam FUNCTIONAL_VERIF   = 1'b1;
  localparam DIGITAL_LOGIC      = 1'b1;
  localparam SEMICONDUCTOR_TECH = 1'b1;
  localparam CDC_ANALYSIS       = 1'b1; // ← currently mastering

  // ── Skill Proficiency ────────────────────────
  // Verilog HDL   ████████████ 95%
  // RTL Design    ███████████░ 90%
  // Verification  █████████░░░ 78%
  // C / Linux     ████████░░░░ 65%
  // DFT / BIST    ███████░░░░░ 60%

  // ── EDA Tools ────────────────────────────────
  // Synopsys DC | Siemens EDA | ModelSim
  // GTKWave     | Vivado      | Multisim

  // ── Protocols ────────────────────────────────
  // UART | APB | SPI (learning) | I2C (learning)

  always @(posedge curiosity) begin
    if (dedication)
      innovation <= innovation + 1'b1;
  end

  // Achievement : Cleared C-DAC Round 1 — 1-TOPS Tape-Out
  // Motto       : "Timing closure waits for no one — verify first."

endmodule
```

<br clear="right"/>

---

## `// TECH STACK` &nbsp;—&nbsp; *synthesizable skill set*

<div align="center">

**◈ &nbsp; Hardware Description & Design &nbsp; ◈**

![Verilog HDL](https://img.shields.io/badge/Verilog%20HDL-70A5FD?style=flat-square&logo=v&logoColor=0d1117)
![RTL Design](https://img.shields.io/badge/RTL%20Design-BF91F3?style=flat-square&logo=circuitverse&logoColor=0d1117)
![Digital Logic](https://img.shields.io/badge/Digital%20Logic%20Design-38BDAE?style=flat-square&logo=hackthebox&logoColor=0d1117)
![UART Protocol](https://img.shields.io/badge/UART%20Protocol-70A5FD?style=flat-square&logo=buffer&logoColor=0d1117)
![APB Protocol](https://img.shields.io/badge/APB%20Protocol-BF91F3?style=flat-square&logo=buffer&logoColor=0d1117)
![Functional Verification](https://img.shields.io/badge/Functional%20Verification-38BDAE?style=flat-square&logo=testcafe&logoColor=0d1117)
![Synthesis](https://img.shields.io/badge/Synthesis%20Concepts-70A5FD?style=flat-square&logo=abstract&logoColor=0d1117)
![DFT/BIST](https://img.shields.io/badge/DFT%20%2F%20BIST-BF91F3?style=flat-square&logo=probot&logoColor=0d1117)
![CDC](https://img.shields.io/badge/CDC%20Analysis-38BDAE?style=flat-square&logo=git&logoColor=0d1117)

**◈ &nbsp; EDA Toolchain &nbsp; ◈**

![Synopsys](https://img.shields.io/badge/Synopsys-E74C3C?style=flat-square&logo=synopsys&logoColor=white)
![Siemens EDA](https://img.shields.io/badge/Siemens%20EDA-009999?style=flat-square&logo=siemens&logoColor=white)
![ModelSim](https://img.shields.io/badge/ModelSim-2C3E50?style=flat-square&logo=intel&logoColor=white)
![GTKWave](https://img.shields.io/badge/GTKWave-27AE60?style=flat-square&logo=gnome&logoColor=white)
![Vivado](https://img.shields.io/badge/Xilinx%20Vivado-E31837?style=flat-square&logo=xilinx&logoColor=white)
![Multisim](https://img.shields.io/badge/Multisim-00ADEF?style=flat-square&logo=ni&logoColor=white)

**◈ &nbsp; Programming & OS &nbsp; ◈**

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Shell](https://img.shields.io/badge/Shell%20Scripting-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

</div>

---

## `// GITHUB METRICS`

<div align="center">
  <a href="https://github.com/INIYA-1010">
    <img height="175" src="https://github-readme-stats.vercel.app/api?username=INIYA-1010&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&bg_color=0d1117&title_color=70a5fd&icon_color=bf91f3&text_color=c9d1d9&border_radius=10&ring_color=38bdae"/>
  </a>
  <a href="https://github.com/INIYA-1010">
    <img height="175" src="https://github-readme-stats.vercel.app/api/top-langs/?username=INIYA-1010&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=70a5fd&text_color=c9d1d9&langs_count=8&border_radius=10"/>
  </a>
</div>

<br/>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=INIYA-1010&theme=tokyonight-duo&hide_border=true&background=0D1117&ring=70A5FD&fire=BF91F3&currStreakLabel=70A5FD&sideLabels=38BDAE&dates=8B949E&currStreakNum=C9D1D9&sideNums=C9D1D9&stroke=0D1117&border_radius=10"/>
</div>

---

## `// ACTIVITY GRAPH`

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=INIYA-1010&theme=tokyo-night&bg_color=0d1117&color=70a5fd&line=bf91f3&point=38bdae&area=true&hide_border=true" width="100%"/>
</div>

---

## `// TROPHIES`

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=INIYA-1010&theme=tokyonight&no-frame=true&no-bg=true&row=1&column=7&margin-w=4"/>
</div>

---

## `// WORK EXPERIENCE` &nbsp;—&nbsp; *synthesis log*

<details>
<summary><code>▶ run synthesis — "Digital Design & Verification using Verilog HDL" | 4-Week Intern | 2024</code></summary>

<br/>

```
[INFO] Role        : Digital Design and Verification using Verilog HDL
[INFO] Duration    : 4 Weeks
[INFO] Domain      : Frontend VLSI Design Flow
[INFO] Environment : Linux + EDA Toolchain (ModelSim / GTKWave)
[INFO] Status      : COMPLETE ✔
```

> ![Verilog](https://img.shields.io/badge/Verilog-70A5FD?style=flat-square&logoColor=0d1117)
> ![RTL](https://img.shields.io/badge/RTL%20Design-BF91F3?style=flat-square&logoColor=0d1117)
> ![ModelSim](https://img.shields.io/badge/ModelSim-38BDAE?style=flat-square&logoColor=0d1117)
> ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
> ![DFT](https://img.shields.io/badge/DFT%20Basics-70A5FD?style=flat-square&logoColor=0d1117)

- 🔧 Developed RTL modules and performed **functional verification** of combinational and sequential digital circuits using Verilog HDL in a professional EDA environment.
- 🖥️ Designed and simulated circuits — from basic gates to FSM-based controllers — gaining full hands-on EDA workflow experience under Linux.
- 📐 Followed the complete **frontend VLSI design flow**: specification → RTL coding → simulation → functional sign-off.
- 🧪 Studied DFT fundamentals (scan path, testability concepts) directly applicable to industry tape-out flows.

```
[PASS] RTL Design & Simulation    : COMPLETE
[PASS] Functional Verification    : COMPLETE
[PASS] DFT Fundamentals           : COMPLETE
[PASS] Linux EDA Environment      : COMPLETE
```

</details>

---

## `// FEATURED PROJECTS` &nbsp;—&nbsp; *netlist view*

```
 CLK ──┐ ┌──┐ ┌──┐ ┌──┐ ┌──┐
        └─┘  └─┘  └─┘  └─┘  └──
              [P1]           [P2]           [P3]
         [UART+APB+CDC]  [AI-SoC FPGA]  [FSM Elevator]
```

<div align="center">

| `signal` Project | `stack` | `output` Key Results |
|:-----------------|:--------|:---------------------|
| 🔄 **[Multi-Clock UART Transceiver + APB Interface](https://github.com/INIYA-1010)** | Verilog · APB · CDC · ModelSim · GTKWave | Dual clock domains (PCLK + UART\_CLK); 2-FF pulse synchronizer for CDC; full APB slave register map (CTRL/STATUS/BAUD\_DIV/DATA); Tx/Rx FSM path fully verified |
| 👁️ **[Real-Time Object Detection — PYNQ-Z2](https://github.com/INIYA-1010)** | PYNQ-Z2 · YOLO · OpenCV DNN · Python · Vivado | FPGA hardware-accelerated real-time inference on Xilinx PYNQ-Z2; developed for Bharat AI-SoC Student Challenge |
| 🏢 **[Smart Elevator FSM Controller](https://github.com/INIYA-1010)** | Verilog · FSM · Vivado · ModelSim | Moore/Mealy hybrid FSM for automated multi-floor + door control; priority arbitration logic for simultaneous floor requests |

</div>

---

## `// ACHIEVEMENTS` &nbsp;—&nbsp; *sign-off report*

<div align="center">

```
╔══════════════════════════════════════════════════════════════════════╗
║                       [ ACHIEVEMENT LOG ]                           ║
╠══════════════════════════════════════════════════════════════════════╣
║  🎯  C-DAC 1-TOPS Semiconductor Tape-Out Program                    ║
║      Cleared Round 1 screening + attended final interview for       ║
║      India's prestigious 1-TOPS semiconductor tape-out initiative   ║
╠══════════════════════════════════════════════════════════════════════╣
║  🤖  Bharat AI-SoC Student Challenge                                ║
║      FPGA-accelerated real-time object detection on PYNQ-Z2         ║
║      using YOLO + OpenCV DNN with hardware acceleration             ║
╠══════════════════════════════════════════════════════════════════════╣
║  📜  Certificates Earned                                             ║
║      • Digital Design & Verification — Verilog HDL (Intern)         ║
║      • PCB Skill Development & Training — Invocrux Technologies     ║
║      • Introduction to Semiconductor Devices — NPTEL                ║
║      • Industrial Training: PCB Design & Fabrication                ║
║      • Introduction to Internet of Things — NPTEL                   ║
║      • Digital Design using Multi-Vt Libraries — VLSI Mentors       ║
╚══════════════════════════════════════════════════════════════════════╝
```

</div>

---

## `// EDUCATION` &nbsp;—&nbsp; *process node*

<div align="center">

| 🎓 Degree | 🏛️ Institution | 📅 Period | 📊 Score |
|:----------|:--------------|:---------:|:--------:|
| **B.E Electronics Engineering** — VLSI Design & Technology | K.S. Rangasamy College of Technology · Anna University | Sep 2023 – Jun 2027 | **CGPA 8.18** |
| Higher Secondary — Bio Maths | Sri Vidya Mandir Matric Hr. Sec. School · State Board | Jul 2019 – Mar 2020 | **57%** |

</div>

---

## `// CURRENTLY LOADING` &nbsp;—&nbsp; *place & route in progress*

```verilog
// ════════════════════════════════════════════════════════════
//  STATUS : Active learning — timing analysis in progress
//  TARGET : Industry-ready VLSI Design / Verification Engineer
// ════════════════════════════════════════════════════════════

task currently_learning;
  begin

    // 🧱 CDC Analysis
    //    → Metastability theory, MTBF calculations
    //    → Pulse synchronizers, handshake protocols
    //    → FIFO-based CDC, multi-bit bus crossing

    // 🔬 UVM Methodology
    //    → Agents, Sequencers, Drivers, Monitors
    //    → Scoreboards, coverage groups
    //    → Functional & code coverage closure

    // ⏱  Static Timing Analysis
    //    → Setup / Hold margins, clock skew
    //    → Multi-corner multi-mode (MCMM)
    //    → Timing exceptions: false path, multicycle

    // 🛡  DFT / BIST
    //    → LFSR, MISR, STUMPS, Circular BIST
    //    → Scan chain insertion & compression
    //    → Boundary Scan — IEEE 1149.1 / JTAG

    // 🔧 Synopsys Design Compiler
    //    → SDC constraint writing
    //    → Area / timing / power optimization
    //    → QoR analysis and ECO flows

  end
endtask
```

---

## `// CONNECT` &nbsp;—&nbsp; *open ports*

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-iniyavan--s-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/iniyavan-s-aa0950290/)
[![GitHub](https://img.shields.io/badge/GitHub-INIYA--1010-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/INIYA-1010)
[![Gmail](https://img.shields.io/badge/Gmail-iniyavansoundar2002-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:iniyavansoundar2002@gmail.com)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=INIYA-1010&label=Profile+Views&color=70a5fd&style=flat-square)

</div>

---

<div align="center">

```verilog
// ── END OF MODULE ─────────────────────────────────────────────
always @(posedge opportunity) begin
  learn <= learn + 1;
  build <= build + 1;
end
// ──────────────────────────────────────────────────────────────
```

</div>

<!-- FOOTER WAVE -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,30:0f2942,70:1a1f35,100:0d1117&height=120&section=footer&animation=twinkling" width="100%"/>
