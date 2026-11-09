# Hi, I'm Narendra 👋

**Backend & Infrastructure Engineer** · IIT Delhi · Mumbai, India

I build distributed systems, multi-tenant infrastructure, and developer platforms — primarily using Go, Kubernetes, and cloud-native technologies.

My experience spans storage systems, Kubernetes operators, control planes, distributed applications, and production infrastructure.

---

## 🔧 What I Work On

### @ Nuvama Wealth (Aug 2026 – Present)
Software Engineer

Working in the financial technology domain, building software in a production engineering environment.

### @ Nava (Aug 2025 – July 2026)
Backend & Infrastructure Engineer

- **S3-compatible Object Storage** — Built a multi-tenant MinIO-based platform in Go with multipart uploads, versioning, lifecycle management, retention, and AWS CLI parity. Serving 100+ tenants at TB scale, with 99.9%+ availability and p99 latency below 150ms.
- **Managed OpenSearch Service** — Designed a Kubernetes-native control plane (Go + gRPC/REST) to provision multi-tenant OpenSearch clusters through a single API call. Built idempotent reconcilers, Traefik-based shared-hostname routing, and health watchers decoupled from data-plane availability.
- **Kubernetes Infrastructure** — Implemented production Helm deployments with tenant-scoped configurations, encryption at rest (Rook-Ceph + KMS-backed MongoDB), and TLS in transit.
- **Observability & Logging** — Built ingress-nginx, cert-manager, and Cloudflare DNS-01 wildcard TLS infrastructure with Fluent Bit → OpenSearch log pipelines.

### @ PolicyBazaar (Mar 2025 – May 2025)
Software Engineering Intern

- Built schema-driven dynamic form APIs (IPD module) with master-data integration for real-time configuration resolution.
- Optimized SQL queries on a 10M+ row production database, reducing p95 latency from 800ms to 440ms (45% improvement).

---

## 🛠 Tech Stack

**Languages:** Go · Python · Java · C++ · SQL

**Backend:** gRPC · REST · Gin · GORM · FastAPI · Spring Boot

**Infrastructure:** Kubernetes · Docker · Helm · MinIO · Rook-Ceph · AWS · GCP

**Databases & Storage:** MongoDB · PostgreSQL · Redis · OpenSearch

**Observability:** Prometheus · Grafana · Fluent Bit

---

## 📚 Projects & CS Foundations

**Router Networks for File Transfer** *(IIT Delhi, 2024)*

Modified Dijkstra + max-heap for throughput maximization; Bitmask DP with anchored final-file subsets — 78% reduction in computation time.

**Efficient Nearby Search** *(IIT Delhi, 2023)*

2D nearest-neighbor search using layered range trees with fractional cascading — query complexity from O(n log n) to O(log²n + k), achieving 60% latency reduction on benchmarks.

**Digital Circuit Implementation** *(IIT Delhi, 2022)*

Programmed multiplexers and sequence generators in Verilog using logic gates and self-implemented flip-flops. Simulated Synchronous Gray-Code and Ring counters using SR and D Flip-Flops on a CPLD board.

**Collision Simulations** *(IIT Delhi, 2022)*

Implemented efficient high-frequency collision handling for up to 1 million objects using min-heaps. Tracked object positions and velocities after collisions with O(1) state retrieval.

**Movie Recommendation System** *(Self Project, 2023)*

Built a content-based recommendation engine using TF-IDF and cosine similarity for personalized suggestions.

---

## 🧠 Interests & Deep Dives

Things I enjoy exploring and building around:

- Distributed systems & consensus protocols
- Multi-tenant control planes & Kubernetes operator patterns
- Sharding, replication & storage engine internals
- Database internals & storage architectures
- Caching strategies & rate limiting at scale
- Event-driven architectures & observability
- System design & scalable backend architectures

---

## 📫 Get in Touch

- 💼 [LinkedIn](https://linkedin.com/in/narendra-nath-sharma-iitd)
- 💻 [GitHub](https://github.com/naren-08)
- 🧩 [LeetCode](https://leetcode.com/u/narendra_2608/)
- 📧 narendranathsharma2608@gmail.com
