# Proyecto - Algoritmo ID3 Aplicado al Conjunto Votes

Este proyecto presenta la implementación, ejecución y análisis del algoritmo clásico de aprendizaje supervisado **ID3 (Iterative Dichotomiser 3)** utilizando la herramienta de minería de datos **Weka**. El objetivo principal es construir y evaluar un árbol de decisión capaz de clasificar la afiliación política de congresistas de los Estados Unidos (*demócrata* o *republicano*) en función de sus registros históricos de votación.

Debido a que el diseño matemático original del algoritmo ID3 puro no tolera registros con valores faltantes (`?`), el proyecto incluye una fase esencial de preprocesamiento mediante técnicas de imputación basadas en la moda de los atributos nominales. Tras la limpieza de los datos, el modelo fue entrenado y evaluado sobre el dataset completo, logrando una precisión diagnóstica superior al 99% e identificando a la regulación del congelamiento de tarifas médicas (`physician-fee-freeze`) como la variable con mayor Ganancia de Información (nodo raíz).

---

## Autores

| Nombre | Matrícula |
|--------|-----------|
| Emiliano Narciso Peralta Barrientos | 190537 |
| Daniela Maite Reyes Arena | 191326 |


---

## Tareas Realizadas

1. **PDF con el resultado de la aplicación de ID3 a Votes**
   - Archivo: `arboles/ID3.pdf`

2. **Reporte en excel**
   - Archivo: `arboles/Final.xlsx`

