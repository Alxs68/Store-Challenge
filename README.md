# Análisis del Rendimiento de Tiendas

## Introducción

Este proyecto se centra en analizar los datos de ventas de cuatro tiendas para entender mejor su desempeño. El objetivo es identificar los aspectos clave que influyen en las ventas y la satisfacción del cliente, 
para así poder tomar decisiones informadas y mejorar los resultados generales.

Utilicé los datos históricos de ventas de cada tienda, consolidándolos para tener una visión completa. A partir de este análisis, busco ofrecer recomendaciones prácticas.

## Fuentes de Datos

Los datos utilizados en este análisis provienen de cuatro archivos CSV alojados en GitHub, cada uno representando los datos de ventas de una tienda individual. Estos archivos se cargaron y combinaron en un único 
DataFrame de pandas para facilitar el análisis integral.

- [Tienda 1](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_1%20.csv)
- [Tienda 2](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_2.csv)
- [Tienda 3](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_3.csv)
- [Tienda 4](https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_4.csv)

## Pasos del Análisis

El análisis se llevó a cabo siguiendo los pasos que se detallan en el notebook, incluyendo:

1.  Carga y limpieza de los datos de ventas.
2.  Cálculo de indicadores clave de rendimiento (KPIs) por tienda.
3.  Análisis de ventas por categoría y la identificación de productos con mejor y peor desempeño.
4.  Visualización de tendencias y relaciones entre métricas (ingresos, reseñas, costos de envío).
5.  Generación de una recomendación basada en un puntaje ponderado del rendimiento de la tienda.

## Hallazgos Clave

-   **Rendimiento de Tiendas:** Observé diferencias en el rendimiento de las tiendas, con la Tienda 1 liderando en ingresos y la Tienda 4 con el rendimiento más bajo según mi análisis ponderado.
-   **Categorías y Productos:** Las categorías de Electrónicos y Electrodomésticos son cruciales para los ingresos. Identifiqué los productos individuales que más y menos contribuyen a las ventas.
-   **Relación entre Métricas:** Analicé cómo se relacionan las calificaciones de los clientes, los ingresos y los costos de envío para cada tienda.

## Recomendación Principal

Basándome en un análisis ponderado de varios factores, recomiendo prestar especial atención a la **Tienda 4** como tienda con mayor potencial de mejora o en su defecto ponerla en venta.

## Visualizaciones Clave

El notebook incluye visualizaciones que resumen:

-   Ingresos totales por tienda.
-   Participación de ingresos por categoría.
-   Relación entre reseñas, ingresos y costos de envío.

Te invito a explorar el notebook para ver el análisis completo y las visualizaciones.


