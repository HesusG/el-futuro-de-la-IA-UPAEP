# Prompt 1 — Protocolo de investigacion y revision del paisaje

## Fase metodologica

**[FASE 1 — Revision del paisaje / Exploracion]**

## Funcion en el arco

Prompt fundacional. Establece las reglas del juego: transforma un dialogo de 5 prompts en un protocolo de investigacion formal. Al mismo tiempo, activa Deep Research para ejecutar la primera fase real del protocolo — la revision de literatura. El usuario no pregunta "que sabes sobre X"; propone un experimento colaborativo y define su estructura.

## Funcion de Gemini utilizada

**Deep Research** — Gemini realiza una busqueda exhaustiva y sintetiza el estado del arte, funcionando como la fase de revision bibliografica del protocolo.

## Texto del prompt

```
Propongo un experimento: vamos a co-investigar el futuro de la IA para el desarrollo academico en America Latina, pero no como una conversacion convencional. Quiero que ejecutemos un protocolo de investigacion real en 5 pasos, donde cada uno de mis prompts sea una fase metodologica y cada una de tus respuestas sea un producto de investigacion.

El protocolo es este:

1. Revision del paisaje (ahora) — mapear el estado actual del tema.
2. Formulacion de hipotesis — a partir del mapeo, proponer hipotesis verificables.
3. Analisis de datos — poner a prueba una hipotesis con datos reales.
4. Redaccion de hallazgos — co-escribir la seccion de resultados.
5. Meta-reflexion — evaluar criticamente nuestra propia metodologia.

La tesis es que este dialogo puede ser, simultaneamente, una investigacion SOBRE la IA en educacion Y una DEMOSTRACION de como la IA transforma la investigacion misma.

Para la Fase 1, necesito que uses Deep Research para realizar un mapeo exhaustivo: ¿cual es el estado actual de la integracion de IA en instituciones de educacion superior en America Latina? Busco tendencias, brechas, politicas institucionales, casos de implementacion, y datos sobre adopcion. Organiza los hallazgos como si fuera la seccion de "revision de literatura" de un articulo academico.

Contexto: soy autor de una tesis sobre el modelo "Aula del Futuro" (Future Classroom Lab, 6 zonas de aprendizaje), asi que conozco el terreno de la tecnologia educativa. Dialoguemos como colegas.
```

## Notas estrategicas

- El prompt hace explicito el protocolo completo desde el inicio, lo que permite a Gemini (y al evaluador) anticipar la estructura del dialogo.
- "Co-investigar" establece la relacion de pares, no de usuario-herramienta.
- La mencion de la tesis del usuario aporta credibilidad y contexto para que Gemini calibre el nivel del dialogo.
- Deep Research aqui no es un truco tecnico: es la herramienta natural para una revision de literatura. La forma sigue la funcion.
- La frase "este dialogo puede ser simultaneamente..." planta la semilla de la capa meta que se desarrollara en los prompts 4 y 5.
