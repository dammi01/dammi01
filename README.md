# Michael Dambock | Data Engineer & Systems Architect

**The Problem**: 
  Data tools are often treated as isolated silos, leading to "Frankenstein" architectures that are expensive and fragile.

**The Solution**: 
  I design integrated **Data Engines**. I don't just pick tools; I select the right components that fit the specific business need to ensure the entire system is lean, reliable, and **Decision-Ready**.

---

### ⚙️ The Data Engineering Engine
A tool is only as good as the architecture it sits in. I focus on the fundamental engineering pillars that keep the engine running at peak performance:

* **Architectural Fit**: I select tools (whether it’s **DuckDB** for local processing or **BigQuery** for massive scale) based on their ability to reduce latency and overhead. 
* **Modular Ingestion & Transformation**: By following a strict folder hierarchy (Ingestion → Transform → Orchestration), I ensure that any part of the system can be upgraded without breaking the whole.
* **Built-in Resilience**: I implement **Idempotency** as a standard. The engine is designed to handle interruptions and retries automatically, ensuring data integrity without manual intervention.
* **Economic Efficiency**: Every architectural decision is filtered through a cost-benefit lens. I prioritize high-performance, low-cost processing logic to maximize the ROI of the data stack.

---

### 🛠️ The Component Gallery
I treat these technologies as precision parts within a larger data product.

| System Layer | Primary Components |
| :--- | :--- |
| **Control Plane** | Kestra, Airflow, GitHub Actions |
| **Processing Core** | Databricks (Spark), dbt, Python (Polars, DuckDB), SQL |
| **Storage & Warehouse** | Databricks (Lakehouse/Delat Lake), Snowflake, BigQuery, PostgreSQL, GCP |
| **Infrastructure** | Docker, Terraform, CI/CD Pipelines |
| **The Interface** | Looker Studio, Streamlit (Designed for 30-second decisions) |

---

### 📈 Proven Data Products
*Each repository showcases a complete "Engine" from raw source to final insight.*

1.  **Zoomcamp Capstone**: A production-grade pipeline demonstrating automated orchestration and modular dbt modeling.
2.  **LH Nautical Challenge**: A transformation engine that turns unorganized maritime data into a high-value business asset.
3.  **GenAI Solutions**: Integrating LLMs as "intelligent components" to automate metadata and cleaning tasks.

---

### 🤝 Let's Build Something Scalable
[LinkedIn](https://www.linkedin.com/in/michael-dambock) | [Portfolio Website](https://dammi01.github.io/Homepage/)

---
