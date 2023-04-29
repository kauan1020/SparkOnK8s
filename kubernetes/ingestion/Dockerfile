
FROM gcr.io/spark-operator/spark-py:v3.0.0

USER root:root

RUN mkdir -p /app

COPY ingest-circuits.py /app/

WORKDIR /app

USER 1001