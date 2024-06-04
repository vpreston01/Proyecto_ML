# Predicción de la realización de ejercicios en pacientes mediante modelos de Machine Learning

Este proyecto se centra en la predicción de si los pacientes están cumpliendo con sus rutinas de ejercicios utilizando técnicas de Machine Learning. La importancia del ejercicio y su impacto en una vida saludable, especialmente para la prevención de la diabetes, es fundamental en este análisis.

## Objetivo

El objetivo principal de este proyecto es utilizar técnicas de Machine Learning para predecir si los pacientes están realizando suficiente ejercicio físico para mejorar y controlar su salud. A través de la clasificación, se evaluarán diferentes modelos de Machine Learning, utilizando diferentes hiperparámetros para seleccionar el más óptimo.

## Métodos Utilizados

1. **Preprocesamiento de Datos:** Se realizó limpieza y preparación de los datos.
2. **Selección de Modelos:** Se probaron varios modelos de clasificación de Machine Learning, incluyendo AdaBoost, Random Forest, XGBoost, Voting Classifier, Decision Tree y K-Nearest Neighbors. Se aplicaron técnicas de optimización como la búsqueda de hiperparámetros para mejorar su rendimiento.
3. **Predicciones con archivo Pickle:** Se guardó el mejor modelo seleccionado en formato .pkl para su posterior uso.

## Estructura del Repositorio

- **data/:** Contiene los datos utilizados para entrenar y probar los modelos de Machine Learning.
- **models/:** Contiene el mejor modelo guardado en formato .pkl.
- **notebooks/:** Carpeta con código para el análisis de datos, construcción y evaluación de modelos.
- **README.md:** Este archivo README que proporciona una descripción general del proyecto.

## Variables Utilizadas

- **SEQN:** ID Número de secuencia del encuestado.
- **age_group:** Grupo de edad del encuestado (mayor/no mayor).
- **RIDAGEYR:** Edad del encuestado.
- **RIAGENDR:** Género del encuestado. (1: Masculino, 2: Femenino)
- **PAQ605:** Si el encuestado practica deportes, ejercicios o actividades recreativas de intensidad moderada o vigorosa en una semana típica. (1: Sí, 2: No)
- **BMXBMI:** Índice de masa corporal del encuestado.
- **LBXGLU:** Glucosa en sangre del encuestado después del ayuno.
- **DIQ010:** Si el encuestado es diabético.
- **LBXGLT:** Oral del demandado.
- **LBXIN:** Niveles de insulina en sangre del encuestado.

## Dependencias

Para ejecutar la aplicación web y utilizar los scripts proporcionados, se necesitan las siguientes bibliotecas de Python:

- Pandas
- NumPy
- Scikit-learn

## Resultados

El modelo final seleccionado ha demostrado una alta precisión en la predicción de si los pacientes hacen ejercicio físico durante la semana. Esto puede ser importante para la mejora de los pacientes, la prevención de enfermedades y la mejora de la salud en general.

