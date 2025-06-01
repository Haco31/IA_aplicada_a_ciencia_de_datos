# Proyecto de IA aplicada a Data Science: Visualización de Datos de E-commerce Zoop

Este proyecto explora el uso de la Inteligencia Artificial (en este caso, como asistente para el análisis exploratorio y la creación de visualizaciones) para analizar datos de ventas y clientes de Zoop, una gran minorista mexicana con operaciones de e-commerce. El objetivo principal es generar visualizaciones clave que ayuden a la directiva de la empresa a obtener insights sobre la facturación, el perfil del cliente y otros indicadores relevantes para la toma de decisiones estratégicas.

El proyecto se desarrolló utilizando Google Colab y la biblioteca Pandas para la manipulación de datos, y Matplotlib y Seaborn para la creación de visualizaciones.

## Problema de Negocio

El equipo de datos de Zoop necesita extraer datos y generar información visualmente presentable para la directiva. Se busca destacar:

*   Datos de facturación a lo largo del tiempo y por diferentes categorías.
*   Perfil demográfico y de comportamiento del cliente.
*   Otros indicadores que puedan informar decisiones estratégicas.

## Base de Datos

Se utilizaron dos conjuntos de datos:

1.  **Datos de Clientes:** Información sobre los clientes que realizaron compras, incluyendo ID de compra, ID de cliente, ubicación (ciudad, estado, región), edad, sexo biológico, participación en programa de cashback y calificación de la compra.
2.  **Datos de Ventas:** Información detallada de las ventas, incluyendo ID de compra, fecha y hora de la compra, categoría del producto, precio unitario, cantidad vendida, costo de envío y método de pago.

Estos datos se obtuvieron de archivos CSV alojados en Gist de GitHub.

## Desafío

Como analista de datos, el desafío consistió en:

1.  Extraer y combinar los datos de ambas fuentes.
2.  Realizar un análisis exploratorio rápido (aunque los datos estaban limpios y tratados para este ejercicio).
3.  Construir visualizaciones significativas basadas en preguntas clave del negocio.
4.  Aplicar principios de diseño visual y storytelling (como el uso de la identidad visual de Zoop) para mejorar la comunicación de los insights.
5.  Utilizar una IA (como ChatGPT, simulado en este ejercicio) como asistente para agilizar el proceso de análisis y visualización.

## Visualizaciones Clave

El proyecto generó y refinó las siguientes visualizaciones para abordar las preguntas del negocio:

1.  **Métodos de Pago Más Utilizados en 2023:** Gráfico de barras verticales que muestra la cantidad de veces que cada método de pago fue utilizado.
2.  **Facturación por Categoría de Producto en 2023:** Gráfico de barras horizontales que muestra la facturación total generada por cada categoría de producto.
3.  **Ventas Totales Mensuales en 2023:** Gráfico de líneas que visualiza la tendencia de las ventas a lo largo de los meses del año.
4.  **Ventas por Trimestre y Método de Pago en 2023:** Gráfico de barras apiladas que muestra la composición de las ventas por método de pago dentro de cada trimestre.
5.  **Proporción de Clientes con Cashback:** Gráfico de dona que ilustra el porcentaje de clientes que participan en el programa de cashback.
6.  **Distribución de las Calificaciones de Compra:** Histograma que muestra la frecuencia de las diferentes calificaciones otorgadas por los clientes.
7.  **Distribución de Edad por Sexo Biológico de los clientes:** Boxplot que compara la distribución de edades entre los diferentes sexos biológicos.

Cada visualización fue estilizada siguiendo una paleta de colores definida y se le añadieron elementos como títulos claros, etiquetas formateadas y anotaciones para resaltar insights clave.

## Estructura del Proyecto

El código principal se encuentra en un notebook de Google Colab.

*   `IA_aplicada_a_ciencia_de_datos.ipynb`: Archivo principal de Google Colab conteniendo el código Python para la carga de datos, preprocesamiento, análisis exploratorio, creación de visualizaciones y exportación.
*   `README.md`: Este archivo, proporcionando una descripción del proyecto.
*   Imágenes exportadas de cada visualización.

## Cómo Ejecutar el Proyecto

1.  Abre el archivo `IA_aplicada_a_ciencia_de_datos.ipynb` en Google Colab.
2.  Asegúrate de tener instaladas las bibliotecas necesarias (Pandas, Matplotlib, Seaborn). En Google Colab, estas suelen estar preinstaladas.
3.  Ejecuta las celdas en secuencia para cargar los datos, realizar el preprocesamiento, generar las visualizaciones y exportar las imágenes.

## Tecnologías Utilizadas

*   Python
*   Pandas
*   Matplotlib
*   Seaborn
*   Google Colab
*   Inteligencia Artificial (como asistente)

## Contribuciones

Este proyecto es un ejercicio guiado de visualización de datos con asistencia de IA. Las contribuciones son bienvenidas para mejoras o análisis adicionales.

## Licencia

Este proyecto se encuentra bajo la Licencia de Alura Latam.

---

**Nota:** Reemplaza `IA_aplicada_a_ciencia_de_datos.ipynb` con el nombre real de tu archivo de notebook en Google Colab. Asegúrate de subir también las imágenes PNG generadas a tu repositorio para que aparezcan en el README. Puedes crear una carpeta (por ejemplo, `images`) y ajustar las rutas en el README para mostrar las imágenes directamente.
