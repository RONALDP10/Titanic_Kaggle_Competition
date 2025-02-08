# 🚢 Titanic Kaggle Competition

## 📌 Descripción
Este proyecto tiene como objetivo predecir la supervivencia de los pasajeros del Titanic utilizando Machine Learning. Se emplea un modelo de clasificación basado en Random Forest, optimizando los datos a través de preprocesamiento y análisis exploratorio.

## 📊 Dataset
Los datos provienen del desafío de Kaggle "Titanic - Machine Learning from Disaster" y contienen información sobre pasajeros, como edad, clase, género y número de familiares a bordo.

## ⚙️ Tecnologías utilizadas
- **Python**
- **Pandas & NumPy** (Manejo y procesamiento de datos)
- **Matplotlib & Seaborn** (Análisis exploratorio y visualización de datos)
- **Scikit-learn** (Modelado predictivo con RandomForestClassifier)

## 🛠️ Preprocesamiento de Datos
- Manejo de valores nulos en `Age` y `Embarked`
- Conversión de variables categóricas con `OrdinalEncoder`
- Normalización de variables según el modelo utilizado

## 🤖 Modelado y Evaluación
- Se entrenó un modelo **Random Forest Classifier**
- Métrica principal: **Accuracy**
- Validación cruzada para evaluar el desempeño

## 📈 Resultados y Conclusiones
El modelo entrenado logra una **accuracy del 80%%**, demostrando la importancia del preprocesamiento y la selección de features en problemas de clasificación. 🚢📊



