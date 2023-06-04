# 🤫 [web whisper plus](https://codeberg.org/pluja/web-whisper-plus)

Web Whiser brings all the features from OpenAI Whisper Speech To Text to your browser. Easily transcribe any audio to text, edit the subtitles, translate to any language and download in many formats with a web interface.

> Video Demo on Codeberg

### [Read the self hosting guide](https://codeberg.org/pluja/web-whisper-plus/src/branch/main/README.md#user-content-self-hosting)

## Features

- 💬 Transcribe any video or audio file to text
    - From a local file
    - Record from micorphone
    - From a URL source (YouTube, Twitter, Vimeo, etc.) via yt-dlp
- 📝 Generate subtitles for any video or audio file
- 📑 Export in multiple formats: .srt, .txt, .json, copy to clipboard...
- ✍️ Edit the generated subtitles with a simple and intuitive interface
- ✅ Job queue for batch processing files.
    - SQLite database to save transcription history and data.
- 🪺 100% Local: Uses OpenAI Whisper
    - Support for GPU (See self-hosting section)
- 🌐 Auto translation: translate the generated subtitles to any language.
