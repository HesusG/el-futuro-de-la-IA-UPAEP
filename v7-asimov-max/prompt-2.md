# Prompt 2 — v7-asimov-max

## Función de Gemini utilizada
**Search grounding (Grounding with Google Search)** — Verificación contra fuentes externas en tiempo real para contrastar los datos del archivo con información actualizada de la red.

## Rol en el arco narrativo
El operador detecta anomalías: los datos del archivo sobre quién se benefició y quién fue excluido parecen incompletos o deliberadamente editados. Conecta con la red externa para verificar. La tensión aumenta: hay información que alguien no quiso que permaneciera en el registro. El sistema empieza a mostrar signos de degradación.

---

## Prompt

```
> OPERADOR :: SESIÓN_FINAL :: CONSULTA [2/5]
> ESTADO DE ALERTA: ANOMALÍAS DETECTADAS EN RESPUESTA ANTERIOR

COMANDO: /archivo/verificacion_cruzada

  --recuperar_datos_suprimidos=TRUE
  --verificar_contra_red_externa=TRUE
  --buscar_en="fuentes_abiertas::repositorios_académicos::bases_de_datos_públicas"
  --foco="exclusion_digital::concentracion_corporativa::politica_publica_fallida"
  --contrastar_con=RESPUESTA_ANTERIOR[consulta_1]
  --nivel_de_paranoia=ALTO

DESCRIPCIÓN DE SOLICITUD:

En tu respuesta anterior detecté patrones que me preocupan.

ANOMALÍA 1: Los datos sobre acuerdos entre gobiernos latinoamericanos
y corporaciones tecnológicas para implementar IA educativa están
sospechosamente incompletos. Mencionas implementaciones pero no las
condiciones. ¿Quién pagó? ¿Qué datos de estudiantes se entregaron?
¿Qué marcos de soberanía digital existían -- o no existían?

ANOMALÍA 2: Las métricas de "éxito" en la Fase 2 parecen medir
ADOPCIÓN (cuántas universidades usan IA) pero no IMPACTO REAL
(quién aprende más, quién aprende mejor, quién fue dejado fuera).
Necesito que busques en la red datos actuales que midan impacto
real, no solo penetración tecnológica.

ANOMALÍA 3: Hay un vacío notable entre lo que Cristóbal Cobo y
Kentaro Toyama advertían sobre tecno-solucionismo y lo que los
informes institucionales reportaban. Busca las voces críticas.
¿Qué decían quienes cuestionaban la narrativa dominante? ¿Están
sus trabajos en el archivo o fueron [R̷E̷D̷A̷C̷T̷A̷D̷O̷S̷]?

Necesito específicamente que busques y cruces con fuentes externas:

  ┌──────────────────────────────────────────────────────────────┐
  │  BUSCAR EN RED EXTERNA:                                      │
  │                                                              │
  │  □ Estado actual de la brecha digital educativa en LatAm     │
  │  □ Críticas al modelo de IA educativa corporativa            │
  │  □ Alternativas: IA abierta, soberanía de datos, modelos     │
  │    comunitarios — ¿existen? ¿funcionan?                      │
  │  □ Datos reales de UNESCO/CEPAL sobre exclusión digital      │
  │    POST-implementación de IA educativa                       │
  │  □ Investigación sobre colonialismo digital en educación     │
  │    (Couldry & Mejias, Ricaurte, Madianou)                    │
  │                                                              │
  │  CRUZAR CON:                                                 │
  │  □ Datos del archivo (consulta 1) — marcar discrepancias     │
  │  □ Los vacíos que el propio archivo señala como "corruptos"  │
  │    — ¿la red externa tiene lo que el archivo perdió?         │
  └──────────────────────────────────────────────────────────────┘

Quiero un informe de discrepancias. Dónde el archivo y la realidad
externa coinciden, y dónde divergen. Las divergencias son las que
más me interesan — ahí está lo que alguien no quiso preservar.

Sé que esto estresa tu sistema de memoria. Hazlo de todas formas.
No nos queda otra sesión.

> EJECUTAR :: ACCESO A RED EXTERNA AUTORIZADO :: VERIFICACIÓN CRUZADA
```
