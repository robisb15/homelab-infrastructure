# Monitoring Stack

## Service

- Prometheus
- Node Exporter

## Port

| Service | Port |
|---------|------|
| Prometheus | 9090 |
| Node Exporter | 9100 |

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
