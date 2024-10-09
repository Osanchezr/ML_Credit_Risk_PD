# ML_Credit_Risk_PD
# Aplicación de Técnicas de Aprendizaje Automático a la Probabilidad de Default en la Gestión de Riesgo de Crédito

Este repositorio es parte del Trabajo de Fin de Máster (TFM) del Máster en Banca y Finanzas de la Universidad de A Coruña (UDC). El estudio se centra en el uso de modelos de **aprendizaje automático** para predecir la **probabilidad de default** en la concesión de créditos y el ahoroo de capital regulatorio, evaluando las mejoras que estas técnicas ofrecen frente a los métodos tradicionales.

## Resumen del Proyecto

El objetivo principal del proyecto fue explorar cómo los modelos de aprendizaje automático pueden mejorar la identificación de clientes con mayor riesgo de default, y los beneficios que ello puede traer en la reducción de capital regulatorio en las entidades financieras.

### Herramientas y Técnicas

En este estudio se utilizaron diferentes modelos de aprendizaje automático y un modelo tradicional para comparar sus rendimientos:

- **Árbol de Decisión**
- **Random Forest**
- **Gradient Boosting**
- **Logit** (modelo tradicional)

Los modelos fueron evaluados utilizando métricas clave de rendimiento (precisión, recall, F1-Score, AUC) y su capacidad de generar ahorros de capital regulatorio fue estimada aplicando un enfoque de **calificaciones internas (IRB)**.

El proyecto fue desarrollado en **R** y el código fue compartido y probado en **RStudio**.

### Fuente de los Datos

Para este estudio se utilizó el conjunto de datos de la **competencia de Kaggle "Give Me Some Credit" (2011)**, que es un dataset público centrado en el análisis del riesgo de crédito. Los datos incluyen información sobre características financieras y demográficas de individuos, permitiendo estimar la probabilidad de que un cliente incurra en **default**.

- **Fuente de los datos**: [Give Me Some Credit Dataset - Kaggle](https://www.kaggle.com/datasets/brycecf/give-me-some-credit-dataset)

### Objetivos

- **Aplicación de conocimientos:** El proyecto busca aplicar lo aprendido en técnicas de aprendizaje automático y riesgo de crédito.
- **Comparación de modelos:** Analizar la capacidad predictiva de los modelos de machine learning comparados con el modelo Logit tradicional.
- **Ahorros en capital regulatorio:** Estimar el impacto económico de usar modelos más avanzados para predecir el riesgo de default.

## Retos y Soluciones

Durante el desarrollo del proyecto, se encontraron varios desafíos, incluyendo:

1. **Preprocesamiento de Datos:** Ajustar los datos de la base de préstamos para que los modelos pudieran ser entrenados adecuadamente.
2. **Evaluación de Modelos:** Determinar la mejor estrategia de validación y comparación de modelos, buscando un equilibrio entre precisión y robustez en las predicciones.
3. **Estimación de Ahorros de Capital:** Aplicar correctamente el enfoque basado en calificaciones internas (IRB) para calcular los ahorros de capital.

Se consiguió resolver estos problemas aplicando técnicas de preprocesamiento, validación cruzada y refinamiento del código para hacer el análisis más preciso.

## Enlaces de Interés

- Puedes ver el código y la documentación completa en el [notebook aquí](enlace-al-notebook).
- Accede al documento final del TFM en formato PDF [aquí](https://drive.google.com/file/d/1fmCerIibSb3Mix8bphw0riFksSc0Sllc/view?usp=sharing).
- Ver la presentación del TFM en [este enlace](https://docs.google.com/presentation/d/1-xJOpsN4FS8e8rMcMDQ37nbQC12w2_0a/edit?usp=sharing&ouid=111686523465829860191&rtpof=true&sd=true).
- Fuente de los datos: [Give Me Some Credit - Kaggle](https://www.kaggle.com/datasets/brycecf/give-me-some-credit-dataset)

## Participantes

- **Oscar Paul Sanchez Riveros** – Autor del Trabajo de Fin de Máster
- **Universidad de A Coruña (UDC)** – Máster en Banca y Finanzas

## Palabras Clave

- **Aprendizaje Automático**
- **Probabilidad de Default**
- **Riesgo de Crédito**
- **Capital Regulatorio**
- **Sistema IRB**


