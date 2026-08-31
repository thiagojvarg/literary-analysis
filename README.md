# Literary Analysis

Skill para agentes de IA que analiza narrativa con una metodología editorial rigurosa: evalúa coherencia, prosa, ritmo, personajes, diálogos, tensión, mostrar vs. contar, lógica narrativa y más, y produce un informe profesional con recomendaciones accionables y veredicto final.

Funciona con cualquier agente compatible con el formato [Agent Skills](https://agentskills.dev), como ZCode, Claude Code y otros.

## Qué hace

* Analiza cuentos, novelas, capítulos, prólogos, escenas y fragmentos narrativos.
* Distingue **hechos objetivos**, **interpretaciones** y **opiniones críticas** — no convierte misterios deliberados en errores.
* Clasifica cada problema por certeza (Confirmada / Probable / Posible / No determinable) y severidad (crítico / importante / moderado / menor).
* Respeta la voz e intención del autor: critica, no reescribe.
* Produce un informe con evidencia textual, recomendaciones accionables, reescrituras opcionales y veredicto con puntuaciones de 1 a 10.

## Contenido

| Archivo                     | Descripción                                              |
| --------------------------- | -------------------------------------------------------- |
| `SKILL.md`                  | Instrucciones principales y flujo de trabajo del agente. |
| `references/metodologia.md` | Metodología detallada de las 22 áreas de análisis.       |
| `templates/informe.md`      | Estructura del informe final.                            |

## Instalación

Copiá la carpeta completa al directorio de skills del agente:

* **ZCode / agentes compatibles con Agent Skills:** `.agents/skills/literary-analysis/` (proyecto) o `~/.agents/skills/literary-analysis/` (usuario).
* **Claude Code:** `.claude/skills/literary-analysis/` o `~/.claude/skills/literary-analysis/`.

El nombre de la carpeta debe coincidir con el campo `name` del frontmatter (`literary-analysis`).

## Uso

La skill se activa automáticamente cuando el agente determina que la tarea coincide con su descripción. Algunos agentes también permiten invocarla manualmente mediante mecanismos propios, como `/skill`:

```text
/skill literary-analysis [texto o archivo a analizar]
```

El mecanismo de instalación y activación puede variar según el agente.

## Compatibilidad

La skill está escrita en Markdown y sigue el estándar abierto de Agent Skills. El mecanismo de instalación y activación puede variar según el agente, pero la skill mantiene las mismas instrucciones y metodología en todos los agentes compatibles con el formato.

## Licencia

[MIT](LICENSE) — libre para usar, modificar y compartir.
