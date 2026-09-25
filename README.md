# Voice Translator

A real-time speech-to-speech translator for Indian languages that aims to preserve the speaker's own voice.

# Voice Translator

A real-time speech-to-speech translator for Indian languages that aims to preserve the speaker's own voice.

## Current status

Working end-to-end prototype that:
- Takes a voice recording in Hindi
- Translates it to English using Whisper (faster-whisper, medium model)
- Speaks the English translation in the user's own cloned voice using F5-TTS
- Uses a spoken consent phrase as the voice reference

Baseline: ~6.5 seconds to generate the cloned audio on a T4 GPU.

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
