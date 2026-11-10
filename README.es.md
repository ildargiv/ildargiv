[English](README.md) | [Русский](README.ru.md) | **Español** | [简体中文](README.zh-CN.md) | [Deutsch](README.de.md) | [Français](README.fr.md) | [Português](README.pt.md) | [Türkçe](README.tr.md)

## Ildar Gaisin · ildargiv

Desarrollador de **KopiTehnik**: software gratuito para centros de fotografía e impresión profesional que los agentes de IA pueden manejar mediante MCP.

## [KopiTehnik Print](https://github.com/ildargiv/KopiTehnik-Print)

[![release](https://img.shields.io/github/v/release/ildargiv/KopiTehnik-Print?label=release)](https://github.com/ildargiv/KopiTehnik-Print/releases/latest) ![Windows](https://img.shields.io/badge/Windows-10%20%7C%2011-0078D4) ![MCP](https://img.shields.io/badge/MCP-server-6E4AFF) [![PyPI](https://img.shields.io/pypi/v/kopitehnik-print-mcp.svg)](https://pypi.org/project/kopitehnik-print-mcp/)

**Calidad fotográfica con tinta compatible.** Software de impresión para Windows: color preciso, impresión sin bordes, recorte inteligente y preparación de pedidos para copisterías, tiendas de fotografía e impresores profesionales. Gratis para uso personal y para un solo puesto de trabajo.

**[Descargar para Windows](https://github.com/ildargiv/KopiTehnik-Print/releases/latest)** · [Descripción completa](https://github.com/ildargiv/KopiTehnik-Print/blob/main/README.es.md) · [Sitio web](https://ildargiv.github.io/KopiTehnik-Print/)

<p align="center"><a href="https://github.com/ildargiv/KopiTehnik-Print"><img src="https://raw.githubusercontent.com/ildargiv/KopiTehnik-Print/main/docs/screenshots/main-window.png" width="860" alt="KopiTehnik Print"></a></p>

- **El color como en pantalla**: impresión con el perfil ICC de la impresora y corrección del perfil para su tinta y papel.
- **Impresión sin bordes exacta** en Epson, Canon, HP y Brother, con hoja de prueba de borde a borde.
- **Recorte inteligente**: caras, personas y mascotas quedan dentro del encuadre.
- **Fotos y documentos en una sola ventana**: PDF, Word, Excel, PowerPoint, de 1 a 30 fotos por hoja.
- **Servidor MCP integrado**: Claude Desktop o cualquier cliente MCP recibe el pedido, prepara las fotos e imprime.
- **15 idiomas de interfaz**, instalador, versión portable y paquete Scoop.

| Vía | Cómo |
|---|---|
| **Instalador o exe portable** | [página de versiones](https://github.com/ildargiv/KopiTehnik-Print/releases/latest) |
| **Scoop** | `scoop bucket add ildargiv https://github.com/ildargiv/scoop-bucket`<br>`scoop install kopitehnik-print` |
| **Agente de IA (MCP)** | `uvx kopitehnik-print-mcp` |

### Más para impresión y fotografía

| Proyecto | Qué hace |
|---|---|
| **[KopiTehnik Converter](https://github.com/ildargiv/kopitehnik-converter)** | Conversión por lotes, color, hojas de impresión, editor de PDF con OCR para escaneos. Gratis para centros de fotografía. |
| **[printshop-mcp](https://github.com/ildargiv/printshop-mcp)** | Una imprenta dentro de un agente de IA: tarjetas de visita, credenciales y folletos con precisión milimétrica y perfiles de impresión memorizados. |
| **[print-mcp](https://github.com/ildargiv/print-mcp)** | Servidor MCP para impresión por lotes con color exacto a través de Adobe Photoshop, con su propio perfil ICC y la autocorrección del controlador desactivada. |
| **[OriginEcho](https://github.com/ildargiv/OriginEcho)** | Recupera los EXIF/XMP/IPTC que borran los editores de fotos con IA: cámara, fecha, GPS, ISO. |
| **[PhotoGeoFinder](https://github.com/ildargiv/photogeofinder)** | Dónde se tomó una foto: GPS del EXIF en mapas de Google, Yandex y OSM. Las fotos no salen del dispositivo, 15 idiomas. |
| **[scoop-bucket](https://github.com/ildargiv/scoop-bucket)** | Manifiestos de Scoop para las aplicaciones KopiTehnik. |

### Habilidades para agentes de IA

| Proyecto | Qué hace |
|---|---|
| **[city3d](https://github.com/ildargiv/city3d-skill)** | Una ciudad real en 3D a partir de OpenStreetMap: cada edificio es un modelo aparte con su nombre y dirección. [Demo en vivo](https://ildargiv.github.io/city3d-skill/) |
| **[motion-site](https://github.com/ildargiv/motion-site)** | Sitios web animados de nivel estudio con autocomprobación fotograma a fotograma. |
| **[pagedrop](https://github.com/ildargiv/pagedrop)** | Describa un sitio y reciba un enlace activo de GitHub Pages. |

### Agentes financieros (mercado ruso)

| Proyecto | Qué hace |
|---|---|
| **[ru-stocks-agent](https://github.com/ildargiv/ru-stocks-agent)** | Un comité de inversión dentro de un agente de IA para acciones rusas (MOEX): lista de seguimiento, carpeta por acción, abogado del diablo. |
| **[ru-portfolio-agent](https://github.com/ildargiv/ru-portfolio-agent)** | Un family office para una cartera de acciones rusas: informe diario tras el cierre, revisión semanal frente al IMOEX, riesgo, dividendos, base de conocimiento en Obsidian. |
| **[ru-bonds-agent](https://github.com/ildargiv/ru-bonds-agent)** | Agente analista de bonos rusos: MOEX, datos fiscales, estados financieros, scoring crediticio. |
| **[finex-agent](https://github.com/ildargiv/finex-agent)** | Acompañamiento a partícipes de los fondos FinEx en liquidación: documentos del liquidador y del tribunal, noticias, pago por participación frente al precio de mercado. |

### IA local en GPU

| Proyecto | Qué hace |
|---|---|
| **[tokenpulse](https://github.com/ildargiv/tokenpulse)** | Monitor de servidor de IA: carga de GPU y CPU, temperaturas, memoria, velocidad de tokens y contador total de tokens. Compatible con Strata, llama.cpp, LM Studio, Ollama, vLLM y ComfyUI. |
| **[ai-flight-log-v100](https://github.com/ildargiv/ai-flight-log-v100)** | Bitácora fechada y solo de adición con mediciones en una Tesla V100 SXM2 de 32 GB; los intentos fallidos se registran igual que los exitosos. |
| **[cmp90hx-strata-tuning](https://github.com/ildargiv/cmp90hx-strata-tuning)** | Historial de Strata en una NVIDIA CMP 90HX de 10 GB: perfil de hardware, desbloqueo de cómputo, pruebas. |
| **[rtx3060-strata-tuning](https://github.com/ildargiv/rtx3060-strata-tuning)** | Ajuste de Strata en una RTX 3060 de 12 GB: decodificación de 44 → 61 tok/s con contexto de 262K, con datos en bruto y scripts. |

---

Perfiles ICC y color: [vk.ru/icc_profil](https://vk.ru/icc_profil)
