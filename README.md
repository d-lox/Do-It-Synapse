# Do-It-Synapse
Synapse — AI study agent for Do It

# Synapse AI 🧠⚡

An experimental, offline-first AI study and productivity companion built for Android. 

Synapse AI bridges the gap between heavy cloud models and local privacy. Whether you're connected to high-speed internet or sitting offline in a remote classroom, Synapse adapts to your environment while keeping your data strictly in your hands.

---

## ✨ What Makes It Different?

* **Hybrid AI Engine:** Switch effortlessly between lightning-fast cloud APIs (Gemini/Groq) and 100% private, on-device quantized small language models (Phi-3 / Gemma 2 via GGUF/MediaPipe) when you have zero internet.
* **Distraction-Free Active Recall:** Designed specifically for deep focus—no bloated feeds, no social noise, just pure document intelligence, active testing, and smart study breakdowns.
* **The "Do It" Ecosystem Bridge:** Uses local Android Intents and custom URI schemes (`doit://`) to seamlessly push action items and study tasks straight into your task manager completely offline.
* **High-End Glassmorphism UI:** Built with a stealthy, monochrome "black box" aesthetic, frosted glass containers (`BackdropFilter`), and sharp geometric minimalism.

---

## 🛠️ Tech Stack

* **Framework:** Flutter / Dart (Android)
* **Local Inference:** `llama.cpp` / MediaPipe wrapper for on-device GGUF execution
* **Inter-app Comms:** Native Android Intents & Custom URL Schemes

---

## 🚀 Status
Currently in active development as part of the local productivity suite. Pull requests, architectural ideas, and contributions are welcome!
