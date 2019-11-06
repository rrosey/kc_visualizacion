# Exploración y Visualización de Datos - Práctica Airbnb (Tableau)
Práctica de Exploración y Visualización de Datos del Bootcamp Big Data &amp; Machine Learning de KeepCoding

## Objetivo del dashboard
El dashboard desarrollado con Tableau tiene como objetivo detectar a nivel de barrio los alquileres que tienen peores valoraciones. Para ello se han utuilizado los siguientes datasets:
- airbnb-listings Madrid: Csv proporcionado para la práctica.
- neighbourhoods.geojson: Poligonos que delimitan cada uno de los barrios con los que poder hacer las agregaciones de datos.

El dashboard se compone de varios graficos entre los que se distinguen:
- Unas tarjetas superiores que se indican unas metricas a nivel global. En elgunas de ellas hacen uso de expresiones LOD para hacerlas independeintes de los filtros.
- Mapa donde se muestra con color aquellos barrios en los que se han detectado más alquileres con malas recomendaciones. En este caso se ha hecho uso de los parámetros de Tableau para hacer el ratio a partir del que considermos una review mala o buena sea configurable.  
Tambien se han tenido que crear varios campos calculados y hacer uso de los joins para poder agrupar los datos a nivel de barrio.
