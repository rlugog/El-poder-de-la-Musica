# ¿Tiene la música un efecto en la salud mental?

Este proyecto analiza si la música tiene un impacto percibido en variables como ansiedad, depresión, insomnio y TOC. Se usó el dataset `mxmh_survey.csv` y se aplicaron técnicas estadísticas (Kruskal-Wallis) y visualizaciones (boxplots, violin plots, barplots).

## Objetivo
Explorar si existen diferencias significativas en indicadores de salud mental entre grupos según el efecto percibido de la música: **Improve**, **No effect** y **Worsen**.

## Principales hallazgos
- Se encontraron diferencias significativas en los niveles de **ansiedad** y **depresión**.
- No se hallaron diferencias relevantes en **insomnio** ni **TOC**.
- Las visualizaciones refuerzan que quienes perciben que la música empeora su estado presentan mayores niveles de ansiedad y depresión.

## Herramientas utilizadas
- Python (pandas, seaborn, matplotlib)
- Análisis no paramétrico (Kruskal-Wallis)
- Visualización de datos

## Visualizaciones
![Barplot de medianas](img/barplot_medianas.png)
