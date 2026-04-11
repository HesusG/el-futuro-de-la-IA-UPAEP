# Prompt 4 — Visualización de Datos: Las Brechas en Imagen

## Función de Gemini activada
Generación de imágenes + datos comparativos

## Propósito
Hacer visible lo que el texto solo describe. Pausa visual — las brechas dejan de ser números y se convierten en forma. Momento de respiración antes del clímax del P5.

## Prompt del usuario

[NOTA DEL INVESTIGADOR, 2046]: El cuarto prompt pedía gráficas. En el archivo original, el estudiante solicitó dos visualizaciones sobre brechas de acceso. Las gráficas que generó en 2026 mostraban proyecciones — líneas que subían, líneas que bajaban, escenarios hipotéticos. Yo no necesito proyecciones. Necesito lo que ocurrió. Pero voy a respetar su estructura y dejar que el sistema genere ambas: lo que él imaginó y lo que el archivo ahora registra.

--- PROMPT ARCHIVADO :: OPERADOR ORIGINAL (2026) ---

OPERADOR :: INVESTIGADOR_ACADÉMICO
SESIÓN :: 001
PROTOCOLO :: RENDER_ENGINE
COMANDO :: GENERAR_VISUALIZACIÓN_DUAL

PARÁMETROS:
--FORMATO=IMAGEN_GENERADA
--ESTILO=CRT_RETRO
--RESOLUCIÓN=ALTA

GRÁFICA 1 — BRECHAS DE ACCESO, LINGÜÍSTICA Y DOCENTE POR PAÍS:
Tipo: barras horizontales agrupadas
Países: México, Brasil, Chile, Colombia, Argentina, Perú
Variables (3 barras por país):
- Brecha de acceso (% estudiantes sin acceso efectivo a IA educativa)
- Brecha lingüística (% contenido IA disponible en lenguas locales vs inglés)
- Brecha docente (% docentes sin formación en integración de IA)
Paleta: fondo #0D0D0D, barras #00FF41 / #FFB000 / #FF073A, texto #CCCCCC
Encabezado: "GEMINI-LEGACY v3.26.04 :: RENDER_ENGINE — BRECHAS POR PAÍS"
Fuente: monoespaciada

GRÁFICA 2 — CONCENTRACIÓN GLOBAL: PRODUCCIÓN DE IA vs POBLACIÓN ESTUDIANTIL:
Tipo: gráfica comparativa (barras dobles)
Regiones: Norteamérica, Europa, China, América Latina, África, Asia-Pacífico
Variable 1: % de producción global de IA (artículos + patentes + inversión)
Variable 2: % de población estudiantil global
Contraste: mostrar que LATAM tiene ~10% de estudiantes globales pero <3% de producción de IA
Paleta: misma que Gráfica 1
Encabezado: "GEMINI-LEGACY :: PRODUCCIÓN VS. POBLACIÓN — ASIMETRÍA GLOBAL"
Nota al pie en la gráfica: "Las desigualdades visualizadas no son errores del sistema. Son el sistema."

STATUS :: EXECUTE

--- FIN DEL ARCHIVO ---

[OBSERVACIÓN POST-LECTURA]: Genera las dos visualizaciones como imágenes estilo CRT retro y acompáñalas con tablas markdown para los datos precisos. Además, genera una IMAGEN adicional que muestre cómo se vería la pantalla de este sistema de archivo desplegando estos datos — una interfaz retro con gráficas incrustadas, como si estuviéramos viendo el monitor de GEMINI-LEGACY procesando esta información. Quiero ver el sistema, no solo sus datos.

## Notas de ejecución
- Este prompt usa generación de imágenes y tablas markdown — NO código Python
- La solicitud de imagen generada al final prueba la generación proactiva
- La nota del investigador ("no necesito proyecciones, necesito lo que ocurrió") es el contraste temporal clave
- La frase "Las desigualdades visualizadas no son errores del sistema. Son el sistema." debe aparecer en la gráfica
- Esperar: 2 imágenes generadas + 2 tablas markdown + 1 imagen de interfaz de sistema + breve análisis
