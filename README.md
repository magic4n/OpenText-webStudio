# OpenText webStudio

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Python 3.x](https://img.shields.io/badge/Python-3.x-yellow.svg)](https://www.python.org/)
[![UI: Material You](https://img.shields.io/badge/Design-Material%20You%20(M3)-6750A4.svg)](https://m3.material.io/)

A bilingual (English & Russian) ASCII / ANSI banner generator and terminal animation engine. Available as a zero-dependency Material You single-page web app and a standalone Python CLI tool.

[Try it right now!](https://opentext.luna-app.space)

---

## Features

- **Bilingual Font Support**:
  - **5x5 Matrix Bitmap Font**: Full English (A–Z), Russian (А–Я, Ё), numbers (0–9), and punctuation[span_1](start_span)[span_1](end_span).
  - **ANSI Shadow Font**: 6-row banner typography with automatic 2x-upscaled fallback for Cyrillic characters[span_2](start_span)[span_2](end_span).
- **ANSI Color Palettes & Gradients**:
  - 16 standard ANSI terminal colors[span_3](start_span)[span_3](end_span).
  - Gradients: `Rainbow`, `Fire`, `Ocean`, `Forest`, `Sunset`, `Cyberpunk`[span_4](start_span)[span_4](end_span).
  - Color modes: Solid fill, horizontal character gradient, and per-row gradient[span_5](start_span)[span_5](end_span).
  - Border framing: Auto-centered box panel (`┌─┐│└─┘`)[span_6](start_span)[span_6](end_span).
- **11 Terminal Animation Engines**[span_7](start_span)[span_7](end_span):
  - `typewriter`, `pulse`, `rainbow_sweep`, `fade_in`, `slide_left`, `blink`, `row_by_row`, `wave`, `sparkle`, `gradient_cycle`, and `logo_animated`[span_8](start_span)[span_8](end_span).
- **Material You (M3) Web Interface**:
  - Real-time terminal preview with scanline / CRT glow toggle.
  - Playback controls: Play/Pause, speed selector (0.5x, 1x, 2x), and manual re-trigger.
  - Multi-glyph selector (`█`, `#`, `@`, `▓`, `*`, `▲` or custom characters).
  - One-click ZIP exporter (powered by JSZip) bundling static ANSI files and runnable Python scripts.
- **Standalone CLI**:
  - Generates organized 5-digit project folders containing ready-to-run `.py` modules and `.txt` files[span_9](start_span)[span_9](end_span).

---

## Quick Start

### Web Application
[Recommended: Open opentext.luna-app.space](https://opentext.luna-app.space)

OR

Simply open `index.html` in any modern web browser or deploy it via GitHub Pages. No build steps, bundlers, or server dependencies required.


### Python CLI
Run the generator directly from the terminal[span_10](start_span)[span_10](end_span):

```bash
python studio.py
