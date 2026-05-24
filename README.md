# Hi, I'm Narendra 👋

**Backend & Infrastructure Engineer** · IIT Delhi · Bangalore, India

I build distributed systems, multi-tenant infrastructure, and developer platforms — mostly in Go, on Kubernetes.

Most of my production work lives in **private org repos** at [Nava](https://github.com/kluisz), but here's what I've been building:

---

## 🔧 What I Work On

### @ Nava (Aug 2025 – Present)
- **S3-compatible Object Storage** — Built a multi-tenant MinIO-based platform in Go with multipart uploads, versioning, lifecycle, retention, and full AWS CLI parity. Serving 100+ tenants at TB scale, 99.9%+ availability, p99 < 150ms.
- **Managed OpenSearch Service** — Designed a Kubernetes-native control plane (Go + gRPC/REST) to provision multi-tenant OpenSearch clusters via a single API call. Built idempotent reconcilers, Traefik-based shared-hostname routing, and a health watcher decoupled from data-plane availability.
- **Kubernetes Infrastructure** — Production Helm deployments with tenant-scoped values, encryption at rest (Rook-Ceph + KMS-backed MongoDB), TLS in transit, ingress-nginx + cert-manager + Cloudflare DNS-01 wildcard certs, and Fluent Bit → OpenSearch log pipelines.

### @ PolicyBazaar (Mar 2025 – May 2025)
- Built schema-driven dynamic form APIs (IPD module) with master-data integration for real-time config resolution.
- Optimized SQL on a 10M+ row production DB — cut p95 latency from 800ms → 440ms (45% improvement).

---

## 🛠 Tech Stack

**Languages:** Go · Python · Java · C++ · SQL  
**Backend:** gRPC · REST · Gin · GORM · FastAPI · Spring Boot  
**Infra:** Kubernetes · Docker · Helm · MinIO · Rook-Ceph · AWS · GCP  
**Data:** MongoDB · PostgreSQL · Redis · OpenSearch  
**Observability:** Prometheus · Grafana · Fluent Bit  

---

## 📚 Algorithms & CS Foundations

**Router Networks for File Transfer** *(IIT Delhi, 2024)*  
Modified Dijkstra + max-heap for throughput maximization; Bitmask DP with anchored final-file subsets — 78% reduction in computation time.

**Efficient Nearby Search** *(IIT Delhi, 2023)*  
2D nearest-neighbor search using layered range trees with fractional cascading — query complexity from O(n log n) to O(log²n + k), 60% latency reduction on benchmarks.

---

## 📫 Get in Touch

- 💼 [LinkedIn](https://linkedin.com/in/narendra-nath-sharma-iitd)
- 💻 [LeetCode](https://leetcode.com/u/narendra_2608/)
- 📧 narendranathsharma2608@gmail.com
