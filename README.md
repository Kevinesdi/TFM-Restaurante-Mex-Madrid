# TFM-Restaurante-Madrid
Código fuente y datasets para el TFM GastroData de mejor ubicación para un restaurante mexicano en Madrid usando Business Analytics e IA

# Análisis de ubicación óptima para Restaurante Mexicano en Madrid

Este repositorio contiene el material suplementario para el Trabajo de Fin de Máster (TFM) titulado "[Gastro Data: Análisis Preciso + Posición Estratégica = Triunfo Gastronómico]". El proyecto utiliza técnicas de Business Analytics y Machine Learning para identificar ubicaciones óptimas.

## Contenido del Repositorio

### 1. Datos (`/data`)
Se incluyen 9 datasets fuente utilizados para el análisis:
- **B1 a B3**: Información de restaurantes, menús y terrazas.
- **B4**: Flujo peatonal.
- **B5**: Licencias urbanísticas.
- **B6 y B7**: Datos demográficos y poblacionales.
- **B8 y B9**: Infraestructura (parking y transporte).
**⚠️ Nota sobre Archivos Grandes:**
> Los archivos `actividadeconomica` y `licencias` en raw se encuentran comprimidos en formato `.zip` debido a su tamaño. El script de carga los procesa automáticamente.

### 2. Código Fuente (`/src`)
- **`01_etl_db`**: Scripts para limpieza de datos y carga en base de datos PostgreSQL.
- **`02_ranking`**: Algoritmo de ponderación para el scoring de mejor zona para un restaurante mexicano en Madrid.
- **`03_models`**: Entrenamiento y validación del modelo de Machine Learning.

## Tecnologías Utilizadas
- Python (Pandas, Scikit-Learn, SQLAlchemy, GeoPandas)
- PostgreSQL / PgAdmin 4
- PowerBI

## Instrucciones de Reproducción
1. Instalar dependencias: `pip install -r requirements.txt`
2. Ejecutar scripts de limpieza.
3. Configurar conexión a BD local en `src/config.py`.
