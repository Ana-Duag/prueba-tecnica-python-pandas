
# Prueba Técnica de Python

## Análisis Exploratorio de Datos. Visualización con Matplotlib y Seaborn. Estadística Descriptiva e Inferencial

Prueba técnica  realizada por **Ana Dueñas** en el **Bootcamp de Análisis de Datos de Adalab (Octubre 2025)**.

---


## Observaciones Generales

Antes de proceder a explicar en qué consiste la prueba y cómo se ha desarrollado, se ha considerado imprescindible mostrar el orden en que deben visualizarse los archivos pues **llevan una secuencia lógica en base a cómo se ha ido desarollando dicha prueba**. Se ha hecho de esta forma para evitar bloqueos De VS Code en la ejecución de los archivos.

1. **Archivo_1_EDA_analisis**. 

2. **Archivo_2_union_conjunto**. Con este archivo se genera un csv denominado **"union_conjunto.csv"**.

3. **Archivo_3_nulos_grafs_bonus**. 

--- 

## Desarrollo Prueba Técnica

### 1. Análisis Exploratorio de Datos (EDA).

- Se ha realizado un análisis exploratorio de datos (EDA) sobre los archivos **“Customer Flight Activity.csv”** y **“Customer Loyalty History.csv”** con el objetivo de evaluar la estructura, distribución y calidad del dataset.

- El proceso incluye la detección de valores nulos, duplicados y outliers, así como el análisis de la distribución de variables numéricas y categóricas.

- Para ello se han utilizado histogramas, boxplots y gráficos de barras, que han permitido identificar patrones, sesgos y posibles errores de codificación. Las visualizaciones se han generado antes de aplicar procesos de limpieza o normalización, proporcionando una visión inicial del estado bruto de los datos y sirviendo como base para las decisiones de depuración y preprocesamiento posteriores.


### 2. Unión de datasets.

- Una vez realizado el EDA inicial, se han unido los dos conjuntos de datos proporcionado utilizando el método que se ha creído más conveniente para ello. 


### 3. Limpieza de datos. Gestión de nulos, normalización y estandarización de variables.
- Se han tratado los valores nulos.
- Se ha verificado la consistencia y corrección de los datos para una presentación de los mismos coherente. 
- Se han realizo ajustes o conversiones necesarias en las columnas.
- Se ha eliminado una columna que resulta redundante en el conjunto de datos (Dollar Cost points Redeemed).
- Se han unificado dos columnas (country y city).

### 4. Visualizaciones.
Con el dataset ya consolidado y transformado, se han realizado visualizaciones más complejas (con seaborn y matplotlib), con el objetivo de extraer patrones de comportamiento que puedan facilitar la toma de decisiones estratégicas. 

---


## 5. Bonus. Estadística Inferencial

Utilizando el dataset limpio, se ha buscado evaluar si existen diferencias significativas en el número de vuelos reservados según el nivel educativo de los clientes. Teniendo en cuenta que los datos son sólo una muestra de una población. Los pasos seguidos han sido:

**Preparación de Datos**

**Análisis Descriptivo:**. Utilizando estadística descriptiva.

**Prueba Estadística:** . Utilizando estadística inferencial.