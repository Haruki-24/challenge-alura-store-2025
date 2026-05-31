# 📊 Desafío Alura Latam: Análisis de Tiendas Alura Store
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)]([https://drive.google.com/file/d/1Tb-olHs6eD04ZkX-LI9Y_UjvKPEiByR7/view?usp=sharing])

## 📋 Descripción del Proyecto
Este proyecto desarrolla un análisis de Business Intelligence y Data Science para evaluar el rendimiento financiero y operativo de las cuatro tiendas de la cadena **Alura Store**. El objetivo principal es transformar datos crudos de ventas en *insights* accionables para responder a un desafío estratégico real: **identificar la tienda óptima para desinversión (venta)**, permitiendo al inversor (Sr. Juan) maximizar su retorno de capital para un nuevo emprendimiento.

---

## 🎯 Objetivo General del Proyecto
El objetivo principal de este proyecto es analizar el rendimiento de un negocio a través de métricas clave. Para lograrlo, cargaremos, manipularemos y visualizaremos datos de un archivo CSV usando las bibliotecas Pandas y Matplotlib, para así obtener información valiosa sobre ingresos, reseñas y ventas.

## 🔍 Objetivo Específico del Desafío
Este proyecto tiene como objetivo analizar el rendimiento de las cuatro tiendas de la cadena Alura Store utilizando datos de ventas, ingresos, calificaciones y distribución geográfica. El análisis busca identificar la tienda menos eficiente y proporcionar una recomendación al Sr. Juan sobre cuál tienda debería considerar vender para iniciar un nuevo emprendimiento.

---

## 🛠️ Stack Tecnológico Utilizado

| Tecnología / Biblioteca | Uso Específico en el Proyecto |
| :--- | :--- |
| **Python (Jupyter Notebook)** | Entorno de desarrollo para el procesamiento y análisis de datos. |
| **Pandas** | Carga, unificación de múltiples fuentes (CSV), limpieza y manipulación de DataFrames. |
| **Matplotlib / Seaborn** | Generación de visualizaciones clave (gráficos de barras, dispersión y mapas de calor). |
| **Google Colab** | Infraestructura en la nube para la ejecución del pipeline de análisis. |

---

## ⚙️ Metodología del Análisis Realizado

1.  **Carga y Unificación de Datos:** Se cargaron los datos de las cuatro tiendas desde archivos CSV y se combinaron en un único DataFrame de pandas.
2.  **Exploración Inicial:** Se realizó una exploración inicial de los datos para entender su estructura y contenido.
3.  **Análisis de Facturación:** Se calcularon métricas clave como ingreso total, ganancia total, ingreso promedio, ganancia promedio y margen de ganancia para cada tienda.
4.  **Ventas por Categoría:** Se analizó la cantidad de productos vendidos por categoría en cada tienda y se identificaron las categorías más populares.
5.  **Calificación Promedio:** Se calculó la calificación promedio de los clientes para cada tienda y se comparó con el promedio general.
6.  **Productos Más y Menos Vendidos:** Se identificaron los productos más y menos vendidos en cada tienda.
7.  **Costo de Envío Promedio:** Se calculó el costo de envío promedio para cada tienda.
8.  **Análisis de Distribución Geográfica:** Se visualizó la distribución geográfica de las ventas utilizando gráficos de dispersión y mapas de calor, analizando las zonas de alta concentración.

---

## 📈 Visualizaciones Clave

Durante el análisis, se generaron varios gráficos para visualizar los resultados, incluyendo:

*   Gráficos de barras para ventas por categoría, calificación promedio y costo de envío promedio por tienda.
*   Gráficos de barras para los productos más y menos vendidos por tienda.
*   Gráficos de dispersión y un mapa de calor para visualizar la distribución geográfica de las ventas.

Puedes encontrar estos gráficos en el notebook principal del proyecto.

----

## 📈 Conclusiones y Recomendación Estratégica

### 📋 Diagnóstico

Se realizó una auditoría integral del rendimiento de las cuatro tiendas de la cadena **Alura Store**. El análisis abarcó la unificación de sus datos de ventas, el cálculo de sus márgenes de facturación y ganancias netas, la evaluación de la satisfacción del cliente mediante calificaciones, el impacto de los costos logísticos de envío y la distribución geográfica de la demanda para identificar la tienda idónea para la desinversión.

* **Análisis de Rentabilidad y Geografía:** El análisis determinó que todas las sucursales operan bajo márgenes rentables. La demanda geográfica muestra un comportamiento homogéneo con una fuerte concentración en núcleos urbanos principales (Bogotá y Medellín), por lo que **no es un factor determinante** al momento de elegir una de las tiendas.
* **Potencial de la Tienda 1:** La Tienda 1 destaca significativamente como el activo con el mayor volumen de ingresos y ganancias totales de la cadena. Aunque presenta costos logísticos sutilmente más altos, su posicionamiento líder en facturación, la sólida base de satisfacción de sus clientes y la alta rotación de sus categorías principales elevan drásticamente su **valor de valuación en el mercado**. 
* **Criterio Financiero de Decisión:** Vender la tienda más fuerte garantiza capturar una prima de valor más alta en el mercado, otorgando al Sr. Juan la máxima liquidez y el mayor Retorno de Inversión (ROI) posible para fondear su nuevo proyecto. Sus sólidos ingresos totales y ganancias, junto con una buena calificación promedio y la popularidad de sus categorías de productos, la convierten en una opción sumamente atractiva para la venta.

### 🎯 Recomendación Final

> **Se recomienda al Sr. Juan que considere vender la Tienda 1.** Aunque tiene un costo de envío promedio ligeramente mayor, sus sólidos ingresos totales y ganancias, junto con una buena calificación promedio y la popularidad de sus categorías de productos, la convierten en una opción atractiva para la venta, potencialmente generando un mayor retorno de la inversión.

## 🚀 Cómo Ejecutar el Proyecto

1. Abre [Google Colab](https://colab.research.google.com/) en tu navegador.
2. Ve a **Archivo** > **Subir notebook** y selecciona el archivo `AluraStoreLatam.ipynb` incluido en este repositorio.
3. Asegúrate de cargar los archivos de la carpeta `base-datos-challenge1-latam` en el entorno de Colab.
4. Ejecuta las celdas de forma secuencial desde el menú **Entorno de ejecución** > **Ejecutar todas**.
