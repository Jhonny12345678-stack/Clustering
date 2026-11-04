# Clustering
# Análisis comparativo de algoritmos de clustering

## Descripción del proyecto

Este proyecto tiene como objetivo aplicar y comparar diferentes algoritmos de agrupamiento (*clustering*) mediante técnicas de aprendizaje no supervisado. Se desarrollaron tres ejercicios prácticos utilizando Python y bibliotecas especializadas en análisis de datos y aprendizaje automático.

Los algoritmos implementados fueron K-Means, DBSCAN y clustering jerárquico, utilizando diferentes conjuntos de datos para observar su funcionamiento, identificar grupos y analizar los resultados obtenidos.

## Objetivos

- Implementar diferentes algoritmos de clustering.
- Aplicar técnicas de preprocesamiento y estandarización de datos.
- Evaluar los agrupamientos mediante métricas de calidad.
- Visualizar e interpretar los resultados obtenidos.
- Comparar las características, ventajas y limitaciones de cada algoritmo.

## Ejercicios desarrollados

### 1. K-Means – Dataset Wine

Se utilizó el conjunto de datos Wine de Scikit-learn, compuesto por 178 observaciones y 13 variables numéricas. Se probaron diferentes valores de K y se seleccionaron tres grupos mediante el análisis del método del codo y el coeficiente Silhouette.

### 2. DBSCAN – Dataset Make Moons

Se generó un conjunto de datos sintético con 500 observaciones y dos variables. Se implementó DBSCAN para identificar grupos de forma irregular y detectar observaciones consideradas ruido.

### 3. Clustering jerárquico – Dataset Iris

Se utilizó el conjunto de datos Iris, compuesto por 150 observaciones y cuatro variables numéricas. Se aplicó agrupamiento jerárquico con el método Ward, utilizando un dendrograma para analizar la estructura de los grupos y PCA para visualizar los resultados.

## Métricas de evaluación

Para evaluar los resultados se utilizaron las siguientes métricas:

- **Silhouette Score:** permite evaluar la cohesión y separación de los grupos.
- **Davies-Bouldin Index:** mide la similitud entre los diferentes grupos; los valores menores indican mejores resultados.
- **Calinski-Harabasz Score:** evalúa la relación entre la dispersión entre grupos y dentro de ellos; los valores mayores suelen indicar una mejor separación.

## Tecnologías y bibliotecas utilizadas

- Python
- Google Colab
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- SciPy

## Estructura del repositorio

```text
Clustering/
│
├── cuadernos/
│   ├── Ejercicio_1_KMeans_Wine.ipynb
│   ├── Ejercicio_2_DBSCAN_Moons.ipynb
│   ├── Ejercicio_3_Jerarquico_Iris.ipynb
│   └── README.md
│
├── figures/
│   ├── 01_metodo_codo.png
│   ├── 02_pca_kmeans.png
│   ├── 03_make_moons_original.png
│   ├── 04_dbscan.png
│   ├── 05_dendrograma_iris.png
│   └── 06_pca_jerarquico.png
│
└── README.md
```

## Instrucciones de ejecución

1. Acceder al repositorio de GitHub.
2. Ingresar a la carpeta `cuadernos`.
3. Seleccionar el ejercicio que se desea ejecutar.
4. Abrir el cuaderno en Google Colab.
5. Ejecutar las celdas en orden para reproducir el análisis, los agrupamientos, las métricas y las visualizaciones.

Los conjuntos de datos Wine e Iris se obtienen directamente desde Scikit-learn, mientras que Make Moons se genera mediante la misma biblioteca. Por esta razón, no es necesario descargar archivos de datos adicionales.

## Resultados

Los ejercicios permitieron observar el comportamiento de tres algoritmos de clustering ante diferentes estructuras de datos. K-Means permitió identificar grupos mediante centroides, DBSCAN reconoció agrupaciones de forma irregular y detectó puntos de ruido, mientras que el clustering jerárquico permitió estudiar las relaciones entre observaciones mediante un dendrograma.

Las visualizaciones y métricas obtenidas se encuentran documentadas en los cuadernos y en la carpeta `figures`.

## Autores

Nombres: Andrés Camilo Patiño Serna, Jhonattan Pineda Cardona, Yansit Stiven Rodríguez Díaz

Introducción a Machine Learning

Proyecto académico sobre técnicas de aprendizaje no supervisado y algoritmos de clustering.
