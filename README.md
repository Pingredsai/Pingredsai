### Hi, I'm Pingredsai 👋

I build **on-device AI** — language models that run entirely on a phone.
No cloud. No API keys. No data leaving the device.

---

#### 🔭 Currently

**[LocalAI](https://github.com/Pingredsai/local-ai-android)** — a fully offline LLM chat app for Android
(llama.cpp + JNI + Jetpack Compose, MIT licensed).

Measured on a 2019 Pixel 4 with Qwen2.5-1.5B Q4_K_M:

| Metric | Result |
|---|---|
| Generation | **18.5 tok/s** |
| First token | **52 ms** |
| Memory | ~1.3 GB |
| Network permission | **none** |

The app's manifest does not request `INTERNET` at all.

---

#### 🛠 What I work on

- **On-device / mobile LLM inference** — llama.cpp, GGUF, ARM optimisation
- **Android** — Kotlin, Jetpack Compose, JNI/NDK, CMake
- **Local & private LLM deployment** — RAG, knowledge bases, air-gapped setups
- **Performance debugging** — and I write up what I find

---

#### 📝 Writing

Debugging notes from the trenches (Chinese and English):

- *Why Your Phone Runs LLMs 80x Slower Than It Should* — the missing `-march`
- *Threads on Big Cores, CPU at Full Clock — Still Slow* — ruling out scheduling and frequency scaling
- *Is Your Phone's LLM 37x Too Slow?* — the `-O0` build trap

Also on [DEV](https://dev.to/pingredsai) and 掘金.

---

#### 💬 Open to

Freelance work on **on-device AI** and **local LLM integration** —
especially where data cannot leave the device
(legal, healthcare, finance, air-gapped environments).

If you're building something in this space, I'd like to hear about it.