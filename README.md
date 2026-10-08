# Whisper Transcription

Transcribe audio files (including Arabic) using OpenAI's Whisper model via the Hugging Face `transformers` library in Google Colab.

## Overview

This project provides a Google Colab notebook for automatic speech recognition (ASR) using Whisper. It supports:

- English and multilingual transcription
- Arabic audio (MSA and dialects)
- Translation to English
- Timestamped segments
- Chunked processing for long audio files

## Features

- 🎙️ Transcribe audio in 90+ languages
- 🌍 Arabic support with dialect hints via `initial_prompt`
- ⏱️ Word/segment-level timestamps
- 🔄 Translation mode (any language → English)
- 📦 Runs on Colab's free T4 GPU
- 🧩 Uses Hugging Face `transformers` pipeline API

## Requirements

- Google Colab (recommended) or a local Python 3.10+ environment
- `transformers`
- `torchaudio`
- `soundfile`
- (Optional) `torch` with CUDA for GPU acceleration

Install dependencies:

```bash
pip install -q transformers torchaudio soundfile
