# Voice Translator

A real-time speech-to-speech translator for Indian languages that aims to preserve the speaker's own voice.

# Voice Translator

A real-time speech-to-speech translator for Indian languages that aims to preserve the speaker's own voice.

## Current status

- Custom accessible web UI (light and dark mode) built with HTML and Tailwind CSS
- FastAPI backend serving the AI pipeline, exposed via Cloudflare Tunnel
- Supports Hindi, Tamil, and Telugu speech input with English voice output

## Pipeline

Voice input → Speech recognition → Translation → Voice-cloned speech output

## Roadmap

- [x] Basic speech-to-English-speech pipeline
- [x] Voice cloning, so the output sounds like the original speaker
- [ ] Support Tamil and Telugu
- [ ] Translate from English back into Indian languages
- [ ] Real-time streaming with under 1 second latency
- [ ] Web app for live two-person conversations
- [ ] Audio watermarking for safe voice cloning

## Tech used

Python, Google Colab, faster-whisper, F5-TTS

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
