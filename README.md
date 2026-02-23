# EXAMENMODULO4COMERCIOYA
Entrega proyecto modulo 4
Análisis de Comportamiento de Clientes – ComercioYA
📌 Descripción del Proyecto

Este proyecto presenta un Análisis Exploratorio de Datos (EDA) realizado para la empresa ficticia ComercioYA, dedicada al comercio electrónico.

El objetivo principal fue analizar el comportamiento de los clientes para identificar patrones de compra, relaciones entre variables y generar recomendaciones estratégicas basadas en evidencia estadística.

El análisis incluye estadística descriptiva, correlación y modelos de regresión lineal utilizando Python.

🎯 Objetivo de Negocio

Apoyar la toma de decisiones comerciales mediante:

Identificación de variables que influyen en el gasto

Segmentación de clientes según comportamiento

Detección de clientes de alto valor

Evaluación predictiva del monto de compra

📂 Descripción del Dataset

El dataset contiene 2000 registros de clientes con variables cuantitativas y categóricas.

🔢 Variables Numéricas

monto_compra

visitas_mensuales

numero_compras

edad

devoluciones

🔠 Variables Categóricas

región

método_pago

categoría_producto

reseña_score

🔎 Metodología Aplicada

El proyecto se desarrolló en 6 etapas:

1️⃣ Análisis Exploratorio de Datos (EDA)

Identificación de tipos de variables

Detección de valores faltantes

Identificación de inconsistencias

2️⃣ Estadística Descriptiva

Media, mediana, varianza y desviación estándar

Cuartiles y percentiles

Histogramas y boxplots

3️⃣ Análisis de Correlación

Matriz de correlación

Coeficiente de Pearson

Scatterplots

4️⃣ Regresión Lineal

Modelo simple

Modelo múltiple

Evaluación con R², MAE y MSE

5️⃣ Visualización Avanzada

Pairplot

Heatmap

Violinplot

Jointplot

6️⃣ Visualización Personalizada

Subplots con Matplotlib

Exportación de gráficos

📊 Principales Hallazgos

Existe correlación positiva entre visitas_mensuales y monto_compra.

numero_compras es una variable estadísticamente significativa.

La edad no resulta significativa en el modelo múltiple.

Se identificó un segmento de clientes de alto valor.

El modelo de regresión múltiple explica un 33.2% de la variabilidad del gasto (R² = 0.332).

💡 Insights de Negocio

Las variables conductuales influyen más que las demográficas.

Aumentar la frecuencia de visitas puede incrementar el gasto.

Es recomendable segmentar clientes según comportamiento.

Existen oportunidades de fidelización para clientes premium.

📈 Desempeño del Modelo
Métrica	Regresión Simple	Regresión Múltiple
R²	0.091	0.332
R² Ajustado	0.091	0.331
MAE	—	127.79
MSE	—	37,839
🛠 Tecnologías Utilizadas

Python

Pandas

Seaborn

Matplotlib

Statsmodels

📁 Estructura del Proyecto
├── data/
├── notebooks/
├── images/
├── informe_final.pdf
└── README.md
🔮 Mejoras Futuras

Incorporar más variables predictoras

Aplicar modelos de Machine Learning

Realizar segmentación mediante clustering

Implementar dashboard interactivo

👨‍💻 Autor Cristóbal  Hernández Labarca
 
Cristóbal Hernández L.
Estudiante de Análisis de Datos
