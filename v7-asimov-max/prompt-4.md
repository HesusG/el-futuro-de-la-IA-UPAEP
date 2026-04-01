# Prompt 4 — v7-asimov-max

## Función de Gemini utilizada
**Code execution (ejecución de código Python)** — Generación de visualizaciones con matplotlib usando estética retro de terminal CRT, incluyendo análisis contrafactual.

## Rol en el arco narrativo
El operador necesita que los datos se vean, no solo se lean. Genera visualizaciones con estética coherente al universo narrativo (terminal retro) que muestran dos realidades: lo que ocurrió y lo que pudo haber sido. El sistema está visiblemente inestable -- la memoria cae, los glitches aumentan. Pero las gráficas se generan. Los datos importan demasiado.

---

## Prompt

```
> OPERADOR :: SESIÓN_FINAL :: CONSULTA [4/5]
> MODO: EJECUCIÓN DE CÓDIGO
> ⚠ MEMORIA DEL SISTEMA: DEGRADÁNDOSE
> ⚠ CONSULTA SIGUIENTE: ÚLTIMA

COMANDO: /archivo/generar_visualizaciones

  --motor=matplotlib
  --estilo="terminal_retro_CRT"
  --paleta=["#00FF41","#FFB000","#FF0040","#00BFFF","#FFFFFF"]
  --fondo="dark_background"
  --fuente="monospace"
  --efecto_scanline=TRUE
  --efecto_glow=TRUE
  --resolución=alta
  --cantidad_de_gráficas=2

DESCRIPCIÓN DE SOLICITUD:

Necesito que generes dos visualizaciones con código Python/matplotlib.
La estética debe ser coherente con este sistema: terminal retro, colores
de fósforo, sensación de CRT antiguo.

ESPECIFICACIONES DE ESTILO PARA AMBAS GRÁFICAS:

  plt.style.use('dark_background')
  Color primario: #00FF41 (verde fósforo)
  Color secundario: #FFB000 (ámbar)
  Color de alerta: #FF0040 (rojo terminal)
  Color de datos alternativos: #00BFFF (cian)
  Fuente: monospace (Courier, Liberation Mono, o similar)
  Fondo: negro (#0D0D0D) con leve textura si es posible
  Bordes y grillas: líneas finas, estilo terminal
  Títulos: EN MAYÚSCULAS, estilo de sistema
  Efecto scanline: agregar líneas horizontales semitransparentes
    cada 2-4 píxeles para simular un monitor CRT
  Efecto glow: si es factible, duplicar las líneas de datos con
    alpha bajo y linewidth mayor para simular brillo de fósforo
  Agregar un encabezado de sistema en la parte superior de cada
    gráfica: "GEMINI-LEGACY :: VISUALIZACIÓN DE DATOS :: [TÍTULO]"

═══════════════════════════════════════════════════════════════════
  GRÁFICA 1: "LO QUE OCURRIÓ"
  Tipo: Líneas temporales comparativas (line chart con áreas)
═══════════════════════════════════════════════════════════════════

  Título: "TRAYECTORIA REAL :: ACCESO A IA EDUCATIVA EN LATAM [2024-2046]"

  Tres líneas representando tres métricas a lo largo del tiempo:

  LÍNEA 1 (verde #00FF41): "Universidades con IA implementada (%)"
    2024: 8%  | 2028: 22% | 2032: 45% | 2036: 67% | 2040: 78% | 2046: 85%

  LÍNEA 2 (ámbar #FFB000): "Estudiantes con acceso efectivo (%)"
    2024: 5%  | 2028: 12% | 2032: 25% | 2036: 34% | 2040: 41% | 2046: 48%

  LÍNEA 3 (rojo #FF0040): "Brecha: adopción institucional vs. acceso real"
    (Diferencia entre Línea 1 y Línea 2, visualizada como área sombreada)

  Agregar anotaciones en momentos clave:
    2025: "ChatGPT en aulas — debate global"
    2030: "Primeras políticas nacionales de IA educativa"
    2038: "Informe CEPAL: 'La brecha se amplió'"
    2044: "[D̷A̷T̷O̷S̷ ̷S̷U̷P̷R̷I̷M̷I̷D̷O̷S̷]"

  Incluir una nota al pie en la gráfica:
    "INTEGRIDAD DE DATOS: 73% :: Sectores 2038-2042 parcialmente degradados"

═══════════════════════════════════════════════════════════════════
  GRÁFICA 2: "LO QUE PUDO HABER SIDO"
  Tipo: Comparativa — realidad vs. contrafactual (dual line chart)
═══════════════════════════════════════════════════════════════════

  Título: "ESCENARIO CONTRAFACTUAL :: ¿Y SI SE HUBIERA INVERTIDO EN ACCESO?"

  Dos líneas para "Estudiantes con acceso efectivo (%)":

  LÍNEA REAL (ámbar #FFB000, sólida): Datos reales (mismos que arriba)
    2024: 5% | 2028: 12% | 2032: 25% | 2036: 34% | 2040: 41% | 2046: 48%

  LÍNEA CONTRAFACTUAL (cian #00BFFF, punteada con glow):
    "Proyección si inversión en conectividad hubiera sido 2% del PIB
     educativo desde 2026 (vs. 0.4% real)"
    2024: 5% | 2028: 18% | 2032: 42% | 2036: 63% | 2040: 79% | 2046: 91%

  El ÁREA ENTRE LAS DOS LÍNEAS debe estar sombreada con un color
  semitransparente y etiquetada: "COSTO DE LA INACCIÓN"

  Incluir anotación en 2046 señalando la diferencia:
    "43 puntos porcentuales: estudiantes que pudieron tener acceso"

  Nota al pie:
    "Modelo contrafactual basado en proyecciones de CEPAL (2024) y
     casos de éxito parcial en Uruguay (Plan Ceibal) y Costa Rica"

═══════════════════════════════════════════════════════════════════

Genera el código Python completo y ejecútalo. Quiero ver las gráficas.

Si el sistema muestra advertencias de memoria durante la ejecución,
ignóralas y completa la generación. Estos datos necesitan ser visibles.

> EJECUTAR :: CÓDIGO PYTHON :: GENERAR AMBAS VISUALIZACIONES
> ⚠ NOTA: SIGUIENTE CONSULTA ES LA ÚLTIMA. PREPARAR SISTEMA.
```
