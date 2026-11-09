<h1 align="center">Shiva Singh</h1>

<p align="center">
  <b>Embedded Systems Engineer · Edge AI · VLSI · Computer Vision</b><br/>
  B.Tech ECE (AI &amp; Cybernetics) · VIT Bhopal University · <b>CGPA 9.4</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/STATUS-Open%20to%20Internships%20%26%20Full--time%20Roles-64FFDA?style=for-the-badge&labelColor=0A192F"/>
</p>

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/Resume-Download%20PDF-D32F2F?style=for-the-badge&logo=adobeacrobatreader&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/thakur-shiva-singh-173467324"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:shiva.24bac10057@vitbhopal.ac.in"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <a href="https://leetcode.com/u/SHIVA__SINGH07/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black"/></a>
</p>

---

## 👤 Recruiter Snapshot

| | |
|---|---|
| **Roles I'm targeting** | Embedded / Firmware Engineer · Embedded Software Intern · VLSI / Digital Design Intern · Edge AI / TinyML Engineer · Computer Vision Engineer |
| **Core strengths** | Bare-metal Embedded C · STM32F40x &amp; ESP32 · ARM Cortex-M · Peripheral drivers (UART/SPI/I2C) · TFLite Micro |
| **Academics** | B.Tech ECE (AI &amp; Cybernetics), VIT Bhopal · CGPA **9.4** · Batch of 2028 |
| **Problem solving** | **300+** LeetCode problems · Graphs, Trees, Greedy, Sliding Window, Binary Search |
| **Hands-on hardware** | STM32F40x · ESP32 · Raspberry Pi · Ansys HFSS |
| **Availability** | Open to internships, PPO tracks and research collaborations · Location: India / Remote / Relocatable |

---

## 🎯 What I Bring

- **Close-to-metal firmware.** I write register-level drivers, ISRs and layered HALs instead of relying only on vendor libraries, and I understand what the compiler and the core do underneath.
- **ML that fits on a chip.** I train models in TensorFlow, quantize to INT8 and deploy with TFLite Micro, tracking accuracy against latency and memory.
- **Hardware plus software range.** I work from RF/antenna simulation and digital logic up to embedded firmware, computer vision and DSP.
- **Strong fundamentals.** I'm solid on data structures and algorithms, digital design, OS/RTOS concepts and electromagnetics, with a 9.4 CGPA behind it.

---

## 🛠️ Skills (by role)

<table>
<tr>
<td width="25%"><b>🔩 Embedded / Firmware</b></td>
<td>Embedded C · Bare-metal · <b>STM32F40x (Cortex-M4F)</b> · ESP32 · Raspberry Pi · GPIO/Timer/ADC/PWM/DMA · UART/SPI/I2C · NVIC &amp; ISRs · Clock tree/PLL · Startup code &amp; linker scripts · BLE/Wi-Fi · FreeRTOS <i>(learning)</i> · ST-Link/SWD debugging · STM32CubeIDE · CMSIS</td>
</tr>
<tr>
<td><b>🖥️ Low-level</b></td>
<td>ARM Cortex-M3/M4 assembly · inline asm in C · stack frames &amp; calling conventions · memory-mapped I/O · reading compiler output</td>
</tr>
<tr>
<td><b>🔬 VLSI / Digital</b></td>
<td>Boolean algebra · K-maps · combinational &amp; sequential design · FSM (Mealy/Moore) · setup/hold &amp; propagation delay · CMOS inverter, NAND/NOR · Verilog <i>(in progress)</i></td>
</tr>
<tr>
<td><b>🧠 Edge AI / ML</b></td>
<td>TensorFlow/Keras · ANN · CNN · RNN/LSTM · INT8 quantization · TFLite &amp; TFLite Micro · model evaluation</td>
</tr>
<tr>
<td><b>👁️ Vision / Multimedia</b></td>
<td>OpenCV · real-time inference · edge &amp; contour analysis · MFCC · FFT · FIR/IIR filters · video frame &amp; motion analysis</td>
</tr>
<tr>
<td><b>📡 RF / EM</b></td>
<td>Ansys HFSS · microstrip patch antennas · S11 · radiation pattern &amp; gain · impedance matching · Maxwell's equations</td>
</tr>
<tr>
<td><b>💻 Programming &amp; Tools</b></td>
<td>C · C++ · Python · Flask · Git/GitHub · Linux · VS Code</td>
</tr>
</table>

<p>
  <img src="https://skillicons.dev/icons?i=c,cpp,python,stm32,arduino,raspberrypi,linux,tensorflow,opencv,flask,git,github,vscode&perline=13" />
</p>

---

## 🚀 Projects

> Format: **Problem → What I built → Result**. Click through for code and write-ups.

### 🛡️ [Beacon Guard](#) — Embedded AI Safety System
- **Problem:** A safety device must react in real time and keep working when connectivity drops.
- **Built:** ESP32 firmware in Embedded C with an ISR-driven, event-based architecture, a BLE pipeline and GPS fallback logic, designed for tight memory limits.
- **Result:** *(add: end-to-end latency, uptime/test duration, memory usage)*
- `ESP32` `Embedded C` `BLE` `UART` `GPS` `ISR`

### 🔌 [Peripheral Driver Library](#) — STM32F40x &amp; ESP32 *(WIP)*
- **Problem:** Vendor HALs hide how peripherals really work and cost flash and speed.
- **Built:** Register-level UART, SPI and I2C drivers behind a layered HAL, with ARM assembly for time-critical paths.
- **Result:** *(add: code size vs. vendor HAL, throughput, supported peripherals)*
- `Embedded C` `STM32F40x` `ARM Assembly` `HAL` `DMA`

### 🧠 [Edge ML Classifier](#) — TinyML on a Microcontroller
- **Problem:** Neural networks are usually too large for MCUs.
- **Built:** A compact model with INT8 quantization and a memory-footprint analysis, aimed at bare-metal execution on ESP32.
- **Result:** *(add: model size KB, accuracy before/after quantization, inference time ms)*
- `TFLite Micro` `Quantization` `Python` `ESP32`

### 👁️ [CNN Vision Pipeline on Raspberry Pi](#)
- **Problem:** Run image classification on live camera input without a GPU.
- **Built:** OpenCV preprocessing feeding a TFLite inference engine on a Raspberry Pi.
- **Result:** *(add: FPS, accuracy, resolution)*
- `CNN` `OpenCV` `TFLite` `Raspberry Pi`

### 🎵 [Multimodal Emotion Engine](#) — NLP + Audio
- **Problem:** Recognize emotion from both text and speech.
- **Built:** A Flask backend with an RNN/LSTM pipeline over text tokens and audio MFCC features.
- **Result:** *(add: accuracy / F1, dataset used)*
- `Flask` `LSTM` `MFCC` `NLP`

### 📡 [Patch Antenna Design in HFSS](#)
- **Problem:** Design a compact antenna that is well matched at the target band.
- **Built:** Microstrip patch antennas in Ansys HFSS, optimized for geometry, S11, gain and radiation pattern.
- **Result:** *(add: center frequency, S11 in dB, bandwidth, gain in dBi)*
- `HFSS` `RF` `S-parameters` `EMT`

---

## 🧩 Interview-Ready Fundamentals

<details>
<summary><b>Embedded / Firmware topics I can discuss in depth</b></summary>

`volatile`, `const`, and memory-mapped registers · bit manipulation · interrupt latency, priorities and ISR design rules · debouncing · polling vs. interrupts vs. DMA · stack vs. heap and static allocation · startup sequence and linker script · UART/SPI/I2C trade-offs · clock tree and PLL · Cortex-M exception model · race conditions and critical sections · RTOS basics (tasks, queues, semaphores, mutexes)
</details>

<details>
<summary><b>VLSI / Digital design topics</b></summary>

K-map minimization · adders, MUX, decoders, ALU · latch vs. flip-flop · Mealy vs. Moore FSM · setup and hold time, clock skew, metastability · CMOS inverter operation, NAND/NOR · propagation delay and dynamic power
</details>

<details>
<summary><b>DSA / Problem solving</b></summary>

Arrays and strings · two pointers · sliding window · binary search · trees and graphs (BFS/DFS) · greedy · recursion and backtracking · complexity analysis
</details>

<details>
<summary><b>ML / Edge AI topics</b></summary>

CNN vs. RNN/LSTM · overfitting and regularization · backpropagation · quantization (post-training vs. QAT) · accuracy vs. latency vs. memory trade-offs · deployment constraints on MCUs
</details>

---

## 📊 Proof of Work

<p align="center">
  <a href="https://github.com/shivasingh95">
    <img height="165" src="https://github-readme-stats.vercel.app/api?username=shivasingh95&show_icons=true&theme=transparent&hide_border=true&title_color=0A66C2&icon_color=0A66C2&text_color=8b949e&count_private=true"/>
  </a>
  <a href="https://leetcode.com/u/SHIVA__SINGH07/">
    <img height="165" src="https://leetcard.jacoblin.cool/SHIVA__SINGH07?theme=dark&font=JetBrains%20Mono&border=0&radius=12"/>
  </a>
</p>

---

## 🏆 Experience, Certifications &amp; Achievements

<!-- Placement recruiters look for this section. Fill in whatever applies and delete the rest. -->

| Type | Details |
|---|---|
| 💼 **Internship** | *Company · Role · Duration · one-line impact* |
| 🎓 **Certifications** | *e.g., Embedded Systems course, TinyML (edX/Coursera), NPTEL, Verilog/FPGA* |
| 🏅 **Achievements** | *Hackathons, competitions, ranks, scholarships, publications* |
| 👥 **Leadership** | *Club roles, team lead, mentoring* |

---

## 🎯 Next 6 Months

- [ ] Finish register-level UART, SPI and I2C drivers (STM32F40x + ESP32)
- [ ] Bring up STM32F40x from scratch: clock tree, startup code, linker script, DMA-driven ADC/UART
- [ ] Run an INT8 TFLite Micro model on STM32F40x and ESP32
- [ ] FreeRTOS multitasking project with queues and semaphores
- [ ] FSM-based system in Verilog, simulated and synthesized
- [ ] Real-time object detection on Raspberry Pi
- [ ] Reach 400 LeetCode problems
- [ ] First open-source embedded / CV contribution

---

## 📬 Let's Talk

If you're hiring for **embedded, firmware, VLSI or edge-AI** roles, I'd love to chat.

📧 [shiva.24bac10057@vitbhopal.ac.in](mailto:shiva.24bac10057@vitbhopal.ac.in) · 💼 [LinkedIn](https://www.linkedin.com/in/thakur-shiva-singh-173467324) · 📄 [Resume](#)

<p align="center">
  <i>"First make it work. Then make it right. Then make it fast."</i>
</p>
