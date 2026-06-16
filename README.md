<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,30:0f2942,70:1a1f35,100:0d1117&height=200&section=header&text=INIYAVAN%20S&fontSize=48&fontColor=70A5FD&animation=twinkling&fontAlignY=35&desc=%E2%96%88%20RTL%20Design%20%E2%86%92%20Synthesis%20%E2%86%92%20Verification%20%E2%86%92%20Tape-Out%20%E2%96%88&descAlignY=62&descSize=14&descColor=BF91F3" width="100%"/>

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=20&duration=2800&pause=900&color=70A5FD&center=true&vCenter=true&width=800&lines=%60define+INIYAVAN+%22VLSI+Design+Engineer%22;assign+passion+%3D+RTL+%7C+Verification+%7C+CDC;always+%40(posedge+CLK)+begin+learn%3B+build%3B+end;%2F%2F+C-DAC+1-TOPS+Tape-Out+Interview+Cleared+%E2%9C%94)](https://git.io/typing-svg)

</div>

---

<!-- DESIGN BLOCK ARCHITECTURE BANNER -->
```
╔══════════════════════════════════════════════════════════════════════╗
║  ┌─────────────────────────────────────────────────────────────┐    ║
║  │  MODULE: iniyavan_s  │  DOMAIN: VLSI Design & Verification  │    ║
║  │  CLOCK:  PCLK + UART_CLK  (Multi-Domain CDC)                │    ║
║  │  STATUS: ✔ Synthesizable  ✔ Verified  ✔ Timing Clean        │    ║
║  └─────────────────────────────────────────────────────────────┘    ║
║                                                                      ║
║   PCLK ──┤▶├── [ APB Slave ] ──── [ Pulse Sync ] ──► [ UART Tx ]   ║
║                      │                                    │          ║
║                  [ Reg Map ]                          [ UART Rx ]   ║
║                      │                                    │          ║
║              [ Baud Rate Gen ] ◄────── UART_CLK ──────────┘         ║
║                                                                      ║
║   LOCATION: Namakkal, TN  │  NODE: Anna University │  YEAR: 2027    ║
╚══════════════════════════════════════════════════════════════════════╝
```

---

## `// WHOAMI`

<img align="right" width="360" src="https://raw.githubusercontent.com/abhisheknaiidu/abhisheknaiidu/master/code.gif"/>

```verilog
// ============================================
//  Engineer  : Iniyavan S
//  Org       : K.S. Rangasamy College of Technology
//  Domain    : VLSI Design & Technology
//  Contact   : iniyavansoundar2002@gmail.com
// ============================================

module iniyavan_s #(
  parameter LOCATION   = "Namakkal, Tamil Nadu",
  parameter DEGREE     = "B.E Electronics Engineering",
  parameter SPEC       = "VLSI Design & Technology",
  parameter CGPA       = 8.18,
  parameter GRAD_YEAR  = 2027
)(
  input  wire  curiosity,
  input  wire  dedication,
  output reg   [7:0] innovation
);

  // ── Technical interests ──────────────────
  localparam RTL_DESIGN          = 1'b1;
  localparam FUNCTIONAL_VERIF    = 1'b1;
  localparam DIGITAL_LOGIC       = 1'b1;
  localparam SEMICONDUCTOR_TECH  = 1'b1;
  localparam CDC_ANALYSIS        = 1'b1; // ← currently mastering

  // ── Tools & EDA ──────────────────────────
  // Synopsys Tools | Siemens EDA | ModelSim
  // GTKWave        | Vivado      | Multisim

  // ── Protocols ────────────────────────────
  // UART | APB

  // ── Languages ────────────────────────────
  // Verilog HDL  ████████████ 95%
  // C Basic      ████████░░░░ 65%
  // Linux Shell  ███████░░░░░ 60%

  always @(posedge curiosity) begin
    if (dedication)
      innovation <= innovation + 1'b1;
  end

  // Fun fact: Cleared C-DAC Round 1 (1-TOPS tape-out program)
  // Motto: "Timing closure waits for no one — verify first."

endmodule
```

<br clear="right"/>

---

## `// TECH STACK` — *synthesizable skill set*

<div align="center">

**◈ Hardware Description & Design ◈**

![Verilog HDL](https://img.shields.io/badge/Verilog%20HDL-70A5FD?style=flat-square&logo=v&logoColor=0d1117)
![RTL Design](https://img.shields.io/badge/RTL%20Design-BF91F3?style=flat-square&logo=circuitverse&logoColor=0d1117)
![Digital Logic](https://img.shields.io/badge/Digital%20Logic-38BDAE?style=flat-square&logo=hackthebox&logoColor=0d1117)
![UART Protocol](https://img.shields.io/badge/UART%20Protocol-70A5FD?style=flat-square&logo=buffer&logoColor=0d1117)
![APB Protocol](https://img.shields.io/badge/APB%20Protocol-BF91F3?style=flat-square&logo=buffer&logoColor=0d1117)
![Functional Verification](https://img.shields.io/badge/Functional%20Verification-38BDAE?style=flat-square&logo=testcafe&logoColor=0d1117)
![Synthesis Concepts](https://img.shields.io/badge/Synthesis%20Concepts-70A5FD?style=flat-square&logo=abstract&logoColor=0d1117)
![DFT Basics](https://img.shields.io/badge/DFT%20%2F%20BIST-BF91F3?style=flat-square&logo=probot&logoColor=0d1117)

**◈ EDA Toolchain ◈**

![Synopsys](https://img.shields.io/badge/Synopsys-E74C3C?style=flat-square&logo=synopsys&logoColor=white)
![Siemens EDA](https://img.shields.io/badge/Siemens%20EDA-009999?style=flat-square&logo=siemens&logoColor=white)
![ModelSim](https://img.shields.io/badge/ModelSim-2C3E50?style=flat-square&logo=intel&logoColor=white)
![GTKWave](https://img.shields.io/badge/GTKWave-27AE60?style=flat-square&logo=gnome&logoColor=white)
![Xilinx Vivado](https://img.shields.io/badge/Vivado-E31837?style=flat-square&logo=xilinx&logoColor=white)
![Multisim](https://img.shields.io/badge/Multisim-00ADEF?style=flat-square&logo=ni&logoColor=white)

**◈ Programming & OS ◈**

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
  <img src="https://streak-stats.demolab.com?user=INIYA-1010&theme=tokyonight-duo&hide_border=true&background=0D1117&ring=70A5FD&fire=BF91F3&currStreakLabel=70A5FD&sideLabels=38BDAE&dates=8B949E&currStreakNum=C9D1D9&sideNums=C9D1D9&stroke=0D1117&border_radius=10" alt="GitHub Streak"/>
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

## `// WORK EXPERIENCE` — *synthesis log*

<details>
<summary><code>▶ run synthesis — "Digital Design & Verification using Verilog HDL" | 4-Week Intern | 2024</code></summary>

<br/>

```
[INFO] Intern Role : Digital Design and Verification using Verilog HDL
[INFO] Duration    : 4 Weeks
[INFO] Domain      : Frontend VLSI Design
[INFO] Environment : Linux + EDA Toolchain
```

> **Tech Used:**
> ![Verilog](https://img.shields.io/badge/Verilog-70A5FD?style=flat-square&logoColor=0d1117)
> ![RTL](https://img.shields.io/badge/RTL%20Design-BF91F3?style=flat-square&logoColor=0d1117)
> ![ModelSim](https://img.shields.io/badge/ModelSim-38BDAE?style=flat-square&logoColor=0d1117)
> ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
> ![DFT](https://img.shields.io/badge/DFT%20Basics-70A5FD?style=flat-square&logoColor=0d1117)

- 🔧 Developed RTL modules and performed **functional verification** of combinational and sequential digital circuits using Verilog HDL.
- 🖥️ Designed and simulated circuits — from basic gates to FSM-based controllers — in a professional EDA environment.
- 📐 Followed the **frontend VLSI design flow**: specification → RTL coding → simulation → functional sign-off.
- 🧪 Studied DFT fundamentals (scan path, testability concepts) aligned with industry tape-out flows.

```
[PASS] Functional Verification : COMPLETE
[PASS] DFT Fundamentals        : COMPLETE
[PASS] Linux EDA Environment   : COMPLETE
```

</details>

---

## `// FEATURED PROJECTS` — *netlist*

```
 CLK  ─┐  ┌──┐  ┌──┐  ┌──┐
        └──┘  └──┘  └──┘  └──
              [P1]        [P2]        [P3]
         [UART+APB]  [AI-SoC FPGA]  [FSM Elev]
```

<div align="center">

| `signal` Project | `stack` | `output` Key Results |
|:-----------------|:--------|:---------------------|
| 🔄 **[Multi-Clock UART Transceiver + APB Interface](https://github.com/INIYA-1010)** | Verilog · APB · CDC · ModelSim | Dual clock domains (PCLK + UART\_CLK); pulse synchronizers for CDC safety; full APB slave register map; Tx/Rx path verified |
| 👁️ **[Real-Time Object Detection — PYNQ-Z2](https://github.com/INIYA-1010)** | PYNQ-Z2 · YOLO · OpenCV DNN · Python | FPGA hardware-accelerated inference; participated in Bharat AI-SoC Student Challenge |
| 🏢 **[Smart Elevator FSM Controller](https://github.com/INIYA-1010)** | Verilog · FSM · Vivado | Moore/Mealy hybrid FSM; automated multi-floor and door control; priority logic for simultaneous requests |

</div>

---

## `// ACHIEVEMENTS` — *sign-off report*

<div align="center">

```
╔══════════════════════════════════════════════════════════════════╗
║                   [ ACHIEVEMENT LOG ]                           ║
╠══════════════════════════════════════════════════════════════════╣
║  🎯  C-DAC 1-TOPS Semiconductor Tape-Out Program                ║
║      Cleared Round 1 + attended interview for India's           ║
║      prestigious 1-TOPS semiconductor tape-out challenge        ║
╠══════════════════════════════════════════════════════════════════╣
║  🤖  Bharat AI-SoC Student Challenge                            ║
║      FPGA-accelerated real-time object detection on PYNQ-Z2     ║
╠══════════════════════════════════════════════════════════════════╣
║  📜  Certificates Earned                                         ║
║      • Digital Design & Verification — Verilog HDL (Intern)     ║
║      • PCB Skill Development — Invocrux Technologies            ║
║      • Introduction to Semiconductor Devices — NPTEL            ║
║      • Industrial Training: PCB Design & Fabrication            ║
║      • Introduction to IoT — NPTEL                              ║
║      • Digital Design using Multi-Vt Libraries — VLSI Mentors  ║
╚══════════════════════════════════════════════════════════════════╝
```

</div>

---

## `// EDUCATION` — *process node*

<div align="center">

| 🎓 Degree | 🏛️ Institution | 📅 Period | 📊 Score |
|:----------|:--------------|:---------:|:--------:|
| **B.E Electronics Engineering** (VLSI Design & Technology) | K.S. Rangasamy College of Technology · Anna University | Sep 2023 – Jun 2027 | **CGPA 8.18** |
| Higher Secondary — Bio Maths | Sri Vidya Mandir Matric Hr. Sec. School · State Board | Jul 2019 – Mar 2020 | **57%** |

</div>

---

## `// CURRENTLY LOADING` — *place & route in progress*

```verilog
// ══════════════════════════════════════════════════════════
//  STATUS: Active learning — timing analysis in progress
// ══════════════════════════════════════════════════════════

task currently_learning;
  begin
    // 🧱 CDC Analysis
    //    → Metastability, Pulse Synchronizers, FIFO-based CDC
    //    → Multi-clock domain crossing signoff

    // 🔬 UVM Methodology
    //    → Agents, Sequencers, Scoreboards
    //    → Coverage groups, Functional coverage

    // ⏱️  Static Timing Analysis (STA)
    //    → Setup / Hold margins, Clock skew
    //    → Multi-corner, multi-mode (MCMM)

    // 🛡️  DFT / BIST
    //    → LFSR, MISR, Scan chains, STUMPS
    //    → Boundary Scan (JTAG / IEEE 1149.1)

    // 🔧 Synopsys Design Compiler
    //    → SDC constraints, optimization
    //    → Timing & area reports
  end
endtask
```

---

## `// CONNECT` — *open ports*

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-iniyavan--s-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/iniyavan-s-aa0950290/)
[![GitHub](https://img.shields.io/badge/GitHub-INIYA--1010-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/INIYA-1010)
[![Gmail](https://img.shields.io/badge/Gmail-iniyavansoundar2002-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:iniyavansoundar2002@gmail.com)

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=INIYA-1010&label=Profile+Views&color=70a5fd&style=flat-square)

</div>

---

<div align="center">

```
// ── END OF MODULE ────────────────────────────────────
//  always @(posedge opportunity) begin
//    learn <= learn + 1;
//    build <= build + 1;
//  end
// ─────────────────────────────────────────────────────
```

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,30:1a1f35,70:0f2942,100:0d1117&height=130&section=footer&animation=twinkling" width="100%"/>
