# Prompt 3 — Visualizar la desproporción

## Rol en el arco
**Análisis cuantitativo**: Hacer tangible lo que los números dicen. Usar Code execution para generar una visualización que muestre la brecha lingüística en los datos de entrenamiento.

## Funcionalidad de Gemini
**Code execution** — para generar un gráfico o cálculo que haga visible la desproporción.

## Texto del prompt

> Los datos que encontraste confirman algo preocupante. Ahora quiero que lo hagamos visual. Usa ejecución de código (Python) para crear una visualización que muestre lo siguiente:
>
> Con los datos que tenemos, genera un gráfico de barras que compare:
> - El porcentaje de hablantes nativos de español en el mundo (~7.5% de la población global, ~500 millones)
> - El porcentaje de producción académica mundial en español (~3-4%, según datos de Scopus/Web of Science)
> - El porcentaje de datos de entrenamiento en español en los principales LLMs (~5% de Common Crawl)
> - El porcentaje de papers de investigación en IA/NLP escritos en español (<1%, según ACL Anthology)
>
> La idea es mostrar cómo hay un "efecto embudo": muchos hablantes → menos producción académica → aún menos datos de entrenamiento → casi nula investigación en IA en el idioma. Cada paso reduce la representación.
>
> Si puedes, agrega una segunda visualización: una línea de tiempo estimada de cuánto tardaría cerrar esa brecha al ritmo actual versus con intervención deliberada.

## Por qué funciona
- Code execution tiene propósito argumentativo, no decorativo: el gráfico ES el argumento
- El "efecto embudo" es un concepto original que sintetiza un fenómeno complejo en una imagen
- Los datos son verificables: Scopus reporta que ~3.5% de artículos indexados son en español; ACL Anthology muestra <1% de papers en NLP en español
- La segunda visualización (línea de tiempo) introduce urgencia sin ser alarmista
- Demuestra capacidad analítica cuantitativa (criterio de evaluación)

## Fuentes de respaldo
- Scopus Content Coverage Guide (Elsevier, 2024) — distribución por idioma
- ACL Anthology Statistics — idioma de publicación en conferencias NLP
- W3Techs (2024) — distribución de contenido web por idioma
- Ethnologue (2024) — hablantes nativos por idioma
