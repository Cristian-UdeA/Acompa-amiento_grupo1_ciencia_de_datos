Análisis de Precios de Medicamentos en 2022
Introducción
Este informe presenta un análisis detallado de los precios de medicamentos en el año 2022, centrándose en la comprensión de las variaciones en el mercado farmacéutico colombiano. Los datos utilizados en este análisis se obtuvieron del "Termómetro de Precios de Medicamentos," una fuente que permite la comparación de precios equivalentes por tableta o cápsula de diferentes alternativas de medicamentos en el mercado. Estos datos son cruciales para comprender las dinámicas de precios en la industria farmacéutica y su importancia en la toma de decisiones en el ámbito de la salud y la química farmacéutica.

Origen de los Datos
Los datos utilizados en este análisis se obtuvieron de https://www.datos.gov.co/Salud-y-Protecci-n-Social/Clicsalud-Term-metro-de-Precios-de-Medicamentos/n4dj-8r7k . Este conjunto de datos proporciona información detallada sobre medicamentos, incluyendo el nombre del principio activo, la concentración, la unidad de dispensación, el nombre comercial, el fabricante, el precio por tableta, y otros factores relacionados con la determinación del precio.

Proceso de Análisis
Limpieza de Datos
Inicialmente, se realizó una limpieza de los datos utilizando la biblioteca Pandas. Se verificó que la base de datos contenía un total de 11,874 registros y no se encontraron datos faltantes en ninguna de las columnas. Además, se ajustó el tipo de dato en algunas columnas, en particular en "precio_por_tableta," para eliminar las comas como separadores de miles y convertir los valores a tipo flotante. No se identificaron filas duplicadas en la base de datos, lo que permitió un análisis preciso.

Correlación de Variables
Se realizó un análisis de correlación utilizando la biblioteca Matplotlib. Se centró en la relación entre la concentración de los medicamentos y el número de expediente INVIMA, así como entre la concentración y el precio por tableta. Los resultados mostraron que no existe una correlación lineal significativa entre estas variables, lo que sugiere que las variaciones en la concentración de los medicamentos no están relacionadas con patrones predecibles en los valores del expediente INVIMA o los precios por tableta.

Análisis Detallado
Se utilizó la biblioteca Seaborn para realizar un análisis más detallado. Se destacó que las tabletas o cápsulas son las unidades de dispensación más comunes, lo que sugiere su preferencia y comodidad en términos de administración. Además, se observó una correlación cercana a cero entre el precio por tableta y la concentración numérica, indicando una relación insignificante entre estas variables.

Medicamentos Costosos
Se identificaron los tres medicamentos más costosos en el mercado colombiano en 2022, incluyendo Spinraza, Remodulin y Juxtapid. Estos medicamentos están asociados con tratamientos especializados y condiciones médicas que requieren terapias avanzadas, lo que explica sus precios elevados.

Análisis de Distribución
El análisis de datos con la biblioteca NumPy reveló una amplia variación en los precios por tableta de medicamentos, con una alta desviación estándar. También se destacó que algunos medicamentos tienen concentraciones extremadamente bajas o altas, lo que puede estar relacionado con la forma de presentación y la efectividad terapéutica.

Conclusiones
En conclusión, el análisis de precios de medicamentos en 2022 en Colombia revela una industria farmacéutica diversa y competitiva. La variedad de principios activos, fabricantes y medicamentos disponibles ofrece opciones a pacientes y profesionales de la salud. Se observa que los medicamentos más costosos están asociados con tratamientos especializados, y las tabletas o cápsulas son las formas de presentación más comunes. La falta de correlación significativa entre la concentración de los medicamentos y el precio por tableta indica la complejidad de los factores que influyen en la determinación de precios en esta industria.
Es importante caracterizar las especificaciones básicas de cada medicamento, con el fin de brindar información detallada tanto a vendedores como a consumidores, permitiendo también, el control de la relación costo-beneficio, por los respectivos entes reguladores como el INVIMA, de igual manera asegurando la eficacia y calidad del producto. Teniendo en cuenta la gran franja que divide el precio de los medicamentos que pertenecen al canal institucional (genérico) o comercial, esta base de datos permite sondear y distribuir aquellos medicamentos de precio más económicos, hacia las establecimientos farmacéuticos ubicados en  zonas de bajos recursos, y de poca accesibilidad a tratamientos farmacológicos de alto costo

Para explorar los hallazgos de manera más interactiva, se ha desarrollado un tablero interactivo en Power BI: https://app.powerbi.com/view?r=eyJrIjoiMTJmMzI1ODEtYTI0Yi00ZmE2LWIwZDQtZTUxMGY2MzNkYmZlIiwidCI6Ijk5ZTFlNzIxLTcxODQtNDk4ZS04YWZmLWIyYWQ0ZTUzYzFjMiIsImMiOjR9
