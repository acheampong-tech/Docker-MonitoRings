# Docker-Monitoring
monitoring docker containers using cadvisor, prometheus,redis and grafana

# Run - Docker-compose up
if everything is working good, you should see this message
msg="Server is ready to receive web requests."
check three containers are running using docker-compose ps

# Accessing cadvisor
access on port 8080

# Acessing prometheus
access on port 9090

# Run Grafana via Docker CLI
To run the latest stable version of Grafana, run the following command:
docker run -d -p 3000:3000 --name=grafana grafana/grafana-enterprise
access on port 3000

# Prometheus data source, you can configure with that of your Grafana
