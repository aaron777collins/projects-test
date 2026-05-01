# sophie-voice-bridge

⭐ 1 stars

## 🔗 Quick Links

- [View on GitHub](https://github.com/aaron777collins/sophie-voice-bridge)

## 📊 Project Details

- **Primary Language:** Python
- **Languages Used:** Python, Dockerfile
- **License:** None
- **Created:** January 28, 2026
- **Last Updated:** April 30, 2026

## 📝 About

# Sophie Voice Bridge

ElevenLabs Custom LLM server that connects to Sophie AI via Clawdbot.

## Architecture

```
WhatsApp Call → ElevenLabs (STT/TTS) → Haiku (fast) ─┬─→ Direct response
                                                      │
                                                      └─→ ask_sophie → Sophie/Opus
                                                                          (full capabilities)
```

- **Haiku** handles fast voice responses (1-3 senten

