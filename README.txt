Always wanted to create or implement you own grafana stack complete with Loki, Promtail, Elk stack, Prometheus, Node Exporter and Cadvisor ?

This framework will give you a baseline to implement just that.

It comes complete with a docker-compose stack to be natively used with Traefik.
The stack get's deployed with a .env file.

Make sure to define your own .env file, with the following details:

TRAEFIK_VOLUME=/path/to/the/traefik/volume/
NEXTCLOUDAuditLog=/path/to/the/traefik/log/
NEXTCLOUDLog=/path/to/the/nextcloud/log/
accessToken=github access token

after the .env file has been created, perform an "docker-compose up -d" and the stack should be created.