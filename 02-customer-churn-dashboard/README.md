# Dashboard de Customer Churn (Power BI)

## 📌 Descripción del Proyecto
Este proyecto analiza la tasa de abandono de clientes (*Customer Churn*) utilizando Power BI.  
El dashboard permite identificar patrones de churn según variables demográficas, comportamiento del cliente y características de la cuenta, facilitando la toma de decisiones basada en datos para mejorar la retención.

El objetivo es entender qué factores influyen en la salida de clientes y detectar segmentos de alto riesgo.

---

## 🎯 Objetivo de Negocio
- Analizar la tasa de churn general
- Identificar perfiles de clientes con mayor probabilidad de abandono
- Comparar churn por país/región, género y edad
- Evaluar impacto de la actividad del cliente y quejas
- Detectar oportunidades de mejora para estrategias de retención

---

## 🛠 Herramientas Utilizadas
- **Power BI Desktop**
- **Power Query** (limpieza y transformación de datos)
- **DAX** (medidas y KPIs)
- Dataset en formato CSV

---

## 📂 Información del Dataset
El dataset utilizado contiene información de clientes bancarios e incluye variables como:

- CustomerId, Surname
- CreditScore, Geography, Gender
- Age, Tenure, Balance
- NumOfProducts, HasCrCard, IsActiveMember
- EstimatedSalary
- Exited (churn)
- Complain
- Satisfaction Score
- Card Type
- Point Earned

---

## 🧹 Preparación y Limpieza de Datos
Transformaciones realizadas en Power Query:
- Corrección de tipos de datos (números, texto y campos categóricos)
- Eliminación de valores nulos e inconsistencias
- Creación de columnas calculadas para segmentación
- Generación de grupos de edad (Age Groups)
- Creación de medidas para métricas clave de churn

---

## 📊 KPIs Principales
El dashboard incluye los siguientes indicadores:

- **Total de Clientes**
- **Clientes Perdidos (Churned Customers)**
- **Churn Rate (%)**
- **Retention Rate (%)**
- **Balance Promedio**
- **Edad Promedio**
- **% Clientes Activos**
- **% Clientes con Quejas**

---

## 📈 Visualizaciones del Dashboard
El dashboard incluye:
- Tarjetas KPI con métricas principales
- Churn Rate por Geography (barras horizontales)
- Churn Rate por Age Group (barras verticales)
- Churn por actividad (Active vs Inactive)
- Churn por tipo de tarjeta (Card Type)
- Scatter plot Balance vs Estimated Salary (segmentación de clientes)
- Segmentadores interactivos para filtrar por país, género, actividad y edad

---

## 🔍 Insights Principales (Ejemplos)
- Los clientes inactivos presentan una tasa de churn significativamente mayor.
- Algunos países/regiones tienen churn más elevado que otros.
- Determinados rangos de edad muestran mayor probabilidad de abandono.
- La presencia de quejas se relaciona fuertemente con el churn.
- Los clientes con balances altos pueden tener churn elevado en ciertos segmentos.

---

## 💡 Recomendaciones
A partir del análisis, se recomienda:
- Crear campañas de retención para clientes inactivos.
- Implementar estrategias específicas para regiones con churn alto.
- Diseñar productos adaptados a los rangos de edad con mayor churn.
- Mejorar el soporte al cliente para reducir quejas.
- Ofrecer beneficios a clientes con balances altos para evitar pérdida de cuentas valiosas.

---

## 📷 Vista Previa del Dashboard
Las capturas del dashboard se encuentran en la carpeta `/screenshots`.

---

## 📁 Estructura del Repositorio
- `/dataset` → dataset original
- `/screenshots` → imágenes del dashboard
- archivo `.pbix` → reporte Power BI

---

## 🔗 Autor
**Marikena Praiz**  
Data Analyst | Power BI | Tableau | Excel  
LinkedIn: www.linkedin.com/in/
marikena-praiz-60b4b924a









# Customer Churn Analysis Dashboard (Bank Customers)

## 📌 Project Overview
This project analyzes customer churn behavior in the banking sector using Power BI.  
The main goal is to identify patterns and key factors that influence customer churn and provide insights to improve retention strategies.

The dashboard is interactive and allows filtering by geography, gender, card type, and customer activity status.

---

## 🎯 Business Objective
- Measure overall churn rate and retention rate
- Identify customer segments with the highest churn risk
- Analyze churn behavior by geography, age group, and customer activity
- Evaluate the impact of complaints and product usage on churn
- Provide actionable recommendations to reduce churn

---

## 🛠 Tools Used
- **Power BI Desktop** (Data Modeling, DAX, Dashboard Design)
- **Power Query** (Data Cleaning and Transformation)
- **CSV Dataset** (Customer churn records)

---

## 📂 Dataset Description
The dataset contains banking customer information with the following key fields:

- Customer demographics: `Age`, `Gender`, `Geography`, `Surname`
- Financial information: `Balance`, `EstimatedSalary`, `CreditScore`
- Customer behavior: `Tenure`, `NumOfProducts`, `IsActiveMember`, `HasCrCard`
- Customer feedback: `Complain`
- Target variable: `Exited` (Churn indicator)

---

## 🧹 Data Cleaning & Transformation
The following transformations were applied in Power Query:
- Corrected data types (numeric, text, categorical fields)
- Removed null values and invalid records
- Standardized column names
- Created calculated columns for segmentation (Age Groups, Tenure Groups, Balance Groups)

---

## 📊 Key KPIs
The dashboard focuses on the following KPIs:

- **Total Customers**
- **Total Churned Customers**
- **Churn Rate (%)**
- **Retention Rate (%)**
- **Average Balance**
- **Average Credit Score**
- **Complaint Rate (%)**

---

## 📈 Dashboard Features
The Power BI dashboard includes:

- KPI cards for churn and customer overview
- Churn Rate analysis by Geography
- Churn Rate analysis by Age Group
- Churn Rate by Active vs Inactive Members
- Churn analysis by Number of Products and Card Type
- Scatter plot: Balance vs Estimated Salary (segmented by churn status)
- Interactive slicers for filtering the analysis

---

## 🔍 Key Insights (Examples)
Some key insights obtained from the analysis include:

- Inactive members show significantly higher churn rates compared to active customers.
- Certain regions/countries present a higher churn concentration.
- Customers who filed complaints are more likely to exit the bank.
- Churn tends to increase in specific age ranges.
- Customers with fewer products show higher churn probability.

---

## 💡 Business Recommendations
Based on the findings, the following actions are recommended:

- Improve engagement programs targeting inactive customers.
- Strengthen retention strategies in high-churn regions.
- Implement proactive customer support for clients who submit complaints.
- Offer personalized product bundles to increase product adoption.
- Design loyalty campaigns for customers in high-risk age segments.

---

## 📷 Dashboard Preview
Dashboard screenshots are available in the `/screenshots` folder.

---

## 📁 Repository Structure
- `/dataset` → original dataset file
- `/screenshots` → dashboard preview images
- `.pbix` file → Power BI report

---

## 🔗 Author
**Marikena Praiz**  
Data Analyst | Power BI | Tableau | Excel  
LinkedIn: www.linkedin.com/in/
marikena-praiz-60b4b924a
