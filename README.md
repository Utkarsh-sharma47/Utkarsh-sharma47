<div align="center">
  <h1>Utkarsh Sharma</h1>
  <h3>Backend • Systems • AI Engineer</h3>

  <p>
    Building high-performance backend systems, distributed infrastructure,
    and AI-powered applications.
  </p>
</div>

---

## About Me

I'm a third-year Integrated M.Tech student in Information Technology at
ABV-IIITM Gwalior, focused on backend engineering, systems programming,
distributed systems, and AI infrastructure.

I enjoy working close to the system boundary, from low-latency C++ and
concurrency to cloud-native infrastructure and scalable backend services.

Currently, I'm:

- Contributing to CNCF open-source projects, particularly CloudNativePG
- Working on web development using React.js in an Agile/Scrum environment
- Exploring distributed inference and scalable AI systems
- Building high-performance and distributed backend systems
- Actively practicing competitive programming and systems engineering

---

## Technical Skills

| Category | Skills |
| :--- | :--- |
| **Languages** | C++, C, Python, Go, JavaScript, TypeScript, SQL |
| **Backend** | FastAPI, Node.js, Express.js, REST APIs, Microservices |
| **Frontend** | React.js, Tailwind CSS |
| **Databases** | PostgreSQL, MongoDB, Redis, Firebase |
| **Infrastructure** | Docker, Kubernetes, Linux, GitHub Actions, CI/CD |
| **Systems** | Multithreading, Concurrency, Lock-Free Data Structures, Memory Management, System Design |
| **AI / Distributed Systems** | AI Agents, Distributed Inference, FastAPI, Redis |
| **Testing & Tools** | Pytest, Postman, Git, GitHub |

---

## Experience

### Web Developer

**IEEE ICIIS 2026**

- Building the conference front-end platform using React.js.
- Working within an Agile/Scrum development workflow.
- Contributing to the implementation and refinement of production-facing
  web interfaces.

---

## Open Source

### CloudNativePG — CNCF

Active contributor to CloudNativePG, a Kubernetes operator for PostgreSQL.

- Implemented DNS customization support for PostgreSQL cluster pods and jobs,
  including `dnsPolicy` and `dnsConfig` handling.
- Worked on CRD evolution and backward compatibility.
- Developed admission webhook warnings for operator-reserved labels to
  prevent users from unintentionally overriding operator-managed resources.
- Investigated interactions across controllers, services, PVC discovery,
  and admission webhooks while developing fixes.
- Contributed documentation improvements covering PostgreSQL trust
  authentication and Windows `psql` tooling.

### HAMi-core

Working with the HAMi-core codebase as part of my open-source systems work,
with a focus on understanding GPU virtualization/infrastructure components,
codebase architecture, and low-level systems behavior.

---

## Featured Projects

### High-Frequency Trade Engine

Ultra-low-latency limit order book and matching engine built in C++20.

**Tech:** C++20 • Multithreading • Lock-Free Concurrency • Memory Management

- Designed a high-performance limit order book and matching engine.
- Achieved approximately **730 ns average matching latency** under benchmark
  workloads.
- Built a lock-free SPSC queue achieving **7.7M+ orders/sec throughput**.
- Implemented a custom slab memory allocator to eliminate approximately
  **99.9% of runtime heap-allocation jitter**.
- Used CPU thread affinity and memory-conscious data structures to minimize
  contention and latency variance.
- Stress-tested the engine with **1M+ synthetic orders**.

---

### Nexus Finance Engine

Scalable asynchronous financial backend built using a microservices
architecture.

**Tech:** FastAPI • PostgreSQL • Redis • Docker • Celery • OAuth2 • JWT • GitHub Actions

- Sustained **2,500+ requests/sec** under concurrent load testing.
- Achieved **<50 ms P99 latency** in benchmark workloads.
- Designed an ACID-compliant double-entry accounting ledger in PostgreSQL.
- Built distributed asynchronous task processing using Celery and Redis.
- Implemented authentication and authorization using OAuth2 and JWT.
- Built automated CI/CD pipelines with GitHub Actions.
- Added endpoint security hardening and automated testing.

---

### CodeSync

Real-time collaborative coding platform combining collaborative editing,
communication, and video streaming.

**Tech:** MERN • Socket.IO • WebRTC • JWT

- Built real-time state synchronization using WebSockets.
- Supported **50+ concurrent user sessions**.
- Used WebRTC peer-to-peer architecture for video communication.
- Reduced video streaming bandwidth by approximately **80%** through
  peer-to-peer communication.
- Achieved **sub-100 ms synchronization latency**.

---

### Distributed Inference Architecture

**In Progress**

Exploring distributed inference architectures for scaling AI/ML model
serving across multiple nodes.

Current areas of investigation include:

- Distributed model inference
- Request routing and workload distribution
- Concurrent request processing
- Payload optimization
- Inter-node communication
- Inference scalability and latency optimization

---

## Competitive Programming & Achievements

- **Google Big Code 2026:** Ranked in the **Top 1500 globally**.
- **Problem Solving:** Solved **400+ DSA problems** across LeetCode,
  Codeforces, and CodeChef.
- **JEE Mains:** Scored **99th percentile** among 1.4M+ candidates.
- **Smart India Hackathon:** Team Lead for a 5-member team that developed
  a full-stack agricultural e-commerce marketplace.

---

## Current Interests

```text
Systems Programming
        │
        ├── C++ / Concurrency
        ├── Low-Latency Systems
        ├── Memory Management
        └── Distributed Systems

Cloud Infrastructure
        │
        ├── Kubernetes
        ├── Containers
        ├── PostgreSQL
        └── Cloud-Native Systems

AI Infrastructure
        │
        ├── Distributed Inference
        ├── AI Agents
        ├── Model Serving
        └── Scalable AI Systems
