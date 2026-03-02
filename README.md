# Predicción de Cancelación de Clientes (Customer Churn)

## Descripción del Proyecto

Este proyecto tiene como objetivo predecir la cancelación de clientes (*churn*) utilizando técnicas de Machine Learning.

Se entrenaron y evaluaron diferentes modelos de clasificación para identificar los factores que influyen en la cancelación y proponer estrategias de retención basadas en los resultados obtenidos.

## Dataset

El conjunto de datos incluye información demográfica, contractual y de comportamiento del cliente, como:

* Tipo de contrato
* Antigüedad del cliente (tenure)
* Método de pago
* Cargos mensuales
* Cargos totales
* Servicios contratados
* Variable objetivo: **Churn (Cancelación)**

División de datos:

* 80% entrenamiento
* 20% prueba


## Modelos Implementados

Se entrenaron los siguientes modelos:

* Regresión Logística
* Árbol de Decisión
* Random Forest
* (Opcional) K-Nearest Neighbors


## Métricas de Evaluación

Cada modelo fue evaluado con:

* Exactitud (Accuracy)
* Precisión
* Recall
* F1-score
* Matriz de confusión

Estas métricas permiten evaluar tanto el rendimiento general como la capacidad de detectar correctamente los clientes que cancelan.

---

## Resultados y Comparación

### Mejor Modelo

El modelo con mejor desempeño general fue **Random Forest**, ya que presentó:

* Mayor F1-score
* Mejor equilibrio entre precisión y recall
* Menor cantidad de falsos negativos

Esto es clave porque detectar clientes que van a cancelar es más importante que simplemente maximizar la exactitud.

---


## Autor

Juan Manuel Diaz Torres

---
