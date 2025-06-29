# TelecomX_LATAM-por-A.-Reyes-P.
Análisis de evasión de clientes de la empresa Telecom X.

# 📊 Telecom X - Análisis de Evasión de Clientes (Churn)

[![Python](https://img.shields.io/badge/Python-3.11-blue.svg)](https://www.python.org/)
[![Platform](https://img.shields.io/badge/Platform-Google_Colab-yellow?logo=googlecolab)](https://colab.research.google.com/)
[![Status](https://img.shields.io/badge/Status-En%20Desarrollo-orange)]()
[![License](https://img.shields.io/badge/Licencia-Educativa-blue)]()

Este proyecto tiene como objetivo analizar los datos de clientes de **Telecom X** para identificar patrones asociados a la **evasión de clientes** (churn). A partir de este análisis, se busca generar **insights estratégicos** que permitan a la empresa mejorar la **retención de clientes**.

---

## 🚀 Objetivo

Analizar de manera exploratoria los datos de clientes para:

- Identificar variables clave que explican la evasión.
- Determinar características de clientes con mayor propensión al abandono.
- Proveer una base sólida para modelos predictivos de churn.
- Apoyar la toma de decisiones estratégicas en retención.

---

## 🗂️ Estructura del proyecto

📁 TelecomX_Churn_Analysis/
│
├── TelecomX_Data.json # Fuente de datos original
├── TelecomX_diccionario.md # Diccionario de datos
├── churn_analysis.ipynb # Notebook de análisis exploratorio
├── README.md # Este archivo

yaml
Copiar
Editar

---

## 📥 Extracción y Procesamiento

Los datos fueron extraídos desde un archivo `.json` estructurado en formato anidado. Se aplicaron técnicas ETL para:

- Extraer estructuras anidadas (`customer`, `phone`, `internet`, `account`)
- Transformar y limpiar los datos (tratamiento de NaNs, tipado de columnas)
- Crear variables útiles como `MonthlyCharges` y `TotalCharges`
- Eliminar columnas sin información útil

---

## 📈 Análisis Exploratorio Realizado

Se evaluaron múltiples variables en relación al churn:

- Distribución general de clientes que se van vs. los que permanecen
- Comparación por género, tipo de contrato, tipo de servicio de internet
- Relación entre churn y:
  - Antigüedad del cliente (`tenure`)
  - Cargos mensuales (`MonthlyCharges`)
  - Total gastado (`TotalCharges`)

---

## 🔍 Principales Insights

- Los contratos **mes a mes** presentan la tasa más alta de churn.
- Clientes con **menos de 12 meses de antigüedad** abandonan más.
- Usuarios con **servicio de fibra óptica** tienen mayor probabilidad de churn.
- Mayores cargos mensuales pueden estar correlacionados con abandono.

---

## 🛠️ Herramientas y Librerías

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab (entorno)

---

## 📌 Próximos pasos

- Entrenamiento de un modelo predictivo de churn (clasificación)
- Evaluación de precisión y recall de diferentes algoritmos
- Desarrollo de dashboard de monitoreo (Power BI / Dash / Streamlit)

---

## 🧠 Autor

**Andrés Reyes Pauzoca**  
Asistente de análisis de datos | Proyecto educativo de Data Science

---

## 📄 Licencia

Este proyecto se entrega como parte de un estudio de caso educativo. Uso libre para fines académicos y personales.
