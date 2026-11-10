[English](README.md) | **Русский** | [Español](README.es.md) | [简体中文](README.zh-CN.md) | [Deutsch](README.de.md) | [Français](README.fr.md) | [Português](README.pt.md) | [Türkçe](README.tr.md)

## Ildar Gaisin · ildargiv

Разработчик **КопиТехник** — бесплатных программ для фотоцентров и профессиональной печати, которыми управляют ИИ-агенты через MCP.

## [KopiTehnik Print](https://github.com/ildargiv/KopiTehnik-Print)

[![release](https://img.shields.io/github/v/release/ildargiv/KopiTehnik-Print?label=release)](https://github.com/ildargiv/KopiTehnik-Print/releases/latest) ![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D4) ![MCP](https://img.shields.io/badge/MCP-server-6E4AFF) [![PyPI](https://img.shields.io/pypi/v/kopitehnik-print-mcp.svg)](https://pypi.org/project/kopitehnik-print-mcp/)

**Фотокачество на совместимых чернилах.** Программа печати для Windows: точный цвет, печать без полей, умное кадрирование и подготовка заказов для копицентров, фотосалонов и профессиональных печатников. Бесплатно для личного использования и для одного рабочего места.

**[Скачать для Windows](https://github.com/ildargiv/KopiTehnik-Print/releases/latest)** · [Полное описание](https://github.com/ildargiv/KopiTehnik-Print/blob/main/README.ru.md) · [Сайт](https://ildargiv.github.io/KopiTehnik-Print/)

<p align="center"><a href="https://github.com/ildargiv/KopiTehnik-Print"><img src="https://raw.githubusercontent.com/ildargiv/KopiTehnik-Print/main/docs/screenshots/main-window.png" width="860" alt="KopiTehnik Print"></a></p>

- **Цвет как на экране**: печать через ICC-профиль принтера и коррекция профиля под ваши чернила и бумагу.
- **Точная печать без полей** на Epson, Canon, HP и Brother, с тестовым листом «от края до края».
- **Умное кадрирование**: лица, люди и животные остаются в кадре.
- **Фото и документы в одном окне**: PDF, Word, Excel, PowerPoint, от 1 до 30 фото на листе.
- **Встроенный MCP-сервер**: Claude Desktop или любой MCP-клиент принимает заказ, готовит фото и печатает.
- **15 языков интерфейса**, установщик, portable-сборка и пакет Scoop.

| Способ | Как |
|---|---|
| **Установщик или portable exe** | [страница релизов](https://github.com/ildargiv/KopiTehnik-Print/releases/latest) |
| **Scoop** | `scoop bucket add ildargiv https://github.com/ildargiv/scoop-bucket`<br>`scoop install kopitehnik-print` |
| **ИИ-агент (MCP)** | `uvx kopitehnik-print-mcp` |

### Ещё для печати и фотографии

| Проект | Что делает |
|---|---|
| **[KopiTehnik Converter](https://github.com/ildargiv/kopitehnik-converter)** | Пакетная конвертация, цвет, печать листами, PDF-редактор с распознаванием сканов. Бесплатно для фотоцентров. |
| **[printshop-mcp](https://github.com/ildargiv/printshop-mcp)** | Типография внутри ИИ-агента: визитки, бейджи, листовки с точностью до миллиметра, с памятью профилей печати. |
| **[print-mcp](https://github.com/ildargiv/print-mcp)** | MCP-сервер для пакетной печати с точным цветом через Adobe Photoshop: свой ICC-профиль, автокоррекция драйвера выключена. |
| **[OriginEcho](https://github.com/ildargiv/OriginEcho)** | Возвращает EXIF/XMP/IPTC, которые стирают ИИ-редакторы фото: камера, дата, GPS, ISO. |
| **[PhotoGeoFinder](https://github.com/ildargiv/photogeofinder)** | Где сделано фото: GPS из EXIF на картах Google, Яндекс и OSM. Фото не покидают устройство, 15 языков. |
| **[scoop-bucket](https://github.com/ildargiv/scoop-bucket)** | Манифесты Scoop для программ КопиТехник. |

### Навыки для ИИ-агентов

| Проект | Что делает |
|---|---|
| **[city3d](https://github.com/ildargiv/city3d-skill)** | Настоящий город в 3D из OpenStreetMap: каждое здание отдельной моделью, со своим названием и адресом. [Живое демо](https://ildargiv.github.io/city3d-skill/) |
| **[motion-site](https://github.com/ildargiv/motion-site)** | Студийные сайты с анимацией и самопроверкой кадр за кадром. |
| **[pagedrop](https://github.com/ildargiv/pagedrop)** | Опишите сайт — получите живую ссылку на GitHub Pages. |

### Финансовые агенты (рынок РФ)

| Проект | Что делает |
|---|---|
| **[ru-stocks-agent](https://github.com/ildargiv/ru-stocks-agent)** | Инвесткомитет в ИИ-агенте для российских акций (MOEX): список наблюдения, папка на каждую акцию, адвокат дьявола. |
| **[ru-portfolio-agent](https://github.com/ildargiv/ru-portfolio-agent)** | Семейный офис для портфеля российских акций: ежедневный брифинг после закрытия торгов, недельный обзор против IMOEX, риск, дивиденды, база знаний в Obsidian. |
| **[ru-bonds-agent](https://github.com/ildargiv/ru-bonds-agent)** | Агент-аналитик облигаций РФ: MOEX, ФНС, отчётность, кредитный скоринг. |
| **[finex-agent](https://github.com/ildargiv/finex-agent)** | Сопровождение пайщиков фондов FinEx в ликвидации: документы ликвидатора и суда, новости, расчёт выплаты на пай против рыночной цены. |

### Локальный ИИ на видеокартах

| Проект | Что делает |
|---|---|
| **[tokenpulse](https://github.com/ildargiv/tokenpulse)** | Монитор ИИ-сервера: загрузка видеокарты и процессора, температуры, память, скорость токенов и постоянный счётчик токенов. Понимает Strata, llama.cpp, LM Studio, Ollama, vLLM и ComfyUI. |
| **[ai-flight-log-v100](https://github.com/ildargiv/ai-flight-log-v100)** | Датированный бортовой журнал измерений на Tesla V100 SXM2 32 ГБ: записи только добавляются, неудачные замеры фиксируются наравне с удачными. |
| **[cmp90hx-strata-tuning](https://github.com/ildargiv/cmp90hx-strata-tuning)** | История Strata на NVIDIA CMP 90HX 10 ГБ: профиль железа, разблокировка вычислений, замеры. |
| **[rtx3060-strata-tuning](https://github.com/ildargiv/rtx3060-strata-tuning)** | Настройка Strata на одной RTX 3060 12 ГБ: декодирование 44 → 61 ток/с при контексте 262K, с сырыми данными и скриптами. |

---

ICC-профили и цвет: [vk.ru/icc_profil](https://vk.ru/icc_profil)
