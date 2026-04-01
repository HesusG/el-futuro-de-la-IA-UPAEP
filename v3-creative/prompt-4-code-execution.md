# Prompt 4 — Code Execution (Visualización de Datos)

## Feature: Ejecución de código Python (matplotlib)
## Propósito: Fundamentar el argumento con evidencia cuantitativa
## Posición en el arco: EVIDENCIA — hacer visible la brecha con datos

---

## Prompt

Quiero visualizar la tensión entre promesa y brecha. Genera código Python que produzca dos gráficas:

1. Un gráfico de radar que compare la "preparación para IA en educación" de 6 países latinoamericanos (México, Chile, Brasil, Colombia, Argentina, Perú) en 5 dimensiones: conectividad escolar, formación docente en competencias digitales, inversión pública en educación como % del PIB, índice de gobierno digital, y producción académica sobre IA en educación. Usa los datos más recientes disponibles de UNESCO, CEPAL, OCDE y Banco Mundial.

2. Un gráfico de barras agrupadas que muestre la brecha: porcentaje de docentes que han recibido formación en herramientas digitales vs. porcentaje de instituciones que ya están usando IA generativa, en al menos 4 países latinoamericanos. Si los datos exactos no existen para todos los indicadores, usa las mejores aproximaciones disponibles y señala explícitamente cuáles son estimaciones.

Incluye título, fuentes y una nota interpretativa debajo de cada gráfica.

---

## Notas de ejecución
- Gemini ejecutará Python en sandbox con matplotlib (la librería más segura)
- La instrucción de señalar estimaciones demuestra honestidad intelectual
- Si la ejecución falla, simplificar a 1 sola gráfica en el siguiente intento
- El radar chart comunica visualmente la asimetría de preparación entre países
- PROBAR ESTE PROMPT POR SEPARADO antes de la conversación final
