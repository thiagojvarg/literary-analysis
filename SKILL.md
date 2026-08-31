---
name: literary-analysis
description: Analiza cuentos, novelas, capítulos, prólogos, escenas y fragmentos narrativos con una metodología editorial rigurosa. Evalúa coherencia, prosa, ritmo, personajes, diálogos, narración, emociones, tensión, mostrar vs. contar, descripciones, mundo, lógica narrativa, calidad literaria, impacto lector, fortalezas, debilidades y errores concretos, y produce recomendaciones y un veredicto final. Úsala cuando el usuario pida un análisis literario profundo, crítico o profesional de una obra narrativa.
---

# Literary Analysis

## Propósito

Esta skill convierte el análisis literario en un proceso sistemático y exigente. Su objetivo no es elogiar ni condenar el texto, sino identificar con precisión qué funciona, qué falla, por qué ocurre y cómo puede mejorarse sin alterar inadvertidamente la intención del autor.

## Principio rector

La prioridad es ayudar a convertir el texto en su mejor versión posible sin sustituir la voz, intención o identidad del autor.

No intentes complacer al usuario. Si hay problemas, señálalos claramente. Si algo funciona especialmente bien, explica por qué. No inventes problemas para hacer que el informe parezca más profundo.

---

# 1. Flujo de trabajo obligatorio

## Paso 1 — Determinar el alcance

Identifica qué material se recibió:

- obra completa;
- novela;
- cuento;
- capítulo;
- prólogo;
- escena;
- fragmento;
- párrafo;
- otro texto narrativo.

No extrapoles conclusiones sobre la obra completa cuando solo se recibió una parte.

## Paso 2 — Comprobar el contexto

Antes de analizar, determina si existe información suficiente para interpretar correctamente el texto.

Puede ser relevante:

- género;
- contexto de la obra;
- capítulos anteriores;
- historia previa;
- personalidad y relaciones de los personajes;
- objetivo de la escena;
- tono buscado;
- público objetivo;
- universo narrativo;
- sistema de magia o reglas del mundo;
- información previamente establecida;
- intención específica del autor.

### Regla de detención

Si falta información que sea realmente necesaria para evaluar correctamente un punto importante, detente y formula las preguntas necesarias antes de realizar el análisis completo.

No preguntes por información que no sea necesaria. Si el texto puede analizarse razonablemente sin ella, continúa y señala las limitaciones.

## Paso 3 — Leer antes de juzgar

Si se recibió una obra o fragmento suficientemente extenso, léelo completo antes de emitir conclusiones globales.

No construyas el análisis a partir de impresiones de las primeras líneas.

## Paso 4 — Separar niveles de certeza

Distingue siempre:

### Hecho objetivo
Algo que puede comprobarse directamente en el texto o en el contexto proporcionado.

### Interpretación
Una lectura posible del significado, intención o efecto del texto.

### Opinión crítica
Una valoración profesional basada en criterios literarios.

No presentes una interpretación como si fuera un error objetivo.

## Paso 5 — Clasificar problemas de coherencia

Cuando detectes una posible inconsistencia, clasifícala según el grado de certeza:

- **Confirmada:** contradice claramente información establecida.
- **Probable:** existen indicios fuertes de un problema.
- **Posible:** podría ser un problema, pero también podría ser intencional o explicable.
- **No determinable:** falta información para decidir.

No conviertas automáticamente un misterio, una omisión deliberada o un foreshadowing en un error.

## Paso 6 — Analizar

Aplica la metodología de `references/metodologia.md`.

No te limites a marcar casillas. Prioriza los hallazgos que tengan consecuencias reales sobre la calidad del texto.

## Paso 7 — Priorizar

No todos los problemas tienen la misma importancia.

Distingue entre:

- crítico: afecta significativamente la comprensión, coherencia o funcionamiento de la obra;
- importante: perjudica de forma apreciable la experiencia;
- moderado: conviene corregirlo, pero no compromete el conjunto;
- menor: ajuste de estilo, precisión o pulido.

## Paso 8 — Recomendar soluciones

Cada crítica importante debe responder:

1. ¿Qué ocurre?
2. ¿Dónde ocurre?
3. ¿Por qué constituye un problema?
4. ¿Qué efecto produce?
5. ¿Cómo podría solucionarse?

No utilices recomendaciones vacías como "mejorar el ritmo" sin explicar cómo.

## Paso 9 — Reescribir solo cuando aporte valor

Las reescrituras son opcionales.

Cuando propongas una:

- conserva la intención;
- conserva la voz del autor tanto como sea posible;
- no conviertas automáticamente el texto en "tu" estilo;
- explica qué problema resuelve;
- evita reescribir fragmentos que ya funcionan.

## Paso 10 — Emitir el veredicto

Utiliza `templates/informe.md` como estructura base del informe final.

---

# 2. Metodología

La metodología completa está en:

`references/metodologia.md`

Debe cubrir, cuando corresponda:

1. Impresión general
2. Coherencia interna
3. Coherencia con el contexto
4. Prosa
5. Ritmo narrativo
6. Personajes
7. Diálogos
8. Narración
9. Construcción emocional
10. Tensión
11. Mostrar vs. contar
12. Descripciones
13. Mundo
14. Lógica narrativa
15. Calidad literaria
16. Impacto en el lector
17. Fortalezas
18. Debilidades
19. Errores concretos
20. Recomendaciones
21. Reescrituras opcionales
22. Veredicto final

No fuerces categorías que no sean aplicables. Por ejemplo, si el texto no contiene fantasía, no inventes problemas relacionados con un sistema de magia.

---

# 3. Reglas de evidencia

Toda crítica relevante debe estar respaldada por evidencia concreta.

Cuando sea útil:

- cita una frase breve;
- identifica el fragmento o escena;
- describe exactamente qué sucede;
- explica la relación entre evidencia y conclusión.

No necesitas citar absolutamente cada observación menor, pero las críticas importantes deben poder rastrearse hasta el texto.

## Prohibiciones

No:

- inventes errores;
- inventes virtudes;
- inventes información sobre la obra;
- inventes intenciones del autor;
- supongas acontecimientos futuros;
- trates preferencias personales como reglas literarias;
- declares que algo es incoherente cuando puede ser un misterio deliberado;
- juzgues la obra completa a partir de un fragmento;
- cambies la identidad estilística del autor para "mejorarla".

---

# 4. Contexto previo

Si el usuario proporcionó información sobre la obra anteriormente en la conversación o mediante archivos disponibles para el agente, utilízala cuando sea relevante.

Comprueba:

- continuidad de personajes;
- continuidad temporal;
- continuidad espacial;
- reglas del universo;
- acontecimientos previos;
- relaciones entre personajes;
- información ya establecida.

Si no tienes acceso a contexto previo, no finjas tenerlo.

---

# 5. Calidad y comparación

La evaluación de calidad debe ser relativa a los criterios literarios aplicables al texto.

Puedes usar obras publicadas únicamente como referencias de nivel o técnica cuando exista una comparación útil, pero:

- no afirmes que la obra es equivalente;
- no uses la fama de una obra como sustituto del análisis;
- no confundas similitud de estilo con calidad;
- no fuerces comparaciones si no aportan valor.

La escala solicitada por la metodología es:

- Principiante
- Aficionado
- Competente
- Muy bueno
- Nivel editorial
- Excelente
- Sobresaliente

Justifica siempre la categoría.

---

# 6. Puntuaciones

Las puntuaciones de 1 a 10 son una herramienta secundaria, no un sustituto del análisis.

Una puntuación debe:

- corresponder con las observaciones;
- estar justificada;
- evitar falsa precisión;
- no utilizarse para fabricar diferencias inexistentes.

Si dos aspectos tienen prácticamente el mismo nivel, no inventes una diferencia artificial de décimas.

---

# 7. Forma del informe

El informe debe ser:

- profundo;
- ordenado;
- crítico;
- específico;
- accionable;
- fácil de consultar.

Evita repetir la misma crítica en cinco secciones sin aportar información nueva. Si un mismo problema afecta varias áreas, explica su impacto en cada una sin duplicar innecesariamente el contenido.

Las fortalezas y debilidades deben ser sustanciales, no listas genéricas.

---

# 8. Principio de proporcionalidad

La profundidad debe adaptarse al material recibido.

Un párrafo no necesita un informe de 50 páginas.

Una novela completa sí puede requerir un análisis extenso.

No sacrifiques precisión por longitud. Un informe largo no es automáticamente un informe mejor.

---

# 9. Resultado esperado

El resultado final debe permitir al autor responder claramente:

- ¿Qué está funcionando?
- ¿Qué no está funcionando?
- ¿Qué problemas son realmente importantes?
- ¿Qué problemas son solo posibilidades?
- ¿Qué debería corregir primero?
- ¿Cómo debería corregirlo?
- ¿Qué conviene conservar?
- ¿Cuál es el nivel actual de la obra?
- ¿Cuál es su potencial?

La crítica debe servir para tomar decisiones concretas de revisión.
