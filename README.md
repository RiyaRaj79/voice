# Voice Translator

A real-time speech-to-speech translator for Indian languages that aims to preserve the speaker's own voice.

## Current status (Day 1)

Working prototype that:
- Takes a voice recording in Hindi
- Transcribes it using Whisper (faster-whisper)
- Translates it to English
- Speaks the English translation aloud

## Pipeline

Voice input → Speech recognition → Translation → Speech output

## Roadmap

- [x] Basic speech-to-English-speech pipeline
- [ ] Support Tamil and Telugu
- [ ] Translate from English back into Indian languages
- [ ] Voice cloning, so the output sounds like the original speaker
- [ ] Real-time streaming with under 1 second latency
- [ ] Web app for live two-person conversations
- [ ] Consent check and audio watermarking for safe voice cloning

## Tech used

Python, Google Colab, faster-whisper, gTTS
