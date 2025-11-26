# Repo-1-H-S-DataAnalysis_Accidentes_Laborales
# 🏭 Análisis de Accidentes Laborales en EE.UU. (2015-2024)

_Un estudio de Data Analysis para la Gestión de Riesgos y la Seguridad Ocupacional._

## 🎯 Objetivo del Proyecto

Analizar más de **95.800 registros de accidentes laborales** reportados en Estados Unidos. El objetivo principal es identificar patrones de **severidad**, los sectores con mayor **riesgo concentrado** y focalizar geográficamente las áreas de alta siniestralidad para una toma de decisiones informada en Higiene y Seguridad.

## 🛠️ Tecnologías Utilizadas

| Categoría | Herramientas |
| :--- | :--- |
| **Lenguajes** | `Python`, `SQL (Conceptos)` |
| **Bibliotecas** | `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`, `Plotly` |
| **Entorno** | `Jupyter Notebook / Google Colab` |

## ✔️ Metodología y Feature Engineering

El proyecto se centró en aplicar técnicas de limpieza de datos (manejo de nulos, normalización de categorías) y **Feature Engineering** para crear variables de valor:

1.  **Creación de la variable "Gravedad":** Se clasificaron las lesiones en una escala numérica de severidad para permitir análisis de correlación y visualizaciones de riesgo relativo.
2.  **Clasificación NAICS:** Se agruparon los datos por el estándar **NAICS** para clasificar el riesgo por sector industrial de manera auditable y profesional.
3.  **Análisis Relacional:** Se cruzó la variable `Gravedad` con la densidad industrial por ciudad.

## 🚀 Insights Clave (Resultados Estratégicos)

| Insight | Valor para el Negocio / H&S |
| :--- | :--- |
| **Concentración de Riesgo (Pareto)** | Los eventos de **Atrapamiento en Maquinaria** y **Caídas** representan más del **32%** del riesgo total. Esto justifica la asignación prioritaria de recursos a protocolos LOTO y protección contra caídas. |
| **Focos de Riesgo por Sector** | Los sectores de **Manufactura** y **Construcción** (Clasificación NAICS) son los mayores concentradores de accidentes, demandando programas de seguridad específicos e intensivos. |
| **Riesgo Geográfico Relativo** | **Chicago** y **Houston** no solo tienen muchos accidentes, sino que presentan el coeficiente más alto de **gravedad relativa**. Esto indica una falla en la gestión de riesgos local que debe ser auditada inmediatamente. |

---

https://colab.research.google.com/drive/1Cw8a_44ns_oTje4RF2MJ1By_LF78v9M4?usp=sharing
