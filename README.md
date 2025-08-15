# 📊 Telecom X - Análisis de Evasión de Clientes

Este proyecto corresponde a un reto de análisis de datos para **Telecom X**, cuyo objetivo es comprender los factores que llevan a la pérdida de clientes (*Customer Churn*).

## 🎯 Objetivos
- Importar y manipular datos desde una API (JSON en GitHub).
- Aplicar el flujo **ETL** (Extracción, Transformación y Carga).
- Realizar un **Análisis Exploratorio de Datos (EDA)**.
- Generar un informe con *insights* clave para el negocio.

## 📂 Archivos
- `TelecomX_ETL_EDA.ipynb` → Cuaderno Jupyter con el flujo completo:
  1. **Extracción** → Descarga de datos desde GitHub.
  2. **Transformación** → Limpieza y normalización de datos.
  3. **Carga y análisis** → Estadísticas y visualizaciones.
  4. **Informe final** → Resultados y exportaciones.
- `telecomx_clean.csv` → Datos limpios listos para modelado (generado por el cuaderno).
- `resumen_estadistico.csv` → Resumen estadístico exportado.

## 🚀 Requisitos
- Python 3.8+
- Librerías:
  ```bash
  pip install pandas requests matplotlib
  ```

## ▶️ Ejecución
1. Clonar el repositorio o descargar este proyecto.
2. Abrir el cuaderno `TelecomX_ETL_EDA.ipynb` en Jupyter Notebook o JupyterLab.
3. Ejecutar las celdas en orden.

## 📌 Notas
- Los datos provienen del [repositorio oficial del reto](https://github.com/ingridcristh/challenge2-data-science-LATAM).
- Este proyecto es una base para posteriores modelos predictivos de churn.
