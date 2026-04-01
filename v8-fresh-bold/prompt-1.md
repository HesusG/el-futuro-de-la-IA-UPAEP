# Prompt 1 — Apertura del caso y primer testigo

## Funcion de Gemini activada
Search grounding (verificacion de datos en tiempo real)

## Rol en el arco narrativo
**Exposicion.** Establece el universo ficticio, presenta las reglas del tribunal y llama al primer testigo: una estudiante de medicina en Buenos Aires que usa IA para estudiar anatomia y diagnostico. Este prompt debe hacer que Gemini construya el escenario completo y responda en las tres voces.

## Texto del prompt

```
Estamos en Quito, marzo de 2027. Se ha convocado un tribunal interamericano sin precedentes. El caso: "Universidades de America Latina vs. Inteligencia Artificial Generativa". La acusacion: que la IA ha socavado la formacion critica de una generacion de profesionales. La defensa: que la IA ha hecho mas por la equidad educativa en cinco anos que las politicas publicas en cincuenta.

Toma tu rol como el Tribunal. Abre la sesion formalmente.

Luego, recibe al primer testigo: Valentina Rojas, 23 anos, estudiante de sexto ano de medicina en la Universidad de Buenos Aires. Valentina declara lo siguiente:

"Yo aprendi semiologia con un modelo generativo. Le describia sintomas y el me explicaba diagnosticos diferenciales mejor que cualquier libro. Cuando llegue a la residencia, podia recitar patrones de diagnostico perfectamente. Pero la primera vez que un paciente me agarro la mano llorando, me quede en blanco. La IA me enseno a pensar como medica. Nadie me enseno a estar presente como persona."

Quiero que el Juez tome nota de la declaracion, que el Fiscal la use para argumentar que la IA crea profesionales tecnicamente competentes pero humanamente deficientes, y que la Defensa contraargumente con evidencia real — usa datos verificados sobre como la IA ha mejorado el acceso a educacion medica en paises donde hay un medico por cada 5,000 habitantes.

Que cada voz sea claramente distinta. Esto es un juicio, no un ensayo.
```

## Por que funciona este prompt
- Establece un formato radicalmente distinto a cualquier otra entrada del concurso — nadie mas va a presentar un juicio ficticio
- Obliga a Gemini a sostener tres perspectivas simultaneas, lo que demuestra interaccion critica con la IA
- El testimonio de Valentina toca el nucleo del tema: la IA como funcion educativa vs. la formacion humana integral
- El pedido de "evidencia real" activa Search grounding de forma natural
- El tono es a la vez dramatico y academico — exactamente lo que las bases permiten ("tono academico o casual")
