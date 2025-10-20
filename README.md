# Evaluación - OceanHackWeek 2025 - W. Abarca

En este ejemplo se presentan datos de concentración de clorofila obtenidos de la plataforma Copernicus Marine, a partir de observaciones satelitales y pronóstico de modelo, para la región determinada.

El código ha sido desarrollado en Python y utiliza las siguientes librerías:

```python
- xarray
- numpy
- matplotlib
- cartopy
- papermill
- copernicusmarine.
```

Para iniciar, asegúrate de tener instaladas las librerías necesarias. Puedes crear los entornos virtuales con los archvios `requirements.txt` o `environment.yml` proporcionados, o instalar las librerías manualmente usando pip o conda.:

Utilizando pip:

```python
python -m venv venv
source venv/bin/activate #Linux
venv\Scripts\activate #Windows
pip install -r requirements.txt
```

Utilizando conda:

```python
conda env create -f environment.yml -y
conda activate oceanhackweek2025
```

En el archivo `Reportes_clorofila.ipynb` se definen los parametros `(min_lat, max_lat, min_lon, max_lon)` de la región de interés, asi como un nombre para esa región para generar el informe en formato html.
