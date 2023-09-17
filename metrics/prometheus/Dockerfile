FROM prom/prometheus:v2.46.0

WORKDIR /etc/prometheus

COPY ./config/alert.rules ./
COPY ./config/prometheus.yaml ./
