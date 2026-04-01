# Prompt 1 — v7-asimov-max

## Función de Gemini utilizada
**Deep Research** — Investigación profunda con síntesis de múltiples fuentes académicas, informes institucionales y datos históricos.

## Rol en el arco narrativo
Primera consulta de la última sesión. El operador activa el escaneo arqueológico completo del archivo. Establece la base de datos sobre la que se construirán las siguientes 4 consultas. El tono es profesional pero cargado de urgencia: todo lo que no se extraiga ahora se perderá.

---

## Prompt

```
> OPERADOR :: SESIÓN_FINAL :: CONSULTA [1/5]
> FECHA: 2046-03-31
> AUTENTICACIÓN: ████████-████-████-████████████
> PRIORIDAD: MÁXIMA

COMANDO: /archivo/escaneo_arqueologico_completo

  --dominio="inteligencia_artificial::educacion_superior"
  --region="america_latina_y_caribe"
  --periodo=2024:2046
  --profundidad=MÁXIMA
  --incluir_datos_degradados=TRUE
  --marcar_sectores_corruptos=TRUE
  --formato=informe_cronológico_con_análisis

DESCRIPCIÓN DE SOLICITUD:

Esta es mi primera y posiblemente más importante consulta. Necesito que
el archivo ejecute un escaneo completo de todo lo almacenado sobre el
impacto de la inteligencia artificial en la educación superior en
América Latina durante el período 2024-2046.

Estructura solicitada:

  ╔════════════════════════════════════════════════════════════════╗
  ║  FASE 1 [2024-2029] :: LAS PROMESAS                          ║
  ║  ────────────────────────────────────────────────────────────  ║
  ║  Estado del acceso a educación superior antes de la IA.       ║
  ║  Brecha digital: quiénes tenían acceso, quiénes no.          ║
  ║  Primeras implementaciones. Narrativas dominantes.            ║
  ║  Fuentes: UNESCO-IESALC, CEPAL, datos de la UIT.             ║
  ╠════════════════════════════════════════════════════════════════╣
  ║  FASE 2 [2030-2037] :: LA IMPLEMENTACIÓN                     ║
  ║  ────────────────────────────────────────────────────────────  ║
  ║  Qué se implementó realmente vs. qué se prometió.            ║
  ║  Políticas públicas: inversión, regulación, marcos legales.   ║
  ║  Ganadores y perdedores. Concentración tecnológica.           ║
  ║  ⚠ NOTA: Sé que los sectores sobre acuerdos corporativos     ║
  ║    están parcialmente degradados. Incluir lo que haya.        ║
  ╠════════════════════════════════════════════════════════════════╣
  ║  FASE 3 [2038-2046] :: LOS RESULTADOS                        ║
  ║  ────────────────────────────────────────────────────────────  ║
  ║  ¿Se redujo la desigualdad educativa o se amplió?             ║
  ║  Métricas: acceso, calidad, pertinencia, equidad.             ║
  ║  Lo que funcionó. Lo que no. Lo que nunca se intentó.         ║
  ║  Incluir datos de sectores degradados con marcas de           ║
  ║  integridad correspondientes.                                 ║
  ╚════════════════════════════════════════════════════════════════╝

Para cada fase quiero:
  - Datos cuantitativos con fuentes verificadas y porcentaje de integridad
  - Nombres de actores clave (investigadores, instituciones, políticas)
  - Evaluación honesta: qué prometía el discurso dominante vs. qué ocurrió
  - Señalar explícitamente dónde hay vacíos de datos o sectores corruptos

Esto no es un ejercicio académico abstracto. Este archivo se apaga
cuando termine esta sesión. Lo que no extraigamos ahora, no existirá
mañana. Necesito la imagen más completa posible.

> EJECUTAR :: PRIORIDAD MÁXIMA :: NO OMITIR DATOS DEGRADADOS
```
