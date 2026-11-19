# What-if Shorts Pipeline

![Python](https://img.shields.io/badge/Python-3b3a36?style=flat-square) ![Claude](https://img.shields.io/badge/Claude-3b3a36?style=flat-square) ![Flux](https://img.shields.io/badge/Flux-3b3a36?style=flat-square) ![Kling](https://img.shields.io/badge/Kling-3b3a36?style=flat-square) ![ElevenLabs](https://img.shields.io/badge/ElevenLabs-3b3a36?style=flat-square) ![FFmpeg](https://img.shields.io/badge/FFmpeg-3b3a36?style=flat-square) ![YouTube API](https://img.shields.io/badge/YouTube%20API-3b3a36?style=flat-square)


Automates vertical "What if…" concept trailers end to end.

```mermaid
flowchart LR
  I[Idea<br/>or auto] --> S[Script · Claude] --> IMG[Scenes · Flux]
  IMG --> ANI[Animation · Kling] --> V[Voice-over · ElevenLabs]
  V --> ED[Edit · FFmpeg<br/>music, captions] --> YT[YouTube upload]
```

## Details
- **Terminal UI** shows each stage live; type an idea or leave it empty for an automatic one
- API keys entered in the UI: saved to `.env` only if you tick *remember*, otherwise kept in memory for the session
- Royalty-free music picked at random from a local folder
- **Dry-run mode** renders the full edit with placeholder scenes — no paid API calls

---

> **Showcase repository.** This repo presents the project — what it does, how it is built and what it looks like.
> The full source code is private. For a walkthrough or a code sample, get in touch.

**Tural Zamanlı** · Data & Automation Developer · [Portfolio](https://dicapso.github.io) · [GitHub](https://github.com/Dicapso)
