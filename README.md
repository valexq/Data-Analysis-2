# Calidad del aire en Colombia - Análisis de datos

## Integrantes:

| Nombre               | Rol                                    | GitHub        |
|----------------------|----------------------------------------|---------------|
| Vanessa Alfaro       | Infraestructura + Exploración de datos | @valexq       |
| Juan Manuel Valencia | Calidad de datos (EDA)                 | @Juanchos2905 |
| Ziuvar Ruiz          | Análisis visual e hipótesis            | @ziuvar       |
| Juan Cardona         | Preprocesamiento y reducción           | @jcardser     |

## Descripción del proyecto
Proyecto del segundo evento evaluativo del curso de Análisis de Datos. 
Se realiza un análisis exploratorio completo (EDA) sobre el dataset de 
Calidad del Aire en Colombia del IDEAM, disponible en Datos Abiertos Colombia.
El análisis incluye exploración diferentes bases de datos, justificación de elección 
de una de ellas, análisis exploratorio completo (EDA), visualizaciones, hipótesis,
aplicación de técnicas de preprocesamiento y reducción de bimensionalidad.

## Dataset
- **Nombre:** Calidad del Aire en Colombia (Promedio Anual)
- **Fuente:** IDEAM — Datos Abiertos Colombia
- **Link:** https://www.datos.gov.co/d/g4t8-zkc3
- **Registros:** 29,683 (muestra del dataset oficial de 32.8M)
- **Variables:** 28

## Estructura del repositorio
```
├── data/
│   ├── raw/                        # Dataset original sin modificar
│   └── processed/                  # Datos limpios y preprocesados
├── notebooks/
│   ├── 01_exploracion.ipynb        # Fase 1 — Exploración de BD (Vanessa)
│   ├── 02_eda_calidad.ipynb        # Fase 2 — Calidad de datos (Integrante 2)
│   ├── 03_eda_visual.ipynb         # Fase 2 — Análisis visual (Integrante 3)
│   └── 04_preprocesamiento.ipynb   # Fase 3 — Preprocesamiento y PCA (Integrante 4)
├── docs/
│   └── hipotesis_insights.md       # Hipótesis e insights del EDA
├── requirements.txt
└── README.md
```

## Instalación
```bash
# Clonar el repositorio
git clone 
cd 
# Instalar dependencias
python3 -m pip install -r requirements.txt
# Abrir Jupyter
jupyter notebook
```
## Tecnologías utilizadas
- Python 3
- pandas, numpy
- matplotlib, seaborn, plotly
- scikit-learn
- scipy
- Jupyter Notebook
