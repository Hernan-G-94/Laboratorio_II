# 📊 Laboratorio II: Análisis de Datos con Power BI

## 📝 Descripción del Proyecto
Este proyecto consiste en un informe interactivo desarrollado en **Microsoft Power BI** como parte del "Laboratorio II". El objetivo principal es transformar datos crudos en información procesable para la toma de decisiones.

El reporte permite visualizar tendencias, patrones y métricas clave (KPIs) relacionadas con **Análisis de ventas para E-Commerce**.

## 🎯 Objetivos
* Consolidar y limpiar los datos provenientes de **https://www.kaggle.com/datasets/dataregina/datasets-para-proyecto-bi?resource=download**.
* Crear un modelo de datos relacional eficiente (Modelo en Estrella).
* Diseñar dashboards interactivos que respondan a preguntas de negocio como:
    * **¿Cuál es el producto más vendido?**
    * **¿En qué región se compra más?**
    * **¿Cuál es el medio de pago mas utilizado?**

## 🛠️ Tecnologías Utilizadas
* **Microsoft Power BI Desktop:** Para la ingesta, modelado y visualización.
* **Power Query (M):** Para la limpieza y transformación de datos (ETL).
* **DAX (Data Analysis Expressions):** Para la creación de medidas calculadas y columnas personalizadas.

## 🗂️ Modelo de Datos
El proyecto cuenta con un modelo de datos estructurado que incluye:

* **Tabla de Ventas:**
    * `Sales`
* **Tablas de Dimensiones:**
    * `Calendar`
    * `Products`
    * `Categories`
    * `Clients_region`
    * `Customers`
    * `Payment_methods`
    * `Measurements`

## 📈 Visualizaciones Clave
El informe incluye las siguientes páginas y gráficos destacados:

1.  **Visión General (Overview):** Tarjetas con KPIs principales.
2.  **Análisis Temporal:** Gráficos de línea/área para ver la evolución en el tiempo.
3.  **Desglose por Categoría:** Gráficos de barras y anillos para comparar segmentos.
4.  **Mapa geográfico**.


## 🚀 Cómo utilizar este archivo
1.  Descarga el archivo `Laboratorio II.pbix`.
2.  Asegúrate de tener instalado **Microsoft Power BI Desktop**.
3.  Abre el archivo.
4.  Interactúa con los filtros (Slicers) ubicados en **la barra lateral izquierda** para segmentar la información.

## 🔄 Estado del Proyecto
* [x] Carga de datos
* [x] Limpieza y ETL
* [x] Modelado de datos
* [x] Diseño de visualizaciones

---
**Autor:** Di Gialonardo, Hernán
**Última actualización:** Noviembre 2025
