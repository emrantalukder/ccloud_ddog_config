# Getting Started

* `ConfluentCloud--2021-06-09T20_05_45.json` DataDog dashboard from presentation

* `env.sh` environment variables needed for running docker-compose. Contains CCloud API keys and hostnames.


* `docker-compose.yml` ccloudexporter and dd-agent services

* `openmetrics.yaml` DataDog config for Prometheus

* `kafka_consumer.yaml`  DataDog config for Kafka Consumer (lag)
  * line 54 set connection string
  * line 153: api key as SASL username
  * line 158: api secret as SASL password
