[English](README.md) | [Русский](README.ru.md) | [Español](README.es.md) | [简体中文](README.zh-CN.md) | [Deutsch](README.de.md) | **Français** | [Português](README.pt.md) | [Türkçe](README.tr.md)

## Ildar Gaisin · ildargiv

Développeur de **KopiTehnik** : des logiciels gratuits pour les boutiques photo et l'impression professionnelle, que les agents IA peuvent piloter via MCP.

## [KopiTehnik Print](https://github.com/ildargiv/KopiTehnik-Print)

[![release](https://img.shields.io/github/v/release/ildargiv/KopiTehnik-Print?label=release)](https://github.com/ildargiv/KopiTehnik-Print/releases/latest) ![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D4) ![MCP](https://img.shields.io/badge/MCP-server-6E4AFF) [![PyPI](https://img.shields.io/pypi/v/kopitehnik-print-mcp.svg)](https://pypi.org/project/kopitehnik-print-mcp/)

**La qualité photo avec des encres compatibles.** Logiciel d'impression pour Windows : couleurs fidèles, impression sans marge, recadrage intelligent et préparation des commandes pour les centres de copie, les boutiques photo et les imprimeurs professionnels. Gratuit pour un usage personnel et pour un seul poste de travail.

**[Télécharger pour Windows](https://github.com/ildargiv/KopiTehnik-Print/releases/latest)** · [Description complète](https://github.com/ildargiv/KopiTehnik-Print/blob/main/README.fr.md) · [Site web](https://ildargiv.github.io/KopiTehnik-Print/)

<p align="center"><a href="https://github.com/ildargiv/KopiTehnik-Print"><img src="https://raw.githubusercontent.com/ildargiv/KopiTehnik-Print/main/docs/screenshots/main-window.png" width="860" alt="KopiTehnik Print"></a></p>

- **La couleur comme à l'écran** : impression via le profil ICC de l'imprimante, avec correction du profil pour votre encre et votre papier.
- **Impression sans marge exacte** sur Epson, Canon, HP et Brother, avec une feuille de test bord à bord.
- **Recadrage intelligent** : visages, personnes et animaux restent dans le cadre.
- **Photos et documents dans une seule fenêtre** : PDF, Word, Excel, PowerPoint, de 1 à 30 photos par feuille.
- **Serveur MCP intégré** : Claude Desktop ou tout client MCP prend la commande, prépare les photos et imprime.
- **15 langues d'interface**, installateur, version portable et paquet Scoop.

| Méthode | Comment |
|---|---|
| **Installateur ou exe portable** | [page des versions](https://github.com/ildargiv/KopiTehnik-Print/releases/latest) |
| **Scoop** | `scoop bucket add ildargiv https://github.com/ildargiv/scoop-bucket`<br>`scoop install kopitehnik-print` |
| **Agent IA (MCP)** | `uvx kopitehnik-print-mcp` |

### Autres outils pour l'impression et la photo

| Projet | Ce qu'il fait |
|---|---|
| **[KopiTehnik Converter](https://github.com/ildargiv/kopitehnik-converter)** | Conversion par lots, couleur, planches d'impression, éditeur PDF avec OCR pour les scans. Gratuit pour les boutiques photo. |
| **[printshop-mcp](https://github.com/ildargiv/printshop-mcp)** | Une imprimerie dans un agent IA : cartes de visite, badges et flyers au millimètre près, avec mémoire des profils d'impression. |
| **[print-mcp](https://github.com/ildargiv/print-mcp)** | Serveur MCP pour l'impression par lots aux couleurs fidèles via Adobe Photoshop, avec votre profil ICC et l'autocorrection du pilote désactivée. |
| **[OriginEcho](https://github.com/ildargiv/OriginEcho)** | Restaure les EXIF/XMP/IPTC effacés par les éditeurs photo IA : appareil, date, GPS, ISO. |
| **[PhotoGeoFinder](https://github.com/ildargiv/photogeofinder)** | Où une photo a été prise : GPS de l'EXIF sur les cartes Google, Yandex et OSM. Les photos ne quittent pas l'appareil, 15 langues. |
| **[scoop-bucket](https://github.com/ildargiv/scoop-bucket)** | Manifestes Scoop pour les applications KopiTehnik. |

### Compétences pour agents IA

| Projet | Ce qu'il fait |
|---|---|
| **[city3d](https://github.com/ildargiv/city3d-skill)** | Une vraie ville en 3D à partir d'OpenStreetMap : chaque bâtiment est un modèle distinct avec son nom et son adresse. [Démo en ligne](https://ildargiv.github.io/city3d-skill/) |
| **[motion-site](https://github.com/ildargiv/motion-site)** | Sites animés de qualité studio avec autovérification image par image. |
| **[pagedrop](https://github.com/ildargiv/pagedrop)** | Décrivez un site et recevez un lien GitHub Pages en ligne. |

### Agents financiers (marché russe)

| Projet | Ce qu'il fait |
|---|---|
| **[ru-stocks-agent](https://github.com/ildargiv/ru-stocks-agent)** | Un comité d'investissement dans un agent IA pour les actions russes (MOEX) : liste de suivi, un dossier par action, un avocat du diable. |
| **[ru-portfolio-agent](https://github.com/ildargiv/ru-portfolio-agent)** | Un family office pour un portefeuille d'actions russes : briefing quotidien après la clôture, revue hebdomadaire face à l'IMOEX, risque, dividendes, base de connaissances Obsidian. |
| **[ru-bonds-agent](https://github.com/ildargiv/ru-bonds-agent)** | Agent analyste des obligations russes : MOEX, données fiscales, états financiers, scoring de crédit. |
| **[finex-agent](https://github.com/ildargiv/finex-agent)** | Accompagnement des porteurs de parts des fonds FinEx en liquidation : documents du liquidateur et du tribunal, actualités, versement par part comparé au prix de marché. |

### IA locale sur GPU

| Projet | Ce qu'il fait |
|---|---|
| **[tokenpulse](https://github.com/ildargiv/tokenpulse)** | Moniteur de serveur IA : charge GPU et CPU, températures, mémoire, vitesse des tokens et compteur de tokens cumulé. Compatible avec Strata, llama.cpp, LM Studio, Ollama, vLLM et ComfyUI. |
| **[ai-flight-log-v100](https://github.com/ildargiv/ai-flight-log-v100)** | Journal de bord daté, en ajout seul, des mesures sur une Tesla V100 SXM2 32 Go ; les essais ratés y figurent au même titre que les réussis. |
| **[cmp90hx-strata-tuning](https://github.com/ildargiv/cmp90hx-strata-tuning)** | Historique de Strata sur une NVIDIA CMP 90HX 10 Go : profil matériel, déverrouillage du calcul, mesures. |
| **[rtx3060-strata-tuning](https://github.com/ildargiv/rtx3060-strata-tuning)** | Réglage de Strata sur une RTX 3060 12 Go : décodage de 44 → 61 tok/s avec un contexte de 262K, données brutes et scripts inclus. |

---

Profils ICC et couleur: [vk.ru/icc_profil](https://vk.ru/icc_profil)
