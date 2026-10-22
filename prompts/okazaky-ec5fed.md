# Engraved lyric music video

A Claude Opus 5.5 motion design video by [@okazaky](https://x.com/okazaky). [Original post](https://x.com/okazaky/status/2107826563786084783) · [Watch on MotionVideo](https://motionvideo.xyz/videos/okazaky-ec5fed?utm_source=github&utm_medium=readme&utm_campaign=awesome-opus-5-5-motion-design)

[![Engraved lyric music video](https://assets.motionvideo.xyz/motion/okazaky-ec5fed/poster-a01975e22a.jpg)](https://motionvideo.xyz/videos/okazaky-ec5fed?utm_source=github&utm_medium=readme&utm_campaign=awesome-opus-5-5-motion-design)

- **Creator:** [@okazaky](https://x.com/okazaky)
- **Model:** Claude Opus 5.5
- **Stack:** Three.js
- **Categories:** Music and audio-reactive, Kinetic typography
- **Posted:** 2026-10-07

## Prompt

```text
Create a 50-second vertical music video using programmatic rendering (Three.js) instead of native video AI.
1. Generate song with Suno. Extract lyrics from embedded metadata.
2. Separate stems with Demucs (vocals, drums, bass, other).
3. Transcribe vocals with mlx_whisper. Align with official lyrics to create script where '1 lyric line = 1 scene'.
4. Write storyboard: define 'What to show in 3D', 'Camera', 'Main word' for each lyric line.
5. Have 4 parallel Opus sub-agents write scene programs.
6. Export 16-frame contact sheet for visual verification.
7. Render headless Chrome at 1080x1920, 60fps.
8. Normalize volume to -14 LUFS.
Style: Engraving-like lines, colors limited to Black, Bone, Orange.
```

More Claude Opus 5.5 motion design, each with its prompt: [motionvideo.xyz/model/opus-5-5](https://motionvideo.xyz/model/opus-5-5?utm_source=github&utm_medium=readme&utm_campaign=awesome-opus-5-5-motion-design)
