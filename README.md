# Stefan Benjamim

**Computer Engineer** — PUCPR, 2026.

I build things that run on their own hardware. Local AI, embedded systems, and whatever
glue they need in between — usually on Linux, usually because I wanted the thing to exist
and nobody had built it yet.

I'm at my best tracing a wrong result back to where it actually starts.

---

### 🎤 Talking-Buddy — a voice assistant with no cloud behind it

[`waifuisalie/Talking-Buddy`](https://github.com/waifuisalie/Talking-Buddy) · [showcase](https://rafapiveta.github.io/talking-buddy-project/)

Wake word → speech-to-text → LLM → speech, running entirely on a Raspberry Pi 5. No cloud,
no API keys: openWakeWord, whisper.cpp, Gemma 3 on Ollama, Supertonic TTS, plus RAG over
per-user PDFs and RFID login. Brazilian Portuguese first.

My final graduation project, built with a classmate — I owned the backend, the wake-word
training, the AI integration, and the testing.

### ☦ Ortholingo — AI pronunciation scoring for liturgical Greek

[`waifuisalie/Ortholingo`](https://github.com/waifuisalie/Ortholingo)

The same speech recognition that took voice commands in Talking-Buddy now grades how you
say the Trisagion. Two-tier faster-whisper scoring, audio and word timings precomputed at
build time so the app stays offline-first, FSRS spaced repetition.

Built alone, from the model to the front-end. It exists because I was learning this Greek
myself and couldn't find anything that taught it the way it's actually prayed.

### ⚙️ A compiler, in four stages

[lexer](https://github.com/waifuisalie/LFC---Analisador-Lexico) →
[LL(1) parser](https://github.com/waifuisalie/RA2_1) →
[semantic analyzer](https://github.com/waifuisalie/RA3_1) →
[codegen + optimizer](https://github.com/waifuisalie/RA4_1)

Our own language in, AVR assembly for the ATmega328P out — the last stage runs a multi-pass
optimizer and flashes the board over AVRDUDE. Four phases, one language, built with three
classmates.

---

**Day to day:** C++ and Python. EndeavourOS + Hyprland, Neovim, and a terminal setup I have
put an unreasonable amount of time into.
