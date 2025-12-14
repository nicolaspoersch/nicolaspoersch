<p align="center">
  <img src="https://i.imgur.com/SpPKhWF.png" width="140" />
</p>

<h1 align="center">Nicolas Poersch</h1>

<p align="center">
  Game hacking & reverse engineering<br/>
  External tooling · input emulation · behavior analysis
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/C%2FC%2B%2B-00599C?style=flat&logo=c%2B%2B&logoColor=white"/>
  <img src="https://img.shields.io/badge/WinAPI-0078D4?style=flat&logo=windows&logoColor=white"/>
  <img src="https://img.shields.io/badge/HID-444444?style=flat"/>
  <img src="https://img.shields.io/badge/Reverse_Engineering-000000?style=flat"/>
</p>

---

## 🧠 Focus

- External game tools (no injection)
- Vision / pixel based detection
- HID & input emulation
- Timing & behavior analysis
- Anti-cheat surface research

---

## ⚙️ Technical Areas

- External architectures
- Behavioral realism
- Input timing & smoothing
- Detection vector reduction
- User-mode research

I prioritize **realism and minimal footprint** over speed or brute-force techniques.

---

## 🚧 Current Project — **Aimi**

**Aimi** is an external vision-based system focused on real-time **model and pixel identification** using **computer vision and neural networks**.

The project relies on a **camera-based pipeline**, avoiding direct interaction with game memory.  
Detection events are forwarded to **microcontrollers**, responsible for movement and input generation via **HID devices**.

### Architecture highlights

- Vision-based detection (CV + NN)
- Camera feed instead of framebuffer access
- Microcontroller communication layer
- HID input via **Makcu / Arduino**
- Human-like movement synthesis
- Designed for operation under **kernel-mode anti-cheat environments**

<p align="center">
  <img src="https://i.imgur.com/8oyqjum.png" />
</p>

---

## ⚠️ Disclaimer

All work is intended for **research and educational purposes**, focused on understanding software behavior, automation detection, and security mechanisms.

---

## 💬 Contact

- Discord: **0130123912391230**
