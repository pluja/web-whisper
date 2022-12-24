# 👐 This project is hosted on **Codeberg**: [See the repo!](https://codeberg.org/pluja/web-whisper)

#### [Read the self hosting guide](https://codeberg.org/pluja/web-whisper/wiki/Self-Hosting)

OpenAI's [Whisper](https://github.com/openai/whisper) Audio to text transcription right into your web browser!

## ✨ Features:


> **Warning**
> All new features will be updated on the [codeberg source repo](https://codeberg.org/pluja/web-whisper)

- [x] Record and transcribe audio right from your browser.
- [x] Upload any media file (video, audio) in any format and transcribe it.
    - [x] Option to cut audio to X seconds before transcription.
    - [x] Option to disable file uploads.
- [x] Select input audio language.
  - [x] Auto-detect input audio language.
- [x] Option to speed up audio by 2x for faster results (this has negative impact on accuracy).
- [x] Translate input audio transcription to english.
- [x] Download `.srt` subtitle file generated from audio.
- [x] Configure whisper
    - [x] Choose the Whisper model you want to use (tiny, base, small...)
    - [x] Configure the number of **threads** and **processors** to use.
- [x] **Docker compose** for easy self-hosting
- [x] **Privacy respecting**: 
    - All happens locally. No third parties involved.
    - Audio files are deleted immediately after processing.
- [x] Uses C++ whisper version from [whisper.cpp](https://github.com/ggerganov/whisper.cpp).
    - You don't need a GPU, uses CPU.
    - No need for complex installations.
- [x] Backend written in **Go**
- [x] Lightweight and beautiful UI.
    - [x] Frontend written with **Svelte** and **Tailwind CSS**.



## Screenshots

> Screenshots may be outdated, see the [source code repo for updated info](https://codeberg.org/pluja/web-whisper)

##### Main page
<img src="https://farside.link/rimgo/GFBHU8V.png" align=center>

##### Recording
<img src="https://farside.link/rimgo/M5pW2BB.png" align=center>

#### Transcription Options
<img src="https://farside.link/rimgo/a4yf4hu.png" align=center>

#### Processing
<img src="https://farside.link/rimgo/SHOTbh8.png" align=center>

#### Result
<img src="https://farside.link/rimgo/8EodxT9.png" align=center>
