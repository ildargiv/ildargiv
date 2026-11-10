[English](README.md) | [Русский](README.ru.md) | [Español](README.es.md) | [简体中文](README.zh-CN.md) | [Deutsch](README.de.md) | [Français](README.fr.md) | [Português](README.pt.md) | **Türkçe**

## Ildar Gaisin · ildargiv

**KopiTehnik** geliştiricisi: fotoğraf merkezleri ve profesyonel baskı için, yapay zekâ ajanlarının MCP üzerinden yönetebildiği ücretsiz yazılımlar.

## [KopiTehnik Print](https://github.com/ildargiv/KopiTehnik-Print)

[![release](https://img.shields.io/github/v/release/ildargiv/KopiTehnik-Print?label=release)](https://github.com/ildargiv/KopiTehnik-Print/releases/latest) ![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D4) ![MCP](https://img.shields.io/badge/MCP-server-6E4AFF) [![PyPI](https://img.shields.io/pypi/v/kopitehnik-print-mcp.svg)](https://pypi.org/project/kopitehnik-print-mcp/)

**Muadil mürekkeple fotoğraf kalitesi.** Windows için baskı yazılımı: doğru renk, kenarlıksız baskı, akıllı kırpma ve fotokopi merkezleri, fotoğrafçılar ve profesyonel baskıcılar için sipariş hazırlığı. Kişisel kullanım ve tek bir iş istasyonu için ücretsiz.

**[Windows için indir](https://github.com/ildargiv/KopiTehnik-Print/releases/latest)** · [Tam açıklama](https://github.com/ildargiv/KopiTehnik-Print/blob/main/README.tr.md) · [Web sitesi](https://ildargiv.github.io/KopiTehnik-Print/)

<p align="center"><a href="https://github.com/ildargiv/KopiTehnik-Print"><img src="https://raw.githubusercontent.com/ildargiv/KopiTehnik-Print/main/docs/screenshots/main-window.png" width="860" alt="KopiTehnik Print"></a></p>

- **Ekrandaki gibi renk**: yazıcının ICC profiliyle baskı ve profilin mürekkebinize ve kâğıdınıza göre düzeltilmesi.
- **Tam kenarlıksız baskı**: Epson, Canon, HP ve Brother'da, kenardan kenara test sayfasıyla.
- **Akıllı kırpma**: yüzler, insanlar ve evcil hayvanlar karede kalır.
- **Fotoğraflar ve belgeler tek pencerede**: PDF, Word, Excel, PowerPoint, sayfa başına 1-30 fotoğraf.
- **Yerleşik MCP sunucusu**: Claude Desktop veya herhangi bir MCP istemcisi siparişi alır, fotoğrafları hazırlar ve yazdırır.
- **15 arayüz dili**, kurulum programı, taşınabilir sürüm ve Scoop paketi.

| Yol | Nasıl |
|---|---|
| **Kurulum programı veya taşınabilir exe** | [sürümler sayfası](https://github.com/ildargiv/KopiTehnik-Print/releases/latest) |
| **Scoop** | `scoop bucket add ildargiv https://github.com/ildargiv/scoop-bucket`<br>`scoop install kopitehnik-print` |
| **Yapay zekâ ajanı (MCP)** | `uvx kopitehnik-print-mcp` |

### Baskı ve fotoğraf için diğer araçlar

| Proje | Ne yapar |
|---|---|
| **[KopiTehnik Converter](https://github.com/ildargiv/kopitehnik-converter)** | Toplu dönüştürme, renk, baskı sayfaları, taramalar için OCR'li PDF düzenleyici. Fotoğraf merkezleri için ücretsiz. |
| **[printshop-mcp](https://github.com/ildargiv/printshop-mcp)** | Yapay zekâ ajanının içinde bir matbaa: milimetrik hassasiyetle kartvizit, yaka kartı ve el ilanı, hatırlanan baskı profilleriyle. |
| **[print-mcp](https://github.com/ildargiv/print-mcp)** | Adobe Photoshop üzerinden renk doğruluğu yüksek toplu baskı için MCP sunucusu: kendi ICC profiliniz, sürücü otomatik düzeltmesi kapalı. |
| **[OriginEcho](https://github.com/ildargiv/OriginEcho)** | Yapay zekâ fotoğraf düzenleyicilerinin sildiği EXIF/XMP/IPTC verilerini geri getirir: kamera, tarih, GPS, ISO. |
| **[PhotoGeoFinder](https://github.com/ildargiv/photogeofinder)** | Fotoğrafın çekildiği yer: EXIF'teki GPS, Google, Yandex ve OSM haritalarında. Fotoğraflar cihazdan çıkmaz, 15 dil. |
| **[scoop-bucket](https://github.com/ildargiv/scoop-bucket)** | KopiTehnik uygulamaları için Scoop manifestleri. |

### Yapay zekâ ajanları için beceriler

| Proje | Ne yapar |
|---|---|
| **[city3d](https://github.com/ildargiv/city3d-skill)** | OpenStreetMap'ten 3B gerçek şehir: her bina, kendi adı ve adresiyle ayrı bir model. [Canlı demo](https://ildargiv.github.io/city3d-skill/) |
| **[motion-site](https://github.com/ildargiv/motion-site)** | Kare kare kendini denetleyen, stüdyo kalitesinde animasyonlu web siteleri. |
| **[pagedrop](https://github.com/ildargiv/pagedrop)** | Siteyi tarif edin, çalışan bir GitHub Pages bağlantısı alın. |

### Finans ajanları (Rusya piyasası)

| Proje | Ne yapar |
|---|---|
| **[ru-stocks-agent](https://github.com/ildargiv/ru-stocks-agent)** | Rus hisseleri (MOEX) için yapay zekâ ajanında yatırım komitesi: izleme listesi, her hisse için bir klasör, şeytanın avukatı. |
| **[ru-portfolio-agent](https://github.com/ildargiv/ru-portfolio-agent)** | Rus hisse portföyü için aile ofisi: kapanış sonrası günlük brifing, IMOEX'e karşı haftalık değerlendirme, risk, temettüler, Obsidian bilgi bankası. |
| **[ru-bonds-agent](https://github.com/ildargiv/ru-bonds-agent)** | Rus tahvilleri için analist ajan: MOEX, vergi dairesi verileri, mali tablolar, kredi skorlaması. |
| **[finex-agent](https://github.com/ildargiv/finex-agent)** | Tasfiye sürecindeki FinEx fonlarının pay sahiplerine destek: tasfiye memuru ve mahkeme belgeleri, haberler, pay başına ödemenin piyasa fiyatıyla karşılaştırması. |

### Ekran kartlarında yerel yapay zekâ

| Proje | Ne yapar |
|---|---|
| **[tokenpulse](https://github.com/ildargiv/tokenpulse)** | Yapay zekâ sunucusu izleyicisi: GPU ve CPU yükü, sıcaklıklar, bellek, token hızı ve kalıcı token sayacı. Strata, llama.cpp, LM Studio, Ollama, vLLM ve ComfyUI ile çalışır. |
| **[ai-flight-log-v100](https://github.com/ildargiv/ai-flight-log-v100)** | Tesla V100 SXM2 32 GB üzerinde yapılan ölçümlerin tarihli, yalnızca eklemeli seyir defteri; başarısız ölçümler de başarılılar gibi kaydedilir. |
| **[cmp90hx-strata-tuning](https://github.com/ildargiv/cmp90hx-strata-tuning)** | NVIDIA CMP 90HX 10 GB üzerinde Strata'nın süregelen geçmişi: donanım profili, hesaplama kilidinin açılması, ölçümler. |
| **[rtx3060-strata-tuning](https://github.com/ildargiv/rtx3060-strata-tuning)** | Tek bir RTX 3060 12 GB üzerinde Strata ayarı: 262K bağlamda kod çözme 44 → 61 tok/s, ham veriler ve betiklerle. |

---

ICC profilleri ve renk: [vk.ru/icc_profil](https://vk.ru/icc_profil)
