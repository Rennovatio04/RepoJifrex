# Contexto del proyecto — RepoJifrex
> Archivo vivo. Leer al inicio de cualquier sesión de trabajo en este repositorio.  
> Última actualización: 2026-06-18

---

## Por qué existe este repositorio

RepoJifrex es el **capital técnico acumulable de Jifrex Studio** — no es un portafolio estético ni un archivo de experimentos sueltos. Cada carpeta corresponde a una línea de negocio activa o en desarrollo del estudio.

El plan de negocio de Jifrex (v3, Junio 2026) parte de tres marcos:

- **Zero to One (Thiel):** ¿En qué será Jifrex el único? → En la intersección de rigor técnico de software (AWS, MCP, plugin dev) + lenguaje artístico computacional (TouchDesigner, MaxMSP, RNBO) + capacidad de investigación. Esa combinación no existe como oferta empaquetada en el mercado hispanohablante.
- **Business Model Canvas (Osterwalder):** El repo materializa tres de las nueve casillas del BMC: Recursos Clave, Actividades Clave y Propuesta de Valor. Lo que se construye aquí es lo que se vende o lo que permite vender.
- **Lean Startup (Ries):** Orden de construcción basado en validación, no en suposición. Primero el plugin más pequeño que resuelve un problema real. Después MCP Labs. Después SaaS. No al revés.

---

## Mapa de carpetas → líneas de negocio

### `plugins/`
**Línea:** Venta directa — Gumroad, plugin stores, comunidades de Ableton/MaxMSP  
**Horizonte:** 0–6 meses  
**Lógica Lean:** es el MVP más rápido de validar. Un plugin que resuelve un problema concreto puede publicarse, medirse y cobrar en semanas.  
**Segmento:** artistas y músicos con necesidades técnicas avanzadas (Segmento A del plan).  
**Próximo paso:** definir el primer plugin MVP del inventario de capacidades — el más pequeño que resuelve algo que el mercado masivo no ofrece.

### `maxmsp/`
**Línea:** Laboratorio y prototipado → alimenta `plugins/`  
**Horizonte:** continuo  
**Lógica:** los patches de MaxMSP son el banco de pruebas. Las ideas maduran aquí antes de convertirse en plugins distribuibles. También incluye proyectos RNBO listos para exportar a VST o web audio.  
**Principio de organización:** modularidad — cada abstracción debe poder vivir fuera del patch que la originó.

### `touchdesigner/`
**Línea:** Instalaciones y performances por comisión — fee por proyecto  
**Horizonte:** 0–6 meses (primer proyecto de instalación)  
**Segmento:** festivales, museos e instituciones culturales (Segmento B); empresas tech con necesidades creativas (Segmento C).  
**Lógica:** los componentes `.tox` reutilizables son activos portables. Cada proyecto de instalación genera componentes que reducen el costo del siguiente.  
**Canal principal:** comunidades de TouchDesigner Discord, MUTEK, Ars Electronica.

### `mcp-labs/`
**Línea:** Consultoría y construcción de MCP servers — el activo estratégico más urgente  
**Horizonte:** 3–9 meses  
**Por qué es prioritario:**
- El mercado MCP es emergente — pocos actores con competencia técnica real
- La intersección MCP + arte computacional (TouchDesigner, Ableton) no existe como oferta
- AWS + MCP es una combinación que empresas tech necesitan y no saben construir
- Ventana de posicionamiento antes de que el mercado se sature

**Acción concreta:** construir y publicar un MCP server propio relacionado con audio o visual generativo. Que funcione como demo pública y tarjeta de presentación técnica.  
**Segmento:** desarrolladores y técnicos creativos + empresas tech (Segmentos C y D).

### `aws/`
**Línea:** Soluciones cloud para proyectos creativos y culturales — B2B  
**Horizonte:** 3–9 meses  
**Lógica:** AWS funciona como capa de distribución y procesamiento. No es un fin en sí mismo sino infraestructura que hace posibles proyectos de mayor escala (streaming A/V, pipelines para instalaciones, distribución de contenido generativo).  
**Meta a mediano plazo:** AWS Partner Network — credibilidad + recursos + acceso a clientes enterprise.

---

## Orden de construcción (Lean)

```
Fase 0 (sem 1–6):   Definir primer plugin MVP → publicar en GitHub → medir respuesta
Fase 1 (sem 7–16):  Lanzar plugin en Gumroad + cerrar primer proyecto instalación + MCP Lab beta
Fase 2 (sem 17–32): Segundo plugin + MCP Labs formalizado + primer taller online
Fase 3 (mes 9+):    Definir SaaS basado en aprendizajes reales
```

---

## Principios de trabajo en este repo

- **Publicar el proceso:** la investigación documentada construye autoridad más rápido que el marketing. Cada experimento relevante merece un README.
- **Protocolos abiertos:** Art-Net, OSC, MIDI como lenguaje común entre herramientas. Favorecer interoperabilidad.
- **Modularidad:** cada componente debe poder desprenderse de su proyecto de origen.
- **Capital acumulable:** cada commit es un activo. El repo crece con el estudio.
- **FOSS + propietario:** evaluar ambos lados del panorama. No hay dogma, hay criterio.

---

## Conexión con la biblioteca de referencia

Los libros estratégicos están disponibles en formato `.md` en:
```
/Users/ray/Desktop/ClaudeMCP/Jifrex/Documentos del Proyecto/Base del negocio a nivel estrategico md/
```
- `DE CERO A UNO_ ...` — Thiel: monopolio, ser el único, preguntas de secreto
- `El MÇtodo Lean Startup ...` — Ries: MVP, aprendizaje validado, pivotar vs. perseverar
- `Generacion de modelos de negocio ...` — Osterwalder: BMC, 9 bloques
- `El_manual_del_emprendedor ...` — Blank: Customer Development, salir a hablar con clientes
- `EOI_LeanManufacturing_2013 ...` — Lean aplicado a procesos

La biblioteca de marketing + IA (~50 libros) está en:
```
/Users/ray/Desktop/ClaudeMCP/Jifrex/Documentos del Proyecto/Marketing and AI md/
```

---

## Estado del repo — Junio 2026

| Carpeta | Estado | Próximo hito |
|---|---|---|
| `plugins/` | ⬜ Vacía | Definir y crear primer plugin MVP |
| `maxmsp/` | ⬜ Vacía | Primer patch de prototipado |
| `touchdesigner/` | ⬜ Vacía | Primer componente reutilizable |
| `mcp-labs/` | ⬜ Vacía | Primer MCP server público (demo de audio/visual) |
| `aws/` | ⬜ Vacía | Primer script de infraestructura |
| README.md | ✅ Completo | — |
| GitHub remote | ✅ Conectado | github.com/Rennovatio04/RepoJifrex |

---

*Plan de negocio activo:* `Plan_de_Negocio_BMC_Jifrex_v3.md`  
*Estudio:* Jifrex Studio — jifrex.com — Toluca, Estado de México  
*Última actualización:* 2026-06-18
