# Proyecto-6-Bootcamp

•	Objetivo: Análisis de Datos de una tienda de videojuegos para identificar patrones que determinen si un juego tiene éxito o no, detectar proyectos prometedores y planificar campañas publicitarias.
•	Librerías usadas: pandas, numpy, matplotlib/seaborn, scipy.stats y/o statsmodels; posible uso de sklearn para transformaciones o modelado simple.

•	Carga de datos y tipos:
o	Lectura de CSV/TSV (ruta relativa o absoluta).
o	Renombrado y normalización de columnas (IDs a str, timestamps a datetime).
o	Creación de columnas derivadas: event_date, event_hour, flags/banderas y agregados por usuario.

•	Preprocesamiento:
o	Filtrado por rango de fechas y condiciones de negocio.
o	Eliminación o manejo de duplicados y nulos (dropna / fillna según celdas).
o	Uso de groupby/pivot_table para agregados por usuario, evento y variante.

•	Análisis exploratorio (EDA):
o	Conteos totales de eventos y usuarios únicos; cálculo de eventos promedio por usuario.
o	Distribuciones temporales (por día/hora), visualizaciones tipo histogramas y barplots.
o	Construcción de embudo de eventos: usuarios únicos por etapa y tasas de conversión entre pasos.

•	Experimentación / tests:
o	Identificación de variantes/exp_id y conteo de usuarios por grupo.
o	Tests de proporciones (z-test / proportions_ztest) para comparar conversiones entre grupos; p-values calculados y decisiones con alpha (probablemente 0.05).
o	Tablas resumen de p-values por evento y, en su caso, conclusiones de aceptación/rechazo.

•	Output y conclusiones:
o	Tablas y gráficos que sintetizan usuarios por evento, conversion rates y resultados de tests.
o	Conclusiones operativas y recomendaciones derivadas del análisis.

