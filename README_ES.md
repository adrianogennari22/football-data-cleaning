🇺🇸 English version: [Read here](README.md)

# ⚽ Análisis de Partidos de Fútbol Europeo  
### Data Cleaning • Exploratory Data Analysis (EDA) • Feature Engineering

---

## 📌 Descripción del Proyecto

Este proyecto explora un dataset de fútbol europeo que contiene estadísticas históricas de partidos a lo largo de múltiples ligas y temporadas.

El objetivo del proyecto es:

- Realizar Data Cleaning sobre datos crudos  
- Ejecutar un Exploratory Data Analysis (EDA) estructurado  
- Identificar patrones en la distribución de goles y resultados  
- Evaluar la ventaja de local (home advantage)  
- Preparar el dataset para futuros modelos de Machine Learning  

El proyecto sigue un workflow profesional desde raw data hasta generación de insights analíticos.

---

## 📊 Resumen del Dataset

- 25.979 matches
- 115 features originales
- Estadísticas a nivel match
- Múltiples ligas y temporadas
- Variables numéricas y categóricas

Después del Data Cleaning:

- Se eliminaron columns con alto porcentaje de missing values
- No se encontraron duplicated rows
- Se trataron los null values restantes
- Se seleccionaron base features para el análisis estructurado

---

## 🧹 Data Cleaning & Preparation

El pipeline de limpieza incluyó:

✔ Eliminación de columns con muchos missing values  
✔ Validación de integridad del dataset  
✔ Tratamiento de null values  
✔ Feature selection  
✔ Creación de nuevas derived features  

### Engineered Features

- Match result (Home Win / Draw / Away Win)
- Goal difference
- Variables agregadas para simplificar el análisis

---

## 📈 Exploratory Data Analysis (EDA)

El análisis se enfocó en comprender:

### 1️⃣ Goal Distribution
- Distribución de home goals
- Distribución de away goals
- Comparación de scoring patterns

### 2️⃣ Home Advantage
- Frecuencia de home wins vs away wins
- Promedio de goals como local vs visitante

### 3️⃣ Match Outcomes
Proporción de:
- Home Wins
- Draws
- Away Wins

### 4️⃣ Statistical Relationships
- Descriptive statistics
- Correlation matrix
- Feature interaction analysis

---

## 🔎 Key Insights

- Los home teams anotan más goals en promedio.
- Las home wins ocurren con mayor frecuencia que las away wins.
- La goal distribution presenta right-skewness.
- Algunas features muestran correlación moderada con el total de goals.

---

## 🛠 Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- Git & GitHub (Version Control)

---

## 📂 Project Structure

football-analysis/
│
├── data/
│   ├── raw_dataset.csv
│   └── cleaned_dataset.csv
│
├── notebooks/
│   ├── 01_data_cleaning.ipynb
│   └── 02_eda.ipynb
│
├── images/
│   └── exported plots
│
└── README_ES.md

---

## 🚀 Cómo Ejecutar el Proyecto

### 1️⃣ Clonar el repository

git clone git@github.com:yourusername/yourrepo.git  
cd yourrepo  

### 2️⃣ Instalar dependencies

pip install -r requirements.txt  

### 3️⃣ Ejecutar notebooks

jupyter notebook  

Abrir y ejecutar:
- 01_data_cleaning.ipynb
- 02_eda.ipynb

---

## 📊 Next Steps

- Advanced Feature Engineering
- Match outcome prediction model
- Implementación de Machine Learning (Logistic Regression / Random Forest)
- Model evaluation (Accuracy, F1-score)
- Dashboard visualization (Streamlit o Power BI)

---

## 🎯 Enfoque Profesional del Proyecto

Este proyecto demuestra:

- Buenas prácticas en Data Cleaning  
- Workflow estructurado de EDA  
- Analytical thinking  
- Fundamentos sólidos de Feature Engineering  
- Organización reproducible del proyecto  

Sirve como base para proyectos de Sports Analytics y modelos predictivos.

---

## 👤 Autor

[Adriano Gennari]  
Aspirante a Data Scientist  
Interesado en Sports Analytics y Data-Driven Decision Making  



