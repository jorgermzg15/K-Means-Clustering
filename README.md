# Aprendizaje No Supervisado: Clustering y Reducción de Dimensionalidad

Este repositorio contiene notebooks de Jupyter enfocados en técnicas de aprendizaje no supervisado, específicamente clustering y reducción de dimensionalidad. El objetivo es proporcionar a los estudiantes una comprensión práctica de estas técnicas y su aplicación en análisis de datos.

## Descripción del Proyecto

El proyecto incluye la implementación y análisis de las siguientes técnicas:

- **Clustering**:
  - K-Means
  - DBSCAN
  - Evaluación de Clusters con el Coeficiente de Silueta
- **Reducción de Dimensionalidad**:
  - PCA (Análisis de Componentes Principales)
  - Visualización y Recuperación de Datos

## Estructura del Proyecto

- `Caso_Mall_Customers.ipynb`: Notebook que analiza el conjunto de datos "Mall Customers" para agrupar clientes utilizando técnicas de clustering.
- `KMeans.ipynb`: Implementación de K-Means para clustering.
- `DBSCAN.ipynb`: Implementación de DBSCAN para clustering basado en densidad.
- `Reducción Dimensionalidad.ipynb`: Notebook que explora técnicas de reducción de dimensionalidad, incluyendo PCA.
- `requirements.txt`: Lista de paquetes de Python necesarios para este proyecto.

## Herramientas y Tecnologías

- **Python** (se recomienda la versión 3.x)
- **Jupyter Notebook**
- **Bibliotecas de Análisis de Datos**:
  - Pandas (≥2.3.1)
  - Plotly (≥6.3.0)
  - Scikit-learn (≥1.7.1)
  - Seaborn
  - Matplotlib
  - NumPy (≥2.3.2)

## Instrucciones de Instalación

1. Clona este repositorio:
   ```bash
   git clone https://github.com/jorgermzg15/aprendizaje-no-supervisado.git
   cd aprendizaje-no-supervisado
   ```

2. Crea un entorno virtual:
   ```bash
   # En macOS/Linux
   python -m venv .venv
   source .venv/bin/activate

   # En Windows
   python -m venv .venv
   .\.venv\Scripts\activate
   ```

3. Instala los paquetes necesarios:
   ```bash
   pip install -r requirements.txt
   ```

4. Lanza Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

5. Abre cualquiera de los notebooks y comienza a explorar.

## Resolución de Problemas

Si encuentras problemas:

1. Asegúrate de que tu entorno virtual esté activado (deberías ver `(.venv)` en tu terminal).
2. Intenta actualizar pip antes de instalar los requisitos:
   ```bash
   pip install --upgrade pip
   ```
3. Si tienes problemas con las visualizaciones:
   ```bash
   pip install plotly seaborn matplotlib
   ```
4. Si encuentras problemas con el kernel en Jupyter:
   ```bash
   python -m ipykernel install --user
   ```

## Para Estudiantes

Este repositorio está diseñado para proporcionar experiencia práctica con técnicas de aprendizaje no supervisado. Para aprovecharlo al máximo:

1. Sigue cuidadosamente las instrucciones de instalación.
2. Ejecuta las celdas de los notebooks en orden.
3. Experimenta con diferentes hiperparámetros para entender su impacto.
4. Completa los ejercicios o desafíos proporcionados en los notebooks.

## Licencia

Este proyecto está disponible para fines educativos. ¡Siéntete libre de usarlo y aprender de él!
