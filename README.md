
---

# README — Chicago Taxi Analysis

```md
# Análisis de Viajes de Taxi en Chicago

## Descripción del proyecto

Este proyecto analiza datos de compañías de taxi y viajes realizados en Chicago con el objetivo de identificar patrones de demanda, zonas más populares y factores externos que afectan la duración de los viajes.

El análisis combina exploración de datos, consultas SQL y pruebas estadísticas para obtener insights relevantes sobre movilidad urbana y comportamiento de usuarios.

## Funcionalidades del análisis

- **Análisis exploratorio de datos**
  - Empresas con mayor cantidad de viajes
  - Barrios con más destinos
  - Distribución de viajes por compañía

- **Consultas SQL**
  - Filtrado y agrupación de datos
  - JOINs entre tablas
  - Análisis temporal

- **Pruebas estadísticas**
  - Comparación de duración de viajes
  - Impacto del clima en los trayectos
  - Validación de hipótesis

- **Visualizaciones**
  - Gráficos de barras
  - Histogramas
  - Diagramas comparativos

## Tecnologías utilizadas

- Python 3
- SQL
- Pandas
- Matplotlib
- SciPy
- Jupyter Notebook

## Estructura del proyecto

```

.
├── README.md
├── chicago\_taxi\_analysis.ipynb
├── company\_trips.csv
├── neighborhoods.csv
└── weather\_data.csv

```

## Principales conclusiones

- Algunas compañías dominan claramente el mercado de viajes.
- Los barrios céntricos concentran la mayor demanda.
- Las condiciones climáticas afectan significativamente la duración de los trayectos.
- Las pruebas estadísticas confirmaron diferencias relevantes entre grupos analizados.

## Cómo ejecutar el proyecto localmente

1. Clona el repositorio:
   ```bash
   git clone <URL_DEL_REPOSITORIO>
   cd <NOMBRE_DEL_REPOSITORIO>

Crea y activa un entorno virtual:

python -m venv env
source env/bin/activate   # macOS/Linux
env\Scripts\activate      # Windows

Instala las dependencias:

pip install pandas numpy matplotlib scipy jupyter

Ejecuta Jupyter Notebook:

jupyter notebook
Abre el archivo .ipynb
