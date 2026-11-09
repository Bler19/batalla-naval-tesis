# Análisis probabilístico y evaluación de estrategias de búsqueda en Batalla Naval

Repositorio del trabajo de grado en Matemáticas desarrollado en la Fundación Universitaria Konrad Lorenz.

## Descripción

Esta investigación analiza y compara tres estrategias de búsqueda en el juego Batalla Naval mediante herramientas de probabilidad, matemática discreta y simulación Monte Carlo.

Las estrategias evaluadas son:

- Conteo de Encajes Consistentes: selecciona disparos a partir del conteo de posibles ubicaciones de barcos compatibles con la información disponible.
- Hunt/Target: combina búsqueda general con disparos dirigidos alrededor de impactos.
- Paridad: utiliza un patrón de búsqueda basado en la paridad de las casillas.

## Metodología

Se realizaron 4682 simulaciones emparejadas sobre tableros de 10 × 10, utilizando una flota de cinco barcos de longitudes 5, 4, 3, 3 y 2.

La investigación incluye análisis estadístico de las diferencias entre estrategias, intervalos de confianza, evaluación de robustez mediante diferentes semillas pseudoaleatorias y análisis de sensibilidad, donde se encuentra que Conteo de Encajes Consistentes presentó el menor promedio de disparos en las condiciones experimentales evaluadas.

## Código fuente

El código completo de las simulaciones y los análisis se encuentra en:

[Consultar notebook de python](Batalla_Naval.ipynb)

Algunas de las gráficas presentadas de realizaron en la herramienta de Microsoft Power BI, pueden ser localizadas en: 

[Consultar informe de Power BI](https://app.powerbi.com/view?r=eyJrIjoiYWNiYTA0NDMtNzVhMC00Y2FhLTkzMmYtODViM2RiZTBiYzUyIiwidCI6IjI5OWEyODgxLTEzODAtNDAyMC1iNDJmLTcxNWEzNWUxYmNhZiIsImMiOjR9)


## Documento de investigación

[Consultar tesis completa en PDF](Batalla_Naval_Tesis.pdf)

## Uso de inteligencia artificial

Durante el desarrollo de la investigación se utilizó ChatGPT como herramienta de apoyo para tareas de revisión lingüística, programación y preparación del documento en LaTeX.

La declaración completa de uso de inteligencia artificial se incluye en el documento académico.

## Institución

Fundación Universitaria Konrad Lorenz — Programa de Matemáticas.
