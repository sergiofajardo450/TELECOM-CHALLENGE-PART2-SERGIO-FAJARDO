# 📊 Telecom X – Análisis y Predicción de Churn

## 📌 Descripción del Proyecto

Este proyecto tiene como objetivo analizar la **evasión de clientes (Churn)** en Telecom X utilizando herramientas de análisis de datos y Machine Learning en Python.

La empresa enfrenta una alta tasa de cancelación de clientes, por lo que se desarrolló un análisis exploratorio de datos (EDA) y modelos predictivos para identificar los factores que influyen en la decisión de los clientes de cancelar el servicio.

A partir de este análisis se generan **insights estratégicos** que pueden ayudar a mejorar la retención de clientes.

---

# 🎯 Objetivos del Proyecto

* Importar y manipular datos desde una API.
* Aplicar el proceso **ETL (Extracción, Transformación y Carga)**.
* Realizar **Análisis Exploratorio de Datos (EDA)**.
* Crear visualizaciones para identificar patrones.
* Construir modelos de **Machine Learning** para predecir la evasión de clientes.
* Generar conclusiones y recomendaciones para el negocio.

---

# 🛠 Tecnologías y Librerías Utilizadas

El proyecto fue desarrollado en **Python** utilizando las siguientes librerías:

* pandas → manipulación y análisis de datos
* matplotlib → visualización de datos
* seaborn → gráficos estadísticos
* scikit-learn → modelos de Machine Learning

---

# 📂 Estructura del Proyecto

TelecomX-Churn-Analysis

│
├── TelecomX_Data.json → Dataset original desde la API
├── TelecomX_clean.csv → Dataset limpio generado en el proceso ETL
├── TelecomX_Analysis.ipynb → Notebook con el análisis completo
└── README.md → Documentación del proyecto

---

# 🔄 Proceso de Análisis

## 1️⃣ Extracción de Datos

Los datos se obtienen desde un repositorio en GitHub en formato **JSON** y se cargan en un DataFrame de pandas.

## 2️⃣ Transformación de Datos

Se aplican varias transformaciones:

* Aplanamiento de estructuras JSON
* Conversión de tipos de datos
* Eliminación de duplicados
* Tratamiento de valores nulos
* Codificación de variables categóricas (One-Hot Encoding)

## 3️⃣ Carga de Datos

El dataset limpio se guarda como:

TelecomX_clean.csv

Este archivo se utiliza posteriormente para el modelado.

---

# 📊 Análisis Exploratorio de Datos (EDA)

Se realizaron diferentes visualizaciones para identificar patrones:

* Distribución de clientes que cancelan el servicio
* Relación entre churn y variables categóricas
* Análisis de variables numéricas
* Correlación entre variables

Este análisis permite detectar factores asociados con la cancelación de clientes.

---

# 🤖 Modelos de Machine Learning

Se entrenaron dos modelos de clasificación:

### 1️⃣ Regresión Logística

Modelo estadístico utilizado para problemas de clasificación binaria.

### 2️⃣ Random Forest

Modelo basado en árboles de decisión que permite capturar relaciones complejas entre variables.

Los modelos fueron evaluados mediante:

* Accuracy
* Precision
* Recall
* F1 Score
* Matriz de confusión

---

# 📈 Resultados e Insights

El análisis permitió identificar algunos factores relevantes asociados al churn:

* Clientes con **contratos mensuales** presentan mayor probabilidad de cancelación.
* Los **cargos mensuales elevados** pueden aumentar el riesgo de churn.
* Clientes con **mayor tiempo de permanencia** tienen menor probabilidad de cancelar.
* Algunos **métodos de pago** están más asociados con cancelaciones.

---

# 💡 Recomendaciones

A partir del análisis se proponen las siguientes estrategias:

* Incentivar contratos de largo plazo.
* Implementar programas de fidelización para clientes nuevos.
* Ofrecer promociones a clientes con alto riesgo de churn.
* Revisar planes con cargos mensuales elevados.

---

# 👨‍💻 Autor

Proyecto desarrollado como parte de un desafío de **Análisis de Datos y Machine Learning**.

Autor: Sergio
