# Análisis de Consumo de Reels y Shorts

Análisis de minería de datos sobre el impacto del consumo de videos cortos en plataformas como Instagram Reels, TikTok y YouTube Shorts.

## Descripción

Este proyecto aplica técnicas de minería de datos para explorar cómo el consumo de videos cortos afecta la atención y el comportamiento de los usuarios en redes sociales. A partir de un conjunto de datos con 12.000 registros, se realiza un análisis de agrupamiento (clustering) para identificar patrones de consumo y perfiles de usuario según su interacción con este tipo de contenido.

El análisis incluye la selección del número óptimo de clusters mediante la métrica del codo (elbow method), la reducción de dimensionalidad para visualización, y la exportación de los resultados a Power BI para construir dashboards interactivos que faciliten la interpretación de los hallazgos.

## Tecnologías

- Python
- Jupyter Notebook
- pandas
- scikit-learn
- matplotlib / seaborn
- Power BI (visualización de resultados)

## Uso

### Requisitos previos

- Python 3.8 o superior
- Jupyter Notebook o JupyterLab

### Instalación

Instala las librerías necesarias con pip:

```bash
pip install pandas scikit-learn matplotlib seaborn notebook
```

### Ejecución

1. Clona el repositorio o descarga los archivos.
2. Abre el notebook principal:

```bash
jupyter notebook Analisis_ReelsShort.ipynb
```

3. Ejecuta las celdas en orden para reproducir el análisis completo.

Los archivos CSV incluidos en el repositorio contienen los datos originales (`reels_attention_span_dataset_12000.csv`) y los resultados intermedios del clustering. El archivo `analisis.pbix` requiere Power BI Desktop para visualizar los dashboards.
