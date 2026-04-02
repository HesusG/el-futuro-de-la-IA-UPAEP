# Sesgo Lingüístico en Sistemas de IA: Datos de Referencia

> Archivo de referencia para GEMINI-LEGACY / TRIBUNAL-LEGACY
> Fuentes: Common Crawl, W3Techs, Meta AI, Google Research, AmericasNLP, UNESCO
> Última actualización: abril 2026
> Nota: datos de fuentes publicadas hasta 2025. Puntos marcados [DATO_NO_VERIFICADO] requieren confirmación.

## 1. Distribución Lingüística en Common Crawl

Common Crawl es el corpus web más utilizado para entrenar LLMs. Su distribución lingüística determina directamente qué lenguas "saben" los modelos.

| Idioma | % de Common Crawl (est.) | % de hablantes globales | Ratio representación |
|--------|--------------------------|------------------------|---------------------|
| Inglés | ~46% | ~17% | 2.7x sobrerepresentado |
| Alemán | ~6% | ~1.5% | 4x sobrerepresentado |
| Ruso | ~5.5% | ~3.4% | 1.6x sobrerepresentado |
| Francés | ~5% | ~3.6% | 1.4x sobrerepresentado |
| Español | ~5% | ~7.5% | 0.67x subrepresentado |
| Japonés | ~5% | ~1.7% | 2.9x sobrerepresentado |
| Portugués | ~3% | ~3.7% | 0.8x subrepresentado |
| Chino | ~3% | ~16% | 0.19x subrepresentado |

(Fuentes: W3Techs, Common Crawl statistics 2023-2024, estimaciones compiladas)

**Dato clave:** El español tiene ~580 millones de hablantes nativos (segundo idioma más hablado del mundo) pero representa apenas ~5% del contenido web indexado. El inglés, con ~380 millones de nativos, representa ~46%.

**El efecto embudo:** Hablantes → contenido web → contenido indexado → datos de entrenamiento → calidad del modelo. En cada paso, las lenguas del Sur Global pierden representación.

## 2. Composición Lingüística de LLMs Principales

### GPT-4 / ChatGPT (OpenAI)
- OpenAI no publica distribución exacta de datos de entrenamiento
- Evaluaciones externas muestran rendimiento significativamente inferior en español vs inglés en tareas de razonamiento complejo
- La "neutralización" del español: el modelo tiende a producir un español "universal" que elimina regionalismos (Fuente: análisis independientes, 2023-2024)

### Gemini (Google)
- Entrenado en datos multilingües pero sin distribución pública específica
- Mejor rendimiento en español que competidores anteriores según benchmarks MMLU
- Aún muestra preferencia por marcos de referencia anglosajones en temas de educación y pedagogía [DATO_NO_VERIFICADO — verificar benchmarks actuales]

### LLaMA (Meta)
- LLaMA 2: ~89.7% inglés en datos de entrenamiento (Fuente: Meta AI, 2023 technical report)
- LLaMA 3: composición multilingüe expandida pero inglés sigue dominando (~85% estimado)
- Español y portugués juntos: ~3-4% estimado del corpus total

### Impacto en calidad:
- En tareas de comprensión lectora (benchmark equivalente): GPT-4 muestra ~15-20% menor precisión en español que en inglés en preguntas que requieren razonamiento cultural contextual
- La brecha se amplía para variantes regionales del español (español mexicano, rioplatense, andino)
(Fuentes: evaluaciones HELM, Open LLM Leaderboard, estudios independientes 2023-2024)

## 3. Lenguas Indígenas: Presencia Digital

### Estado de recursos digitales (clasificación NLP):

| Lengua | Hablantes (est.) | Clasificación NLP | Wikipedia (artículos) | Presencia web |
|--------|-------------------|-------------------|----------------------|---------------|
| Quechua | ~8-10M | Baja | ~23,000 | Mínima |
| Náhuatl | ~1.7M | Baja | ~7,000 | Mínima |
| Guaraní | ~6M | Baja | ~4,500 | Baja |
| Maya (yucateco) | ~800K | Muy baja | ~1,000 | Mínima |
| Aymara | ~2M | Baja | ~5,000 | Mínima |
| Zapoteco | ~450K | Muy baja | ~500 | Casi nula |
| Mapudungun | ~250K | Muy baja | ~2,000 | Casi nula |

(Fuentes: UNESCO Atlas of World's Languages in Danger, Ethnologue, Wikipedia stats 2024)

**Contraste:** El inglés tiene ~6.8 millones de artículos en Wikipedia. El quechua — con 8-10 millones de hablantes — tiene 23,000. El zapoteco, con ~450,000 hablantes, tiene ~500.

### Problemas específicos de LLMs con lenguas indígenas:
1. **Alucinación estructural:** Los modelos aplican gramática del español/inglés a lenguas aglutinantes (quechua, náhuatl), produciendo texto gramaticalmente incoherente
2. **Folklorización:** Cuando se pide contenido educativo en lenguas indígenas, los modelos producen traducciones literales del español o contenido "culturalmente decorativo" sin profundidad pedagógica
3. **Imposibilidad de oralidad:** Muchas lenguas indígenas son primariamente orales. Los LLMs, entrenados en texto escrito, no pueden representar tradiciones de conocimiento oral
4. **Datos insuficientes para fine-tuning:** No existen corpus paralelos de calidad suficiente para la mayoría de lenguas indígenas americanas

## 4. "Neutralización Lingüística" del Español

Fenómeno documentado: los LLMs producen un español "neutro" que:
- Elimina modismos regionales (mexicanismos, argentinismos, colombianismos)
- Prefiere formas peninsulares en contextos formales
- Homogeneiza el vocabulario académico hacia equivalentes del inglés
- Pierde matices de registro que distinguen español oral/escrito en diferentes regiones

**Impacto educativo:** Un estudiante mexicano que interactúa con un LLM recibe contenido en un español que no es exactamente el suyo. La "alienación cognitiva" sutil: adaptar el pensamiento a la lógica del modelo para obtener respuestas coherentes. (Concepto discutido en literatura sobre sesgos lingüísticos de IA, 2023-2024)

## 5. AmericasNLP: Estado y Hallazgos

**AmericasNLP** es la principal red de investigación en procesamiento de lenguas naturales de las Américas, con enfoque en lenguas indígenas.

### Talleres y contribuciones:
- AmericasNLP 2021-2024: workshops co-ubicados en conferencias ACL
- Shared tasks en traducción automática para lenguas indígenas (quechua, guaraní, aymara, náhuatl, entre otras)
- Creación de datasets paralelos para investigación

### Hallazgos clave:
1. **La traducción automática para lenguas indígenas sigue siendo de muy baja calidad** — BLEU scores significativamente inferiores a pares de lenguas europeas
2. **El problema no es solo datos sino tipología:** Las lenguas aglutinantes y polisintéticas requieren arquitecturas diferentes a las optimizadas para lenguas analíticas (inglés)
3. **El conocimiento comunitario es esencial:** Los mejores sistemas son co-desarrollados CON hablantes, no sobre ellos
4. **La brecha de recursos persiste:** A pesar de esfuerzos, las lenguas indígenas americanas siguen clasificadas como "low-resource" en NLP

(Fuentes: AmericasNLP Proceedings 2021-2024, ACL Anthology)

## 6. Datos para Argumentación

### Para el Fiscal:
- La distribución lingüística de los LLMs es una forma de colonialidad del saber: el inglés funciona como lengua franca algorítmica, no por superioridad sino por acumulación de datos.
- "No es que la IA no hable quechua. Es que el quechua no existe en el universo de datos que la IA considera real." — reformulación del concepto de línea abismal de Santos.

### Para el Defensor:
- AmericasNLP demuestra que es técnicamente posible construir herramientas para lenguas indígenas. El problema es de inversión y voluntad, no de imposibilidad técnica.
- El español, aunque subrepresentado, tiene masa crítica suficiente para que los modelos funcionen bien en la mayoría de tareas prácticas.

### Para el Juez:
- La brecha lingüística tiene tres niveles: (1) inglés vs español/portugués (medible, parcialmente compensable), (2) español estándar vs variantes regionales (sutil, menos documentada), (3) español vs lenguas indígenas (estructural, sin solución a corto plazo sin cambios fundamentales en la arquitectura de los modelos).
