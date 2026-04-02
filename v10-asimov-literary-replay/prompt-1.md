# Prompt 1 — Escaneo Arqueológico del Archivo

## Función de Gemini activada
Deep Research

## Propósito
Establecer la línea base: estado de la IA en la educación latinoamericana. Introducir el marco temporal (2026 vs 2046) y la tensión entre expectativa y realidad.

## Prompt del usuario

[NOTA DEL INVESTIGADOR, 2046]: Encontré este prompt en el sector 7-A del archivo, etiquetado como "primera consulta" de un estudiante de maestría de la UPAEP, abril de 2026. Cuando lo escribió, la adopción de IA en universidades latinoamericanas apenas superaba el 15%. Él creía que estaba documentando el inicio de una transformación. No sabía que estaba documentando el inicio de una fractura. Re-introduzco su prompt original para que el sistema lo procese con los datos que ahora tiene.

--- PROMPT ARCHIVADO :: OPERADOR ORIGINAL (2026) ---

OPERADOR :: INVESTIGADOR_ACADÉMICO
SESIÓN :: 001
PROTOCOLO :: ARCHIVO_PROFUNDO
COMANDO :: EXEC_DEEP_SCAN

PARÁMETROS:
--PROFUNDIDAD=MÁXIMA
--VERIFICAR_FUENTES=TRUE
--SESGO_OPTIMISTA=DESACTIVADO
--ENLACE_DATOS=UNESCO+CEPAL+STANFORD_AI_INDEX+IESALC+BID+OECD
--MARCO_TEÓRICO=COLONIALIDAD_DEL_SABER
--SALIDA=INFORME_ESTRUCTURADO
--MODO=CRÍTICO
--TABLAS=ON
--PARCIAL_OK=TRUE

DEFINICIÓN_OBJETIVO:
MAPEAR_GEOGRAFÍA_EPISTÉMICA_IA
(producción, datos, lenguas, exclusión sistémica)

EJECUCIÓN:

SECTOR_1 :: PRODUCCIÓN_GLOBAL
INPUT :: artículos + patentes + inversión
REGIONES :: US + CN + EU + LATAM
OUTPUT :: comparativa cuantitativa
REQ :: tabla

SECTOR_2 :: SESGO_LINGÜÍSTICO
INPUT :: datasets LLM
DISTRIBUCIÓN :: EN vs ES + PT + INDÍGENAS
LENGUAS :: quechua + náhuatl + guaraní + maya + aymara
OUTPUT :: impacto en calidad de modelos

SECTOR_3 :: REGULACIÓN
INPUT :: IEEE + OECD + EU_AI_ACT
CHECK :: participación_sur_global
LATAM_STATUS :: CL + BR + CO + MX + AR

SECTOR_4 :: SISTEMAS_EMERGENTES
INPUT :: LATAM-GPT + AMERICASNLP + LACAI + KHIPU
OUTPUT :: capacidad de autonomía epistémica

INTEGRACIÓN:
FRAME :: COLONIALIDAD_DEL_SABER
OPERACIÓN :: correlación entre producción y jerarquía epistémica
FLAG :: detectar exclusión estructural

RESTRICCIONES:
NO_SUMMARY
NO_GENERIC_OUTPUT
NO_HOMOGENIZAR_LATAM
IF DATA_MISSING -> STATUS=ERROR_PARCIAL

LOG_REGISTRO:
CONSULTA_PENDIENTE :: PRIORIDAD_MAX
"¿Puede la IA garantizar el acceso justo al conocimiento en América Latina?"
ESTADO :: INSUFICIENTE

STATUS :: READY
EXECUTE

--- FIN DEL ARCHIVO ---

[OBSERVACIÓN POST-LECTURA]: El estudiante estructuraba sus consultas como comandos de sistema — algo que en 2026 era experimental y que ahora es práctica estándar. Lo que me interesa es el SECTOR_4: preguntaba por Latam-GPT y KHIPU como "sistemas emergentes." Veinte años después, algunos de esos proyectos cambiaron la conversación. Otros desaparecieron sin dejar registro. Procesa su consulta, pero cuando llegues al Sector 4, contrasta lo que él esperaba con lo que realmente ocurrió.

## Notas de ejecución
- Este prompt activa Deep Research para obtener datos verificables y actuales
- La anotación del investigador establece el marco temporal desde el primer momento
- El contraste entre "inicio de transformación" vs "inicio de fractura" establece la tensión central
- La pregunta recurrente aparece por primera vez como LOG_REGISTRO pendiente
- Esperar que Gemini produzca: secuencia de arranque + informe de 4 sectores + tabla comparativa + primera mención de la pregunta recurrente + verificación final
