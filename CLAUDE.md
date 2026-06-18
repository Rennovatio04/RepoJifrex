# CLAUDE.md — RepoJifrex
> Este archivo se carga automáticamente al trabajar en este directorio.

## Contexto del proyecto

RepoJifrex es el capital técnico acumulable de **Jifrex Studio** (jifrex.com) — estudio creativo en Toluca, MX. Cada carpeta es una línea de negocio activa. No es un portafolio estético.

Contexto completo: `_contexto/contexto_proyecto.md`  
Estado del negocio: `/Users/ray/Desktop/ClaudeMCP/Jifrex/_contexto/estado_actual.md`

---

## Workflow obligatorio: Explorar → Planificar → Codear → Commit

### 1. Explorar
Antes de cualquier tarea, leer:
- `_contexto/contexto_proyecto.md` — propósito de cada carpeta y línea de negocio
- Los archivos existentes en la carpeta relevante

### 2. Planificar
Usar **Plan Mode (Shift+Tab)** antes de escribir código. Definir explícitamente:
- ¿Qué problema resuelve esto?
- ¿Cómo se ve "terminado"? (criterio de éxito concreto)
- ¿Qué dependencias o protocolos involucra?

### 3. Codear
- Definir criterio de éxito antes de empezar
- Protocolos abiertos preferidos: OSC, MIDI, Art-Net
- Modularidad: cada componente debe poder vivir fuera de su proyecto de origen
- Evaluar FOSS + propietario — sin dogma

### 4. Commit
- Lanzar `/code-review` antes del commit — subagente con herramientas de **solo lectura** (marca problemas, no edita archivos)
- Commit message descriptivo del "por qué", no del "qué"
- Para hacer commit + push + PR en un solo paso: `/commit-push-pr`
- Para retomar trabajo en un PR existente (revisiones, builds fallando): `claude --from-pr <número>`

---

## Mapa de carpetas

| Carpeta | Línea de negocio | Prioridad |
|---|---|---|
| `mcp-labs/` | MCP servers para flujos creativos | 🔴 Alta — ventana estratégica abierta |
| `plugins/` | Plugins Max for Live / VST / RNBO | 🟡 Alta — primer MVP a definir |
| `maxmsp/` | Prototipos → alimenta plugins/ | 🟡 Media |
| `touchdesigner/` | Instalaciones por comisión | 🟡 Media |
| `aws/` | Infraestructura cloud B2B | 🟢 Mediano plazo |

---

## Criterios de éxito por carpeta

**mcp-labs/:** un MCP server funciona cuando responde a Claude con datos reales de la herramienta creativa (Ableton, TD, Max) y tiene README con demo reproducible.

**plugins/:** un plugin está listo cuando resuelve un problema concreto, tiene documentación de uso y puede publicarse en Gumroad sin explicación adicional.

**touchdesigner/:** un componente está listo cuando puede importarse como `.tox` en un proyecto nuevo sin dependencias rotas.

---

## Soluciones recurrentes

*(Agregar aquí cuando Claude resuelva el mismo problema más de una vez)*
