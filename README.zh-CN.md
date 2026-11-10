[English](README.md) | [Русский](README.ru.md) | [Español](README.es.md) | **简体中文** | [Deutsch](README.de.md) | [Français](README.fr.md) | [Português](README.pt.md) | [Türkçe](README.tr.md)

## Ildar Gaisin · ildargiv

**KopiTehnik** 的开发者：为照片冲印店和专业打印提供的免费软件，AI 智能体可通过 MCP 直接操控。

## [KopiTehnik Print](https://github.com/ildargiv/KopiTehnik-Print)

[![release](https://img.shields.io/github/v/release/ildargiv/KopiTehnik-Print?label=release)](https://github.com/ildargiv/KopiTehnik-Print/releases/latest) ![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D4) ![MCP](https://img.shields.io/badge/MCP-server-6E4AFF) [![PyPI](https://img.shields.io/pypi/v/kopitehnik-print-mcp.svg)](https://pypi.org/project/kopitehnik-print-mcp/)

**兼容墨水也能打出照片级品质。** Windows 打印软件：色彩准确、无边距打印、智能裁剪，并为复印店、照相馆和专业打印人员准备订单。个人使用和单个工作站免费。

**[下载 Windows 版](https://github.com/ildargiv/KopiTehnik-Print/releases/latest)** · [完整说明](https://github.com/ildargiv/KopiTehnik-Print/blob/main/README.zh-CN.md) · [网站](https://ildargiv.github.io/KopiTehnik-Print/)

<p align="center"><a href="https://github.com/ildargiv/KopiTehnik-Print"><img src="https://raw.githubusercontent.com/ildargiv/KopiTehnik-Print/main/docs/screenshots/main-window.png" width="860" alt="KopiTehnik Print"></a></p>

- **所见即所得的色彩**：通过打印机 ICC 配置文件打印，并可针对您的墨水和纸张校正配置文件。
- **精确的无边距打印**：支持 Epson、Canon、HP 和 Brother，附带满版测试页。
- **智能裁剪**：人脸、人物和宠物始终保留在画面内。
- **照片与文档同在一个窗口**：PDF、Word、Excel、PowerPoint，每张纸可排 1 到 30 张照片。
- **内置 MCP 服务器**：Claude Desktop 或任何 MCP 客户端都能接单、处理照片并打印。
- **15 种界面语言**，提供安装程序、便携版和 Scoop 包。

| 方式 | 方法 |
|---|---|
| **安装程序或便携版 exe** | [发布页面](https://github.com/ildargiv/KopiTehnik-Print/releases/latest) |
| **Scoop** | `scoop bucket add ildargiv https://github.com/ildargiv/scoop-bucket`<br>`scoop install kopitehnik-print` |
| **AI 智能体 (MCP)** | `uvx kopitehnik-print-mcp` |

### 更多打印与摄影工具

| 项目 | 功能 |
|---|---|
| **[KopiTehnik Converter](https://github.com/ildargiv/kopitehnik-converter)** | 批量转换、色彩处理、拼版打印，带扫描件 OCR 的 PDF 编辑器。对照片冲印店免费。 |
| **[printshop-mcp](https://github.com/ildargiv/printshop-mcp)** | AI 智能体里的印刷厂：名片、胸牌、传单，精确到毫米，并记住打印配置。 |
| **[print-mcp](https://github.com/ildargiv/print-mcp)** | 通过 Adobe Photoshop 进行色彩准确的批量打印的 MCP 服务器：使用自己的 ICC 配置文件，关闭驱动自动校正。 |
| **[OriginEcho](https://github.com/ildargiv/OriginEcho)** | 恢复被 AI 修图工具抹掉的 EXIF/XMP/IPTC：相机、日期、GPS、ISO。 |
| **[PhotoGeoFinder](https://github.com/ildargiv/photogeofinder)** | 照片拍摄地点：将 EXIF 中的 GPS 显示在 Google、Yandex 和 OSM 地图上。照片不离开设备，支持 15 种语言。 |
| **[scoop-bucket](https://github.com/ildargiv/scoop-bucket)** | KopiTehnik 应用的 Scoop 清单。 |

### AI 智能体技能

| 项目 | 功能 |
|---|---|
| **[city3d](https://github.com/ildargiv/city3d-skill)** | 基于 OpenStreetMap 的真实 3D 城市：每栋建筑都是独立模型，带有名称和地址。 [在线演示](https://ildargiv.github.io/city3d-skill/) |
| **[motion-site](https://github.com/ildargiv/motion-site)** | 工作室级动画网站，逐帧自检。 |
| **[pagedrop](https://github.com/ildargiv/pagedrop)** | 描述一个网站，即可获得可访问的 GitHub Pages 链接。 |

### 金融智能体（俄罗斯市场）

| 项目 | 功能 |
|---|---|
| **[ru-stocks-agent](https://github.com/ildargiv/ru-stocks-agent)** | AI 智能体中的投资委员会，面向俄罗斯股票 (MOEX)：自选清单、每只股票一个文件夹、“魔鬼代言人”。 |
| **[ru-portfolio-agent](https://github.com/ildargiv/ru-portfolio-agent)** | 俄罗斯股票投资组合的家族办公室：收盘后每日简报、对比 IMOEX 的周度回顾、风险、股息、Obsidian 知识库。 |
| **[ru-bonds-agent](https://github.com/ildargiv/ru-bonds-agent)** | 俄罗斯债券分析智能体：MOEX、税务数据、财务报表、信用评分。 |
| **[finex-agent](https://github.com/ildargiv/finex-agent)** | 为清算中的 FinEx 基金持有人提供支持：清算人和法院文件、新闻、每份额赔付与市场价格的对比。 |

### GPU 上的本地 AI

| 项目 | 功能 |
|---|---|
| **[tokenpulse](https://github.com/ildargiv/tokenpulse)** | AI 服务器监视器：GPU 和 CPU 负载、温度、内存、token 速度以及累计 token 计数。支持 Strata、llama.cpp、LM Studio、Ollama、vLLM 和 ComfyUI。 |
| **[ai-flight-log-v100](https://github.com/ildargiv/ai-flight-log-v100)** | Tesla V100 SXM2 32 GB 的带日期、只追加的测量日志；失败的测量与成功的同样记录在案。 |
| **[cmp90hx-strata-tuning](https://github.com/ildargiv/cmp90hx-strata-tuning)** | Strata 在 NVIDIA CMP 90HX 10 GB 上的持续记录：硬件概况、计算解锁、基准测试。 |
| **[rtx3060-strata-tuning](https://github.com/ildargiv/rtx3060-strata-tuning)** | 在单张 RTX 3060 12 GB 上调优 Strata：262K 上下文下解码速度 44 → 61 tok/s，附原始数据和脚本。 |

---

ICC 配置文件与色彩: [vk.ru/icc_profil](https://vk.ru/icc_profil)
