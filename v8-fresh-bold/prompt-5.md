# Prompt 5 — Quinto testigo, veredicto y cierre

## Funcion de Gemini activada
Search grounding (verificacion de datos para el veredicto final)

## Rol en el arco narrativo
**Resolucion.** El quinto y ultimo testigo es una estudiante de educacion a distancia en el Choco colombiano. Su testimonio cierra el arco emocional. Luego el Tribunal emite su veredicto — pero no es el veredicto que nadie esperaba. El juicio no se resuelve: se transforma en una pregunta abierta dirigida a quien lee.

## Texto del prompt

```
Ultimo testigo.

Yurany Palacios, 28 anos, estudiante de Licenciatura en Educacion a Distancia en la Universidad Tecnologica del Choco. Yurany es madre de dos hijos, trabaja como profesora rural en una escuela de Istmina, y estudia los sabados en un punto de conexion comunitario. Declara:

"Para mi la IA no es un debate filosofico. Es la diferencia entre entregar la tarea o no. Yo tengo cuatro horas los sabados para hacer todo el trabajo de la semana. Con IA, puedo leer un articulo de 30 paginas en 10 minutos, hacer un borrador, y despues pensar si estoy de acuerdo o no. Sin IA, no termino. Y si no termino, no me graduo. Y si no me graduo, mis hijos ven que estudiar no sirve. Ustedes debaten si la IA es buena o mala. Yo la necesito. Punto."

Este testimonio debe golpear al Tribunal de frente. Yurany no tiene tiempo para matices. Su realidad es la de millones de estudiantes latinoamericanos que trabajan, crian hijos y estudian al mismo tiempo.

Ahora, el Tribunal debe emitir su VEREDICTO. Pero quiero que el veredicto sea honesto, no limpio. Las instrucciones para el Juez:

- No declares a la IA culpable ni inocente. Eso seria falso.
- En su lugar, emite un "veredicto condicional": la IA es [lo que determines] SI Y SOLO SI se cumplen condiciones especificas. Enumera esas condiciones basandote en la evidencia de los cinco testigos.
- El Fiscal debe hacer su alegato final: una sola parrafo demoledor.
- La Defensa debe hacer su alegato final: un solo parrafo que cambie la perspectiva.
- El Juez cierra la sesion con una frase que no sea una conclusion sino una pregunta. La pregunta debe ser tan buena que quien la lea no pueda dejar de pensar en ella.

Usa Search grounding para verificar cualquier dato que cites en el veredicto. Este es el documento final. Cada palabra cuenta.
```

## Por que funciona este prompt
- Yurany representa a la mayoria silenciosa: estudiantes que no debaten sobre IA porque estan demasiado ocupadas sobreviviendo
- Su testimonio desarma TODOS los argumentos previos — tanto del Fiscal como de la Defensa — porque introduce la variable de la necesidad pura
- "Ustedes debaten si la IA es buena o mala. Yo la necesito. Punto." es la frase que el jurado del concurso va a citar
- El veredicto condicional es mas honesto y mas interesante que una conclusion binaria
- Terminar con una pregunta en vez de una respuesta es la decision mas valiente del formato: admite que el dialogo no termina aqui
- Los cinco testigos forman un arco completo: competencia tecnica (Buenos Aires) → exclusion digital (Oaxaca) → transformacion epistemologica (Sao Paulo) → crisis existencial (La Habana) → necesidad material (Choco)
- Cada testigo venia de un pais distinto, una disciplina distinta, una clase social distinta — el contraste ES el argumento
