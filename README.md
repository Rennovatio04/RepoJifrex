# RepoJifrex
### Jifrex Studio — Software as a Structure

Repositorio de código de **[Jifrex Studio](https://jifrex.com)**, estudio creativo basado en Toluca, Estado de México, dedicado al diseño y construcción de experiencias audiovisuales e inmersivas desde una lógica artística y tecnológica.

> *El software como material artístico. Cada experimento es una estructura.*

---

## Idea central

La mayoría de los estudios de software construyen herramientas. La mayoría de los estudios de arte crean experiencias. Jifrex hace algo diferente: **trata el software como material artístico y estructural** — igual que un arquitecto trata al concreto o un compositor trata al sonido.

Este repositorio es el capital técnico acumulable del estudio: plugins, patches, servidores, infraestructura y laboratorios de investigación, todo construido desde esa lógica.

---

## Stack

| Herramienta | Rol en el estudio |
|---|---|
| **TouchDesigner** | Visuales generativos en tiempo real, instalaciones interactivas |
| **MaxMSP / RNBO** | Audio interactivo, síntesis, exportación a VST y web audio |
| **Ableton** | Producción musical, performance en vivo, integración Max for Live |
| **AWS** | Infraestructura cloud para distribución, streaming y procesamiento A/V |
| **MCP Servers** | Laboratorios de integración con IA para flujos de trabajo creativos |

---

## Estructura del repositorio

```
RepoJifrex/
├── plugins/          # Plugins para DAWs y entornos creativos
├── touchdesigner/    # Patches y componentes de TouchDesigner
├── maxmsp/           # Patches de MaxMSP
├── mcp-labs/         # Servidores MCP y experimentos de integración con IA
└── aws/              # Scripts e infraestructura cloud
```

---

### `plugins/`
Plugins desarrollados para Max for Live, RNBO (exportados a VST/web audio) y entornos audiovisuales interactivos.

Cada plugin nace de una necesidad concreta de la práctica: si el mercado no tiene la herramienta, la construimos. El objetivo a mediano plazo es publicarlos en Gumroad y plataformas de distribución de plugins para la comunidad de Ableton, MaxMSP y Cycling '74.

**Lo que vive aquí:** código fuente de plugins, documentación de uso, versiones de release.

---

### `touchdesigner/`
Patches y componentes reutilizables de TouchDesigner para instalaciones audiovisuales, visuales generativos en tiempo real y entornos de performance.

La lógica de esta carpeta es modular: cada componente debe poder desprenderse del proyecto original y funcionar como bloque autónomo. Eso los convierte en activos portables para proyectos futuros.

**Lo que vive aquí:** `.toe` y componentes `.tox`, organizados por tipo (generativo, reactivo-audio, sensor input, output/mapping).

---

### `maxmsp/`
Patches de MaxMSP para síntesis de audio, procesamiento en tiempo real, control MIDI/OSC y composición algorítmica.

Incluye también patches de RNBO preparados para exportación — a VST, web audio o código C++. Esta carpeta es el laboratorio de prototipado rápido: ideas que luego migran a `plugins/` cuando maduran.

**Lo que vive aquí:** patches `.maxpat` y `.maxproj`, abstracciones reutilizables, proyectos RNBO.

---

### `mcp-labs/`
Laboratorio de servidores MCP (Model Context Protocol) para integrar modelos de IA en flujos de trabajo creativos y técnicos.

Este es el activo más estratégico del estudio en este momento: el mercado MCP es emergente y la intersección **MCP + arte computacional** (TouchDesigner, Ableton, MaxMSP) prácticamente no existe como oferta. El objetivo es construir y publicar servidores MCP propios relacionados con audio y visual generativo — demos públicas que funcionen como tarjeta de presentación técnica y como productos distribuibles.

**Lo que vive aquí:** código de servidores MCP, documentación de endpoints, experimentos de integración IA-herramientas creativas.

---

### `aws/`
Scripts, configuraciones e infraestructura cloud para proyectos de Jifrex.

AWS funciona como capa de distribución y procesamiento para proyectos que requieren escala: streaming de contenido audiovisual, procesamiento de audio/video en la nube, pipelines para instalaciones que consumen datos en tiempo real.

**Lo que vive aquí:** scripts de despliegue, configuraciones CDK/CloudFormation, documentación de arquitecturas por proyecto.

---

## Líneas de negocio que alimenta este repo

| Carpeta | Línea de negocio |
|---|---|
| `plugins/` | Venta directa en Gumroad / plugin stores — ingreso escalable |
| `touchdesigner/` + `maxmsp/` | Instalaciones y performances por comisión — ingreso por proyecto |
| `mcp-labs/` | Consultoría y construcción de MCP servers — mercado emergente, alto valor |
| `aws/` | Soluciones cloud para proyectos creativos y culturales — B2B |

---

## Principios de trabajo

- **Publicar el proceso:** la investigación y la documentación construyen autoridad más rápido que el marketing.
- **Protocolos abiertos:** Art-Net, OSC, MIDI como lenguaje común entre herramientas.
- **Modularidad:** cada componente debe poder vivir fuera del proyecto que lo originó.
- **Capital acumulable:** cada commit es un activo. El repositorio crece con el estudio.

---

## Estado

> Canvas vivo — actualizar con cada plugin lanzado, proyecto cerrado o experimento publicado.

| Activo | Estado |
|---|---|
| Estructura base del repo | ✅ Lista |
| Primer plugin MVP | ⬜ En definición |
| Primer MCP server público | ⬜ En desarrollo |
| Primer proyecto de instalación documentado | ⬜ Pendiente |
| Presencia en Cycling '74 / TD Discord | ⬜ Pendiente |

---

*Jifrex Studio — Toluca, Estado de México*  
*[jifrex.com](https://jifrex.com)*
