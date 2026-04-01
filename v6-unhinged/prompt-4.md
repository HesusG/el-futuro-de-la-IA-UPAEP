# Prompt 4 -- Visualizacion de escenarios: Codigo ejecutable

## Funcionalidad de Gemini
**Ejecucion de codigo (Python)** -- Generacion de graficos con matplotlib/seaborn usando datos reales como semilla y proyecciones con supuestos explicitos

## Fase narrativa
**Interludio analitico: Entre la segunda y la tercera carta**
El cronista hace una pausa en la prosa para adjuntar evidencia visual. Incluso en la ficcion, los numeros hablan.

## Rol en el arco
Rompe el ritmo epistolar deliberadamente para demostrar versatilidad. Muestra que el concursante domina la ejecucion de codigo como herramienta analitica. Los dos escenarios (Promesa vs. Inercia) preparan el terreno emocional e intelectual para la carta final.

---

## Texto del prompt

> Antes de tu carta final, necesito que hagas algo distinto. Necesito ver los numeros.
>
> Genera un grafico -- o una serie de graficos -- que visualice dos escenarios proyectados para America Latina en el periodo 2026-2036:
>
> **Escenario "Promesa":**
> Los paises de la region invierten en formacion docente en IA, desarrollan marcos eticos regionales, crean contenido educativo en espanol de alta calidad, y establecen alianzas publico-privadas con gobernanza transparente. La brecha digital se reduce gradualmente. Usa como punto de partida los datos reales de inversion educativa, conectividad, y formacion docente que encontraste en tu investigacion inicial.
>
> **Escenario "Inercia":**
> La adopcion de IA ocurre de facto -- los estudiantes la usan, los profesores la ignoran o la prohiben, no hay regulacion regional, las herramientas dominantes son en ingles, y la brecha entre universidades de elite y el resto se amplifica. Los datos de partida son los mismos, pero los supuestos de politica publica son opuestos.
>
> Para el grafico necesito:
> - **Eje temporal:** 2026 a 2036, por anos.
> - **Metricas a proyectar (elige 3-4 que sean visualizables):** Pueden incluir: porcentaje de docentes capacitados en IA, indice de brecha digital educativa, tasa de adopcion institucional de herramientas de IA, indice de produccion academica asistida por IA en espanol, o las que consideres mas reveladoras.
> - **Supuestos explicitos:** Debajo del grafico o como comentarios en el codigo, lista los supuestos de cada escenario. No quiero numeros magicos -- quiero que cada tasa de crecimiento o declive tenga una justificacion.
> - **Fuentes semilla:** Indica que datos reales de 2024-2026 usaste como punto de partida.
>
> Enmarca esto dentro de la narrativa: es un anexo que el cronista adjunta a sus cartas. El titulo del grafico puede ser algo como: "Lo que pude haber sido: dos futuros posibles para la educacion latinoamericana."
>
> Usa Python con matplotlib o seaborn. Que sea visualmente limpio y legible. Si puedes usar una paleta de colores que evoque la tension entre los dos escenarios (no rojo/verde generico -- piensa mas), mejor.

---

## Notas tecnicas
- La ejecucion de codigo es una funcionalidad evaluada por el jurado. Este prompt la integra organicamente en la narrativa en lugar de forzarla.
- Pedir supuestos explicitos demuestra literacidad estadistica y pensamiento critico.
- La instruccion sobre la paleta de colores ("no rojo/verde generico") muestra atencion al detalle y eleva la calidad visual.
- "Lo que pude haber sido" como titulo del grafico mantiene la voz del cronista incluso en una pieza analitica.
- Los datos semilla del Prompt 1 (Deep Research) se reutilizan aqui, demostrando coherencia entre prompts.
