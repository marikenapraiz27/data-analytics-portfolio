# Dashboard de Rendimiento de Campañas de Marketing (Power BI)

## 📌 Descripción del Proyecto
Este proyecto analiza el rendimiento de campañas de marketing utilizando Power BI.  
El dashboard permite visualizar de forma interactiva la efectividad de campañas según canal, tipo de campaña, audiencia y segmento de clientes.

El objetivo principal es evaluar KPIs claves como ROI, tasa de conversión, impresiones, clicks y engagement, para facilitar la toma de decisiones basada en datos.

---

## 🎯 Objetivo de Negocio
- Monitorear el rendimiento general de campañas
- Identificar los canales más efectivos según ROI
- Analizar la evolución del ROI en el tiempo
- Evaluar distribución de campañas por canal y tipo
- Detectar qué tipos de campañas generan más clicks e interacción

---

## 🛠 Herramientas Utilizadas
- **Power BI Desktop**
- **Power Query** (limpieza y transformación de datos)
- **DAX** (medidas y KPIs)
- Dataset en formato CSV

---

## 📂 Información del Dataset
El dataset contiene información por campaña, incluyendo:
- Campaign ID y company
- Tipo de campaña y audiencia objetivo
- Canal utilizado y segmento de clientes
- Ubicación e idioma
- Duración de campaña (días)
- Clicks e impresiones
- Conversion rate
- Acquisition cost
- ROI
- Engagement score
- Fecha

---

## 🧹 Preparación y Limpieza de Datos
Transformaciones realizadas:
- Normalización de nombres de columnas
- Conversión de `duration` desde texto (ej: "30 days") a número
- Conversión de `acquisition cost` desde texto con símbolo monetario a número decimal
- Corrección de formatos de fecha
- Revisión y eliminación de valores inválidos o faltantes
- Creación de tabla calendario para análisis temporal

---

## 📊 KPIs Principales
- **Total de Campañas**
- **Clicks Totales**
- **Impresiones Totales**
- **CTR %**
- **Tasa de Conversión Promedio**
- **ROI Promedio**
- **Engagement Score Promedio**
- **Gasto Total (Acquisition Cost)**

---

## 📈 Visualizaciones del Dashboard
El dashboard incluye:
- Tarjetas KPI (resumen ejecutivo)
- ROI promedio por canal (barras)
- Evolución mensual del ROI (línea)
- Clicks por tipo de campaña (columnas)
- Distribución de clicks por canal (gráfico de anillos)
- Segmentadores interactivos (canal, tipo de campaña, audiencia, segmento, ubicación, fecha)

---

## 🔍 Insights Principales (Ejemplos)
- Algunos canales muestran ROI promedio superior de forma consistente.
- Existen tipos de campaña con muchos clicks pero ROI bajo.
- Se observan variaciones de ROI según el período (posible estacionalidad).
- Los segmentos de clientes responden diferente según el canal.
- La distribución de clicks permite identificar qué canales generan mayor tráfico.

---

## 💡 Recomendaciones
- Priorizar inversión en canales con ROI alto.
- Optimizar campañas con muchos clicks pero baja conversión.
- Analizar tendencias mensuales para detectar estacionalidad.
- Usar segmentación para mejorar la estrategia de targeting.

---

## 📷 Vista Previa del Dashboard
Las capturas se encuentran en la carpeta `/screenshots`.

---

## Dataset
El dataset fue obtenido de Kaggle.

Debido a las limitaciones de tamaño de archivos en GitHub, el dataset no está incluido en este repositorio.
Podés descargarlo acá: https://www.kaggle.com/datasets/manishabhatt22/marketing-campaign-performance-dataset
## 📁 Estructura del Repositorio
- `/dataset` → dataset original
- `/screenshots` → imágenes del dashboard
- archivo `.pbix` → reporte Power BI

---

## 🔗 Autor
**Marikena Praiz**  
Data Analyst | Power BI | Tableau | Excel  
LinkedIn: www.linkedin.com/in/marikena-praiz-60b4b924a











# Marketing Campaign Performance Dashboard (Power BI)

## 📌 Project Overview
This project analyzes marketing campaign performance using Power BI.  
The dashboard provides an interactive view of campaign effectiveness across different channels, campaign types, audiences, and customer segments.

It focuses on key marketing KPIs such as ROI, conversion rate, impressions, clicks, and engagement score to support data-driven decision-making.

---

## 🎯 Business Objective
- Monitor overall campaign performance
- Identify top-performing marketing channels based on ROI
- Analyze trends in ROI over time
- Understand campaign distribution across channels and campaign types
- Detect which campaign types generate the highest engagement and clicks

---

## 🛠 Tools Used
- **Power BI Desktop**
- **Power Query** (data cleaning and transformation)
- **DAX** (KPIs and measures)
- Dataset in CSV format

---

## 📂 Dataset Information
The dataset includes campaign-level information such as:
- Campaign ID and company
- Campaign type and target audience
- Channel used and customer segment
- Location and language
- Duration (days)
- Clicks and impressions
- Conversion rate
- Acquisition cost
- ROI
- Engagement score
- Date

---

## 🧹 Data Preparation
Data cleaning and transformation steps:
- Standardized column names
- Converted `duration` from text (e.g., "30 days") to numeric format
- Converted acquisition cost values from currency text to numeric format
- Fixed date formatting issues
- Validated missing and incorrect values
- Created a calendar table for time-based analysis

---

## 📊 Key KPIs Included
- **Total Campaigns**
- **Total Clicks**
- **Total Impressions**
- **CTR %**
- **Average Conversion Rate**
- **Average ROI**
- **Average Engagement Score**
- **Total Spend (Acquisition Cost)**

---

## 📈 Dashboard Visuals
The dashboard includes:
- KPI Cards (high-level performance summary)
- ROI by Channel (bar chart)
- ROI Trend by Month (line chart)
- Clicks by Campaign Type (column chart)
- Clicks Distribution by Channel (donut chart)
- Interactive filters (channel, campaign type, target audience, segment, location, date)

---

## 🔍 Key Insights (Examples)
- Some channels consistently show higher ROI than others.
- Certain campaign types generate high clicks but lower ROI.
- ROI trends vary significantly depending on time periods.
- Customer segments and target audiences respond differently across channels.
- Click distribution reveals which channels drive the majority of campaign traffic.

---

## 💡 Recommendations
- Invest more budget into high-ROI channels.
- Optimize campaign types with high clicks but low conversion rate.
- Monitor monthly ROI trends to detect seasonality.
- Use segmentation insights to improve targeting strategies.

---

## 📷 Dashboard Preview
Screenshots are available in the `/screenshots` folder.

---

## Dataset
The dataset was obtained from Kaggle.

Due to GitHub file size limitations, the dataset is not included in this repository.
You can download it here: https://www.kaggle.com/datasets/manishabhatt22/marketing-campaign-performance-dataset

---

## 📁 Repository Structure
- `/dataset` → original dataset
- `/screenshots` → dashboard images
- `.pbix` file → Power BI report

---

## 🔗 Author
**Marikena Praiz**  
Data Analyst | Power BI | Tableau | Excel  
LinkedIn: www.linkedin.com/in/marikena-praiz-60b4b924a
