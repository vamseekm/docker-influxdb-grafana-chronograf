# docker-influxdb-grafana-chronograf

Aanalytics & Monitoring software bundled up into convenient docker containers.

What it contains ?
- InfluxDB 
- Grafana
- Chronograf

API & Web UI details:
- http://127.0.0.1:8086/  - InfluxDB API end-point.
- http://127.0.0.1:8087/  - Chronograf Web UI.
- http://127.0.0.1:3000/  - Grafana Web UI.

How to use it:
- First clone this repo.
- Switch to the repo folder.
- Use command ```docker-compose up -d``` to start containers in background.
