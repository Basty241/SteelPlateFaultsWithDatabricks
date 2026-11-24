# Steel Plates Faults Analysis with Databricks

Análisis exploratorio e inferencial sobre el conjunto de datos **Steel Plates Faults** ejecutado en **Databricks**.

## Objetivo y Alcance Técnico

- **Propósito de usar Databricks:** El uso de esta plataforma responde netamente al objetivo de **familiarizarse con el ecosistema de Databricks** (notebooks, gestión de datos y consultas en Databricks SQL), ya que desde el punto de vista computacional es una herramienta sobredimensionada para procesar un archivo de datos del tamaño utilizado (~300 KB).
- **Objetivo analítico:** Caracterizar y diferenciar los distintos tipos de fallas superficiales en placas de acero mediante **estadística descriptiva** (univariada, bivariada y multivariada) e **inferencial** (pruebas de hipótesis), con el fin de identificar los indicadores clave para su **detección automática**.

## Fuente del Dataset

- **Nombre:** *Steel Plates Faults Data Set* (ID: 198)
- **Origen:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/198/steel+plates+faults) — donado por **Semeion Research Center of Sciences of Communication** (Roma, Italia).
- **Descripción:** 1.941 registros de defectos superficiales en placas de acero (`A300` y `A400`), descritos por 27 variables independientes (geométricas, de posición y de luminosidad) y 7 clases de falla (`Pastry`, `Z_Scratch`, `K_Scratch`, `Stains`, `Dirtiness`, `Bumps` y `Other_Faults`).

## Estructura del Repositorio

| Carpeta | Contenido |
| :--- | :--- |
| [`Analysis_With_Pandas/`](./Analysis_With_Pandas/) | Notebook `SteelPlateFaults_Analysis.ipynb` con el análisis exploratorio, correlaciones e inferencia estadística usando Pandas y librerías de Python en Databricks. |
| [`Analysis_With_SQL/`](./Analysis_With_SQL/) | Espacio reservado para consultas y análisis mediante **Databricks SQL**. |
| [`data/`](./data/) | Archivos originales del dataset (`Faults.NNA` y `Faults27x7_var`). |
