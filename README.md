# data-engineering-zoomcamp-2026
repository for data engineering zoomcamp

Arquitectura propuesta

data-engineering-zoomcamp-2026/
├── README.md                          # Overview y guía de inicio rápido
├── requirements.txt                   # Dependencias globales
├── docker-compose.yml                 # Servicios comunes (Postgres, pgAdmin, Kestra)
├── .env.example                       # Template de variables de entorno
│
├── 01-docker-terraform/              # Module 1: Containerization & IaC
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