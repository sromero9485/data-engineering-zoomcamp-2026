# data-engineering-zoomcamp-2026

Repository for data engineering zoomcamp

## Arquitectura propuesta

```
data-engineering-zoomcamp-2026/
├── README.md                          # Overview y guía de inicio rápido
├── requirements.txt                   # Dependencias globales
├── docker-compose.yml                 # Servicios comunes (Postgres, pgAdmin, Kestra)
├── .env.example                       # Template de variables de entorno
│
├── 01-docker-terraform/               # Module 1: Containerization & IaC
│   ├── README.md                      # Objetivos y recursos del módulo
│   ├── homework/                      # Tareas entregables
│   │   ├── solution.py
│   │   └── README.md
│   ├── notes/                         # Tus notas personales
│   ├── scripts/                       # Código de referencia del curso
│   └── terraform/                     # Archivos Terraform
│
├── 02-workflow-orchestration/         # Module 2: Kestra
│   ├── README.md
│   ├── homework/
│   ├── flows/                         # Archivos YAML de Kestra
│   │   ├── 01_hello_world.yaml
│   │   ├── 02_python.yaml
│   │   └── ...
│   └── notes/
│
├── 03-data-warehouse/                 # Module 3: BigQuery
│   ├── README.md
│   ├── homework/
│   ├── sql/                           # Queries y modelos
│   └── notes/
│
├── 04-analytics-engineering/          # Module 4: dbt & Transformations
│   ├── README.md
│   ├── homework/
│   ├── dbt/                           # Proyecto dbt
│   │   ├── models/
│   │   ├── tests/
│   │   └── dbt_project.yml
│   └── notes/
│
├── 05-data-platforms/                 # Module 5: Bruin Data Platforms
│   ├── README.md
│   ├── homework/
│   ├── pipelines/                     # Pipelines Bruin
│   └── notes/
│
├── 06-batch/                          # Module 6: Spark
│   ├── README.md
│   ├── homework/
│   ├── scripts/                       # Scripts PySpark
│   └── notes/
│
├── 07-streaming/                      # Module 7: Kafka
│   ├── README.md
│   ├── homework/
│   ├── kafka/                         # Configuración Kafka
│   ├── producers/                     # Código de productores
│   ├── consumers/                     # Código de consumidores
│   └── notes/
│
├── workshops/                         # Talleres especiales
│   ├── 01-data-ingestion-dlt/
│   │   ├── README.md
│   │   ├── homework/
│   │   └── examples/
│   └── ...
│
├── final-project/                     # Proyecto Final
│   ├── README.md                      # Problem statement detallado
│   ├── src/
│   │   ├── ingestion/                 # ETL/streaming
│   │   ├── warehouse/                 # Transformaciones
│   │   └── analytics/                 # dbt o SQL
│   ├── infrastructure/                # Terraform/IaC
│   ├── dashboards/                    # Looker/Streamlit
│   ├── tests/                         # Unit tests (extra mile)
│   ├── docker-compose.yml
│   └── Makefile                       # (extra mile)
│
├── docs/                              # Documentación centralizada
│   ├── setup.md                       # Guía de setup
│   ├── glossary.md                    # Glosario de conceptos
│   └── tools-guide.md                 # Guías de herramientas
│
├── .gitignore
├── Makefile                           # (Opcional, para automatizar tareas)
└── LICENSE
```

## Estructura de módulos

Cada módulo sigue este patrón:

| Carpeta | Descripción |
|---------|-------------|
| `README.md` | Objetivos, recursos y guía del módulo |
| `homework/` | Tareas entregables con soluciones |
| `notes/` | Tus notas personales de aprendizaje |
| `scripts/` o `flows/` o `sql/` | Código de referencia y ejemplos |

## Primeros pasos

1. Clona el repositorio
2. Copia `.env.example` a `.env`
3. Configura tus variables de entorno
4. Ejecuta `docker-compose up` para los servicios comunes
5. Navega a cada módulo y sigue el README correspondiente

## Requisitos

- Python 3.10+
- Docker & Docker Compose
- Terraform (para módulos IaC)
- Git

## Contribuyendo

Sigue la estructura propuesta al agregar nuevo contenido a cada módulo.
