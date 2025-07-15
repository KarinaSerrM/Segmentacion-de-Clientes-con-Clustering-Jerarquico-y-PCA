# Segmentación de Clientes con Clustering Jerárquico y PCA

Este repositorio documenta un proyecto de machine learning no supervisado orientado a identificar grupos de clientes con características similares. Se aplican métodos de clustering jerárquico y análisis de componentes principales (PCA), complementados con visualizaciones y una función de recomendación automática.

## Objetivo

Segmentar un conjunto de clientes según sus atributos numéricos para generar recomendaciones personalizadas basadas en patrones de comportamiento compartidos.

## Flujo de trabajo

### 1. Preprocesamiento de datos
- Carga del dataset con `pandas`
- Estandarización de variables con `StandardScaler` para asegurar comparabilidad
- Eliminación de valores atípicos y verificación de consistencia

### 2. Clustering jerárquico
- Visualización del dendrograma para identificar cantidad óptima de grupos
- Aplicación de `AgglomerativeClustering` para definir los clusters
- Asignación de etiquetas de agrupamiento a cada cliente

### 3. Reducción de dimensionalidad
- Uso de `PCA` para representar los datos en 2 dimensiones
- Visualización de los grupos identificados mediante scatter plot
- Interpretación de relaciones visuales entre clusters

### 4. Recomendaciones automáticas
- Creación de función en Python que recibe el nombre del cliente y devuelve sugerencias personalizadas según su grupo
- Ejemplos desarrollados para Salomé, Stephania y Lydia

## Tecnologías utilizadas

- Python 3.x  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib / Seaborn

## Conclusiones

- El uso de dendrogramas facilita la interpretación jerárquica de los datos y la cantidad adecuada de grupos.
- PCA permite visualizar agrupamientos complejos en espacios reducidos sin perder significado.
- Las recomendaciones basadas en clusters mejoran la personalización y escalabilidad de decisiones automatizadas.
