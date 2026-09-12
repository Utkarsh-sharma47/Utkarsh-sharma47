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
concurrency to cloud-native infrastructure and scalable AI systems.

---

## Experience

### Software Developer Intern

**Techneow**  
*January 2026 – July 2026*

- **Developed and enhanced backend services** during a **6-month** internship,
  focusing on performance, reliability, and maintainable software design.
- **Optimized backend operations** by identifying inefficient implementations
  and improving system-level performance and execution efficiency.
- **Engineered reliable backend components** by investigating technical issues,
  strengthening failure handling, and improving application stability.

---

### Software Engineering Intern

**CircuitEvolve**  
*August 2026 – September 2026*

- **Engineered and debugged a Cadence Virtuoso-based GUI workflow**, integrating
  simulation, schematic generation, and automated validation across **900+ tests**.
- **Automated end-to-end circuit simulation workflows**, reducing repetitive
  manual setup and validation across multiple Cadence execution paths.
- **Improved GUI reliability and regression coverage** across **4+ major workflow
  components**, resolving waveform/PSF extraction, environment, and
  process-launch failures.

---

## Open Source

### CloudNativePG — CNCF

Contributor to CloudNativePG, a Kubernetes operator for PostgreSQL.

- **Extended CloudNativePG's Kubernetes API** to support `dnsPolicy` and
  `dnsConfig`, propagating native `PodDNSConfig` across **2 workload paths:
  PostgreSQL instance Pods and operator-managed Jobs**, with CRD, API,
  deepcopy, and unit-test updates.
- **Fixed PodMonitor lifecycle reconciliation** to correctly clean up
  Pooler-owned monitoring resources when monitoring is disabled, while
  preserving safeguards for manually managed resources and adding regression
  coverage.
- **Resolved upstream integration conflicts** across generated APIs, CRDs,
  Pod/Job specifications, and reconciliation logic while maintaining passing
  CI and regression tests.

---

## Featured Projects

### Sentinel

Real-time industrial safety and emergency response platform combining
deterministic risk detection with AI-assisted decision support.

**Tech:** FastAPI • WebSockets • Next.js • RAG • Neo4j • Multi-Agent AI

- **Engineered a real-time safety platform across 20+ plant areas** using
  FastAPI, WebSockets, Next.js, and deterministic compound-risk detection.
- **Built a 5-agent AI emergency assistant** integrating RAG, Neo4j, intent
  routing, and predictive analysis for grounded operator decisions.
- **Achieved 363 req/s, 8.9 ms P95 latency, 0% errors**, with **7.9 ms P95
  telemetry-to-alert propagation** under a **20-VU** workload.

---

### High-Frequency Trade Engine

Ultra-low-latency limit order book and matching engine built in C++20.

**Tech:** C++20 • Multithreading • Lock-Free Concurrency • Memory Management

- **Achieved ~730 ns average matching latency** while stress-testing the
  matching engine with **1M+ synthetic orders**.
- **Built a lock-free SPSC queue achieving 7.7M+ orders/sec throughput**,
  eliminating lock contention from the critical data path.
- **Reduced runtime heap-allocation jitter by 99.9%** using a custom slab
  allocator combined with CPU core thread affinity.

---

### CodeSync

Real-time collaborative coding and communication platform supporting
synchronized editing and video communication.

**Tech:** MERN • Socket.IO • WebRTC • JWT

- **Supported 50+ concurrent user sessions** using WebSocket-based real-time
  state synchronization.
- **Reduced video streaming bandwidth by 80%** using WebRTC peer-to-peer
  communication.
- Achieved **sub-100 ms synchronization latency** for collaborative
  sessions.

---

### Distributed LLM Inference Architecture

**In Progress**

Distributed infrastructure for scalable LLM inference across multiple
worker nodes.

**Tech:** Python • FastAPI • Redis • PyTorch • Hugging Face • Docker

- Designing an **asynchronous inference pipeline** using FastAPI, Redis,
  and distributed workers to decouple request ingestion from model execution.
- Exploring **tensor parallelism, continuous batching, and KV-cache
  optimization** to improve GPU utilization and inference throughput.
- Building the architecture around measurable **latency, throughput,
  memory-efficiency, and horizontal scalability** benchmarks.

---

## Technical Skills

| Category | Skills |
| :--- | :--- |
| **Languages** | C++, C, Python, Go, JavaScript, TypeScript, SQL |
| **Backend** | FastAPI, Node.js, Express.js, REST APIs, Microservices |
| **Frontend** | React.js, Next.js, Tailwind CSS |
| **Databases** | PostgreSQL, MongoDB, Redis, Neo4j |
| **AI / ML** | LLMs, RAG, AI Agents, PyTorch, Hugging Face, Distributed Inference |
| **Infrastructure** | Kubernetes, Docker, Linux, GitHub Actions, CI/CD |
| **Systems** | Multithreading, Concurrency, Lock-Free Data Structures, Memory Management, System Design |
| **Tools** | Git, GitHub, Pytest, Postman, WebSockets, WebRTC, Socket.IO |

---

## Achievements

- **Google Big Code 2026:** Ranked **Top 1500 globally**.
- **Competitive Programming:** Solved **400+ DSA problems** across LeetCode,
  Codeforces, and CodeChef.
- **JEE Mains:** Scored **99th percentile** among **1.4M+ candidates**.
- **Smart India Hackathon:** Led a **5-member team** to build a full-stack
  agricultural e-commerce marketplace.

---

