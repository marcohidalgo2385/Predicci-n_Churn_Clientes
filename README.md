# Predicción de la tasa de cancelación de clientes para el operador de telecomunicaciones Interconnect

## Descripción del Proyecto

Este proyecto tiene como objetivo desarrollar un modelo de aprendizaje automático para predecir la tasa de cancelación de clientes (churn) para el operador de telecomunicaciones Interconnect. El objetivo es identificar a los usuarios que planean cancelar sus servicios y ofrecerles códigos promocionales y opciones de planes especiales para mantenerlos. 

## Objetivo

El objetivo principal es construir un modelo que prediga la probabilidad de cancelación de clientes, permitiendo a Interconnect implementar estrategias de retención eficaces y reducir la tasa de cancelación.

## Metodología

1. **Recopilación y preparación de datos:** Se recopilaron datos de clientes, incluyendo detalles sobre sus planes, contratos e información personal. Se realizó un análisis exploratorio de datos (EDA) para comprender los patrones en los datos y se procesaron para su uso en el modelo.
2. **Ingeniería de características:** Se crearon nuevas características relevantes para mejorar la precisión del modelo, como la duración de la suscripción del cliente.
3. **Selección del modelo:** Se evaluaron varios modelos de aprendizaje automático, incluyendo RandomForest, XGBoost, CatBoost y LightGBM. Se seleccionó el modelo Catboost como el de mejor rendimiento en función de la métrica AUC-ROC.
4. **Entrenamiento y evaluación del modelo:** El modelo seleccionado se entrenó utilizando un conjunto de datos balanceado y se evaluó utilizando métricas como AUC-ROC, precisión y F1-Score.
5. **Afinación de hiperparámetros:** Se realizó una búsqueda de hiperparámetros para optimizar el rendimiento del modelo.

## Resultados

El modelo Catboost logró un AUC-ROC de 0.8199 en el conjunto de prueba, lo que indica una alta capacidad para predecir la cancelación de clientes. Los otros modelos también mostraron un buen rendimiento, con valores de AUC-ROC cercanos al 0.80.

## Conclusiones

El modelo desarrollado puede ayudar a Interconnect a identificar y retener a los clientes en riesgo de cancelación, lo que lleva a una reducción en la tasa de cancelación y un aumento en los ingresos.

## Próximos pasos

* Implementar el modelo en un entorno de producción para la predicción en tiempo real.
* Monitorear continuamente el rendimiento del modelo y reentrenarlo según sea necesario.
* Explorar técnicas adicionales de ingeniería de características para mejorar aún más la precisión del modelo.
