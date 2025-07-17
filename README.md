# Análisis de Personalidad con Machine Learning

  ## Descripción
  Proyecto de clasificación binaria para predecir si una persona es introvertida o extrovertida basándose en características de comportamiento social.

  ## Dataset
  - **Archivo**: personality.csv
  - **Registros**: 2,490 (después de eliminar 8 duplicados)
  - **Variables**: 7 características predictoras
  - **Target**: Personalidad (Introvert/Extrovert)
  - **Distribución**: 70% Extrovert, 30% Introvert

  ## Variables
  - Time_spent_Alone: Tiempo que pasa solo (0-11)
  - Stage_fear: Miedo escénico (Yes/No)
  - Social_event_attendance: Asistencia a eventos sociales (0-10)
  - Going_outside: Frecuencia de salir (0-7)
  - Drained_after_socializing: Agotamiento después de socializar (Yes/No)
  - Friends_circle_size: Tamaño del círculo de amigos (0-15)
  - Post_frequency: Frecuencia de publicaciones (0-10)

  ## Modelos Implementados
  1. Logistic Regression
  2. K-Nearest Neighbors (KNN)
  3. Decision Tree
  4. XGBoost
  5. LightGBM

  ## Resultados
  - Todos los modelos lograron F1-Score > 0.90
  - Mejor modelo: Decision Tree Optimizado
  - Variables más importantes: Friends_circle_size, Stage_fear, Time_spent_Alone

  ## Estructura del Proyecto
  Personality_Analysis_ML.ipynb  # Notebook principal con todo el análisis
  personality.csv               # Dataset original

  ## Requisitos
  - Python 3.x
  - pandas, numpy, scikit-learn, matplotlib, seaborn
  - xgboost, lightgbm

  ## Uso
  Ejecutar todas las celdas del notebook en orden secuencial.

## Creacion de 
  Carolina Melero
