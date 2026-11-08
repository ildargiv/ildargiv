<h1 align="center">KopiTehnik Print</h1>
<p align="center"><b>Фотокачество на совместимых чернилах.</b><br>
Программа печати для Windows: точный цвет, печать без полей, умное кадрирование и подготовка заказов<br>
для копицентров, фотосалонов и профессиональных печатников.</p>

<p align="center">
  <a href="https://github.com/ildargiv/KopiTehnik-Print/releases/latest"><b>Скачать для Windows</b></a> ·
  <a href="https://ildargiv.github.io/KopiTehnik-Print/">Сайт</a> ·
  <a href="https://github.com/ildargiv/KopiTehnik-Print/blob/main/README.ru.md">Документация</a> ·
  <a href="https://github.com/ildargiv/KopiTehnik-Print">English</a>
</p>

<p align="center">
  <a href="https://github.com/ildargiv/KopiTehnik-Print/releases/latest"><img src="https://img.shields.io/github/v/release/ildargiv/KopiTehnik-Print?label=release" alt="Последний релиз"></a>
  <a href="https://github.com/ildargiv/KopiTehnik-Print/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-free%20for%20one%20workstation-2E7D32.svg" alt="Бесплатно для одного рабочего места"></a>
</p>

<p align="center"><a href="https://github.com/ildargiv/KopiTehnik-Print"><img src="https://raw.githubusercontent.com/ildargiv/KopiTehnik-Print/main/docs/screenshots/main-window.png" width="860" alt="KopiTehnik Print: фото в рамке кадрирования, формат печати и профиль принтера в одном окне"></a></p>

Печатает на Epson, Canon, HP, Brother и других струйных принтерах. 15 языков интерфейса, Python не нужен.
Бесплатно для личного использования и для одного рабочего места (копицентр, студия, мастерская); больше рабочих мест, сети и перепродажа — по коммерческой лицензии, см. [LICENSE](https://github.com/ildargiv/KopiTehnik-Print/blob/main/LICENSE).

### Установка

| Способ | Что даёт | Как |
|---|---|---|
| **Установщик** | ярлык в меню «Пуск», запись в «Установке и удалении программ» | [Скачать Setup](https://github.com/ildargiv/KopiTehnik-Print/releases/latest) |
| **Portable** | один exe, ничего не пишется в реестр | [Скачать Portable](https://github.com/ildargiv/KopiTehnik-Print/releases/latest) |
| **Scoop** | portable-сборка в `~/scoop`, обновление через `scoop update` | `scoop bucket add ildargiv https://github.com/ildargiv/scoop-bucket`<br>`scoop install kopitehnik-print` |
| **ИИ-агент (MCP)** | программу ведёт Claude Desktop или любой MCP-клиент | `uvx kopitehnik-print-mcp` |

### Почему KopiTehnik Print

- **Цвет как на экране.** Печать через ICC-профиль принтера, без подбора вручную.
- **Профиль под ваши чернила.** Совместимые чернила и бумага меняют цвет: подправьте имеющийся профиль и проверьте тестовым листом, не делая новый с нуля.
- **Точная печать без полей.** Фото не обрезается лишним, меньше брака и перерасхода бумаги и чернил.
- **Умное кадрирование.** Лица, люди и животные остаются в кадре.
- **Фото и документы в одном окне:** PDF, Word, Excel, PowerPoint, свой профиль для каждого принтера. Счётчик листов с выгрузкой в CSV.

### Подключите своего ИИ-агента

В программу встроен MCP-сервер: Claude Desktop или другой MCP-клиент откроет папку с фото, выставит формат, кадрирует, поправит цвет, разложит листы, проверит и напечатает. Агент работает в том же окне, что видите вы, изменения отменяются по Ctrl+Z. Приём заказов и разговор с клиентами ведёт ваш агент, подготовку и печать делает программа.

Пример запроса: «Открой папку Клиент_Иванов, поставь 10×15, проверь фото и напечатай по 3 копии каждого».
Реестр MCP: `io.github.ildargiv/kopitehnik-print` · пакет на PyPI: `kopitehnik-print-mcp`.

---

## Вокруг KopiTehnik Print

### Печать и фотография

| Проект | Что делает |
|---|---|
| **[КопиТехник Конвертор](https://github.com/ildargiv/kopitehnik-converter)** | Пакетная конвертация, цвет, печать листами, PDF-редактор с распознаванием сканов. Бесплатно для фотоцентров. Работает в паре с KopiTehnik Print |
| **[printshop-mcp](https://github.com/ildargiv/printshop-mcp)** | Типография внутри ИИ-агента: визитки, бейджи, листовки с точностью до миллиметра, с памятью профилей печати, без Photoshop |
| **[print-mcp](https://github.com/ildargiv/print-mcp)** | MCP-сервер пакетной печати готовых файлов через Adobe Photoshop: свой ICC-профиль, автокоррекция драйвера выключена, зеркало для сублимации |
| **[OriginEcho](https://github.com/ildargiv/OriginEcho)** | Возвращает EXIF/XMP/IPTC, которые стирают ИИ-редакторы фото: камера, дата, GPS, ISO |
| **[PhotoGeoFinder](https://github.com/ildargiv/photogeofinder)** | Где сделано фото: GPS из EXIF на Google, Яндекс и OSM-картах. Фото не покидают устройство, 15 языков |
| **[scoop-bucket](https://github.com/ildargiv/scoop-bucket)** | Установка и обновление KopiTehnik Print через Scoop |

Какой печатный MCP выбрать: готовые фото на струйном принтере и интерфейс программы — KopiTehnik Print; дизайн с нуля (визитки, бейджи, листовки) на любом принтере — printshop-mcp; готовые файлы через цветовой конвейер Photoshop — print-mcp.

### Навыки для ИИ-агентов

| Проект | Что делает |
|---|---|
| **[city3d](https://github.com/ildargiv/city3d-skill)** | Настоящий город в 3D из OpenStreetMap: каждое здание отдельной моделью, со своим названием и адресом. [Живое демо](https://ildargiv.github.io/city3d-skill/) |
| **[motion-site](https://github.com/ildargiv/motion-site)** | Студийные сайты с анимацией и самопроверкой кадр за кадром |
| **[pagedrop](https://github.com/ildargiv/pagedrop)** | Опишите сайт — получите живую ссылку на GitHub Pages |

<details>
<summary><b>Финансовые агенты</b> (облигации, акции, портфель, FinEx)</summary>

<br>

Работают с Hermes Agent, OpenClaw, Claude Code и Codex CLI. Не инвестиционная рекомендация.

| Проект | Что делает |
|---|---|
| **[ru-bonds-agent](https://github.com/ildargiv/ru-bonds-agent)** | Агент-аналитик облигаций РФ: MOEX, ФНС, отчётность, кредитный скоринг · [сайт](https://ildargiv.github.io/ru-bonds-agent/?utm_source=github&utm_medium=profile&utm_campaign=ru-bonds-agent) |
| **[ru-stocks-agent](https://github.com/ildargiv/ru-stocks-agent)** | Инвестиционный отдел в ИИ-агенте: список наблюдения, папка на каждую акцию, инвесткомитет с адвокатом дьявола · [сайт](https://ildargiv.github.io/ru-stocks-agent/?utm_source=github&utm_medium=profile&utm_campaign=ru-stocks-agent) |
| **[ru-portfolio-agent](https://github.com/ildargiv/ru-portfolio-agent)** | Семейный офис: портфель акций Мосбиржи, ежедневный брифинг после закрытия, недельный обзор против IMOEX · [сайт](https://ildargiv.github.io/ru-portfolio-agent/?utm_source=github&utm_medium=profile&utm_campaign=ru-portfolio-agent) |
| **[finex-agent](https://github.com/ildargiv/finex-agent)** | Сопровождение ликвидации фондов FinEx: документы ликвидатора и суда, новости и Telegram, расчёт выплаты на пай против рыночной цены · [сайт](https://ildargiv.github.io/finex-agent/?utm_source=github&utm_medium=profile&utm_campaign=finex-agent) |

</details>

<details>
<summary><b>Локальный ИИ и железо</b> (замеры Strata, монитор GPU)</summary>

<br>

Замеры сделаны на движке [Strata](https://github.com/Niko1221/Strata).

| Проект | Что делает |
|---|---|
| **[tokenpulse](https://github.com/ildargiv/tokenpulse)** | Монитор ИИ-сервера по сети: загрузка и температуры GPU/CPU, скорость токенов, счётчик за день и за всё время. Strata, llama.cpp, LM Studio, Ollama, vLLM, ComfyUI; шесть скинов |
| **[rtx3060-strata-tuning](https://github.com/ildargiv/rtx3060-strata-tuning)** | Замеры Strata на одной RTX 3060 12 GB: от 44 до 61 ток/с декода при контексте 262K |
| **[cmp90hx-strata-tuning](https://github.com/ildargiv/cmp90hx-strata-tuning)** | История карты NVIDIA CMP 90HX (GA102, 10 GB): базовые замеры Strata и разблокировка вычислений |
| **[ai-flight-log-v100](https://github.com/ildargiv/ai-flight-log-v100)** | Журнал работы с ИИ на Tesla V100 SXM2 32GB (Volta): записи только добавляются, неудачи пишутся наравне с успехами |

</details>

---

Ильдар Гайсин · разработчик КопиТехник · [все проекты на ildargiv.github.io](https://ildargiv.github.io/?utm_source=github&utm_medium=profile&utm_campaign=hub) · ICC-профили и цвет: [vk.ru/icc_profil](https://vk.ru/icc_profil)
