# keepcoding-exploracion-y-visualizacion-de-datos
# Impacto Ambiental y Alojamientos de Airbnb en Madrid

## Pregunta de Análisis
¿Existe una relación entre la calidad del aire, específicamente los niveles de **NO₂ (Dióxido de Nitrógeno)**, y la distribución de alojamientos de Airbnb en Madrid? Este informe explora si los niveles de contaminación pueden estar correlacionados con el precio, la categoría de propiedad y otros parámetros de Airbnb.

## Fuentes de Datos
Para desarrollar este análisis, se integraron y analizaron datos de distintas fuentes:
- **Datos de Airbnb:** Incluyendo precios, reseñas, tipo de propiedad, ubicación y disponibilidad.
- **Datos de Calidad del Aire en Madrid:** Provenientes de estaciones de monitoreo, con foco en **NO₂**, obtenido de las bases de datos oficiales de medición atmosférica. 
- **Enriquecimiento de Datos:** Se cruzaron ambas fuentes para asignar mediciones de calidad del aire a los alojamientos según su proximidad geográfica.

## Metodología de Análisis
1. **Exploración de Datos**: Se identificaron patrones en precios de Airbnb y niveles de contaminación de NO₂.
2. **Segmentación por Categorías**:
   - Se agruparon los alojamientos por tipo de propiedad y rangos de precio.
   - Se clasificaron los niveles de NO₂ en **bajo (<31 µg/m³), moderado (31-40 µg/m³) y alto (>40 µg/m³)**.
3. **Visualización en Power BI**:
   - **Mapas de calor** para representar geográficamente los niveles de contaminación y la densidad de alojamientos.
   - **Gráficos de dispersión** para evaluar la correlación entre precios y calidad del aire.
   - **Tendencias temporales** para examinar la evolución de los alojamientos y la contaminación a lo largo de los años.
   - **Diagramas de barras** para segmentar la cantidad de alojamientos por nivel de contaminación.

## Hallazgos Clave
- **Distribución Geográfica**: Se observó que las zonas con mayor concentración de alojamientos no siempre coinciden con los niveles más altos de contaminación.
- **Relación Precio vs. Contaminación**: Aunque los precios más altos se encuentran en zonas menos contaminadas, existen excepciones donde la demanda supera la calidad ambiental.
- **Tendencias Temporales**: En ciertos años, la disponibilidad de alojamientos aumentó mientras que la contaminación de NO₂ disminuyó, posiblemente debido a cambios en regulaciones ambientales y turismo.

##  Conclusión
Este análisis ayuda a entender si la calidad del aire es un factor que influye en la distribución y precios de los alojamientos en Madrid. Las visualizaciones en **Power BI** proporcionan una visión clara de cómo se comportan las variables y permiten tomar decisiones informadas.


