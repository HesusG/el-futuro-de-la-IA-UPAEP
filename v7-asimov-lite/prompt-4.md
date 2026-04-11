# Prompt 4 — Visualizacion comparativa (grafica retro)

## Prompt (4 de 5)

```
> CONSULTA_ARCHIVO #004
> ESTADO_SESIÓN: ACTIVA
> MÓDULO: RENDER_ENGINE

════════════════════════════════════════════════
 GENERAR_GRÁFICA :: COMPARATIVO REGIONAL
════════════════════════════════════════════════

SOLICITUD: Generar visualización comparativa del acceso
digital educativo en América Latina.

PAÍSES A INCLUIR:
  > México
  > Colombia
  > Brasil
  > Chile
  > Perú
  > Argentina

VARIABLES:
  > Penetración de internet en instituciones de educación
    superior (% de universidades con conectividad estable)
  > Porcentaje de estudiantes universitarios con acceso a
    herramientas de IA en su institución
  > Inversión pública en tecnología educativa como % del
    presupuesto de educación superior

ESPECIFICACIONES TÉCNICAS DE RENDERIZADO:
  > Biblioteca: matplotlib
  > Estilo: terminal retro / fósforo verde
  > Paleta de colores:
    - Fondo: #0D0D0D (negro profundo)
    - Datos primarios: #00FF41 (verde fósforo)
    - Datos secundarios: #00CC33 (verde medio)
    - Datos terciarios: #008F11 (verde oscuro)
    - Texto y ejes: #00FF41
    - Cuadrícula: #003B00 (verde muy tenue)
  > Fuente: monospace
  > Incluir encabezado en la gráfica:
    "GEMINI-LEGACY v2.26.04 :: RENDER_ENGINE"
  > Incluir nota al pie con fuentes de los datos

NOTA: Si los datos exactos no están disponibles en las
fuentes, utilizar las estimaciones más recientes de ITU,
CEPAL o Banco Mundial, indicando el año del dato.

> EJECUTAR_RENDERIZADO...
```

## Herramienta de Gemini utilizada

**Code Execution** (RENDER_ENGINE) — Gemini ejecutará código Python con matplotlib para generar una gráfica con estética retro-terminal. La paleta de colores especificada (verdes sobre negro) mantiene la coherencia visual con el concepto de terminal de fósforo. Se solicitan datos reales de fuentes verificables.

## Rol en el arco narrativo

**Evidencia visual y demostración técnica.** Después de tres prompts textuales densos, la gráfica cumple dos funciones: (1) ofrece una pausa visual en el diálogo que lo hace más dinámico para el evaluador, y (2) traduce las brechas discutidas en prompts anteriores a una representación comparativa concreta. El estilo retro de la gráfica refuerza la coherencia estética sin distraer del contenido: los datos son reales, la paleta es temática. Además, demuestra el uso de Code Execution como herramienta de Gemini, diversificando las capacidades mostradas en el diálogo.
