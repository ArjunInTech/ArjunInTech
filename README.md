### Hi, I'm Arjun B.

**Associate Software Engineer (AI/ML & Backend)** at RevDau Industries | **MCA in AI & ML** | **Open Source Contributor to Google JAX**

I build production Python microservices, distributed cloud analytics pipelines, and agentic AI systems—and I spend my free time digging into compiler internals and tracing logic in `jax-ml/jax`.

---

### Open Source Contributions — [`jax-ml/jax`](https://github.com/jax-ml/jax)

| PR | Status | Technical Summary |
| :--- | :--- | :--- |
| **[#42199](https://github.com/jax-ml/jax/pull/42199)** | **Merged** | Implemented `'sqrt'` and `'sturges'` bin estimators in `jnp.histogram_bin_edges` using static array metadata (`arr.size`) to guarantee `jax.jit` shape compatibility. |
| **[#42610](https://github.com/jax-ml/jax/pull/42610)** | **Open** | Removed artificial `core.concrete_or_error` constraints for scalar inputs in `jax.random.choice`, enabling dynamic `Tracer` bounds under `@jax.jit`. |
| **[#42731](https://github.com/jax-ml/jax/pull/42731)** | **Open** | Wired `axis_size` directly into `_batch_with_explicit_loop` in Pallas to support `vmap` on zero-argument custom kernels. |

---

### What I Build

* **Multi-Cloud Backend & Distributed Systems:** Production Python microservices, asynchronous REST APIs, and low-latency Elasticsearch Query DSL aggregations for AWS, Azure, and GCP billing and resource analytics.
* **Agentic AI & Retrieval:** 11-node cyclic LangGraph state machines, self-healing Pydantic API validation pipelines, and Hybrid RAG engines (Qdrant dense + BM25 sparse embeddings).
* **Real-Time ML Infrastructure:** Low-latency FastAPI prediction services consuming Apache Kafka streams, containerized with Docker and monitored via Prometheus and Grafana.

---

### Technical Stack

* **Languages & Core:** Python (Asyncio), SQL, JavaScript (ES6+), C++, Data Structures & Algorithms, System Design
* **AI / ML:** JAX, NumPy, LangGraph, LangChain, Hybrid RAG, Scikit-learn, XGBoost
* **Backend & Web:** FastAPI, Django REST Framework, React, Pydantic, OpenAPI/Swagger, JWT
* **Cloud, Data & DevOps:** AWS, Azure, GCP, Docker, Apache Kafka, Terraform, Elasticsearch, Qdrant, PostgreSQL, MySQL, Prometheus, Grafana, GitHub Actions

---

### Connect
* **Email:** arjun.b21012004@gmail.com
* **LinkedIn:** https://www.linkedin.com/in/arjun-b-2928a829a/
<!--
**ArjunInTech/ArjunInTech** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
