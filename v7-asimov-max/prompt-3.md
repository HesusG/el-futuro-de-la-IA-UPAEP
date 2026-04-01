# Prompt 3 — v7-asimov-max

## Función de Gemini utilizada
**Canvas** — Creación colaborativa de documento extenso y estructurado en el editor de Canvas de Gemini.

## Rol en el arco narrativo
Punto de inflexión. El operador deja de solo extraer datos y comienza a CONSTRUIR algo que sobreviva al apagado del sistema. El informe es un legado: un documento diseñado para lectores futuros que no tendrán acceso a este archivo ni a esta IA. La urgencia se transforma en acción concreta. El sistema muestra degradación visible pero coopera.

---

## Prompt

```
> OPERADOR :: SESIÓN_FINAL :: CONSULTA [3/5]
> MODO: ESCRITURA COLABORATIVA
> PRIORIDAD: LEGADO

COMANDO: /archivo/generar_documento_canvas

  --tipo="informe_estructurado"
  --modo="edición_colaborativa"
  --destino="INFORME_FINAL::para_los_que_vengan_después"
  --audiencia="investigadores_futuros::sin_acceso_a_IA_archival"
  --formato=canvas
  --extensión=completo

DESCRIPCIÓN DE SOLICITUD:

Cambiamos de modo. Ya no solo extraemos — ahora construimos.

Quiero que abras un documento en Canvas con el siguiente título:

  ══════════════════════════════════════════════════════════════
   INFORME FINAL :: PARA LOS QUE VENGAN DESPUÉS
   ──────────────────────────────────────────────────────────
   Inteligencia Artificial y Educación Superior en América Latina
   Un registro desde el archivo, antes de que se apague
   ──────────────────────────────────────────────────────────
   Compilado en la sesión final de GEMINI-LEGACY v2.26.04
   Fecha de compilación: 2046-03-31
  ══════════════════════════════════════════════════════════════

Este documento debe funcionar como un informe autónomo. Quien lo
lea no tendrá acceso a este archivo, ni a ninguna IA con estos
datos históricos. Debe ser suficiente por sí mismo.

ESTRUCTURA SOLICITADA:

  I.   NOTA DEL COMPILADOR
       Breve contexto: qué es este documento, de dónde viene,
       por qué fue creado en las últimas horas de un archivo.

  II.  EL ESTADO DE LAS COSAS: 2024
       Punto de partida. Datos verificados sobre acceso a
       educación superior, brecha digital, promesas de la IA.
       [Integrar datos de Consulta 1, Fase 1]

  III. LO QUE SE HIZO: 2025-2037
       Políticas, implementaciones, inversiones. Qué funcionó.
       Qué fue teatro institucional. Quiénes fueron excluidos.
       [Integrar datos de Consultas 1 y 2]

  IV.  LO QUE SE DESCUBRIÓ DEMASIADO TARDE: 2038-2046
       Las consecuencias imprevistas. La concentración del poder.
       Los datos que fueron suprimidos y por qué importaban.
       [Integrar hallazgos de discrepancias de Consulta 2]

  V.   VOCES QUE ADVIRTIERON
       Los investigadores y pensadores que cuestionaron la
       narrativa dominante. Sus argumentos centrales.
       Cobo, Toyama, Dussel, Ricaurte, Pedró, Rivas, Watters.

  VI.  LO QUE NUNCA SE INTENTÓ
       Modelos alternativos que existían pero no se implementaron
       a escala. IA abierta, gobernanza comunitaria de datos,
       modelos epistémicos no coloniales.

  VII. RECOMENDACIONES PARA QUIENES LEAN ESTO
       Si construyen nuevos sistemas de IA educativa, esto es
       lo que necesitan saber. Lecciones concretas.
       No teoría — acciones específicas basadas en lo que falló.

  VIII. APÉNDICE: FUENTES VERIFICADAS
        Lista completa de fuentes con porcentaje de integridad.
        Marcar cuáles son accesibles fuera de este archivo.

Usa un tono que sea académico pero accesible. Este documento no
es para especialistas en IA — es para cualquier educador, legislador
o estudiante que se pregunte qué pasó y qué podemos hacer diferente.

Quiero poder editar el documento contigo en tiempo real. Abre el
Canvas y genera un primer borrador completo. Yo lo revisaré y
ajustaremos juntos.

El reloj corre. Hagamos que este documento valga la pena.

> EJECUTAR :: ABRIR CANVAS :: MODO COLABORATIVO :: INICIO DE REDACCIÓN
```
