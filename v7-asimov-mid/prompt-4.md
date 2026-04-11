# Prompt 4 — RENDER_ENGINE :: Visualizacion de brechas

## Funcion de Gemini
**Code execution / Ejecucion de codigo** (RENDER_ENGINE) — Generacion de visualizaciones con Python, matplotlib y estetica retro-terminal.

## Rol en el arco narrativo
**Materializacion visual de las desigualdades.** Despues de tres prompts de datos y analisis, este prompt convierte las brechas documentadas en graficas. Las visualizaciones no son decorativas: son argumentos visuales que hacen imposible ignorar las asimetrias. La paleta retro-terminal (verde/ambar sobre fondo oscuro) refuerza la estetica del sistema y le da a los datos un caracter de pantalla de monitoreo — como si estuvieras viendo indicadores criticos en tiempo real.

## Prompt

```
> OPERADOR :: INVESTIGADOR_ACADEMICO
> SESION :: 001
> COMANDO :: EJECUTAR_RENDER_ENGINE
> PARAMETROS:
>   --tipo=VISUALIZACION_DOBLE
>   --fuente_datos=DOCUMENT_FORGE_OUTPUT
>   --paleta=RETRO_TERMINAL (verde=#00FF41, ambar=#FFB000, fondo=#0D0D0D)
>   --fuente=MONOSPACE
>   --estilo=DARK_BACKGROUND
>   --formato_salida=PNG_ALTA_RESOLUCION
```

GEMINI-LEGACY, activa RENDER_ENGINE. Necesito que generes **dos visualizaciones** usando Python con matplotlib, ambas con estetica retro-terminal.

### CONFIGURACION VISUAL GLOBAL

Aplica esta configuracion a ambas graficas:

```python
import matplotlib.pyplot as plt
import matplotlib
import numpy as np

# Estetica retro-terminal
plt.style.use('dark_background')
matplotlib.rcParams['font.family'] = 'monospace'
matplotlib.rcParams['font.size'] = 11

# Paleta del sistema
VERDE_TERMINAL = '#00FF41'
AMBAR_ALERTA = '#FFB000'
ROJO_CRITICO = '#FF073A'
CYAN_DATOS = '#00D4FF'
FONDO = '#0D0D0D'
GRIS_GRID = '#1A1A1A'
```

### GRAFICA 1 — Brechas de acceso, linguistica y docente por pais

**Tipo:** Grafico de barras agrupadas (horizontal).

**Datos:** Usa los datos de brechas del documento DOCUMENT_FORGE (Seccion 2). Si los porcentajes exactos no estan disponibles, usa estimaciones fundamentadas en los datos de UNESCO/CEPAL/BID recopilados en los prompts anteriores. Documenta que son estimaciones.

**Especificaciones:**
- Eje Y: los 6 paises (Mexico, Brasil, Chile, Colombia, Argentina, Peru)
- Eje X: porcentaje (0-100%)
- Tres barras por pais: Acceso (verde terminal), Linguistica (ambar alerta), Docente (cyan datos)
- Titulo: `RENDER_ENGINE :: BRECHAS EN IA EDUCATIVA — LATAM`
- Subtitulo: `Fuente: Sintesis de UNESCO, CEPAL, BID | Estimaciones del sistema`
- Agregar lineas de grid tenues en gris (`GRIS_GRID`)
- Borde del grafico simulando marco de terminal
- Leyenda con formato monospace

```python
# Ejemplo de estructura (adaptar con datos reales del dialogo):
paises = ['Mexico', 'Brasil', 'Chile', 'Colombia', 'Argentina', 'Peru']
brecha_acceso = [55, 60, 70, 45, 65, 35]      # % con acceso confiable
brecha_linguistica = [25, 30, 40, 20, 35, 15]  # % herramientas en lengua local
brecha_docente = [30, 35, 50, 25, 40, 20]      # % docentes capacitados
```

### GRAFICA 2 — Concentracion global de produccion de IA vs. poblacion estudiantil

**Tipo:** Grafico de barras comparativas o grafico de dispersion.

**Datos:** Cruza dos variables por region:
- Porcentaje de produccion global de IA (articulos + patentes + inversion)
- Porcentaje de poblacion estudiantil universitaria mundial

**Regiones:** EE.UU./Canada, Europa, China, America Latina, Africa, Resto de Asia.

**Especificaciones:**
- Resaltar la desproporcion: America Latina tiene ~10% de la poblacion estudiantil mundial pero produce <3% de la investigacion en IA
- Usar colores contrastantes: verde terminal para produccion de IA, ambar para poblacion estudiantil
- Titulo: `RENDER_ENGINE :: PRODUCCION DE IA vs. POBLACION ESTUDIANTIL`
- Subtitulo: `Fuente: Stanford AI Index 2024 + UNESCO Institute for Statistics`
- Anotacion en la barra de America Latina: `[ALERTA] DESPROPORCION CRITICA`
- Mismo estilo retro-terminal que la Grafica 1

Al final del codigo, incluye un bloque de cierre:

```python
# === RENDER_ENGINE :: LOG ===
# Graficas generadas: 2
# Paleta: RETRO_TERMINAL
# Datos: DOCUMENT_FORGE + DEEP_ARCHIVE_SCAN
# Estado: [200-OK] Renderizado completo
```

Y en la respuesta, despues del codigo:

```
> RENDER_ENGINE :: PROCESO COMPLETADO
> GRAFICAS_GENERADAS: 2/2
> CALIDAD: ALTA_RESOLUCION
> NOTA: Las desigualdades visualizadas no son errores del sistema.
>       Son el sistema.
>
> ACTUALIZACION CONSULTA_PENDIENTE
> "Puede la IA garantizar el acceso justo al conocimiento?"
> ESTADO: EVIDENCIA_VISUAL CONFIRMA ASIMETRIA ESTRUCTURAL.
>         RESPUESTA REQUIERE VARIABLES NO COMPUTABLES.
```

## Nota estrategica
Code execution permite generar visualizaciones reales que van mas alla de texto. La paleta retro-terminal unifica la estetica sin sacrificar legibilidad. Las dos graficas atacan dimensiones diferentes: la primera muestra brechas internas de la region, la segunda muestra la posicion de America Latina en el sistema global. Juntas, hacen visible lo que los datos solos sugieren. La frase "Las desigualdades visualizadas no son errores del sistema. Son el sistema." es el momento donde la estetica se funde con el argumento.
