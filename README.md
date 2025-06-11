🏆 Predicción de recuperación de oro en procesos industriales 🏭

Este proyecto desarrolla un modelo de aprendizaje automático para predecir la eficiencia de recuperación de oro durante las etapas de purificación en una planta de procesamiento.

🎯 Objetivo
- Predecir el porcentaje de recuperación de oro en las etapas "rougher" y "final".
- Evaluar la precisión del modelo con la métrica sMAPE (error medio absoluto porcentual simétrico).
- Identificar el mejor modelo para aplicar sobre datos reales del proceso.

🛠️ Herramientas y tecnologías
- pandas
- numpy
- scikit-learn
- matplotlib
- Jupyter Notebook

📈 Modelos utilizados
- Regresión lineal
- Random Forest Regressor

📊 Dataset
Los archivos contienen datos de sensores de la planta:
- `gold_recovery_train.csv`: Datos de entrenamiento con variables y salidas reales.
- `gold_recovery_test.csv`: Datos de prueba sin valores objetivo.
- `gold_recovery_full.csv`: Contiene los valores reales de prueba para evaluación final.

📌 Resultados
- El modelo de **Random Forest** obtuvo un **sMAPE Total < 10**, cumpliendo el umbral esperado.
- La predicción para la etapa **Final** fue más compleja debido a su mayor varianza.
- Se logró una predicción aceptable para ambas fases con buen rendimiento en producción.

🚀 Cómo ejecutarlo
1. Clona este repositorio:
```bash
git clone https://github.com/TU_USUARIO/TU_REPO.git
2. Navega al proyecto:
## 🚀 Cómo ejecutarlo

1. Clona este repositorio:
   ```bash
   git clone https://github.com/cesardud/gold-recovery.git
2. Navega al proyecto:
   ```bash
   cd gold-recovery
4. Instala las librerías requeridas:
    ```bash
   pip install -r requirements.txt
6. Abre el notebook:
    ```bash
   jupyter notebook gold_recovery.ipynb
