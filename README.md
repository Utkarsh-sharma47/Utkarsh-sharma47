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

## Technical Skills

| Category | Skills |
| :--- | :--- |
| **Languages** | C++, C, Python, Go, JavaScript, TypeScript, SQL |
| **Backend** | FastAPI, Node.js, Express.js, REST APIs, Microservices |
| **Frontend** | React.js, Tailwind CSS |
| **Databases** | PostgreSQL, MongoDB, Redis, Firebase |
| **Infrastructure** | Docker, Kubernetes, Linux, GitHub Actions, CI/CD |
| **Systems** | Multithreading, Concurrency, Lock-Free Data Structures, Memory Management, System Design |
| **AI / Distributed Systems** | PyTorch, Hugging Face, Distributed Inference, AI Agents, FastAPI, Redis |
| **Testing & Tools** | Pytest, Postman, Git, GitHub |

---

## Experience

### Software Developer Intern

**Forematic Techneow Solution Pvt. Ltd. — Techneow**  
*January 2026 – July 2026*

- Developed and improved backend services with a focus on performance,
  reliability, and maintainability.
- Worked on engineering tasks involving efficient backend software design
  and implementation.
- Analyzed complex technical requirements and contributed to production
  software development.
- Worked independently and collaboratively within an engineering team.

---

### Software Engineering Intern

**circuitEvolve**  
*August 2026 – September 2026*

- Contributing to software engineering and research-oriented development
  within the circuitEvolve platform.
- Working on software implementation, debugging, testing, and engineering
  workflows across the development stack.
- Applying Python-based development and systems-oriented problem solving
  to engineering tasks.

> Internship work is subject to confidentiality and is not publicly
> described beyond the scope permitted by the company.

---

### Web Developer

**IEEE ICIIS 2026**

- Building the conference front-end platform using React.js.
- Working within an Agile/Scrum development workflow.
- Contributing to production-facing web interfaces and application
  development.

---

## Featured Projects

### High-Frequency Trade Engine

Ultra-low-latency limit order book and matching engine built in C++20.

**Tech:** C++20 • Multithreading • Lock-Free Concurrency • Memory Management

- Designed a high-performance limit order book and matching engine.
- Achieved approximately **730 ns average matching latency** under
  benchmark workloads.
- Built a lock-free SPSC queue achieving **7.7M+ orders/sec throughput**.
- Implemented a custom slab memory allocator to eliminate approximately
  **99.9% of runtime heap-allocation jitter**.
- Used CPU thread affinity and memory-conscious data structures to minimize
  contention and latency variance.
- Stress-tested the engine with **1M+ synthetic orders**.

---

### Sentinel

AI-assisted document verification and decision pipeline designed around
deterministic validation, safety constraints, and auditable processing.

**Tech:** Python • FastAPI • PostgreSQL • React • LLMs • SQLAlchemy

- Designed a staged processing pipeline separating **extraction,
  validation, routing, and querying** rather than relying on a single
  end-to-end LLM decision.
- Combined LLM-assisted extraction with deterministic validation rules
  to improve reliability and auditability.
- Implemented safety gates for uncertain results, missing evidence, and
  validation mismatches before automated decisions.
- Designed an allow-listed intent classification layer with parameterized
  database access to prevent user-controlled text from reaching SQL
  queries directly.
- Built persistent validation records using PostgreSQL and JSONB-based
  result storage.
- Designed the system around **fail-closed decision boundaries** to reduce
  the risk of unsafe automatic approvals.

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

### Distributed LLM Inference & Orchestration Engine

**In Progress**

Distributed backend infrastructure for asynchronous, scalable LLM
inference across multiple worker nodes.

**Tech:** Python • FastAPI • Redis • Celery/Ray • PostgreSQL • PyTorch •
Hugging Face • NCCL • Docker

- Designing an asynchronous inference architecture where API requests are
  ingested into a high-speed queue instead of blocking the web server.
- Using **FastAPI + Redis + background workers** to separate request
  ingestion from inference execution.
- Exploring **tensor parallelism** to shard model weights across multiple
  processes/GPUs.
- Investigating GPU memory optimization through block-based KV-cache
  management inspired by PagedAttention.
- Exploring **continuous batching** to improve GPU utilization and
  inference throughput.
- Designing the system as a distributed inference benchmark platform with
  emphasis on throughput, latency, memory efficiency, and scalability.

---

## Open Source

### CloudNativePG — CNCF

Contributor to CloudNativePG, a Kubernetes operator for PostgreSQL.

- Implemented DNS customization support for PostgreSQL cluster pods and
  jobs, including `dnsPolicy` and `dnsConfig` handling.
- Worked on CRD evolution and backward compatibility.
- Developed admission webhook warnings for operator-reserved labels.
- Investigated controller, service, PVC discovery, and webhook behavior
  while developing fixes.
- Contributed documentation improvements covering PostgreSQL trust
  authentication and Windows `psql` tooling.

---

## Competitive Programming & Achievements

- **Google Big Code 2026:** Ranked in the **Top 1500 globally**.
- **Problem Solving:** Solved **400+ DSA problems** across LeetCode,
  Codeforces, and CodeChef.
- **JEE Mains:** Scored **99th percentile** among 1.4M+ candidates.
- **Smart India Hackathon:** Team Lead for a 5-member team that developed
  a full-stack agricultural e-commerce marketplace.

---

## GitHub Analytics

<div align="center">
  <img
    src="https://github-readme-activity-graph.vercel.app/graph?username=Utkarsh-sharma47&theme=github-dark&hide_border=true&area=true&bg_color=0D1117"
    width="100%"
    alt="GitHub Activity Graph"
  />
</div>
