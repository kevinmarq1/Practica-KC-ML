# Practica-KC-ML
Análisis de precios de Airbnb con ML Este repositorio contiene un modelo de Machine Learning para predecir precios de alojamientos mediante regresión y selección de características. Se comparan Ridge, Lasso, RandomForest y XGBoost, con optimización mediante GridSearchCV. Incluye análisis, limpieza de datos y predicción de precios futuros.
Practica-KC-ML
📊 Análisis de precios de Airbnb con Machine Learning

📌 Descripción
Este repositorio contiene un proyecto de Machine Learning aplicado a la predicción de precios de alojamientos en Airbnb. Se han utilizado técnicas de regresión, selección de características y optimización de modelos para obtener estimaciones precisas.

⚡ Tecnologías y herramientas utilizadas
✅ Python – Lenguaje principal para procesamiento de datos y modelado. ✅ pandas y numpy – Manipulación de datos y estructuras numéricas. ✅ scikit-learn – Modelos de regresión (Ridge, Lasso, RandomForestRegressor, XGBoostRegressor). ✅ matplotlib y seaborn – Visualizaciones de tendencias y análisis exploratorio. ✅ GridSearchCV – Optimización de hiperparámetros para mejorar la precisión de los modelos.

🚀 Objetivo del proyecto
El propósito de este trabajo es analizar datos reales de Airbnb y construir un modelo de aprendizaje automático que permita: 🔹 Predecir precios de alojamientos en función de características relevantes. 🔹 Comparar diferentes modelos para elegir el más preciso. 🔹 Optimizar la predicción usando técnicas avanzadas como GridSearchCV. 🔹 Generar estimaciones futuras, como el precio esperado de Airbnb en mayo de 2030.

🔍 Estructura del proyecto
📌 notebooks/ – Contiene los análisis y desarrollo de los modelos en Jupyter Notebook. 📌 data/ – Almacena los datasets utilizados en el proyecto. 📌 src/ – Código fuente con funciones para limpieza de datos y entrenamiento de modelos. 📌
🎯 Cómo usar este repositorio
1️⃣ Clonar el repositorio
bash
git clone https://github.com/kevinmarq1/Practica-KC-ML.git
cd Practica-KC-ML
2️⃣ Instalar dependencias
bash
pip install -r requirements.txt
3️⃣ Ejecutar el análisis en Jupyter Notebook
bash
jupyter notebook notebooks/airbnb_analysis.ipynb
💡 Dentro del notebook, puedes seguir los pasos de limpieza de datos, entrenamiento de modelos y predicción de precios.

📊 Comparación de modelos
Modelo	RMSE Inicial	R² Inicial	RMSE Optimizado	R² Optimizado
Ridge Regression	0.72	0.43	-	-
Lasso Regression	0.72	0.43	-	-
RandomForestRegressor	0.63	0.55	0.62	0.56
XGBoostRegressor	0.61	0.58	0.59	0.61
📌 Conclusión: ✅ XGBoostRegressor ha sido el modelo más preciso, con menor error (RMSE) y mayor capacidad explicativa (R²). ✅ La optimización con GridSearchCV mejoró los resultados, demostrando la importancia del ajuste de hiperparámetros. ✅ Este análisis permite realizar predicciones futuras, como estimar el precio de Airbnb en mayo de 2030 basado en datos históricos.
