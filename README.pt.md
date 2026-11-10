[English](README.md) | [Русский](README.ru.md) | [Español](README.es.md) | [简体中文](README.zh-CN.md) | [Deutsch](README.de.md) | [Français](README.fr.md) | **Português** | [Türkçe](README.tr.md)

## Ildar Gaisin · ildargiv

Desenvolvedor do **KopiTehnik**: software gratuito para centros de fotografia e impressão profissional que agentes de IA podem controlar via MCP.

## [KopiTehnik Print](https://github.com/ildargiv/KopiTehnik-Print)

[![release](https://img.shields.io/github/v/release/ildargiv/KopiTehnik-Print?label=release)](https://github.com/ildargiv/KopiTehnik-Print/releases/latest) ![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D4) ![MCP](https://img.shields.io/badge/MCP-server-6E4AFF) [![PyPI](https://img.shields.io/pypi/v/kopitehnik-print-mcp.svg)](https://pypi.org/project/kopitehnik-print-mcp/)

**Qualidade fotográfica com tinta compatível.** Software de impressão para Windows: cor precisa, impressão sem margens, recorte inteligente e preparação de pedidos para copiadoras, lojas de fotografia e impressores profissionais. Gratuito para uso pessoal e para um único posto de trabalho.

**[Baixar para Windows](https://github.com/ildargiv/KopiTehnik-Print/releases/latest)** · [Descrição completa](https://github.com/ildargiv/KopiTehnik-Print/blob/main/README.pt.md) · [Site](https://ildargiv.github.io/KopiTehnik-Print/)

<p align="center"><a href="https://github.com/ildargiv/KopiTehnik-Print"><img src="https://raw.githubusercontent.com/ildargiv/KopiTehnik-Print/main/docs/screenshots/main-window.png" width="860" alt="KopiTehnik Print"></a></p>

- **Cor como na tela**: impressão pelo perfil ICC da impressora, com correção do perfil para a sua tinta e o seu papel.
- **Impressão sem margens exata** em Epson, Canon, HP e Brother, com folha de teste de borda a borda.
- **Recorte inteligente**: rostos, pessoas e animais ficam dentro do quadro.
- **Fotos e documentos em uma só janela**: PDF, Word, Excel, PowerPoint, de 1 a 30 fotos por folha.
- **Servidor MCP integrado**: o Claude Desktop ou qualquer cliente MCP recebe o pedido, prepara as fotos e imprime.
- **15 idiomas de interface**, instalador, versão portátil e pacote Scoop.

| Forma | Como |
|---|---|
| **Instalador ou exe portátil** | [página de versões](https://github.com/ildargiv/KopiTehnik-Print/releases/latest) |
| **Scoop** | `scoop bucket add ildargiv https://github.com/ildargiv/scoop-bucket`<br>`scoop install kopitehnik-print` |
| **Agente de IA (MCP)** | `uvx kopitehnik-print-mcp` |

### Mais para impressão e fotografia

| Projeto | O que faz |
|---|---|
| **[KopiTehnik Converter](https://github.com/ildargiv/kopitehnik-converter)** | Conversão em lote, cor, folhas de impressão, editor de PDF com OCR para digitalizações. Gratuito para centros de fotografia. |
| **[printshop-mcp](https://github.com/ildargiv/printshop-mcp)** | Uma gráfica dentro de um agente de IA: cartões de visita, crachás e folhetos com precisão milimétrica e perfis de impressão memorizados. |
| **[print-mcp](https://github.com/ildargiv/print-mcp)** | Servidor MCP para impressão em lote com cor exata pelo Adobe Photoshop, com o seu perfil ICC e a autocorreção do driver desligada. |
| **[OriginEcho](https://github.com/ildargiv/OriginEcho)** | Restaura os EXIF/XMP/IPTC que os editores de fotos com IA apagam: câmera, data, GPS, ISO. |
| **[PhotoGeoFinder](https://github.com/ildargiv/photogeofinder)** | Onde a foto foi tirada: GPS do EXIF nos mapas do Google, Yandex e OSM. As fotos não saem do dispositivo, 15 idiomas. |
| **[scoop-bucket](https://github.com/ildargiv/scoop-bucket)** | Manifestos Scoop para os aplicativos KopiTehnik. |

### Habilidades para agentes de IA

| Projeto | O que faz |
|---|---|
| **[city3d](https://github.com/ildargiv/city3d-skill)** | Uma cidade real em 3D a partir do OpenStreetMap: cada edifício é um modelo separado, com nome e endereço. [Demo ao vivo](https://ildargiv.github.io/city3d-skill/) |
| **[motion-site](https://github.com/ildargiv/motion-site)** | Sites animados de nível de estúdio com autoverificação quadro a quadro. |
| **[pagedrop](https://github.com/ildargiv/pagedrop)** | Descreva um site e receba um link ativo do GitHub Pages. |

### Agentes financeiros (mercado russo)

| Projeto | O que faz |
|---|---|
| **[ru-stocks-agent](https://github.com/ildargiv/ru-stocks-agent)** | Um comitê de investimento dentro de um agente de IA para ações russas (MOEX): lista de acompanhamento, uma pasta por ação, advogado do diabo. |
| **[ru-portfolio-agent](https://github.com/ildargiv/ru-portfolio-agent)** | Um family office para uma carteira de ações russas: resumo diário após o fechamento, revisão semanal contra o IMOEX, risco, dividendos, base de conhecimento no Obsidian. |
| **[ru-bonds-agent](https://github.com/ildargiv/ru-bonds-agent)** | Agente analista de títulos russos: MOEX, dados fiscais, demonstrações financeiras, scoring de crédito. |
| **[finex-agent](https://github.com/ildargiv/finex-agent)** | Acompanhamento para cotistas dos fundos FinEx em liquidação: documentos do liquidante e do tribunal, notícias, pagamento por cota frente ao preço de mercado. |

### IA local em GPUs

| Projeto | O que faz |
|---|---|
| **[tokenpulse](https://github.com/ildargiv/tokenpulse)** | Monitor de servidor de IA: carga de GPU e CPU, temperaturas, memória, velocidade de tokens e contador total de tokens. Compatível com Strata, llama.cpp, LM Studio, Ollama, vLLM e ComfyUI. |
| **[ai-flight-log-v100](https://github.com/ildargiv/ai-flight-log-v100)** | Diário de bordo datado, apenas com acréscimos, das medições em uma Tesla V100 SXM2 de 32 GB; tentativas fracassadas são registradas como as bem-sucedidas. |
| **[cmp90hx-strata-tuning](https://github.com/ildargiv/cmp90hx-strata-tuning)** | Histórico do Strata em uma NVIDIA CMP 90HX de 10 GB: perfil de hardware, desbloqueio de computação, benchmarks. |
| **[rtx3060-strata-tuning](https://github.com/ildargiv/rtx3060-strata-tuning)** | Ajuste do Strata em uma RTX 3060 de 12 GB: decodificação de 44 → 61 tok/s com contexto de 262K, com dados brutos e scripts. |

---

Perfis ICC e cor: [vk.ru/icc_profil](https://vk.ru/icc_profil)
