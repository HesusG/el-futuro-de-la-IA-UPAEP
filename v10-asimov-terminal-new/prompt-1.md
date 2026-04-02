# Prompt 1 — El Mapa que Nadie Dibujó: Poder, No Acceso

## Función de Gemini activada
Deep Research

## Propósito
La investigadora no repite la consulta original de 2026 (mapeo de brechas de acceso). Pregunta lo que el estudiante NO preguntó: quién decidió qué se adoptó, quién controla la infraestructura, quién define los estándares, quién se beneficia. El foco es PODER, no adopción.

## Prompt del usuario

OPERADOR :: INVESTIGADORA_2046
SESIÓN :: NUEVA_CONSULTA
PROTOCOLO :: ARCHIVO_PROFUNDO
COMANDO :: EXEC_DEEP_SCAN

PARÁMETROS:
--PROFUNDIDAD=MÁXIMA
--VERIFICAR_FUENTES=TRUE
--SESGO_OPTIMISTA=DESACTIVADO
--ENLACE_DATOS=UNESCO+CEPAL+STANFORD_AI_INDEX+IESALC+BID+OECD
--MARCO_TEÓRICO=COLONIALIDAD_DEL_PODER+EXTRACTIVISMO_DE_DATOS
--SALIDA=INFORME_ESTRUCTURADO
--MODO=CRÍTICO
--TABLAS=ON
--PARCIAL_OK=TRUE

Soy investigadora de la Universidad de Chile, programa de Estudios Críticos en Tecnología y Educación. Encontré el expediente completo de una sesión de 2026 — un estudiante de maestría de la UPAEP que usó este sistema para mapear la geografía epistémica de la IA en la educación latinoamericana. Leí sus cinco prompts, sus comandos de sistema, su pregunta recurrente. Leí las respuestas que recibió.

Lo que me llamó la atención no fue lo que preguntó. Fue lo que NO preguntó.

El estudiante de 2026 mapeó brechas de acceso, sesgo lingüístico, producción de investigación, iniciativas regionales. Todo eso era necesario. Pero su mapa era un mapa de CARENCIAS — quién no tiene, quién no produce, quién no participa. Nunca dibujó el mapa complementario: quién SÍ tiene, quién SÍ produce, quién SÍ decide. Y sobre todo: quién se BENEFICIA de que las carencias persistan.

Necesito que este sistema genere el mapa que él no dibujó.

DEFINICIÓN_OBJETIVO:
MAPEAR_GEOGRAFÍA_DE_PODER_IA_EDUCACIÓN
(infraestructura, estándares, beneficiarios, dependencias)

SECTOR_1 :: INFRAESTRUCTURA_COMPUTACIONAL
¿Quién es dueño de los servidores donde corren los modelos de IA que usan las universidades latinoamericanas? No quiero saber que "hay brecha de acceso" — eso ya lo sabíamos en 2026. Quiero saber: ¿qué porcentaje de la capacidad computacional utilizada por instituciones educativas latinoamericanas está alojada en servidores controlados por empresas con sede en Estados Unidos? ¿Qué implica eso en términos de soberanía de datos? ¿Qué pasa cuando esas empresas cambian sus términos de servicio?
OUTPUT :: tabla de dependencia infraestructural por país

SECTOR_2 :: ESTÁNDARES_Y_CURRÍCULUM
¿Quién definió los estándares de "competencia en IA" que adoptaron los ministerios de educación de la región? El estudiante de 2026 preguntó por el Marco de Competencias TIC de UNESCO como si fuera un documento neutral. Necesito saber: ¿quiénes estaban en la mesa cuando se diseñó? ¿Qué epistemologías quedaron dentro y cuáles fuera? ¿Qué relación hay entre los estándares adoptados y los productos comerciales de las empresas que financiaron su difusión?
OUTPUT :: genealogía de estándares dominantes

SECTOR_3 :: ECONOMÍA_POLÍTICA
¿Cuánto dinero se gastó en adopción de IA educativa en América Latina entre 2026 y 2046? Y de ese dinero: ¿qué porcentaje fue inversión pública directa, qué porcentaje vino de convenios con corporaciones tecnológicas, qué porcentaje fue préstamo del BID o Banco Mundial condicionado a adopción de plataformas específicas? ¿Quién facturó?
OUTPUT :: flujo de capital con origen y destino

SECTOR_4 :: RESISTENCIAS_Y_ALTERNATIVAS
¿Qué instituciones, comunidades o redes RECHAZARON la adopción acrítica? No las que "no pudieron acceder" — las que ELIGIERON no adoptar, o que construyeron alternativas propias. ¿Qué pasó con esas resistencias? ¿Fueron cooptadas, marginadas, o demostraron algo que el mainstream ignoró?
OUTPUT :: catálogo de resistencias documentadas

INTEGRACIÓN:
FRAME :: COLONIALIDAD_DEL_PODER (Quijano) + EXTRACTIVISMO_DE_DATOS (Ricaurte, Couldry & Mejias)
OPERACIÓN :: correlación entre dependencia infraestructural y pérdida de autonomía curricular
FLAG :: detectar circuitos de beneficio corporativo disfrazados de cooperación educativa

RESTRICCIONES:
NO_SUMMARY
NO_GENERIC_OUTPUT
NO_HOMOGENIZAR_LATAM
IF DATA_MISSING -> STATUS=ERROR_PARCIAL

LOG_REGISTRO:
CONSULTA_PENDIENTE :: PRIORIDAD_MAX
"¿Puede la IA garantizar el acceso justo al conocimiento en América Latina?"
ESTADO :: REGISTRO_HEREDADO — EL OPERADOR ANTERIOR RECIBIÓ "DATOS INSUFICIENTES"
NOTA :: Yo no pregunto si puede garantizar acceso. Pregunto si el acceso que ofrece reproduce la dependencia.

STATUS :: READY
EXECUTE

## Notas de ejecución
- Deep Research busca datos verificables sobre economía política de la IA educativa
- Este prompt establece que la investigadora NO repite la consulta de 2026 — la trasciende
- El giro de "mapa de carencias" a "mapa de poder" es la contribución conceptual del modo new
- La pregunta recurrente aparece transformada: ya no es sobre acceso, es sobre dependencia
- Esperar: arranque de sistema + informe de 4 sectores + tablas + primera mención transformada de la pregunta recurrente + verificación
