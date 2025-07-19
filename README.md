# 👩‍🔬 Pandas Workshop Data Sources

Este repositorio proporciona archivos CSV de muestra como alternativas a los datos de Excel en el [Colab del Taller Pandas-Excel](https://colab.research.google.com/drive/1cL25mifmnJc5JwvVryRaowH0bU_c8bw-?usp=sharing). Úsalos con Pandas mediante `pd.read_csv('/ruta/al/archivo.csv')` después de montar Google Drive.

## Inicio Rápido
1. Clona este repo ó descarga los archivos de la carpeta `data/`.
2. Sube los CSVs a Google Drive.
3. En Colab: 
```bash
import pandas as pd; df = pd.read_csv('/content/drive/My Drive/{csv_name}.csv')
```
4. Ejecuta los pasos de EDA del taller (p. ej., `df.head()`, `df.describe()`).
