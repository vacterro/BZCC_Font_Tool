<div align="center">

# BZCC Font Tool

**Build and tune replacement fonts for Battlezone: Combat Commander from a Windows GUI.**

![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=flat-square&logo=python&logoColor=white)
![PyQt5](https://img.shields.io/badge/UI-PyQt5-41CD52?style=flat-square)
![Game](https://img.shields.io/badge/game-BZCC-D4B86A?style=flat-square)

<img width="1000" alt="BZCC Font Tool interface" src="https://github.com/user-attachments/assets/6218a89a-7773-4f12-8350-a8ddb06a0043" />

</div>

## What it does

BZCC Font Tool turns a desktop font into a Battlezone-compatible font asset while exposing the rendering controls that usually require repetitive trial and error.

The tool can render the game character set from a selected font and lets you adjust pixel size, anti-aliasing, stroke, sharpening, contrast, brightness, color, size offset, and letter spacing before export.

## Quick start

Requirements: **Windows**, **Python 3**, PyQt5, FreeType bindings, and Pillow.

```powershell
pip install PyQt5 freetype-py Pillow
python bz2_font_tool.py
```

The application stores UI preferences through Qt settings, so the working setup survives between sessions.

## Highlights

- visual font selection and preview;
- game-oriented bitmap rendering for character codes 1–255;
- anti-aliased or monochrome rendering;
- adjustable stroke, size offset, and letter spacing;
- brightness, contrast, sharpening, and color controls;
- safe font-name sanitization for generated output;
- one-file Python application that is easy to inspect and modify.

## Repository

| Path | Purpose |
|---|---|
| `bz2_font_tool.py` | complete application and rendering pipeline |
| `README.md` | project overview and usage |
| `SUPPORT.md` | optional support methods |


## Project network

Part of the broader **SAIPEN / vacterro** project ecosystem.

[**Author hub**](https://github.com/vacterro) · [**SAIPEN HQ**](https://github.com/saipenhq) · [**SAIPEN Core**](https://github.com/vacterro/saipen) · [**ZAICODE**](https://github.com/vacterro/zaicode) · [**FastPrompter**](https://github.com/vacterro/FastPrompter) · [**SAIPEN Community**](https://discord.gg/SEYaYkuVgN)

For reproducible bugs and durable feature requests, use [GitHub Issues](https://github.com/vacterro/BZCC_Font_Tool/issues).

<!-- VACTERRO_SUPPORT:BEGIN -->
---
<sub>If BZCC Font Tool is useful to you, optional support: [Buy Me a Coffee](https://buymeacoffee.com/vacuum34) · [Boosty](https://boosty.to/vacuum34/donate) · [PayPal](https://paypal.me/AlexNelin) · [other ways](https://github.com/vacterro/vacterro/blob/main/SUPPORT.md)</sub>
<!-- VACTERRO_SUPPORT:END -->
