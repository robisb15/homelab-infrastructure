# Monitoring Stack

## Service

- Prometheus
- Node Exporter

## Port

| Service       | Fungsi                      | Port |
| ------------- | --------------------------- | ---: |
| Prometheus    | Time-series database        | 9090 |
| Node Exporter | Monitoring host Ubuntu      | 9100 |
| Grafana       | Dashboard visualisasi       | 3000 |
| cAdvisor      | Monitoring container Docker | 8080 |


## Cara Menjalankan

```bash
docker compose up -d
```

## Cara Menghentikan

```bash
docker compose down
```

## Struktur

- compose.yml
- prometheus.yml
- .env.example

## Keterangan

Prometheus mengambil metrics dari Node Exporter setiap 15 detik.

## Dashboard

Grafana menggunakan dashboard:

- Node Exporter Full (ID: 1860)

## Monitoring

- CPU
- Memory
- Disk
- Filesystem
- Network
- Uptime

## Monitoring Stack

- Prometheus
- Grafana
- Node Exporter
- cAdvisor

### Features

- Host Monitoring
- Docker Monitoring
- Resource Usage