# Realtime Data Streaming | End-to-End Data Engineering Project

## Tabla de contenido

- [Introducción](#introducción)
- [Arquitectura del sistema](#arquitectura-del-sistema)
- [Lo que hice](#lo-que-hice)
- [Tecnologias](#tecnologias)
- [Getting Started](#getting-started)

## Introducción

Este proyecto sirve como una guía integral para construir una tubería de ingeniería de datos de extremo a extremo. Cubre cada etapa desde la ingestión de datos hasta el procesamiento y finalmente el almacenamiento, utilizando un conjunto tecnológico sólido que incluye Apache Airflow, Python, Apache Kafka, Apache Zookeeper, Apache Spark y Cassandra. Todo está contenerizado con Docker para facilitar la implementación y escalabilidad.

## Arquitectura del Sistema

![System Architecture](https://github.com/Skpow1234/end-to-end-data-engineering-project/blob/main/Data%20engineering%20architecture.png)

**El proyecto está diseñado con los siguientes componentes:**

- **Fuente de Datos**: Utilizamos la API `randomuser.me` para generar datos de usuario aleatorios para nuestra tubería.

- **Apache Airflow**: Encargado de orquestar la tubería y almacenar los datos obtenidos en una base de datos PostgreSQL.

- **Apache Kafka y Zookeeper**: Utilizados para la transmisión de datos desde PostgreSQL hacia el motor de procesamiento.

- **Control Center y Schema Registry**: Ayudan en la supervisión y gestión de esquemas de nuestras transmisiones en Kafka.

- **Apache Spark**: Para el procesamiento de datos con sus nodos maestros y de trabajo.

- **Cassandra**: Donde se almacenarán los datos procesados.

## Lo que hice

- **Configuración de una tubería de datos con Apache Airflow**
- **Transmisión de datos en tiempo real con Apache Kafka**
- **Sincronización distribuida con Apache Zookeeper**
- **Técnicas de procesamiento de datos con Apache Spark**
- **Soluciones de almacenamiento de datos con Cassandra y PostgreSQL**
- **Contenerización de toda tu configuración de ingeniería de datos con Docker**

## tecnologias

- Apache Airflow
- Python
- Apache Kafka
- Apache Zookeeper
- Apache Spark
- Cassandra
- PostgreSQL
- Docker

## Getting Started

1. Clone the repository:

    ```bash
    git clone https://github.com/Skpow1234/end-to-end-data-engineering-project.git
    ```

2. Run Docker Compose to spin up the services:

    ```bash
    docker-compose up
    ```
