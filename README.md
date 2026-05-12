# K-Means Clustering

Este repositorio contiene notebooks de Jupyter enfocados en clustering con K-Means, incluyendo un caso aplicado al dataset de clientes de centro comercial.

## Contenido del repositorio

- `KMeans.ipynb`: Notebook con fundamentos y flujo general de K-Means.
- `Mall Customers KMeans.ipynb`: Aplicación de K-Means al caso de segmentacion de clientes (Mall Customers).
- `requirements.txt`: Dependencias de Python para ejecutar los notebooks.

## Requisitos

- Python 3.10 o superior (recomendado)
- Jupyter Notebook o JupyterLab

Dependencias principales (ver `requirements.txt` para el listado completo):

- pandas
- numpy
- scikit-learn
- scipy
- statsmodels
- plotly
- ipykernel
- nbformat
- requests

## Instalacion y ejecucion

1. Clona este repositorio:

```bash
git clone https://github.com/jorgermzg15/K-Means-Clustering.git
cd K-Means-Clustering
```

2. Crea y activa un entorno virtual:

```bash
# macOS/Linux
python -m venv .venv
source .venv/bin/activate

# Windows
python -m venv .venv
.\.venv\Scripts\activate
```

3. Instala las dependencias:

```bash
pip install -r requirements.txt
```

4. Inicia Jupyter:

```bash
jupyter notebook
```

5. Abre `KMeans.ipynb` o `Mall Customers KMeans.ipynb` y ejecuta las celdas en orden.

## Notas

- Si usas VS Code, selecciona el kernel del entorno virtual `.venv` para evitar errores de dependencias.
- Si falta el kernel en Jupyter:

```bash
python -m ipykernel install --user
```

## Licencia

Uso educativo y personal.
