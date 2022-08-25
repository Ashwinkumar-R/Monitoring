# Monitoring

Docker based monitoring using Prometheus and Grafana.  
Docker file is written to be in compatible with MacOS mapping to internal host.

# Start

docker-compose -f docker-compose.yml up

# Metrics URL

- Grafana - (http://localhost:3000)
- Prometheus - [localhost:9090] (http://localhost:9090)
- Alert Manager - [localhost:9093] (http://localhost:9093)
- Cadvisor - [localhost:8084] (http://localhost:8084)
- Node Exporter - [localhost:9100] (http://localhost:9100)
- Redis Exporter - [localhost:9121] (http://localhost:9121)
