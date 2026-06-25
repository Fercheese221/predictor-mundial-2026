# Predictor del Mundial 2026


Este proyecto implementa dos modelos estadísticos, uno basado en **Power ranking** y otro basado en la **Distribución de Poisson**, para predecir hasta que fase llegará cada selección y para obtener la probabilidad de un marcador dentro de un partido, respectivamente. Ambos modelos toman en cuenta la historia de cada selección (resultados 2014-2026) y la forma actual (resultados mundial 2026).

## 📁 Estructura del Repositorio

El proyecto está organizado de la siguiente manera para garantizar su reproducibilidad:

```text
├── Datos/                       # Carpeta con los archivos origen y datos procesados
├── Creación del dataset.ipynb   # Notebook de ETL, limpieza y feature engineering
├── Modelo.ipynb                 # Notebook con el power ranking y el motor de Poisson y visualizaciones
├── datos_modelo_poisson.csv     # Dataset final con las fuerzas híbridas calculadas
└── README.md                    # Portada del proyecto
