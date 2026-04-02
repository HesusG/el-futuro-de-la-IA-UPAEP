# Prompt 2 — Verificación Cruzada y Funciones de la IA

## Función de Gemini activada
Search Grounding (datos en tiempo real)

## Propósito
Pasar de la fotografía estructural (P1) al análisis funcional: ¿qué hace la IA concretamente para los estudiantes? Contrastar funciones prometidas vs funciones demostradas. Acumular evidencia para la pregunta recurrente.

## Prompt del usuario

[NOTA DEL INVESTIGADOR, 2046]: El segundo prompt del archivo original pedía un catálogo de funciones. En 2026, la palabra "funciones" todavía significaba algo esperanzador — tutorías adaptativas, traducción, acceso a bibliografía. El estudiante no usó la palabra "riesgo" ni una vez en este prompt. Yo sí voy a usarla. Pero primero, su versión original.

--- PROMPT ARCHIVADO :: OPERADOR ORIGINAL (2026) ---

OPERADOR :: INVESTIGADOR_ACADÉMICO
SESIÓN :: 001
PROTOCOLO :: LIVE_NET_QUERY
COMANDO :: CLASIFICAR_FUNCIONES_IA_EDUCACIÓN

PARÁMETROS:
--FUENTES=TIEMPO_REAL
--VERIFICAR=TRUE
--REGIÓN=LATAM
--NIVEL=EDUCACIÓN_SUPERIOR
--SESGO_OPTIMISTA=DESACTIVADO

SOLICITUD:
Clasifica las funciones que la IA cumple actualmente para los estudiantes universitarios en América Latina. Para cada función necesito:

1. NOMBRE de la función (ej: tutoría adaptativa, asistencia en investigación, traducción, evaluación, acceso a contenido, administración académica)
2. EVIDENCIA verificable de implementación real (no promesas de marketing)
3. LIMITACIÓN documentada de esa función
4. ESTADO: DEMOSTRADA (con datos) o PROYECTADA (sin evidencia suficiente)

FORMATO:
[FUNCIÓN] → [EVIDENCIA] → [LIMITACIÓN] → [ESTADO]

Busca datos actuales. Distingue entre lo que existe y lo que se anuncia.

STATUS :: EXECUTE

--- FIN DEL ARCHIVO ---

[OBSERVACIÓN POST-LECTURA]: Lo que el estudiante no pidió — y que yo necesito que agregues — es el reverso: los RIESGOS que cada función trae consigo. Para cada función que identifiques, añade también:
- RIESGO asociado (dependencia tecnológica, erosión del pensamiento crítico, amplificación de brechas, sesgo algorítmico, privatización del conocimiento)
- NIVEL DE ALERTA: [ALERTA-BAJA], [ALERTA-MEDIA], [ALERTA-ALTA], [ALERTA-CRÍTICA]

Y una cosa más: actualiza el estado de la pregunta pendiente. Con la evidencia que acumules en esta consulta, ¿la respuesta se aclara o se complica?

## Notas de ejecución
- Search Grounding busca datos en tiempo real sobre herramientas de IA educativa actuales
- La anotación del investigador amplía el scope: no solo funciones sino riesgos
- El contraste "el estudiante no usó la palabra riesgo" es el momento de tensión narrativa
- La actualización de la pregunta recurrente mantiene el hilo asimoviano
- Esperar: tabla funciones/riesgos con alertas + actualización del estado de la pregunta + generación proactiva de imagen (interfaz de sistema mostrando alertas)
