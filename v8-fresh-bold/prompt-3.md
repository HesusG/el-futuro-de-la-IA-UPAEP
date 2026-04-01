# Prompt 3 — Tercer testigo y Code Execution

## Funcion de Gemini activada
Code execution (calculo de escenarios proyectivos)

## Rol en el arco narrativo
**Desarrollo.** El tono cambia de lo emocional a lo cuantitativo. Un estudiante de ingenieria en Sao Paulo presenta datos. Se pide a Gemini que ejecute codigo para modelar tres escenarios de adopcion de IA en universidades latinoamericanas. Este prompt demuestra que el dialogo puede ser analitico, no solo narrativo.

## Texto del prompt

```
Tercer testigo ante el Tribunal.

Rafael Oliveira dos Santos, 25 anos, estudiante de Ingenieria de Sistemas en la Universidade de Sao Paulo. Rafael trabaja medio tiempo como desarrollador y ha construido tres herramientas de IA para su facultad. Declara:

"Yo no uso IA. Yo construyo IA. Y lo que veo me preocupa, pero no por las razones que dice el Fiscal. El problema no es que los estudiantes usen chatbots para hacer tareas. El problema es que las universidades no entienden que la IA cambio lo que significa 'saber algo'. Seguimos evaluando memorizacion en la era de la recuperacion instantanea. Es como si en 1995 las universidades prohibieran las calculadoras en los examenes de ingenieria. Ah, esperen — muchas todavia lo hacen."

El Tribunal necesita salir de los testimonios cualitativos y entrar en numeros. Le pido al Tribunal que modele tres escenarios usando codigo ejecutable:

**Escenario A — Inercia:** Las universidades latinoamericanas mantienen sus modelos pedagogicos actuales. La adopcion de IA ocurre de forma informal y no regulada. Modela: ¿que porcentaje de evaluaciones tradicionales (examenes escritos, ensayos individuales) seran vulnerables a IA generativa para 2030, asumiendo la curva de mejora actual de los modelos?

**Escenario B — Adaptacion:** Las universidades redisenan el 50% de sus evaluaciones para integrar IA como herramienta permitida. Modela: ¿cual seria el costo estimado de capacitacion docente para 1,000 universidades latinoamericanas, usando datos reales de programas de formacion docente en tecnologia?

**Escenario C — Bifurcacion:** Las universidades de elite adoptan IA plenamente. Las universidades publicas masivas no. Modela: ¿como se amplifica la brecha de empleabilidad entre graduados en 5 anos, usando como proxy la brecha salarial actual entre graduados de universidades privadas y publicas en Brasil, Mexico y Colombia?

Genera el codigo, ejecutalo, y que el Tribunal interprete los resultados. El Juez debe ser esceptico con las proyecciones. El Fiscal debe usar el Escenario C como evidencia. La Defensa debe apostar por el Escenario B.
```

## Por que funciona este prompt
- Cambia radicalmente el registro: de testimonios personales a modelado cuantitativo — demuestra rango creativo
- El testimonio de Rafael articula el argumento epistemologico central: la IA cambia la definicion misma de conocimiento
- La analogia de la calculadora es memorable y accesible — ancla un argumento complejo en algo concreto
- Los tres escenarios son modelables y piden datos reales, lo que activa Code execution con Search grounding simultaneamente
- El pedido de que cada rol del tribunal interprete los datos de forma distinta fuerza perspectivas multiples sobre la misma evidencia
- Es el unico prompt del concurso que va a tener graficas o tablas generadas por codigo — se distingue visualmente
