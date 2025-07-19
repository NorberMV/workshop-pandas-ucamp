# Data CSVs for Pandas Workshop

Este repositorio proporciona archivos CSV de muestra como alternativas a los datos de Excel en el [Colab del Taller Pandas-Excel](https://colab.research.google.com/drive/1cL25mifmnJc5JwvVryRaowH0bU_c8bw-?usp=sharing). Úsalos con Pandas mediante `pd.read_csv('/ruta/al/archivo.csv')` después de montar Google Drive.

## Archivos
- `sample_data1.csv`: Conjunto de datos básico con columnas numéricas y categóricas.
- `sample_data2.csv`: Equivalente a múltiples hojas (archivos divididos si es necesario); incluye fechas y valores faltantes.

## Inicio Rápido
1. Sube los CSVs a Google Drive.
2. En Colab: `import pandas as pd; df = pd.read_csv('/content/drive/My Drive/sample_data1.csv')`.
3. Ejecuta los pasos de EDA del taller (p. ej., `df.head()`, `df.describe()`).
