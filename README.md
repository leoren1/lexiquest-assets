# LexiQuest Assets

Public model assets for the **LexiQuest** English-learning app, served at
runtime so the app binary stays small enough for the App Store.

These are open-source ML models (no proprietary code):

| File | Size | What |
|---|---|---|
| `models/gemma3-1b-it.task` | ~554 MB | Gemma 3 1B-IT LLM (LiteRT/MediaPipe) |
| `tts/kokoro.zip` | ~369 MB | Kokoro English neural TTS |
| `tts/zipvoice.zip` | ~204 MB | ZipVoice voice-cloning model |

The app downloads them on first launch via raw URLs:
`https://github.com/leoren1/lexiquest-assets/raw/main/<path>`

The application source code lives in a separate private repository.
