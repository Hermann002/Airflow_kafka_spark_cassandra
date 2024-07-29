# Airflow_kafka_spark_cassandra
## Introduction
The aim of this project is to create a live streaming data ingestion pipeline. Get the data from the API, pass it through the kafka broker and save it in the cassandra database.

## Project structure
- `dags`: Contient le code Kafka d'ingestion des données, connecté
- `script`: Contient le processus principal qui sera exécuté lorsque le conteneur est démarré
- `spark_stream.py`
- `docker-compose.yml`: contient les images des conteneurs qui seront exécutés.
