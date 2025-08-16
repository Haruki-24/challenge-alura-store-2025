# Desafío de Alura Latam: Análisis de Tiendas Alura Store

## Descripción del Proyecto

Este proyecto tiene como objetivo analizar el rendimiento de las cuatro tiendas de la cadena Alura Store utilizando datos de ventas, ingresos, calificaciones y distribución geográfica. El análisis busca identificar la tienda menos eficiente y proporcionar una recomendación al Sr. Juan sobre cuál tienda debería considerar vender para iniciar un nuevo emprendimiento.

## Análisis Realizado

El análisis se llevó a cabo siguiendo los siguientes pasos:

1.  **Carga y Unificación de Datos:** Se cargaron los datos de las cuatro tiendas desde archivos CSV y se combinaron en un único DataFrame de pandas.
2.  **Exploración Inicial:** Se realizó una exploración inicial de los datos para entender su estructura y contenido.
3.  **Análisis de Facturación:** Se calcularon métricas clave como ingreso total, ganancia total, ingreso promedio, ganancia promedio y margen de ganancia para cada tienda.
4.  **Ventas por Categoría:** Se analizó la cantidad de productos vendidos por categoría en cada tienda y se identificaron las categorías más populares.
5.  **Calificación Promedio:** Se calculó la calificación promedio de los clientes para cada tienda y se comparó con el promedio general.
6.  **Productos Más y Menos Vendidos:** Se identificaron los productos más y menos vendidos en cada tienda.
7.  **Costo de Envío Promedio:** Se calculó el costo de envío promedio para cada tienda.
8.  **Análisis de Distribución Geográfica:** Se visualizó la distribución geográfica de las ventas utilizando gráficos de dispersión y mapas de calor, analizando las zonas de alta concentración.

## Visualizaciones Clave

Durante el análisis, se generaron varios gráficos para visualizar los resultados, incluyendo:

*   Gráficos de barras para ventas por categoría, calificación promedio y costo de envío promedio por tienda.
*   Gráficos de barras para los productos más y menos vendidos por tienda.
*   Gráficos de dispersión y un mapa de calor para visualizar la distribución geográfica de las ventas.

Puedes encontrar estos gráficos en el notebook principal del proyecto.

## Conclusiones y Recomendación

Basado en el análisis exhaustivo de las métricas financieras, de ventas, de clientes y geográficas, se llegó a la siguiente conclusión y recomendación:

*   **Conclusión:** Todas las tiendas son rentables, pero presentan diferencias en su rendimiento en diversas áreas. La Tienda 1 destaca en ingresos y ganancias totales. La distribución geográfica de las ventas es similar en todas las tiendas, concentrándose en ciudades principales como Bogotá y Medellín.
*   **Recomendación:** Se recomienda al Sr. Juan que considere vender la **Tienda 1**. Aunque tiene un costo de envío promedio ligeramente mayor, sus sólidos ingresos totales y ganancias, junto con una buena calificación promedio y la popularidad de sus categorías de productos, la convierten en una opción atractiva para la venta, potencialmente generando un mayor retorno de la inversión.

## Cómo Ejecutar el Proyecto

Para ejecutar este proyecto, sigue los siguientes pasos:

    1. Abre Google Colab en tu navegador web.
    2. Haz clic en "Archivo" > "Subir notebook" y selecciona el archivo .ipynb de este proyecto desde tu computadora.
    3. Una vez que el notebook esté abierto en Colab, ejecuta las celdas del notebook secuencialmente. Puedes hacerlo haciendo usando "Entorno de ejecución" > "Ejecutar todas".
