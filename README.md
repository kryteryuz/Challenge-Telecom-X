# Challenge Churn Telecom X 📉📊

## Insignias

[![Estado del Proyecto](https://img.shields.io/badge/estado-terminado-brightgreen)](https://github.com/tu_usuario/telecomx-churn)  
[![Licencia](https://img.shields.io/badge/licencia-MIT-green)](https://opensource.org/licenses/MIT)

## Índice

1. [Descripción del Proyecto](#descripción-del-proyecto)  
2. [Tecnologías Utilizadas](#tecnologías-utilizadas)  
3. [Personas Contribuyentes](#personas-contribuyentes)  
4. [Personas Desarrolladoras del Proyecto](#personas-desarrolladoras-del-proyecto)  
5. [Licencia](#licencia)  

---

## Descripción del Proyecto

**Telecom X Churn Analysis** es un proyecto de análisis exploratorio de datos (EDA) diseñado para investigar las causas de la alta tasa de evasión de clientes (churn) en una compañía de telecomunicaciones.  

Se llevó a cabo un flujo completo de ETL:

- **Extracción** de datos desde una API JSON con estructuras anidadas.  
- **Transformación** y normalización de campos anidados (`customer`, `phone`, `internet`, `account`).  
- **Limpieza** de valores inválidos y conversión de tipos (`GastoMensual`, `GastoTotal`, variables binarias).  
- **Enriquecimiento** con la métrica `Cuentas_Diarias` (GastoMensual / 30).  

El análisis exploratorio incluyó:

- Distribución global: **5163** clientes permanecieron vs **1869** que se fueron.  
- Comportamiento según **género**, **tipo de contrato** y **método de pago**.  
- Patrones en variables numéricas: gasto mensual, meses de contrato y cuentas diarias.  
- Visualizaciones con barras anotadas y boxplots con medias para resaltar insights.

---

## Tecnologías Utilizadas

- **Python 3** – Lenguaje principal  
- **Pandas** – Limpieza y manipulación de datos  
- **NumPy** – Cálculos numéricos y creación de variables  
- **requests** – Extracción de datos desde API  
- **Matplotlib & Seaborn** – Visualizaciones estadísticas  
- **Jupyter Notebook** – Documentación y ejecución de análisis  

---

## Personas Contribuyentes

Este proyecto es gestionado de forma individual; contribuciones futuras son bienvenidas vía *fork* y *pull request*.

---

## Personas Desarrolladoras del Proyecto

- **Bryan Vera** – Analista de datos y desarrollador de visualizaciones.

---

## Licencia

Este proyecto está bajo la Licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más detalles.  
