# Análisis del Mercado de Guantes de Nitrilo en MercadoLibre con Looker Studio ARG

## Descripción del Proyecto

Este proyecto tiene como objetivo analizar el mercado de guantes de nitrilo en MercadoLibre, para explorar posibles mercados en la categoría de suplementos en odontología.

Para este análisis, utilicé la API de MercadoLibre para recolectar datos sobre los anuncios de guantes de nitrilo. Los datos fueron procesados y visualizados en Looker Studio para proporcionar un vistazo claro a la oferta de este tipo de producto en dicha plataforma.

## Contenido del Proyecto

El proyecto consta de los siguientes componentes:

1. **Jupyter Notebook:** Un notebook que se conecta a la API de MercadoLibre, extrae los datos relevantes y los guarda en un archivo CSV.
2. **Archivo CSV:** Un archivo que contiene los datos extraídos.
3. **Tablero en Looker Studio:** Un tablero interactivo que presenta los datos de manera visual y facilita el análisis.

## Estructura del Repositorio

  - `guantes_nitrilo_datos.csv`: El archivo CSV con los datos extraídos.
  - `extraccion_datos_ML_guantes_nitrilo.ipynb`: El script de Python utilizado para extraer los datos.
  - `look_studio_dashboard.png`: Una imagen del tablero de Looker Studio.
  - `README.md`: Este archivo con la descripción del proyecto.

## Tablero Interactivo

Puedes acceder al tablero interactivo en Looker Studio a través del siguiente enlace: https://lookerstudio.google.com/s/ud9PTnp4Ow0

## Resultados

El tablero en Looker Studio incluye las siguientes visualizaciones:

  **Número de Anuncios Activos y Valor Potencial:** Indicadores clave del tamaño del mercado.
  **Gráfico de Barras:** Precio unitario promedio vs Unidades en venta.
  **Gráfico de Pastel:** Distribución de marcas a la venta.
  **Filtros Interactivos:** Filtros para formato de venta y rango de precios.

## Conclusión

Este análisis proporciona una primera visión al mercado de guantes de nitrilo en MercadoLibre, destacando tendencias en precios y distribución de marcas. El tablero interactivo permite explorar los datos de manera dinámica, facilitando la toma de decisiones informadas.

## Próximos Pasos

Para añadir más complejidad y valor al proyecto, se podrían incluir las siguientes mejoras:

  **Análisis de Tendencias Temporales:** Incorporar datos históricos para analizar cómo han cambiado los precios y la disponibilidad a lo largo del tiempo.
  
  **Comparación Regional:** Comparar el mercado de guantes de nitrilo en diferentes regiones.
  
  **Análisis de Sentimientos:** Utilizar web scraping para obtener reseñas de clientes para luego utilizar técnicas de procesamiento de lenguaje natural (NLP) para analizarlas y obtener insights sobre la satisfacción de los compradores.
