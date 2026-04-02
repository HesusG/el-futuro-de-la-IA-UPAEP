# Prompt 3 — Tres Testigos + Evidencia Cuantitativa

## Feature: Google Search grounding + Code Execution
## Fuente: v8-fresh-bold (testigos reducidos de 5 a 3) + v5 (curva de Lorenz)
## Posición en el arco: ACTO III — Fase probatoria

---

## Prompt

> AUDIENCIA: 3 de 5
> FASE: TESTIMONIOS Y PRUEBAS PERICIALES

[Aquí el operador responde a la contra-pregunta de P2 — reacción auténtica a la autoconfesión de Gemini.]

El tribunal ha escuchado al acusado. Ahora necesita escuchar a quienes viven las consecuencias. Solicito tres testimonios y una prueba pericial.

**TESTIMONIO 1 — Valentina Rojas, estudiante de Medicina, Buenos Aires:**
Valentina aprendió diagnóstico diferencial con IA generativa. Sacó las mejores notas de su generación. Pero en su primera guardia real, frente a un paciente que lloraba, se quedó paralizada. La IA le enseñó a pensar; nadie le enseñó a estar presente. Busca evidencia reciente sobre el fenómeno de competencia técnica sin competencia humana en la formación mediada por IA.

**TESTIMONIO 2 — Tlali Mendoza, estudiante de Educación Intercultural, Oaxaca:**
Tlali quiere enseñar en comunidades zapotecas. La IA no habla zapoteco. El internet en su comunidad es intermitente. Cuando le pidió a una IA que generara material educativo bilingüe, el resultado fue un español neutro con traducciones literales que ningún hablante reconocería. Busca datos sobre la representación de lenguas indígenas americanas en los modelos de IA y en iniciativas como AmericasNLP.

**TESTIMONIO 3 — Yurany Palacios, estudiante a distancia, Chocó, Colombia:**
Yurany no tiene el lujo de debatir si la IA es buena o mala. La necesita. Es su único acceso a tutoría, a bibliografía, a una explicación que su programa a distancia no le da. "Ustedes debaten. Yo sobrevivo." Busca datos sobre cómo la IA funciona como compensador de desigualdad en contextos de exclusión educativa.

**PRUEBA PERICIAL — Curva de Lorenz de desigualdad educativa en IA:**
Genera código Python que produzca una curva de Lorenz que compare la distribución del acceso a herramientas de IA educativa entre 6 países latinoamericanos (México, Chile, Brasil, Colombia, Argentina, Perú), usando los datos más recientes de conectividad escolar, acceso a dispositivos e inversión en tecnología educativa. Paleta retro CRT: fondo #0D0D0D, verde #00FF41, ámbar #FFB000. Fuentes monoespaciadas. Señala explícitamente qué datos son estimaciones.

Una nota para el Fiscal: soy consciente de una contradicción en mi propio método. Este tribunal critica que la IA hable *por* las comunidades en lugar de *con* ellas — y sin embargo, yo mismo acabo de inventar tres voces ficticias para representar realidades que no son la mía. ¿No estoy replicando el mismo ventriloquismo epistémico que denuncio? Quiero que el Fiscal levante esta objeción y que el tribunal la pondere con la misma severidad que aplica al acusado.

Que el Fiscal, el Defensor y el Juez ponderen los tres testimonios, la objeción metodológica, y la evidencia cuantitativa.

---

## Notas de ejecución
- Dos features en un prompt: Google Search buscará datos actuales para cada testimonio; Code Execution genera la curva de Lorenz
- Si la ejecución del código falla, priorizar los testimonios (el contenido narrativo es más valioso que la gráfica)
- Los tres testigos están elegidos para cubrir el espectro: competencia sin humanidad (Argentina), exclusión lingüística (México), pragmatismo de supervivencia (Colombia)
- "Ustedes debaten. Yo sobrevivo." debe aparecer como línea directa — es la frase más poderosa del repositorio según los 4 jurados
- La contra-pregunta de P3 preparará el terreno para la meta-crítica de P4
