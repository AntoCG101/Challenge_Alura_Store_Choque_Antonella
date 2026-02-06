# 📊 Análisis Estratégico Alura Store - Challenge Data Science

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Pandas](https://img.shields.io/badge/Library-Pandas-150458)
![Matplotlib](https://img.shields.io/badge/Library-Matplotlib-orange)
![Status](https://img.shields.io/badge/Status-Finalizado-success)

## 🎯 Propósito del Proyecto
Este proyecto forma parte del **Challenge de Data Science de Alura Latam**. El objetivo principal es actuar como consultor de datos para el Sr. Juan, dueño de una cadena de tiendas, quien busca optimizar su capital.

La misión es analizar el rendimiento de **4 Tiendas** utilizando datos históricos de ventas, logística y satisfacción del cliente para responder una pregunta estratégica clave:
> **¿Qué tienda debería ser vendida (liquidada) por ser la menos eficiente?**

## 🗂️ Estructura del Repositorio
El análisis se encuentra centralizado en el siguiente Jupyter Notebook:

* 📄 **`Challenge_Alura_01.ipynb`**: Cuaderno principal que contiene todo el ciclo de vida del dato:
    1.  **Carga de Datos:** Importación de datasets desde fuentes remotas (CSV).
    2.  **Limpieza y Preprocesamiento:** Unificación de tablas y manejo de tipos de datos.
    3.  **Análisis Exploratorio (EDA):** Cálculo de métricas clave (KPIs) como ingresos, volumen de ventas y ratings.
    4.  **Visualización:** Generación de gráficos comparativos (Barras, Torta, Gráficos Agrupados).
    5.  **Informe Final:** Conclusión de negocio justificada con datos.

## 🔍 Insights y Hallazgos Clave
Tras procesar los datos, se descubrieron patrones determinantes para la toma de decisiones:

* **📉 La Tienda Menos Rentable:** Se identificó que la **Tienda 4** es la candidata ideal para la venta. A pesar de tener los costos de envío más competitivos, es la que genera **menores ingresos totales** (~$1,038 Millones), con una brecha significativa respecto a la líder.
* **🏆 La "Vaca Lechera":** La **Tienda 1** lidera la facturación (~$1,150 Millones) y el volumen de ventas, aunque presenta desafíos operativos como la calificación de cliente más baja (3.97) y costos de envío elevados.
* **📦 Preferencias de Consumo:** Se detectaron diferencias notables en el mix de productos; por ejemplo, el *Microondas* es el best-seller de la Tienda 1, mientras que artículos como el *Celular ABXY* tienen una rotación mínima.

## 📊 Ejemplos de Visualizaciones
El proyecto incluye gráficos avanzados para comunicar los hallazgos:
* **Gráfico de Ingresos (Barras):** Para comparar la facturación millonaria de cada sucursal.
* **Barras Agrupadas:** Comparativa directa entre el "Producto Más Vendido" y el "Menos Vendido" para medir la brecha de catálogo.
* **Análisis de Costos Logísticos:** Evaluación del impacto del costo de envío en cada tienda.

## 🚀 Instrucciones de Ejecución
Este proyecto fue desarrollado en **Google Colab**. Para interactuar con el código:

1.  Abre el archivo `Challenge_Alura_01.ipynb` desde este repositorio.
2.  Si deseas ejecutarlo, verás un botón **"Open in Colab"** (o descárgalo y ábrelo en Jupyter Notebook).
3.  **Importante:** El notebook carga los datos directamente desde URLs públicas de GitHub, por lo que **no es necesario descargar los CSVs manualmente**. Solo asegúrate de tener conexión a internet.
4.  Ejecuta las celdas en orden secuencial (Run All) para reproducir el análisis y los gráficos.

---
*Proyecto realizado por **Antonella Choque Goljanek** para el Challenge de Data Science - Alura Latam (2025).*
