# Análisis de Datos Históricos de Acciones e Ingresos: Tesla y GameStop

## Descripción del proyecto

Este proyecto consiste en extraer, procesar y visualizar datos históricos del precio de las acciones y los ingresos trimestrales de **Tesla (TSLA)** y **GameStop (GME)** mediante Python.

El trabajo utiliza técnicas de extracción de datos financieros y *web scraping* para organizar la información en DataFrames y construir gráficos que permitan observar la evolución de ambas empresas a lo largo del tiempo.

## Objetivos

- Obtener datos históricos de las acciones de Tesla y GameStop.
- Extraer información de los ingresos trimestrales mediante *web scraping*.
- Limpiar y organizar los datos utilizando pandas.
- Visualizar la evolución de los precios de las acciones y los ingresos.
- Identificar tendencias y comparar el comportamiento de ambas variables.

## Herramientas y tecnologías

- **Python:** lenguaje de programación utilizado para el análisis.
- **yfinance:** extracción de datos históricos del mercado bursátil.
- **pandas:** manipulación, limpieza y organización de datos.
- **BeautifulSoup:** análisis de contenido HTML y extracción de tablas.
- **Requests:** descarga del contenido de páginas web.
- **Matplotlib:** generación de gráficos para visualizar los resultados.

## Desarrollo del proyecto

El notebook se organiza en seis ejercicios principales:

| Pregunta | Actividad |
|---|---|
| 1 | Extracción de datos históricos de las acciones de Tesla. |
| 2 | Extracción y limpieza de los ingresos trimestrales de Tesla mediante *web scraping*. |
| 3 | Extracción de datos históricos de las acciones de GameStop. |
| 4 | Extracción y limpieza de los ingresos trimestrales de GameStop mediante *web scraping*. |
| 5 | Visualización del precio histórico de las acciones y los ingresos de Tesla. |
| 6 | Visualización del precio histórico de las acciones y los ingresos de GameStop. |

## Procesamiento de datos

Durante el desarrollo se realizan las siguientes operaciones:

1. Descarga de los datos históricos de las acciones mediante `yfinance`.
2. Extracción de las tablas de ingresos desde páginas web utilizando `Requests` y `BeautifulSoup`.
3. Creación de DataFrames con pandas para organizar la información.
4. Limpieza de los datos de ingresos mediante la eliminación de comas, símbolos de dólar y valores vacíos.
5. Generación de gráficos para analizar la evolución temporal de las acciones y los ingresos.

## Resultados esperados

El análisis permite observar las tendencias históricas del precio de las acciones y de los ingresos trimestrales de Tesla y GameStop.

En los gráficos se aprecia un fuerte crecimiento del precio de las acciones de Tesla hacia 2020-2021. En GameStop destaca el aumento pronunciado del precio de sus acciones alrededor de 2021, mientras que sus ingresos presentan fluctuaciones que no muestran un incremento comparable.

Estas visualizaciones permiten comparar las tendencias de ambas variables, aunque no demuestran por sí solas una relación causal entre los ingresos y el precio de las acciones.

## Estructura del repositorio

```text
tesla-gamestop-stock-analysis/
│
├── Revenue Data and Building a Dashboard_Meza.ipynb
└── README.md
```

## Cómo ejecutar el proyecto

1. Descarga o clona este repositorio.
2. Abre el archivo `.ipynb` en Jupyter Notebook, JupyterLab o Google Colab.
3. Instala las librerías necesarias si no están disponibles en tu entorno.
4. Ejecuta las celdas en orden para obtener los datos, procesarlos y generar las visualizaciones.

Para instalar las principales dependencias, puedes utilizar:

```bash
pip install yfinance pandas requests beautifulsoup4 matplotlib
```

## Fuente de datos

- Datos históricos de acciones: Yahoo Finance, mediante la biblioteca `yfinance`.
- Ingresos trimestrales: tablas web utilizadas en el notebook del proyecto.

## Nota

Este proyecto tiene fines educativos y se centra en la extracción, el procesamiento y la visualización de datos financieros históricos. No constituye asesoramiento financiero ni una recomendación de inversión.
