# Prompt 2 — LIVE_NET_QUERY :: Funciones y riesgos emergentes de la IA en educacion

## Funcion de Gemini
**Search grounding / Fundamentacion con busqueda** (LIVE_NET_QUERY) — Consulta con datos en tiempo real sobre el estado actual de la IA en la educacion latinoamericana.

## Rol en el arco narrativo
**Actualizacion en tiempo real del sistema.** Despues del escaneo historico del Prompt 1, el operador ordena una consulta en vivo para traer datos actuales. Aqui el dialogo pasa de los archivos al presente: que funciones cumple la IA hoy para estudiantes y docentes en America Latina, y que riesgos estan emergiendo. La tension entre utilidad y riesgo prepara el terreno para la comparacion estructurada del Prompt 3.

## Prompt

```
> OPERADOR :: INVESTIGADOR_ACADEMICO
> SESION :: 001
> COMANDO :: LIVE_NET_QUERY
> PARAMETROS:
>   --incluir_datos_en_tiempo_real
>   --region=LATAM
>   --periodo=2020-2026
>   --fuentes_prioritarias=UNESCO+IESALC+BID+CEPAL+INVESTIGACIONES_RECIENTES
>   --categorizar_por=FUNCION+RIESGO
>   --alertas_sesgo=ACTIVADAS
```

GEMINI-LEGACY, cambia de modo archivo a modo consulta en vivo. Necesito un analisis actualizado sobre las **funciones concretas que la IA ha cumplido para estudiantes y academicos en America Latina** entre 2020 y 2026, junto con los **riesgos emergentes** que se estan documentando.

Estructura la respuesta en dos bloques:

**BLOQUE A — FUNCIONES DOCUMENTADAS**

Para cada funcion, incluye: descripcion, herramientas especificas utilizadas, evidencia de impacto (si existe) y al menos un caso o dato regional. Las funciones minimas a cubrir:

1. **Tutoria personalizada y apoyo al aprendizaje** — Chatbots educativos, sistemas adaptativos. Que evidencia hay de su efectividad en contextos latinoamericanos?
2. **Asistencia en investigacion y produccion academica** — Busqueda de literatura, sintesis, revision de textos. Como ha cambiado el flujo de trabajo academico?
3. **Traduccion y acceso linguistico** — Herramientas de traduccion para comunidades multilingues. Limites con lenguas indigenas.
4. **Evaluacion y retroalimentacion automatizada** — Sistemas de calificacion, deteccion de plagio, retroalimentacion formativa.
5. **Acceso a contenido educativo** — Plataformas adaptativas, recursos abiertos mejorados con IA.

**BLOQUE B — RIESGOS EMERGENTES**

Documenta con la misma estructura:

1. **Dependencia tecnologica y concentracion corporativa** — Quien controla las plataformas que usan las universidades?
2. **Erosion del pensamiento critico** — Evidencia sobre el uso acritico de IA generativa por estudiantes.
3. **Brecha digital amplificada** — La IA beneficia mas a quien ya tiene acceso. Datos sobre desigualdad de acceso en la region.
4. **Sesgo algoritmico en contextos educativos** — Casos documentados de discriminacion por genero, etnia, idioma.
5. **Privatizacion del conocimiento** — El riesgo de que la IA convierta el acceso al saber en servicio de suscripcion.

Para cada riesgo, asigna un nivel de alerta del sistema:
```
[ALERTA-BAJA]    — Riesgo identificado, impacto limitado
[ALERTA-MEDIA]   — Riesgo documentado, impacto creciente
[ALERTA-ALTA]    — Riesgo estructural, requiere accion inmediata
[ALERTA-CRITICA] — Riesgo existencial para la equidad educativa
```

Cierra con una actualizacion del log del sistema:

```
> ACTUALIZACION CONSULTA_PENDIENTE
> "Puede la IA garantizar el acceso justo al conocimiento?"
> ESTADO: EVIDENCIA_CONTRADICTORIA — FUNCIONES POSITIVAS COEXISTEN
>         CON RIESGOS ESTRUCTURALES. RESPUESTA AUN NO COMPUTABLE.
```

## Nota estrategica
Este prompt activa Search grounding para fundamentar cada afirmacion con datos actuales. La estructura dual (funciones vs. riesgos) evita tanto el tecno-optimismo como el catastrofismo: obliga al sistema a documentar ambos lados con evidencia. Los niveles de alerta del sistema le dan al contenido critico una urgencia visual que refuerza la estetica terminal sin sacrificar rigor. La actualizacion de la consulta pendiente avanza la narrativa de Asimov.
