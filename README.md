# Un estudio comparativo entre distintos algoritmos de las familias epsilon-greedy, UCB y Ascenso de Gradiente

## Información
- **Alumnos:** Castillo Blaya, María; López Quiñonero, Juan José
- **Asignatura:** Extensiones de Machine Learning
-  **Curso:** 2024/2025
-  **Grupo:** CBLQ

## Descripción

El objetivo de este trabajo es implementar una serie de algoritmos pertenecientes a las familias **ε-greedy**, **UCB** y **Ascenso por Gradiente**, y evaluar su desempeño en un problema clásico de exploración-explotación: el **problema del Bandido de K-brazos**.

El estudio se llevará a cabo variando tanto los hiperparámetros de cada algoritmo como la distribución de recompensas del bandido. Se considerarán las siguientes distribuciones:

- **Normal**
- **Bernoulli**
- **Binomial**

El análisis de rendimiento se contrastará mediante una serie de métricas y gráficas que permitirán una visualización intuitiva de los resultados obtenidos.

## Estructura del Repositorio

El repositorio se organiza de la siguiente manera:

- **src/**: Contiene el código fuente del proyecto, dividido en subcarpetas:
  - **algorithms/**: Implementación de los distintos algoritmos.
  - **arms/**: Configuración de los bandidos según su distribución.
  - **plotting/**: Funciones para la visualización gráfica de los resultados.

- **doc/**: Documentación del proyecto en formato PDF.

- **README.md**: Este archivo, con la explicación de la organización, estructura e instrucciones de uso del proyecto.

- **notebook1.ipynb**: Introducción al problema.
- **notebook2.ipynb**: Estudio de la familia ε-greedy.
- **notebook3.ipynb**: Estudio de la familia UCB.
- **notebook4.ipynb**: Estudio de la familia de Ascenso por Gradiente.

## Instalación y Uso

Para explorar los experimentos realizados y el análisis correspondiente, se recomienda abrir en **Google Colab** el archivo `main.ipynb`, ejecutarlo para importar los archivos necesarios, y desde allí acceder a los notebooks:

- `notebook1.ipynb`
- `notebook2.ipynb`
- `notebook3.ipynb`
- `notebook4.ipynb`

## Tecnologías Utilizadas

- **Lenguaje de programación:** Python  
- **Librerías y módulos:**
  - NumPy  
  - Matplotlib  
  - `abc` (Abstract Base Classes)  
  - `typing`  
  - `math`  
  - `random`
