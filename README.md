# Challenge_Alura_Store

# 📊 Data Analytics Pipeline: Alura Store Performance
> **Optimización de activos y toma de decisiones basada en datos para la gestión de retail.**

[![Python](https://img.shields.io/badge/Python-3.12-blue?style=flat-square&logo=python)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Library-Pandas-informational?style=flat-square)](https://pandas.pydata.org/)
[![Matplotlib](https://img.shields.io/badge/Library-Matplotlib-orange?style=flat-square)](https://matplotlib.org/)
[![Colab](https://img.shields.io/badge/Runtime-Google%20Colab-yellow?style=flat-square&logo=googlecolab)](https://colab.research.google.com/drive/1_c49duqJZq_-hqOppSo4M2YfW55pen6p)

---

## 🎯 Resumen del Proyecto
Este proyecto consiste en un **análisis integral de KPIs** (Key Performance Indicators) aplicado a cuatro unidades de negocio de la franquicia **Alura Store**. El objetivo técnico fue procesar volúmenes de ventas, métricas de satisfacción y costos logísticos para identificar ineficiencias operativas.

El entregable final proporciona al *stakeholder* (Sr. Juan) una base cuantitativa para ejecutar una desinversión estratégica: **determinar qué sucursal presenta el menor rendimiento integral.**

---

## 🛠️ Stack Tecnológico
Para el desarrollo de la solución se empleó un ecosistema de Ciencia de Datos estándar en la industria:

| Componente | Herramientas |
| :--- | :--- |
| **Lenguaje** | `Python 3.12` |
| **Manipulación de Datos** | `Pandas`, `NumPy` |
| **Visualización** | `Matplotlib`, `Seaborn` |
| **Geolocalización** | `Folium` |
| **Entorno** | `Google Colab` |

---

## 🏗️ Flujo de Trabajo (Workflow)
El análisis se dividió en las siguientes fases de ingeniería:

1.  **Ingesta de Datos:** Extracción y carga de fuentes externas.
2.  **Exploratory Data Analysis (EDA):** Evaluación de la integridad de los datos y estructuras.
3.  **Procesamiento y Métricas:**
    * Cálculo de facturación bruta.
    * Segmentación por categorías de producto.
    * Modelado de costos de envío y logística.
4.  **Visualización Geoespacial:** Mapeo de puntos de venta y cobertura.

---

## 📉 Análisis de Resultados
Tras el procesamiento de los datasets, se obtuvieron los siguientes *insights* críticos:

| Unidad | Facturación (COP) | Rating Promedio | Observación Técnica |
| :--- | :--- | :--- | :--- |
| **Tienda 1** | **$1,150,880,400** | 3.98⭐ | Alta rentabilidad, baja eficiencia en CX y altos costos logísticos. |
| **Tienda 2** | Estable | 4.02⭐ | Operación equilibrada con alta previsibilidad. |
| **Tienda 3** | Media | **4.05⭐** | Máxima eficiencia en satisfacción al cliente. |
| **Tienda 4** | $1,038,375,700 | 4.00⭐ | **Mínimo rendimiento financiero y baja diversificación.** |

---

## 💡 Conclusiones y Recomendaciones Económicas

1.  **Desinversión Prioritaria:** Se recomienda la venta de la **Tienda 4**. Sus métricas de facturación están por debajo del umbral de rentabilidad óptimo en comparación con el resto del portafolio.
2.  **Escalabilidad:** Los procesos de la **Tienda 2** deben ser documentados como "Best Practices" para su replicación.
3.  **Optimización de Costos:** La **Tienda 1** requiere una reingeniería en su cadena de suministro para mitigar los altos costos de envío que afectan el margen neto.
4.  **Estrategia de Crecimiento:** Impulsar el inventario de la **Tienda 3** aprovechando su alta fidelización de clientes para escalar los ingresos.

