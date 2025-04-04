

Este proyecto está enfocado en la realización de una exploración y limpieza de datos, seguido de un análisis visual utilizando herramientas de Pandas y matplotlib/seaborn.

``Fase 1: Exploración y Limpieza de Datos``

1. Exploración Inicial:

- En esta fase me he centrado en la revisión de los datos para entender su estructura y tipos de datos (numérico/categórico) y verificar la existencia de valores nulos.
- He identificado los valores únicos de las columnas, así como mostrado estadísticas que pueden sernos de utilidad más adelante.
- Por otra parte, he identificado los valores duplicados y nos hemos encargado de su limpieza antes de continuar con el siguiente paso.

2. Unión de Datos:

He utilizado funciones de Pandas para combinar los datos sobre una columna clave común. De esta forma, unimos los DataFrames.

3. Limpieza de Datos:

Una vez identificados los problemas en los datos he procedido a realizar la limpieza de los mismos. Algunos de los cambios realizados han sido:

- Tratamiento de nulos: He sustituido los valores en las columnas correspondientes según sus características.
- Modificación de datos erróneos: Columnas con valores erróneos como Salary (con valores negativos) han sido sustituidas por su valor absoluto para su correcta lectura.
- Cambios en el tipo de dato: Algunas columnas presentaban un tipo de dato mejorable en cuanto a claridad en la visualización de los datos.



``Fase 2: Visualización``

1. Distribución de vuelos reservados por mes:
Para comprender cómo varían los vuelos a lo largo del año, he creado un gráfico de barras donde el eje X representa los meses del año y el eje Y el número de vuelos reservados. Esto nos da una visión clara de las tendencias mensuales.

2. Relación entre la distancia de los vuelos y los puntos acumulados:
Aquí he utilizado un gráfico de dispersión y mostrado los puntos acumulados en el eje Y y la distancia de los vuelos en el eje X para ver si existe una relación entre ambas variables.

3. Distribución de clientes por provincia:
Con un gráfico de barras, he podido visualizar cuántos clientes hay en cada provincia. Esto nos ayuda a entender la distribución geográfica de los clientes.

4. Salario promedio por nivel educativo:
Para comparar el salario entre diferentes niveles educativos utilizamos un gráfico boxplot, ya que muestra la mediana, los cuartiles y los valores atípicos, proporcionando una visión clara de las diferencias salariales.

5. Proporción de clientes con diferentes tipos de tarjetas de fidelidad:
Para visualizar las proporciones de cada tipo de tarjeta de fidelidad he utilizado un gráfico de pastel, ya que muestra la distribución relativa entre las categorías.

6. Distribución por estado civil y género:
En este caso, un gráfico de barras apiladas es útil para mostrar cómo se distribuyen los clientes según su estado civil y género, permitiendo comparaciones entre ambos factores.


``Fase 3: Evaluación de diferencias en Reservas de Vuelos por Nivel Educativo``


1. Preparación de Datos:
He filtrado el conjunto de datos para incluir únicamente las columnas relevantes:'Flights Booked' y 'Education'.

2. Análisis Descriptivo:
He agrupa los datos por nivel educativo y calculado estadísticas descriptivas básicas como el promedio y la desviación estándar del número de vuelos reservados para cada grupo.
