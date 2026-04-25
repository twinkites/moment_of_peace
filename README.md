# Moment of Peace

A breathing meditation app by Twin Kites LLC. One HTML file, no dependencies, works offline.

---

## What it does

The orb expands and contracts to guide your breath. Tap it to pause. Three patterns: even 4·4, 4·7·8, and box breathing. A thin arc ring around the orb counts down 1, 3, or 5-minute sessions.

Sound is generated in the browser via Web Audio — no files downloaded. Binaural option runs 432 Hz left / 436 Hz right (best with headphones). Rain is layered filtered noise.

The orb slowly cycles through colors, particles drift upward around it, and it shifts with your mouse or phone tilt. Time-of-day tinting adjusts automatically — warm at dawn and dusk, cool indigo at night.

---

## Notes

- Audio is synthesized entirely via Web Audio API — no samples, no downloads
- Orb animation is JS-driven frame by frame so the visual and breath label stay in sync
- Wake lock keeps the screen on during sessions (Chrome/Safari; ignored in Firefox)
- Pattern and dark mode preferences are saved in `localStorage`
- Installable as a PWA on iOS 16.4+ and Android

---

Built by [Twin Kites LLC](https://twinkites.com)
