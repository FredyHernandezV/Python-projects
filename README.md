# 📊 Análisis de Cobertura de Internet Fijo y Móvil en Colombia (2023)

Este proyecto documenta el proceso analítico completo de dos datasets públicos gubernamentales que detallan el número de accesos a internet (fijo y móvil) en Colombia durante el año 2023. 

El objetivo principal es estructurar la información bruta para identificar brechas de conectividad y patrones de penetración tecnológica, con un análisis segmentado para la región de Bogotá y Cundinamarca.

## 🗂️ Fuente de los Datos
Los datos utilizados son de dominio público, proporcionados por el **Ministerio de Tecnologías de la Información y las Comunicaciones (MinTIC)** y alojados en el portal de Datos Abiertos de Colombia:
* 🔗 [Datos.gov.co - Portal Oficial](https://www.datos.gov.co/)

## 🛠️ Stack Tecnológico
* **Lenguaje:** Python 🐍
* **Librerías:** Pandas, Matplotlib, NumPy
* **Visualización y BI:** Power BI, Python (Colab) 
* **Herramientas de apoyo:** Excel Avanzado (Power Query)

## ⚙️ Metodología y Fases del Proyecto

A lo largo de este repositorio se evidencia el flujo de trabajo integral del ciclo de vida del dato:

### 1. Ingeniería de Datos y Limpieza (ETL)
* **Extracción:** Carga de los datasets globales desde fuentes gubernamentales.
* **Transformación:** Estandarización de formatos, normalización de texto y segmentación geográfica de los datos.
* **Calidad del Dato:** Tratamiento de valores nulos y detección de anomalías para asegurar la fiabilidad del análisis posterior.

### 2. Análisis Exploratorio de Datos (EDA)
* Análisis descriptivo mediante Python para identificar tendencias iniciales de crecimiento en accesos móviles frente a conexiones fijas.
* Comprensión del comportamiento de adopción tecnológica por municipio.

### 3. Modelado y Visualización (Power BI)
* Construcción de un modelo relacional de datos.
* Diseño de un **Dashboard interactivo** con capacidades de *drill-down* (vistas minables), permitiendo a los tomadores de decisiones profundizar en las métricas clave de cobertura e interpretar las brechas de conectividad de forma intuitiva.

## 📂 Estructura del Repositorio
* `notebooks/`: Contiene los archivos de Google Colab/Jupyter con el código en Python para el proceso ETL y EDA.
