# Challenge TelecomX parte 2

### Este proyecto forma parte del plan de estudios ONE | TECH FOUNDATION - Especialización Data Science 2025.

**🧠Objetivo del Challenge**

Esta segunda parte del proyecto de ciencia de datos tiene como objetivo desarrollar modelos predictivos capaces de prever qué clientes tienen mayor probabilidad de cancelar sus servicios (Churn).
La empresa TelecomX quiere anticiparse al problema de la cancelación, por lo cual se era importante construir un pipeline robusto para esta etapa inicial de modelado.

El presente proyecto busca identificar los factores principales, correlaciones y variables clave que influyen en la cancelación, con el fin de proponer estrategias efectivas para mejorar la retención de clientes.

## 🛠️Herramientas utilizadas

 - Entorno Google Colab
 - Lenguaje Python
 - Bibliotecas Pandas: Procesamiento y análisis de datos.
 - Numpy: Manipulación matemática. 
 - Matplotlib: Visualización de datos, gráficas.
 - Seaborn: Creación de gráficos estadísticos atractivos e informativos.
 - Scikit-learn: Implementación de modelos de Machine Learning y preprocesamiento.

 ##📁Estructura del proyecto

El repositorio en Git Hub contiene:
- Cuaderno con los datos del challenge TelecomX. El desarrollo del codígo y gráficos del proyecto en lenguaje Python, junto con las librerias.
- Al final del notebook se encuentra el informe Final con el análisis y gráficos del proyecto.
- Readme (Este Archivo) para guía e información del proyecto.

##🔎Instrucciones de Uso
- Clonar el repositorio de Git Hub [https://github.com/Andy062025/Challenge-TelecomX-Segunda-Parte-Completado-2025.git]
- Hacer una copia del cuaderno en su Google Drive y luego editarlo en Google Colab. O puede descargarlo en su PC y editarlo en VS Code por ejemplo.
- Para la visualización y el manejo de datos, va a necesitar instalar las bibliotecas NumPy, Pandas y Matplotlib. Cada una de estas bibliotecas va a ser necesaria para poder realizar la correcta manipulación y tratamiento de los datos.
- Ejemplo de importar biblioteca Pandas:
```bash
  import Pandas as pd

```
- Ejemplo de importar biblioteca Numpy:
```bash
  import Numpy as np

```
- Ejemplo de importar biblioteca Matplotlib:
```bash
  import Matplotlib.pyplot as plt

```

## 🎨Vista previa

1. Carga y limpieza de datos
2. Análisis exploratorio (EDA)
3. Selección de características
4. Entrenamiento de los diferentes Modelos
   . Regresión Logística
   . Random Forest
   . Grandient Boosting
   . KNN ( K- Nearest Neighbors)
   . Ensemble ( LR + GB )

5. Optimización de hiperparámetro
6. Evaluación 
7. Informe  Final y conclusiones

## 📲Screenshots 

Gráfica para visualizar más detalladamente las variables relacionadas al abandono (Churn). 

![image_alt](https://github.com/Andy062025/Challenge-TelecomX-Segunda-Parte-Completado-2025/blob/2de251e8001bb9d68dfb52dbb7af528eaeadcfae/Gr%C3%A1fica%204%20Matriz%20de%20correlaci%C3%B3n%20Variables%20abandono.png)

Gráfica de matrices de confusión comparativas Modelos ( Regresión logística, Random Forest, KNN).

![image_alt](https://github.com/Andy062025/Challenge-TelecomX-Segunda-Parte-Completado-2025/blob/2de251e8001bb9d68dfb52dbb7af528eaeadcfae/Gr%C3%A1fica%203%20matrices%20de%20confusi%C3%B3n%20.png)

Gráfica Curva ROC, comparativa de los diferentes modelos para determinar cual tiene la mayor capacidad de distinguir positivos de negativos en todos los umbrales.

![image_alt](https://github.com/Andy062025/Challenge-TelecomX-Segunda-Parte-Completado-2025/blob/2de251e8001bb9d68dfb52dbb7af528eaeadcfae/Gr%C3%A1fica%202%20Curvas%20ROC.png)

Tabla comparativa de los modelos utilizados para la previsión de las variables más influyentes en el abandono (churn). 

![image_alt](https://github.com/Andy062025/Challenge-TelecomX-Segunda-Parte-Completado-2025/blob/2de251e8001bb9d68dfb52dbb7af528eaeadcfae/Gr%C3%A1fica%207%20Tabla%20de%20resultado%20Modelos%20.png)

Esemble LR+GB, fue el modelo más adecuado para lograr estas predicciones porque al ser una combinación de modelos aprovecha lo mejor de LR (interpretabilidad) y GB (performance), logrando el mejor AUC.

Gráfica de enjambre para ampliar el análisis de las variables más influyentes, asi como patrones y otros factores. 

![image_alt](https://github.com/Andy062025/Challenge-TelecomX-Segunda-Parte-Completado-2025/blob/2de251e8001bb9d68dfb52dbb7af528eaeadcfae/Gr%C3%A1fica%201%20enjambre%20Shap.png)


## Conclusión
1. 📶Factores principales que más influyen en la cancelación.
Del análisis estadístico y de interpretabilidad (coeficientes de la Regresión Logística y valores SHAP del modelo Ensemble), se identificaron 5 factores clave:

- Tipo de contrato
- Costo mensual (charges.monthly)
- Forma de pago
- Antigüedad y gasto acumulado (tenure, charges.total)
- Servicios adicionales

2. 📈Propuesta de estrategias de Retención Recomendadas
Con base en los hallazgos, se proponen acciones concretas:

- Incentivar contratos a largo plazo
- Ajustar y flexibilizar los costos mensuales
- Optimizar los métodos de pago
- Potenciar servicios de valor agregado
- Estrategias diferenciadas según antigüedad del cliente

## ✅Estado del proyecto

✅Finalizado en agosto 2025 

## Autor del proyecto

- Faxin Andres Pabuena Yepes | Data Science Student | 2025 | 
   
