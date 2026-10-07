Proyecto Final: Predicción del éxito académico en educación superior

Este proyecto analiza el rendimiento académico de estudiantes de educación superior utilizando técnicas de Machine Learning supervisado y no supervisado. Se abordan tres tareas principales: clasificación, regresión y clustering.

El objetivo es entender qué factores influyen en el abandono y el éxito académico, y evaluar hasta qué punto es posible anticipar estos resultados.

Estructura del proyecto

    - Tarea1.Clasificacion.ipynb
        Contiene el análisis de clasificación supervisada para predecir la situación final del estudiante (abandono, matriculado o graduado). Incluye entrenamiento de modelos, evaluación y análisis de resultados.

    - Tarea2.Regresion.ipynb
        Contiene el análisis de regresión para predecir la nota media del segundo semestre. Se comparan distintas configuraciones de variables para estudiar el efecto del data leakage.

    - Tarea3.NoSupervisado.ipynb
        Contiene el análisis de clustering (K-Means) para identificar perfiles de estudiantes. Incluye selección del número de clusters, evaluación y visualización mediante PCA.

    - Proyecto_Final_Angela_Porres.pdf
        Informe completo con la explicación detallada de la metodología, resultados y conclusiones.

    - Archivos de datos (CSV)
        Dataset utilizado en los notebooks. Deben estar en la ruta indicada en el código.

Requisitos

    - Se recomienda usar Python 3.9 o superior.
    - Instalar las librerías necesarias con:
        pip install numpy pandas scikit-learn matplotlib seaborn

Cómo reproducir los resultados
    1) Descargar o descomprimir la carpeta del proyecto.
    2) Asegurarse de que los datos (CSV) están en la ruta correcta.
    3) Ejecutar los notebooks en el siguiente orden:
    4) Tarea1.Clasificacion.ipynb
    5) Tarea2.Regresion.ipynb
    6) Tarea3.NoSupervisado.ipynb

Seguir el orden es importante porque el análisis está estructurado de forma progresiva.

Angela Porres Cobb
2ºB IMAT