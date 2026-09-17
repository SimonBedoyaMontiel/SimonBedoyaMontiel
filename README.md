## Simón Bedoya

**Data Scientist** · Estudiante de Ingeniería de Software e Ingeniería Mecatrónica

Trabajo en el punto donde los datos se convierten en decisiones. Vengo de tres formaciones que se complementan: mecatrónica me enseñó a entender sistemas completos, ingeniería de software a construirlos, y la ciencia de datos a sacarles respuestas.

Me interesa el ciclo completo — desde la limpieza del dato hasta el modelo desplegado y monitoreado en producción — y elegir el modelo que resuelve el problema, no el más complejo.

---

### Proyectos

**[credit-risk-mlops](https://github.com/simonbm17/credit-risk-mlops)** — Riesgo crediticio con enfoque MLOps

Predicción del comportamiento de pago de clientes de crédito, con el ciclo completo: EDA, ingeniería de características, cuatro modelos comparados y despliegue en una API con FastAPI y Docker. El reto principal fue el desbalance de clases: los malos pagadores son solo el 5%. La primera evaluación daba un recall del 100%, sospechosamente perfecto — estaba midiendo la clase mayoritaria. Al corregirlo, el Random Forest quedó con un F1 de 0.84 sobre la clase de interés y un ROC-AUC de 0.96.

`Python` · `scikit-learn` · `XGBoost` · `FastAPI` · `Docker` · `Streamlit`

**[bank-churn-prediction](https://github.com/simonbm17/bank-churn-prediction)** — Predicción y segmentación de abandono de clientes

Un banco digital que pierde el 20% de sus clientes al año. El proyecto combina modelado supervisado para predecir quién se va (XGBoost, ROC-AUC de 0.870) con segmentación no supervisada para agrupar la acción comercial. El hallazgo más interesante llegó por partida doble: K-Means, sin recibir la variable de abandono, identificó por su cuenta el mismo segmento de alto riesgo que ya habían señalado los modelos supervisados.

`Python` · `scikit-learn` · `XGBoost` · `LightGBM` · `CatBoost` · `K-Means`

**[seasonal-stock-recommender](https://github.com/simonbm17/seasonal-stock-recommender)** — Pronóstico de demanda estacional _(proyecto en equipo)_

Sistema de predicción de stock para e-commerce, desarrollado con el equipo MetricEdge. Incluye ETL reproducible, backtesting rolling sin fuga temporal y una demo en Streamlit con monitoreo de data drift. Comparamos tres métodos de pronóstico y ganó el más simple, con un error del 2.36%: agregar tendencia no aportaba nada en una serie sin crecimiento sostenido.

`Python` · `pandas` · `Streamlit` · `Power BI` · `statsmodels`

---

### Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat&logo=pandas&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-337AB7?style=flat)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat&logo=postgresql&logoColor=white)
![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

---

### Formación

- **Data Science** — Soy Henry
- **Ingeniería de Software** _(en curso)_
- **Ingeniería Mecatrónica** _(en curso)_

---

### Contacto

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/sim%C3%B3n-bedoya-05bb57398/)
