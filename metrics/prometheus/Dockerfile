FROM prom/prometheus:v2.49.1

WORKDIR /etc/prometheus

COPY ./config/alert.rules ./
COPY config/prometheus.yml ./
