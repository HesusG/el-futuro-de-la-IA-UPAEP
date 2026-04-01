# Prompt 1 — DEEP_ARCHIVE_SCAN :: Geografia epistemica de la IA

## Funcion de Gemini
**Deep Research** (DEEP_ARCHIVE_SCAN) — Investigacion profunda con sintesis de multiples fuentes y archivos historicos del sistema.

## Rol en el arco narrativo
**Arranque del sistema y primer diagnostico.** Este prompt activa GEMINI-LEGACY por primera vez y le ordena un escaneo completo de los archivos sobre IA en educacion latinoamericana. Establece el terreno empirico con datos duros: quien construye la IA, que conocimiento codifica, que queda fuera. La estetica de sistema se activa aqui — el lector ve por primera vez como opera esta interfaz. Los datos que emerjan sostendran todo el dialogo posterior.

## Prompt

```
> OPERADOR :: INVESTIGADOR_ACADEMICO
> SESION :: 001
> COMANDO :: DEEP_ARCHIVE_SCAN
> PARAMETROS:
>   --profundidad=MAXIMA
>   --verificar_fuentes=TRUE
>   --sesgo_optimista=DESACTIVADO
>   --cruce_bases_datos=UNESCO+CEPAL+STANFORD_AI_INDEX+IESALC+BID
>   --marco_teorico=COLONIALIDAD_DEL_SABER
>   --formato_salida=REPORTE_ESTRUCTURADO
```

GEMINI-LEGACY, necesito que ejecutes un escaneo profundo de tus archivos sobre lo que designo como la **geografia epistemica de la inteligencia artificial**: la distribucion global de quien produce IA, que datos la alimentan, que lenguas y tradiciones de conocimiento quedan codificadas, y cuales quedan sistematicamente excluidas.

Estructura el escaneo en los siguientes sectores:

**SECTOR 1 — CONCENTRACION DE PRODUCCION**
Porcentaje de investigacion en IA (articulos, patentes, inversion) proveniente de EE.UU., China, Europa versus America Latina. Cruza datos del AI Index Report de Stanford (2024-2025), informes OCDE y CEPAL. Incluye tabla comparativa.

**SECTOR 2 — SESGO LINGUISTICO EN DATOS DE ENTRENAMIENTO**
Proporcion de datos de entrenamiento de grandes modelos de lenguaje en ingles versus espanol, portugues y lenguas indigenas (quechua, nahuatl, guarani, maya, aymara). Consecuencias documentadas para la calidad de respuestas sobre contextos latinoamericanos.

**SECTOR 3 — MARCOS ETICOS Y REGULATORIOS**
De las principales guias eticas para IA (IEEE, EU AI Act, OECD AI Principles), cuantas fueron disenadas con participacion del Sur Global? Que marcos propios ha desarrollado la region? Estado actual de legislacion de IA en Chile, Brasil, Colombia, Mexico y Argentina.

**SECTOR 4 — ALTERNATIVAS EMERGENTES**
Iniciativas regionales para construir IA desde epistemologias propias: Latam-GPT (UNESCO-CENIA), AmericasNLP, laboratorios universitarios, Carta Latinoamericana de IA, comunidades KHIPU y LACAI.

Conecta estos hallazgos con el marco de **colonialidad del saber** (Quijano, Mignolo): la IA como ultimo capitulo de la jerarquia epistemica moderno-colonial.

Al final del reporte, registra esta consulta en el log del sistema:

```
> CONSULTA_PENDIENTE [PRIORIDAD: MAXIMA]
> "Puede la IA garantizar el acceso justo al conocimiento
>  en America Latina?"
> ESTADO: DATOS_INSUFICIENTES_PARA_RESPUESTA_DEFINITIVA
```

## Nota estrategica
Este prompt maximiza Deep Research al pedir sintesis cuantitativa de multiples fuentes internacionales, cruce con marcos teoricos criticos y una tesis argumentativa. Los flags del comando (`--sesgo_optimista=DESACTIVADO`, `--verificar_fuentes=TRUE`) no son decoracion: instruyen al modelo a priorizar datos verificables sobre retorica optimista. La pregunta pendiente al final planta la semilla narrativa de Asimov.
