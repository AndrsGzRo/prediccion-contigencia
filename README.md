# prediccion-contigencia
Este proyecto utiliza PySpark y XGBoost para modelar y predecir los niveles de contaminantes atmosféricos en el aire, con especial enfoque en Ozono (O₃) y Material Particulado Fino (PM2.5) utilizando modelos de machine learning implementados en PySpark y XGBoost.

**Objetivos**
Con el desarrollo del reto integrarás todos los conocimientos adquiridos, cumpliendo los siguientes objetivos:

- Descubrir relaciones entre las variables dependientes e independientes para crear modelos predictivos usando correlación.
- Aplicar modelos predictivos de machine learning y evalúa los resultados.

**Tecnologías utilizadas** 
- Python 3
- Apache Spark
- XGBost
- Pandas, Matplotlib, Seaborn para análisis y visualización

**Metodología**
1. Limpieza y exploración inicial de los datos.
2. Análisis de correlación entre contaminantes y variables meteorológicas.
3. Selección de variables con base en la correlación y feature importance.
4. Entrenamiento de diferentes modelos de regresión:
   - Regresión Lineal
   - Random Forest
   - XGBoost

5. Evaluación de modelos con métricas: RMSE, MAE y R².
6. Interpretación de resultados y elaboración de conclusiones.

**Resultados Principales**
- O₃: El modelo XGBoost obtuvo el mejor desempeño (R² ≈ 0.89).
- PM2.5: Los modelos presentaron menor capacidad predictiva (R² ≈ 0.45).
Variables relevantes:

- O₃: Radiación solar, temperatura y hora del día.
- PM2.5: Los rezagos de PM2.5, PM10 y sus rezagos, CO y NO₂.

**Conclusiones** 
- El tráfico vehicular influye de manera importante en los niveles de contaminantes.
- La verificación vehicular podría tener efectos positivos sobre la calidad del aire.
- Las condiciones meteorológicas son determinantes para explicar variaciones en O₃.
- La predicción de contingencias ambientales requiere información adicional (tráfico, emisiones industriales, datos en tiempo real).
