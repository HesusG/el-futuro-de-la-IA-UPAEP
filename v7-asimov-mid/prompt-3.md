# Prompt 3 — DOCUMENT_FORGE :: Tabla comparativa de funciones de IA en educacion

## Funcion de Gemini
**Canvas** (DOCUMENT_FORGE) — Creacion de documento estructurado y editable con analisis comparativo regional.

## Rol en el arco narrativo
**Consolidacion y estructura.** Los Prompts 1 y 2 generaron datos en bruto y analisis. Ahora el operador ordena al sistema construir un documento de referencia: una tabla comparativa que organice las funciones de la IA en educacion por pais, nivel de implementacion y evidencia de impacto. Este es el momento donde la informacion se convierte en herramienta de consulta. Tambien establece el contraste necesario para las visualizaciones del Prompt 4.

## Prompt

```
> OPERADOR :: INVESTIGADOR_ACADEMICO
> SESION :: 001
> COMANDO :: INICIAR_DOCUMENT_FORGE
> PARAMETROS:
>   --tipo_documento=TABLA_COMPARATIVA_REGIONAL
>   --paises=MEXICO+BRASIL+CHILE+COLOMBIA+ARGENTINA+PERU
>   --categorias=FUNCION_IA+IMPLEMENTACION+EVIDENCIA+BRECHA
>   --formato=DOCUMENTO_ESTRUCTURADO_CON_SECCIONES
>   --incluir_fuentes=TRUE
>   --optimizar_para=CONSULTA_RAPIDA
```

GEMINI-LEGACY, activa el modulo DOCUMENT_FORGE. Necesito que construyas un **documento comparativo estructurado** sobre como seis paises de America Latina estan integrando la IA en sus sistemas educativos.

### ESPECIFICACIONES DEL DOCUMENTO

**Titulo del documento:**
`REGISTRO COMPARATIVO :: IA EN EDUCACION SUPERIOR — AMERICA LATINA (2020-2026)`

**Seccion 1 — Matriz de funciones por pais**

Construye una tabla con las siguientes columnas:
- **Pais**
- **Funcion de IA predominante** (tutoria, investigacion, evaluacion, acceso, administracion)
- **Herramientas/plataformas principales** en uso
- **Nivel de implementacion** (PILOTO / PARCIAL / AMPLIO / POLITICA_NACIONAL)
- **Evidencia de impacto** (DOCUMENTADA / LIMITADA / AUSENTE)
- **Marco regulatorio** (EXISTENTE / EN_DESARROLLO / AUSENTE)

Paises: Mexico, Brasil, Chile, Colombia, Argentina, Peru.

**Seccion 2 — Analisis de brechas**

Para cada pais, documenta:
- **Brecha de acceso**: porcentaje de estudiantes universitarios con acceso confiable a herramientas de IA
- **Brecha linguistica**: disponibilidad de herramientas en lenguas locales (espanol regional, portugues, lenguas indigenas)
- **Brecha de formacion docente**: existencia de programas de capacitacion en IA para profesores

Usa el formato de barra de progreso del sistema para representar visualmente cada brecha:
```
ACCESO     ████████░░░░░░░░ 50%
LINGUISTICA ███░░░░░░░░░░░░░ 20%
DOCENTE    █████░░░░░░░░░░░ 35%
```

**Seccion 3 — Iniciativas destacadas**

Para cada pais, identifica 1-2 iniciativas concretas que representen esfuerzos por construir IA educativa con perspectiva regional (no solo adopcion de herramientas del Norte Global). Incluye: nombre, institucion responsable, objetivo y estado actual.

**Seccion 4 — Diagnostico del sistema**

Cierra el documento con un diagnostico general del sistema en formato de reporte:

```
> DIAGNOSTICO_GENERAL :: DOCUMENT_FORGE
> ═══════════════════════════════════════════
> PATRON DOMINANTE: [identificar]
> RIESGO PRINCIPAL: [identificar]
> OPORTUNIDAD NO EXPLOTADA: [identificar]
> PAIS CON MAYOR AVANCE REGULATORIO: [identificar]
> PAIS CON MAYOR BRECHA: [identificar]
> ═══════════════════════════════════════════
> NOTA: Los datos de esta tabla alimentaran RENDER_ENGINE
>        en la siguiente consulta.
```

Y actualiza el log:

```
> ACTUALIZACION CONSULTA_PENDIENTE
> "Puede la IA garantizar el acceso justo al conocimiento?"
> ESTADO: PATRON EMERGENTE — EL ACCESO DEPENDE MAS DE POLITICA
>         PUBLICA QUE DE CAPACIDAD TECNOLOGICA.
>         RESPUESTA AUN INCOMPLETA.
```

## Nota estrategica
Canvas es ideal para documentos estructurados y editables. Este prompt lo usa para crear una pieza de referencia que organiza datos dispersos en formato consultable. Las barras de progreso de las brechas cumplen doble funcion: son estetica terminal Y visualizacion de datos. La nota al final del diagnostico crea continuidad narrativa: los datos de este documento alimentan las graficas del Prompt 4. La consulta pendiente sigue acumulando evidencia sin resolverse.
