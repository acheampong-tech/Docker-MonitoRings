# Docker-Monitoring
monitoring docker containers using cadvisor, prometheus,redis and grafana

# Run - Docker-compose up
If everything is functioning correctly, you should see the following message:
msg="Server is ready to receive web requests."
Verify that the containers are running by using the command:
docker-compose ps

# Accessing cadvisor
access on port 8080
eg. http://localhost:8080

# Acessing prometheus
access on port 9090
eg. http://localhost:9090

# Run Grafana via Docker CLI
To run the latest stable version of Grafana, run the following command:
docker run -d -p 3000:3000 --name=grafana grafana/grafana-enterprise
eg. http://localhost:3000

# Prometheus data source, you can configure with that of your Grafana
