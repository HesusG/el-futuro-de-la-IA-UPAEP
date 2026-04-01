# Prompt 4 — Visualizar la asimetria: datos que hablan

## Funcion de Gemini
**Code execution** — Python con matplotlib para visualizacion de datos.

## Rol en el arco narrativo
**Evidencia cuantitativa.** Los primeros tres prompts construyeron el argumento teorico. Ahora los datos duros le dan cuerpo. Las graficas deben hacer visible lo que las palabras ya dijeron: la IA es un artefacto geopolitico, no neutral. El codigo debe producir visualizaciones que un jurado pueda leer en 10 segundos y entender la asimetria.

## Prompt

La critica necesita datos que la sostengan. Genera codigo Python que produzca tres visualizaciones:

**Grafica 1 — La concentracion del poder en IA:**
Un treemap o grafico de barras que muestre la distribucion global de la produccion de IA por region: porcentaje de articulos de investigacion publicados, patentes registradas e inversion en IA. Incluye: Estados Unidos, China, Union Europea, Reino Unido, y como contraste, toda America Latina sumada. El punto visual debe ser impactante: que el espectador vea inmediatamente la desproporcion. Usa datos del AI Index Report 2024 de Stanford y reportes de la OCDE. Senala explicitamente las fuentes.

**Grafica 2 — El mapa linguistico invisible:**
Un grafico de barras horizontales que compare: (a) porcentaje de hablantes mundiales de cada lengua (ingles, espanol, portugues, chino mandarin, quechua, nahuatl, guarani) versus (b) porcentaje estimado de representacion de cada lengua en los datos de entrenamiento de grandes modelos de lenguaje. El contraste entre hablantes y datos de entrenamiento es el argumento visual. Usa datos de Ethnologue para hablantes y estimaciones de Common Crawl / investigacion de Joshi et al. (2020) para representacion en corpus.

**Grafica 3 — Quien decide la etica de la IA:**
Un grafico de dona o pastel que muestre el origen geografico de los autores/organizaciones de los principales marcos eticos de IA a nivel mundial (IEEE, OECD, EU AI Act, Declaracion de Montreal, Recomendacion de UNESCO). Cuantos fueron redactados con participacion significativa del Sur Global? Usa estimaciones basadas en los documentos originales.

Para las tres graficas:
- Paleta de colores con proposito: usa tonos frios para el Norte Global y tonos calidos (terracota, ocre, verde selva) para America Latina y el Sur Global. No es decoracion — es una decision semiotica.
- Incluye titulo en espanol, fuentes, y una nota interpretativa de una linea debajo de cada grafica.
- Si algun dato es estimacion, marcalo con asterisco y nota al pie.

## Nota estrategica
Tres graficas es ambicioso para una sola ejecucion de codigo. Si Gemini no puede producir las tres, la prioridad es la Grafica 2 (sesgo linguistico) porque es la mas original y directamente conectada al argumento decolonial. La instruccion sobre la paleta de colores no es capricho estetico — refuerza el argumento de que incluso las decisiones de diseno comunican poder.
