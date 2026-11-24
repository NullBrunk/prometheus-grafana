<div align="center">

# prometheus-grafana
_Monitoring lab with the Prometheus + Grafana stack (WiP)_

![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?logo=grafana&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)

<!-- ![Discord](https://img.shields.io/badge/Discord-5865F2?logo=discord&logoColor=white) -->
<!-- ![Alertmanager](https://img.shields.io/badge/Alertmanager-E6522C) -->

</div>


```
git clone https://github.com/NullBrunk/prometheus-grafana/
cd prometheus-grafana/

sudo chown -R 65534:65534 data/prometheus
sudo chown -R 472:472 data/grafana

cp .env.example .env
```

Edit .env then:

```
sudo docker compose up
```
