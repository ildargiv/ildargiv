## Ильдар Гайсин · ildargiv

Разработчик **КопиТехник** — бесплатных программ для фотоцентров и профессиональной печати, которыми управляют ИИ-агенты через MCP.
*Developer of KopiTehnik: free photo-lab and print software, controlled by AI agents through MCP.*

### С чего начать

| Задача | Проект |
|---|---|
| Печатать фото на струйном принтере (Epson, Canon, HP, Brother) | [KopiTehnik Print](https://github.com/ildargiv/KopiTehnik-Print) |
| Пакетно конвертировать и печатать листами в фотоцентре | [КопиТехник Конвертор](https://github.com/ildargiv/kopitehnik-converter) |
| Печатать папки через Adobe Photoshop с точным цветом | [print-mcp](https://github.com/ildargiv/print-mcp) |
| Визитки, бейджи, листовки с точностью до миллиметра | [printshop-mcp](https://github.com/ildargiv/printshop-mcp) |
| Вернуть EXIF/XMP/IPTC, которые стёрли ИИ-редакторы | [OriginEcho](https://github.com/ildargiv/OriginEcho) |
| Разобрать облигации или акции РФ с помощью ИИ-агента | [ru-bonds-agent](https://github.com/ildargiv/ru-bonds-agent), [ru-stocks-agent](https://github.com/ildargiv/ru-stocks-agent) |
| Следить за GPU и токенами локальной модели | [tokenpulse](https://github.com/ildargiv/tokenpulse) |

Установка на Windows через [Scoop](https://scoop.sh):

```powershell
scoop bucket add ildargiv https://github.com/ildargiv/scoop-bucket
scoop install kopitehnik-print
```

В бакете сейчас лежит KopiTehnik Print (портативная сборка). Остальные проекты ставятся по инструкции в их README.

### Печать и фотография

| Проект | Что делает |
|---|---|
| **[KopiTehnik Print](https://github.com/ildargiv/KopiTehnik-Print)** | Печать фото на Epson, Canon, HP, Brother: ICC-профили, коррекция цвета принтера, печать без полей, умное кадрирование. Режим MCP для ИИ-агентов |
| **[КопиТехник Конвертор](https://github.com/ildargiv/kopitehnik-converter)** | Пакетная конвертация, цвет, печать листами, PDF-редактор с распознаванием сканов. Бесплатно для фотоцентров |
| **[print-mcp](https://github.com/ildargiv/print-mcp)** | MCP-сервер пакетной печати через Adobe Photoshop: свой ICC-профиль принтера, автокоррекция драйвера выключена, зеркало для сублимации, 16 инструментов. Windows, Photoshop 26.x |
| **[printshop-mcp](https://github.com/ildargiv/printshop-mcp)** | Типография внутри ИИ-агента: визитки, бейджи, листовки с точностью до миллиметра, с памятью профилей печати |
| **[OriginEcho](https://github.com/ildargiv/OriginEcho)** | Возвращает EXIF/XMP/IPTC, которые стирают ИИ-редакторы фото: камера, дата, GPS, ISO |
| **[PhotoGeoFinder](https://github.com/ildargiv/photogeofinder)** | Где сделано фото: GPS из EXIF на Google, Яндекс и OSM-картах. Фото не покидают устройство, 15 языков |

### Навыки для ИИ-агентов

| Проект | Что делает |
|---|---|
| **[city3d](https://github.com/ildargiv/city3d-skill)** | Настоящий город в 3D из OpenStreetMap: каждое здание отдельной моделью, со своим названием и адресом. [Живое демо](https://ildargiv.github.io/city3d-skill/) |
| **[motion-site](https://github.com/ildargiv/motion-site)** | Студийные сайты с анимацией и самопроверкой кадр за кадром |
| **[pagedrop](https://github.com/ildargiv/pagedrop)** | Опишите сайт — получите живую ссылку на GitHub Pages |

### Финансовые агенты

Работают с Hermes Agent, OpenClaw, Claude Code и Codex CLI. Не инвестиционная рекомендация.

| Проект | Что делает |
|---|---|
| **[ru-bonds-agent](https://github.com/ildargiv/ru-bonds-agent)** | Агент-аналитик облигаций РФ: MOEX, ФНС, отчётность, кредитный скоринг |
| **[ru-stocks-agent](https://github.com/ildargiv/ru-stocks-agent)** | Инвестиционный отдел в ИИ-агенте: список наблюдения, папка на каждую акцию, инвесткомитет с адвокатом дьявола |
| **[ru-portfolio-agent](https://github.com/ildargiv/ru-portfolio-agent)** | Семейный офис: портфель акций Мосбиржи, ежедневный брифинг после закрытия, недельный обзор против IMOEX |
| **[finex-agent](https://github.com/ildargiv/finex-agent)** | Сопровождение ликвидации фондов FinEx: документы ликвидатора и суда, новости и Telegram, расчёт выплаты на пай против рыночной цены |

### Локальный ИИ и железо

Замеры сделаны на движке [Strata](https://github.com/Niko1221/Strata).

| Проект | Что делает |
|---|---|
| **[tokenpulse](https://github.com/ildargiv/tokenpulse)** | Монитор ИИ-сервера по сети: загрузка и температуры GPU/CPU, скорость токенов, счётчик за день и за всё время. Strata, llama.cpp, LM Studio, Ollama, vLLM, ComfyUI; шесть скинов |
| **[rtx3060-strata-tuning](https://github.com/ildargiv/rtx3060-strata-tuning)** | Замеры Strata на одной RTX 3060 12 GB: от 44 до 61 ток/с декода при контексте 262K |
| **[cmp90hx-strata-tuning](https://github.com/ildargiv/cmp90hx-strata-tuning)** | История карты NVIDIA CMP 90HX (GA102, 10 GB): базовые замеры Strata и разблокировка вычислений |
| **[ai-flight-log-v100](https://github.com/ildargiv/ai-flight-log-v100)** | Журнал работы с ИИ на Tesla V100 SXM2 32GB (Volta): записи только добавляются, неудачи пишутся наравне с успехами |

---

ICC-профили и цвет: [vk.ru/icc_profil](https://vk.ru/icc_profil)
