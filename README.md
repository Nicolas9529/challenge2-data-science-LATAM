# Análisis de Evasión de Clientes - TelecomX

Este proyecto desarrolla un análisis exploratorio y estadístico sobre la pérdida de clientes (Churn) de la empresa TelecomX. El objetivo es identificar patrones críticos y proponer estrategias basadas en datos para mejorar la retención.

## Estructura del Proyecto
El análisis se divide en las siguientes etapas:

Ingesta y Limpieza: Consolidación de datos desde JSON y tratamiento de valores nulos/inconsistentes.

Análisis Descriptivo: Resumen estadístico de variables numéricas y categóricas.

Visualización de Datos (EDA): Uso de Matplotlib y Seaborn para identificar tendencias de abandono.

Matriz de Correlación: Análisis de la relación entre costos, permanencia y evasión.

Informe Estratégico: Conclusiones y recomendaciones de negocio.

## Tecnologías Utilizadas
Python 
Pandas: Manipulación y limpieza de datos.
Matplotlib & Seaborn: Visualización de datos avanzada.
Google Colab / Jupyter Notebooks

## Hallazgos Principales
Tasa de Churn: 26.58%.

Factor Crítico: Los clientes con contratos mensuales y métodos de pago manuales (Electronic Check) presentan la mayor deserción.
Sensibilidad al Precio: Los clientes con cargos mensuales más altos tienen una correlación positiva con la evasión.
