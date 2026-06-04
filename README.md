# Hey, I'm Vanshul 👋

**Platform Engineer** building observability infrastructure at scale.

Active open-source contributor to the [OpenTelemetry Collector](https://github.com/open-telemetry/opentelemetry-collector) ecosystem — fixing bugs, improving reliability, and making telemetry pipelines more robust.

---

### Open Source Contributions

<a href="https://github.com/open-telemetry/opentelemetry-collector"><img src="https://img.shields.io/badge/OpenTelemetry-Collector-blue?logo=opentelemetry&logoColor=white" /></a>
<a href="https://github.com/open-telemetry/opentelemetry-collector-contrib"><img src="https://img.shields.io/badge/OpenTelemetry-Contrib-blueviolet?logo=opentelemetry&logoColor=white" /></a>

**Merged contributions to OpenTelemetry Collector (CNCF Graduated Project):**

| Area | Contribution |
|------|-------------|
| **Data Integrity** | Fixed batch splitter data loss when items exceed max batch size |
| **Spec Compliance** | Aligned `Value.AsString()` with OTel spec for NaN/Infinity representation |
| **HTTP Protocol** | Added RFC 9110 `identity` Content-Encoding support |
| **Exporter Telemetry** | Documented native histogram support for Prometheus exporter |
| **ClickHouse** | Fixed exporter connecting to wrong database when `create_schema: false` |
| **Azure Monitor** | Fixed regression swapping client/server attributes in trace mapping |
| **OTTL** | Fixed `Substring` function corrupting multibyte UTF-8 strings (CJK, emoji) |
| **Load Balancing** | Removed process-killing `log.Fatalf` in AWS Cloud Map resolver |
| **PostgreSQL Storage** | Fixed SQL syntax error with hyphens in component IDs |
| **telemetrygen** | Fixed `--allow-export-failures` flag ignored in batch mode |

---

### Tech Stack

```
Observability    OpenTelemetry | Prometheus | Grafana | ClickHouse | Datadog
Cloud            AWS (S3, CloudWatch, EKS, IAM) | Kubernetes | Terraform
Languages        Go | Java | Python | HCL
Infrastructure   ArgoCD | Helm | Docker | Kafka
```

---

### What I'm Working On

- Improving reliability of the OpenTelemetry Collector's exporter/receiver components
- Building observability platforms with OTel, ClickHouse, and Grafana
- Infrastructure-as-Code with Terraform and Kubernetes

---

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Vanshul97&show_icons=true&theme=dark&hide_border=true&count_private=true" width="48%" />
  <img src="https://github-readme-streak-stats.herokuapp.com?user=Vanshul97&theme=dark&hide_border=true" width="48%" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/vanshulsuneja/"><img src="https://img.shields.io/badge/-LinkedIn-0077B5?logo=linkedin&logoColor=white&style=flat-square" /></a>
</p>
