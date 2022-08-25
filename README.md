# Monitoring

Docker based monitoring using Prometheus and Grafana.  
Docker file is written to be in compatible with MacOS mapping to internal host.

# Start

docker-compose -f docker-compose.yml up

# Metrics URL

- Grafana - http://localhost:3000
- Prometheus - http://localhost:9090
- Alert Manager - http://localhost:9093
- Cadvisor - http://localhost:8084
- Node Exporter - http://localhost:9100)
- Redis Exporter - http://localhost:9121

# Login Details

**Grafana**

username: admin  
password: admin
