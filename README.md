# Sprint7 — Exploración de datos de vehículos (Streamlit + Plotly)

Aplicación web sencilla para realizar análisis exploratorio de datos (EDA) sobre anuncios de vehículos en EE. UU. usando Streamlit, Pandas y Plotly.
Permite visualizar la distribución del odómetro y la relación entre precio y kilometraje, con controles interactivos (botones/casillas).

Funcionalidad

- Carga del dataset vehicles_us.csv.

- Visualizaciones interactivas con Plotly:

  - Histograma del odometer (kilometraje).

  - Dispersión odometer vs price.

- Interfaz web con Streamlit (ejecución local o en la nube).

Estructura del proyecto
SPRINT7/
├─ notebooks/
│ └─ EDA.ipynb # Análisis exploratorio en Jupyter (opcional para la app)
├─ .gitignore
├─ app.py # App principal de Streamlit (dashboard)
├─ requirements.txt # Dependencias mínimas
├─ README.md
└─ vehicles_us.csv # Dataset usado por la app

Ejecutar localmente
copia y pega en tu terminal el codigo que esta denajo de los numerales (1, 2, 3, etc.)

1. (Opcional) Crear y activar entorno:
   conda create -n vehicles_env python=3.10
   conda activate vehicles_env

2. Instalar dependencias:
   pip install -r requirements.txt

3. Ejecutar la app:
   streamlit run app.py

Abrirá el navegador en http://localhost:8501.

Nota: vehicles_us.csv debe estar en la raíz del repo para que la app lo encuentre en Render.
