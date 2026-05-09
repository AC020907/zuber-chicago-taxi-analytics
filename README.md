```markdown
# 🚖 Zuber Chicago Taxi Analytics - Análisis de Mercado y Comportamiento de Usuarios

Python
Pandas
SciPy
Matplotlib

📋 Descripción del Proyecto
Este proyecto constituye un análisis estratégico integral del mercado de taxis en Chicago para la empresa Zuber, utilizando datos de viajes, empresas competidoras y condiciones climáticas. El objetivo es identificar patrones de comportamiento de usuarios, evaluar la estructura competitiva del mercado y cuantificar el impacto de factores externos en la duración de los viajes para optimizar la estrategia de entrada al mercado.

🎯 Objetivos Estratégicos
🏢 Analizar la estructura competitiva del mercado de taxis en Chicago
🗺️ Identificar zonas de alta demanda y patrones espaciales de movilidad urbana
🌦️ Evaluar el impacto del clima en la duración y comportamiento de viajes
📊 Realizar pruebas estadísticas para validar hipótesis sobre factores externos
💡 Proporcionar recomendaciones estratégicas basadas en evidencia para Zuber
🔍 Detectar oportunidades de mercado y nichos desatendidos
📊 Dataset y Alcance del Análisis
Período de análisis: 15-16 de noviembre de 2017  
Ubicación: Chicago, Illinois  
Enfoque: Viajes Loop ↔ Aeropuerto O'Hare

Estructura de datos:
Empresas de taxis (project_sql_result_01.csv):
- company_name: Nombre de la empresa de taxis
- trips_amount: Número total de viajes realizados
- Volumen: 64 empresas analizadas

Barrios y demanda (project_sql_result_04.csv):
- dropoff_location_name: Nombre del barrio de destino
- average_trips: Promedio de viajes finalizados en noviembre 2017
- Volumen: 94 barrios de Chicago

Viajes Loop-O'Hare (project_sql_result_07.csv):
- start_ts: Timestamp de inicio del viaje
- weather_conditions: Condiciones climáticas (Good/Bad)
- duration_seconds: Duración del viaje en segundos
- Volumen: 1,068 viajes analizados

🛠️ Stack Tecnológico
Python 3.9+: Lenguaje principal de análisis
Pandas: Manipulación y análisis de datos estructurados
NumPy: Cálculos numéricos y operaciones estadísticas
Matplotlib: Visualización de datos y generación de insights gráficos
SciPy: Pruebas estadísticas avanzadas (t-tests de Student)
**
