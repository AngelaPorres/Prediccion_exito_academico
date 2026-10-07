Proyecto Final: Predicción del éxito académico en educación superior

Este proyecto analiza el rendimiento académico de estudiantes de educación superior utilizando técnicas de Machine Learning supervisado y no supervisado. Se abordan tres tareas principales: clasificación, regresión y clustering.

El objetivo es entender qué factores influyen en el abandono y el éxito académico, y evaluar hasta qué punto es posible anticipar estos resultados.

## Estructura

| Archivo | Descripción |
|---------|-----------|
| **Tarea1.Clasificacion.ipynb** | Contiene el análisis de clasificación supervisada para predecir la situación final del estudiante (abandono, matriculado o graduado). Incluye entrenamiento de modelos, evaluación y análisis de resultados |
| **Tarea2.Regresion.ipynb** | Contiene el análisis de regresión para predecir la nota media del segundo semestre. Se comparan distintas configuraciones de variables para estudiar el efecto del data leakage |
| **Tarea3.NoSupervisado.ipynb** |  Contiene el análisis de clustering (K-Means) para identificar perfiles de estudiantes. Incluye selección del número de clusters, evaluación y visualización mediante PCA |
| **rendimiento_estudiantes.csv** | Dataset utilizado en los notebooks. Deben estar en la ruta indicada en el código |
| **Proyecto_Final_Angela_Porres.pdf** | Informe completo con la explicación detallada de la metodología, resultados y conclusiones |

Requisitos

    - Se recomienda usar Python 3.9 o superior.
    - Instalar las librerías necesarias con:
        pip install numpy pandas scikit-learn matplotlib seaborn

## Instalación y Uso

1. **Clonar o descargar el repositorio**
   ```bash
   git clone https://github.com/usuario/prediccion-exito-academico.git
   cd prediccion-exito-academico
   ```

2. **Instalar dependencias**
   ```bash
   pip install numpy pandas scikit-learn matplotlib seaborn
   ```

3. **Ejecutar los notebooks en orden**
   - Tarea1.Clasificacion.ipynb
   - Tarea2.Regresion.ipynb
   - Tarea3.NoSupervisado.ipynb

> El orden es importante: el análisis está estructurado de forma progresiva.

## Tecnologías

```
Python 3.9+
scikit-learn    - modelos ML
pandas          - manipulación de datos
numpy           - cálculos numéricos
matplotlib      - visualización
seaborn         - gráficos estadísticos
```

Angela Porres Cobb
2ºB IMAT
