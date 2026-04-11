# Prompt 2 — Dimensionar el problema con datos actuales

## Rol en el arco
**Evidencia**: Pasar de la intuición a los datos. Usar Search grounding para que Gemini busque información actual sobre la representación del español en los datasets de IA.

## Funcionalidad de Gemini
**Search grounding** — para obtener datos verificables y actualizados.

## Texto del prompt

> Gracias por esa honestidad. Ahora quiero que busquemos datos concretos juntos. Usa tu capacidad de búsqueda para encontrar información reciente (2023-2026) sobre estos puntos:
>
> 1. ¿Qué porcentaje del corpus de entrenamiento de los principales LLMs corresponde a español? ¿Y qué fracción de ese español es latinoamericano versus peninsular?
> 2. ¿Existen estudios que hayan medido la calidad de las respuestas de IA en español académico comparado con inglés académico? (precisión, riqueza de vocabulario, adecuación al registro)
> 3. ¿Hay algún proyecto activo en América Latina para crear modelos de lenguaje entrenados específicamente con corpus académico en español latinoamericano?
>
> No me des respuestas vagas. Si no encuentras datos específicos sobre algún punto, dilo — eso en sí mismo es un dato revelador sobre cuánta atención se le presta al tema.

## Por qué funciona
- El uso de Search grounding está justificado: necesitamos datos actuales que ni el usuario ni Gemini tienen memorizados
- La instrucción "si no encuentras datos, dilo" convierte la ausencia de información en argumento — sofisticación retórica
- La distinción entre español peninsular y latinoamericano muestra conocimiento del problema (no todo el español es igual para los modelos)
- Referencia implícita: Joshi et al. (2020) clasificaron el español como lengua "ganadora" en NLP pero no distinguieron variantes regionales — ese matiz es original

## Datos de respaldo propios (no incluidos en el prompt)
- Common Crawl, la principal fuente de datos para LLMs, tiene ~5% de contenido en español (W3Techs, 2024)
- El proyecto BERTIN y MarIA (IXA Group, Universidad del País Vasco) son modelos en español pero peninsular
- AYA de Cohere (2024) es uno de los pocos esfuerzos multilingües que incluye variantes latinoamericanas
