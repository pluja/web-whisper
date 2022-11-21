# 👐 This project is hosted on **Codeberg**: [See the repo!](https://codeberg.org/pluja/web-whisper)

## [web-whisper](https://codeberg.org/pluja/web-whisper)

Get OpenAI's [Whisper](https://github.com/openai/whisper) Audio to text transcription right into your web browser!

## ✨ Features:


> **Warning**
> All new features will be updated on the [codeberg source repo](https://codeberg.org/pluja/web-whisper)

- [x] Record and transcribe audio right from your browser.
- [x] Upload any media file (video, audio) in any format and transcribe it.
- [x] Download `.srt` subtitle file generated from audio.
- [x] Lightweight and beautiful UI.
- [x] Self-hosted. No 3rd parties.
- [x] **Docker compose** for easy self-hosting
- [x] Select input audio language
- [x] **Privacy respecting**: 
    - All happens locally. No third parties involved.
    - Audio files are deleted immediately after processing.
- [x] Backend written in **Go**
- [x] Frontend written with **Svelte** and **Tailwind CSS**.
- [x] Uses C++ whisper version from [whisper.cpp](https://github.com/ggerganov/whisper.cpp).
    - You don't need a GPU, uses CPU.
    - No need for complex installations.
