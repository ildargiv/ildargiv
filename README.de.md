[English](README.md) | [Русский](README.ru.md) | [Español](README.es.md) | [简体中文](README.zh-CN.md) | **Deutsch** | [Français](README.fr.md) | [Português](README.pt.md) | [Türkçe](README.tr.md)

## Ildar Gaisin · ildargiv

Entwickler von **KopiTehnik**: kostenlose Software für Fotostudios und professionellen Druck, die KI-Agenten über MCP steuern können.

## [KopiTehnik Print](https://github.com/ildargiv/KopiTehnik-Print)

[![release](https://img.shields.io/github/v/release/ildargiv/KopiTehnik-Print?label=release)](https://github.com/ildargiv/KopiTehnik-Print/releases/latest) ![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D4) ![MCP](https://img.shields.io/badge/MCP-server-6E4AFF) [![PyPI](https://img.shields.io/pypi/v/kopitehnik-print-mcp.svg)](https://pypi.org/project/kopitehnik-print-mcp/)

**Fotoqualität mit kompatibler Tinte.** Drucksoftware für Windows: präzise Farben, randloser Druck, intelligenter Zuschnitt und Auftragsvorbereitung für Copyshops, Fotoläden und professionelle Drucker. Kostenlos für den privaten Gebrauch und für einen einzelnen Arbeitsplatz.

**[Für Windows herunterladen](https://github.com/ildargiv/KopiTehnik-Print/releases/latest)** · [Vollständige Beschreibung](https://github.com/ildargiv/KopiTehnik-Print/blob/main/README.de.md) · [Website](https://ildargiv.github.io/KopiTehnik-Print/)

<p align="center"><a href="https://github.com/ildargiv/KopiTehnik-Print"><img src="https://raw.githubusercontent.com/ildargiv/KopiTehnik-Print/main/docs/screenshots/main-window.png" width="860" alt="KopiTehnik Print"></a></p>

- **Farbe wie auf dem Bildschirm**: Druck über das ICC-Profil des Druckers, mit Korrektur des Profils für Ihre Tinte und Ihr Papier.
- **Exakter randloser Druck** auf Epson, Canon, HP und Brother, mit Testblatt von Kante zu Kante.
- **Intelligenter Zuschnitt**: Gesichter, Personen und Haustiere bleiben im Bild.
- **Fotos und Dokumente in einem Fenster**: PDF, Word, Excel, PowerPoint, 1 bis 30 Fotos pro Blatt.
- **Integrierter MCP-Server**: Claude Desktop oder ein beliebiger MCP-Client nimmt den Auftrag an, bereitet die Fotos vor und druckt.
- **15 Oberflächensprachen**, Installer, portable Version und Scoop-Paket.

| Weg | Wie |
|---|---|
| **Installer oder portable exe** | [Release-Seite](https://github.com/ildargiv/KopiTehnik-Print/releases/latest) |
| **Scoop** | `scoop bucket add ildargiv https://github.com/ildargiv/scoop-bucket`<br>`scoop install kopitehnik-print` |
| **KI-Agent (MCP)** | `uvx kopitehnik-print-mcp` |

### Mehr für Druck und Fotografie

| Projekt | Was es macht |
|---|---|
| **[KopiTehnik Converter](https://github.com/ildargiv/kopitehnik-converter)** | Stapelkonvertierung, Farbe, Druckbögen, PDF-Editor mit OCR für Scans. Kostenlos für Fotostudios. |
| **[printshop-mcp](https://github.com/ildargiv/printshop-mcp)** | Eine Druckerei im KI-Agenten: Visitenkarten, Namensschilder und Flyer millimetergenau, mit gespeicherten Druckprofilen. |
| **[print-mcp](https://github.com/ildargiv/print-mcp)** | MCP-Server für farbgenauen Stapeldruck über Adobe Photoshop mit eigenem ICC-Profil und abgeschalteter Treiber-Autokorrektur. |
| **[OriginEcho](https://github.com/ildargiv/OriginEcho)** | Stellt EXIF/XMP/IPTC wieder her, die KI-Fotoeditoren entfernen: Kamera, Datum, GPS, ISO. |
| **[PhotoGeoFinder](https://github.com/ildargiv/photogeofinder)** | Wo ein Foto aufgenommen wurde: GPS aus EXIF auf Karten von Google, Yandex und OSM. Fotos verlassen das Gerät nicht, 15 Sprachen. |
| **[scoop-bucket](https://github.com/ildargiv/scoop-bucket)** | Scoop-Manifeste für KopiTehnik-Programme. |

### Skills für KI-Agenten

| Projekt | Was es macht |
|---|---|
| **[city3d](https://github.com/ildargiv/city3d-skill)** | Eine echte Stadt in 3D aus OpenStreetMap: jedes Gebäude als eigenes Modell mit Namen und Adresse. [Live-Demo](https://ildargiv.github.io/city3d-skill/) |
| **[motion-site](https://github.com/ildargiv/motion-site)** | Animierte Websites auf Studioniveau mit Selbstprüfung Bild für Bild. |
| **[pagedrop](https://github.com/ildargiv/pagedrop)** | Website beschreiben und einen funktionierenden GitHub-Pages-Link erhalten. |

### Finanzagenten (russischer Markt)

| Projekt | Was es macht |
|---|---|
| **[ru-stocks-agent](https://github.com/ildargiv/ru-stocks-agent)** | Ein Anlageausschuss im KI-Agenten für russische Aktien (MOEX): Beobachtungsliste, ein Ordner pro Aktie, Advocatus Diaboli. |
| **[ru-portfolio-agent](https://github.com/ildargiv/ru-portfolio-agent)** | Ein Family Office für ein Portfolio russischer Aktien: tägliches Briefing nach Börsenschluss, Wochenrückblick gegen den IMOEX, Risiko, Dividenden, Wissensbasis in Obsidian. |
| **[ru-bonds-agent](https://github.com/ildargiv/ru-bonds-agent)** | Analystenagent für russische Anleihen: MOEX, Daten der Steuerbehörde, Abschlüsse, Kreditscoring. |
| **[finex-agent](https://github.com/ildargiv/finex-agent)** | Begleitung für Anteilseigner der FinEx-Fonds in Liquidation: Dokumente von Liquidator und Gericht, Nachrichten, Auszahlung je Anteil gegenüber dem Marktpreis. |

### Lokale KI auf Grafikkarten

| Projekt | Was es macht |
|---|---|
| **[tokenpulse](https://github.com/ildargiv/tokenpulse)** | Monitor für KI-Server: GPU- und CPU-Last, Temperaturen, Speicher, Token-Geschwindigkeit und dauerhafter Token-Zähler. Unterstützt Strata, llama.cpp, LM Studio, Ollama, vLLM und ComfyUI. |
| **[ai-flight-log-v100](https://github.com/ildargiv/ai-flight-log-v100)** | Datiertes, nur fortgeschriebenes Messprotokoll einer Tesla V100 SXM2 32 GB; fehlgeschlagene Messungen werden wie erfolgreiche festgehalten. |
| **[cmp90hx-strata-tuning](https://github.com/ildargiv/cmp90hx-strata-tuning)** | Laufende Geschichte von Strata auf einer NVIDIA CMP 90HX 10 GB: Hardwareprofil, Compute-Unlock, Benchmarks. |
| **[rtx3060-strata-tuning](https://github.com/ildargiv/rtx3060-strata-tuning)** | Tuning von Strata auf einer RTX 3060 12 GB: Dekodierung 44 → 61 tok/s bei 262K Kontext, mit Rohdaten und Skripten. |

---

ICC-Profile und Farbe: [vk.ru/icc_profil](https://vk.ru/icc_profil)
