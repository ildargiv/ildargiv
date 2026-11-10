**English** | [Русский](README.ru.md) | [Español](README.es.md) | [简体中文](README.zh-CN.md) | [Deutsch](README.de.md) | [Français](README.fr.md) | [Português](README.pt.md) | [Türkçe](README.tr.md)

## Ildar Gaisin · ildargiv

Developer of **KopiTehnik**: free software for photo centres and professional printing that AI agents can drive through MCP.

## [KopiTehnik Print](https://github.com/ildargiv/KopiTehnik-Print)

[![release](https://img.shields.io/github/v/release/ildargiv/KopiTehnik-Print?label=release)](https://github.com/ildargiv/KopiTehnik-Print/releases/latest) ![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D4) ![MCP](https://img.shields.io/badge/MCP-server-6E4AFF) [![PyPI](https://img.shields.io/pypi/v/kopitehnik-print-mcp.svg)](https://pypi.org/project/kopitehnik-print-mcp/)

**Photo quality on compatible ink.** Print software for Windows: accurate colour, borderless printing, smart cropping and order preparation for copy centres, photo desks and professional printers. Free for personal use and for a single workstation.

**[Download for Windows](https://github.com/ildargiv/KopiTehnik-Print/releases/latest)** · [Full description](https://github.com/ildargiv/KopiTehnik-Print#readme) · [Website](https://ildargiv.github.io/KopiTehnik-Print/)

<p align="center"><a href="https://github.com/ildargiv/KopiTehnik-Print"><img src="https://raw.githubusercontent.com/ildargiv/KopiTehnik-Print/main/docs/screenshots/main-window.png" width="860" alt="KopiTehnik Print"></a></p>

- **Colour as on screen**: printing through the printer's ICC profile, with correction of the profile for your ink and paper.
- **Exact borderless printing** on Epson, Canon, HP and Brother, with an edge-to-edge test sheet.
- **Smart cropping**: faces, people and pets stay in the frame.
- **Photos and documents in one window**: PDF, Word, Excel, PowerPoint, 1 to 30 photos per sheet.
- **Built-in MCP server**: Claude Desktop or any MCP client takes the order, prepares the photos and prints.
- **15 interface languages**, installer, portable build and Scoop package.

| Way | How |
|---|---|
| **Installer or portable exe** | [Releases page](https://github.com/ildargiv/KopiTehnik-Print/releases/latest) |
| **Scoop** | `scoop bucket add ildargiv https://github.com/ildargiv/scoop-bucket`<br>`scoop install kopitehnik-print` |
| **AI agent (MCP)** | `uvx kopitehnik-print-mcp` |

### More for print and photo

| Project | What it does |
|---|---|
| **[KopiTehnik Converter](https://github.com/ildargiv/kopitehnik-converter)** | Batch conversion, colour, print sheets, PDF editor with OCR for scans. Free for photo centres. |
| **[printshop-mcp](https://github.com/ildargiv/printshop-mcp)** | A print shop inside an AI agent: business cards, badges and flyers accurate to the millimetre, with remembered print profiles. |
| **[print-mcp](https://github.com/ildargiv/print-mcp)** | MCP server for colour-accurate batch printing through Adobe Photoshop with your own ICC profile and driver auto-correction off. |
| **[OriginEcho](https://github.com/ildargiv/OriginEcho)** | Restores the EXIF/XMP/IPTC that AI photo editors strip: camera, date, GPS, ISO. |
| **[PhotoGeoFinder](https://github.com/ildargiv/photogeofinder)** | Where a photo was taken: GPS from EXIF on Google, Yandex and OSM maps. Photos never leave the device, 15 languages. |
| **[scoop-bucket](https://github.com/ildargiv/scoop-bucket)** | Scoop manifests for KopiTehnik apps. |

### Skills for AI agents

| Project | What it does |
|---|---|
| **[city3d](https://github.com/ildargiv/city3d-skill)** | A real city in 3D from OpenStreetMap: every building is a separate model with its own name and address. [Live demo](https://ildargiv.github.io/city3d-skill/) |
| **[motion-site](https://github.com/ildargiv/motion-site)** | Studio-grade animated websites with a frame-by-frame self-check. |
| **[pagedrop](https://github.com/ildargiv/pagedrop)** | Describe a site and get a live GitHub Pages link. |

### Financial agents (Russian market)

| Project | What it does |
|---|---|
| **[ru-stocks-agent](https://github.com/ildargiv/ru-stocks-agent)** | An investment committee in an AI agent for Russian stocks (MOEX): watchlist, a folder per stock, a devil's advocate. |
| **[ru-portfolio-agent](https://github.com/ildargiv/ru-portfolio-agent)** | A family office for a portfolio of Russian stocks: daily briefing after the close, weekly review against IMOEX, risk, dividends, an Obsidian knowledge base. |
| **[ru-bonds-agent](https://github.com/ildargiv/ru-bonds-agent)** | Analyst agent for Russian bonds: MOEX, tax-service data, financial statements, credit scoring. |
| **[finex-agent](https://github.com/ildargiv/finex-agent)** | Support for holders of FinEx funds in liquidation: liquidator and court documents, news, payout per share against the market price. |

### Local AI on GPUs

| Project | What it does |
|---|---|
| **[tokenpulse](https://github.com/ildargiv/tokenpulse)** | AI-server monitor: GPU and CPU load, temperatures, memory, token speed and a lifetime token counter. Works with Strata, llama.cpp, LM Studio, Ollama, vLLM and ComfyUI. |
| **[ai-flight-log-v100](https://github.com/ildargiv/ai-flight-log-v100)** | A dated, append-only flight log of measurements on a Tesla V100 SXM2 32 GB; failed runs are recorded like passing ones. |
| **[cmp90hx-strata-tuning](https://github.com/ildargiv/cmp90hx-strata-tuning)** | Running history of Strata on an NVIDIA CMP 90HX 10 GB: hardware profile, compute unlock, benchmarks. |
| **[rtx3060-strata-tuning](https://github.com/ildargiv/rtx3060-strata-tuning)** | Tuning Strata on one RTX 3060 12 GB: 44 → 61 tok/s decode at 262K context, with raw data and scripts. |

---

ICC profiles and colour: [vk.ru/icc_profil](https://vk.ru/icc_profil)
