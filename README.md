# 📊 Telecom X PARTE 2 – Predicción de Cancelación de Clientes (Churn)

## 👋 Sobre este proyecto

Hola! Este proyecto forma parte del **Challenge de Data Science de Alura LATAM**.
El objetivo fue analizar datos de clientes de **Telecom X** para intentar **predecir qué clientes podrían cancelar su servicio (churn)** usando modelos de Machine Learning.

La idea es que la empresa pueda **anticiparse a estas cancelaciones** y tomar decisiones para mejorar la experiencia de los clientes y evitar que se vayan.

Este proyecto continúa el trabajo realizado en la **Parte 1 del challenge**, donde primero limpié, transformé y exploré los datos.

---

## 🎯 Objetivo

Construir modelos predictivos que permitan identificar **clientes con mayor probabilidad de cancelar el servicio**, analizando diferentes variables relacionadas con su contrato, consumo y características del servicio.

---

## 🧠 Lo que hice en este análisis

Durante este proyecto trabajé en varias etapas importantes del proceso de Data Science:

* Carga de los datos previamente tratados
* Eliminación de columnas que no aportaban valor al modelo
* Transformación de variables categóricas a variables numéricas
* Análisis de correlación entre variables
* Visualización de patrones relacionados con la cancelación de clientes
* División del dataset en datos de **entrenamiento** y **prueba**
* Entrenamiento de modelos de **Machine Learning**
* Evaluación del rendimiento de los modelos
* Análisis de las variables más importantes para la predicción

---

## ⚙️ Tecnologías utilizadas

En este proyecto utilicé principalmente Python y algunas librerías muy usadas en análisis de datos:

* Python
* Pandas
* Numpy
* Matplotlib
* Seaborn
* Scikit-learn
* Google Colab

---

## 🤖 Modelos utilizados

Para la predicción del churn probé diferentes modelos de clasificación:

* Regresión Logística
* Árbol de Decisión
* Random Forest

Luego comparé su rendimiento utilizando métricas como:

* Accuracy
* Precision
* Recall
* F1-score
* Matriz de confusión

---

## 🔎 Principales hallazgos

Durante el análisis se observaron algunos factores que parecen influir bastante en la cancelación de clientes:

* Clientes con **contratos mensuales** tienden a cancelar más.
* Los clientes con **menos tiempo en la empresa** tienen mayor riesgo de churn.
* Algunos **cargos mensuales altos** también pueden influir en la cancelación.

Estos factores pueden ayudar a la empresa a entender mejor el comportamiento de sus clientes.

---

## 💡 Posibles estrategias para la empresa

Basado en los resultados del análisis, algunas ideas que podrían ayudar a reducir la cancelación son:

* Ofrecer incentivos para que los clientes cambien a **contratos de mayor duración**.
* Crear programas de **fidelización para clientes nuevos**.
* Mejorar beneficios o promociones para clientes con **cargos mensuales más altos**.

---

## 📁 Estructura del proyecto

```
telecomx-churn-prediction
│
├── TelecomX_Churn_Model.ipynb
├── datos_tratados.csv
└── README.md
```

---

## 🚀 Reflexión final

Este proyecto fue una experiencia muy interesante porque me permitió practicar varias etapas del proceso de **Data Science y Machine Learning** en un caso más cercano a un problema real de negocio.

Todavía estoy aprendiendo, pero este challenge me ayudó mucho a entender mejor cómo los datos pueden utilizarse para **tomar decisiones más inteligentes en una empresa**.

¡Gracias por revisar este proyecto! 🙂

Autor : Danny Andrew Rimac Roque
Correo : danny.andrew.r.r@gmail.com


