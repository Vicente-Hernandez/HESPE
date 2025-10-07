HESPE: Predicción del Rendimiento Académico de Estudiantes 🎓
Contexto del Problema
Este repositorio contiene el proyecto HESPE (Higher Education Student Performance Evaluation), desarrollado para el equipo de análisis de rendimiento de la facultad de ingeniería y ciencias de la Universidad de Wisconsin.

El objetivo principal es construir un modelo de aprendizaje de máquina capaz de predecir el resultado académico (la variable "grade") de los estudiantes al cursar una asignatura. El modelo se basa en un conjunto de datos que incluye información personal, familiar y hábitos de estudio.

📊 Conjunto de Datos
El análisis se basa en un set de datos recolectado durante 2019, que contiene:

145 instancias, donde cada una corresponde a un estudiante.

32 características que se dividen en:

Información personal (10 primeras).

Preguntas familiares (de la 11 a la 16).

Hábitos de estudio (el resto).

🚀 Metodología
El proyecto se estructura en las siguientes etapas clave:

Preparación de Datos: Incluye la limpieza, traducción y decodificación de las variables para asegurar la calidad y consistencia de los datos antes del análisis.

Análisis Exploratorio de Datos (EDA): Se utilizan visualizaciones para explorar la relación entre diversas variables (edad, sexo, becas, hábitos de estudio) y las calificaciones finales, con el fin de extraer insights iniciales.

Modelado y Evaluación: Se entrenan y comparan múltiples modelos de aprendizaje automático para identificar el de mayor capacidad predictiva.

Selección del Mejor Modelo: Se elige el modelo con el mejor rendimiento en base a métricas de precisión.

🏆 Resultados y Conclusiones
Tras evaluar diferentes arquitecturas, el modelo que obtuvo el mejor rendimiento fue un modelo de red neuronal profunda (Modelo 71), logrando la mayor precisión en la predicción de las calificaciones.

A pesar de ser el más efectivo, se concluyó que la precisión del modelo aún tiene un margen de mejora considerable. Se recomienda continuar con la optimización de hiperparámetros, la experimentación con otras arquitecturas y la posible incorporación de más datos para aumentar la robustez y fiabilidad de las predicciones.

🛠️ Tecnologías Utilizadas
Python 3

Pandas: Para la manipulación y análisis de datos.

NumPy: Para operaciones numéricas.

Scikit-learn: Para el preprocesamiento de datos y modelado.

Matplotlib & Seaborn: Para la generación de gráficos y visualizaciones.

TensorFlow / Keras: Para la construcción del modelo de red neuronal.

⚙️ Cómo Replicar el Análisis
Clona el repositorio:

Bash

git clone [URL-del-repositorio]
cd HESPE-Project
Instala las dependencias:
(Se recomienda crear un entorno virtual)

Bash

pip install -r requirements.txt
Ejecuta el Notebook:
Abre el archivo Caso_Hespe.ipynb en un entorno como Jupyter Lab, Jupyter Notebook o Google Colab y ejecuta las celdas en orden para replicar todo el proceso de análisis y modelado.
