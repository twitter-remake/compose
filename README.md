# Local Docker Compose

This repository contains a docker-compose file that can be used to run the application infrastructure dependencies locally such as:

1. Postgres database for each service
2. Consul service discovery
3. Kafka (not yet implemented)
4. Prometheus monitoring (not yet implemented)
5. Grafana dashboard (not yet implemented)
6. etc.

## Important Links and Ports

* [Consul UI](http://localhost:8500)
* [Grafana Dashboard](#) (not yet implemented)
* Postgres
  * Auth
    * DB: auth
    * Port: 5432
  * User
    * DB: user
    * Port: 5433
* Kafka (not yet implemented)