# QCM-Sensor-Alcohol-Dataset Clasificación de Alcoholes (QCM sensor)

## Descripción
Pipeline PySpark para clasificar 5 alcoholes usando datos del sensor QCM (archivo QCM3.csv). Incluye EDA, preprocesamiento, entrenamiento con Cross-Validation y visualizaciones.

## Estructura
- `data/QCM3.csv` - dataset
- `notebooks/Analisis_QCM.ipynb` - notebook
- `src/pipeline_evaluacion.py` - script PySpark
- `models/` - modelos guardados
- `outputs/figures` - figuras generadas
- `Informe_Plantilla.md` - plantilla de informe

## Requisitos
1. Java (OpenJDK 11+)
2. Python 3.8+
3. Instalar dependencias:
```bash
pip install -r requirements.txt
