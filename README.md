Fintech Data Pipeline
Pipeline de datos diseñado para procesar, transformar y analizar información financiera utilizando herramientas modernas de ingeniería de datos.
 Objetivo del proyecto
Construir un pipeline modular y escalable que permita:
- Ingesta de datos desde APIs, archivos o fuentes externas
- Almacenamiento en Google Cloud Storage
- Procesamiento y orquestación con Airflow
- Modelado y transformación con dbt
- Exposición de datos listos para análisis en BigQuery

   Estructura del proyecto
fintech-data-pipeline/
│
├── airflow/        # DAGs y configuración de Airflow
├── data/           # Datos crudos o temporales
├── dbt/            # Modelos, tests y documentación de dbt
├── notebooks/      # Exploración y análisis en Jupyter
├── scripts/        # Scripts auxiliares (ETL, utils, loaders)
└── infra/          # Infraestructura (IaC, configs, deploy)


 Tecnologías principales
- Python 3.10+
- Apache Airflow
- dbt Core
- Google Cloud Platform
- Cloud Storage
- BigQuery
- GitHub para versionado
   Próximos pasos
- Configurar entorno virtual
- Crear primer DAG en Airflow
- Crear proyecto dbt
- Conectar Airflow → GCP → BigQuery
- Implementar primer pipeline end-to-end

¿Qué hacemos ahora?
Tenés dos caminos posibles:
 Seguimos con el pipeline (recomendado)
- Crear entorno Python
- Instalar Airflow
- Crear primer DAG
- Crear bucket en GCP
- Crear dataset en BigQuery
 Mejoramos el README con más detalles
- Agregar diagrama del pipeline
- Agregar instrucciones de instalación
- Agregar roadmap
- Agregar badges (build, version, etc.)


