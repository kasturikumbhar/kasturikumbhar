<h1 align="center">Hi, I'm Kasturi 👋</h1>

<p align="center">
  <a href="https://github.com/kasturikumbhar">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=19&pause=1000&color=2F80ED&center=true&vCenter=true&width=650&lines=Senior+Backend+Software+Engineer;Java+%7C+Python+%7C+Spring+Boot;AWS+%7C+Distributed+Systems+%7C+Data+Processing" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/kasturi-kumbhar/">LinkedIn</a> ·
  <a href="https://github.com/kasturikumbhar">GitHub</a>
</p>

---

### About Me

Senior Backend Software Engineer with 6 years of experience at JPMorgan Chase building and modernizing enterprise backend systems, asynchronous processing platforms, and data-intensive applications. Experienced in Java, Spring Boot, AWS, SQL, distributed systems, and production performance engineering. Delivered measurable improvements in cloud compute efficiency, JVM memory consumption, API latency, and data-processing performance. Experienced in production incident resolution, technical design reviews, and cross-team platform enablement.

---

### Skills

#### Languages & Backend
- Java
- Python
- SQL
- PySpark
- Spring Boot
- Spring WebFlux
- REST APIs
- Microservices

#### AWS & Infrastructure
- ECS
- EKS
- Lambda
- SQS
- S3
- Glue
- EMR
- StepFunctions
- Route53
- Cloudwatch
- IAM
- Docker
- Terraform
- CI/CD

#### Data & Observability
- Snowflake
- Aurora
- DynamoDB
- Oracle
- Redshift
- Datadog
- Dynatrace
- Splunk
- Grafana

#### Concepts
- Event-Driven Architecture
- Distributed Systems
- Concurrency
- Idempotency
- JVM Tuning
- Query Optimization

---

### Professional Experience

#### JPMorgan Chase & Co. (Mumbai) | Aug 2020 – Present

##### Software Engineer III (Senior Associate) | Jan 2026 – Present
- Redesigned ECS capacity management around SQS queue depth, replacing memory-driven scaling that could grow to ~100 tasks and reducing peak compute capacity by ~85%.
- Extended this scaling approach to other applications with similar workload patterns.
- Re-engineered the report-generation platform to handle monthly bursts of ~750K+ requests arriving simultaneously, alongside ~65K+ PDFs generated daily, using parallel processing, independently scalable services, and disk-based processing.
- Led JVM performance optimization by eliminating duplicate objects and fixing object-retention and disk-resource cleanup issues in asynchronous processing. Reduced JVM memory consumption by >75% and eliminated recurring out-of-memory failures.
- Improved production reliability with ECS task protection, graceful shutdown, timeout and connection-pool tuning, and Datadog monitoring, metrics, and alerting.
- Served as technical point of contact, leading architecture discussions and design/code reviews, and driving adoption of shared backend capabilities across teams.

##### Software Engineer II (Associate) | Jan 2023 – Jan 2026
- Re-architected a synchronous report-generation workflow into an asynchronous, template-driven platform on open-source JasperReports, removing licensing cost and supporting language-agnostic processing of 50+ report types.
- Built a platform-independent data-access capability for clients and resolved a severe performance regression caused by multi-table joins over millions of records, reducing API response times from minutes to milliseconds through query optimization, indexing redesign, partitioning, and selective denormalization.
- Built a merchant-facing backend capability to load subscription data and trigger automated workflows based on subscription state, enabling value-added reporting across merchant accounts.
- Migrated a data-processing workflow handling 14M+ records from PySpark on AWS Glue to Snowflake, reducing end-to-end processing time from ~2.5 hours to ~55 minutes and lowering compute costs.
- Enhanced a reactive Spring WebFlux report-download service delivering large reports through S3 pre-signed URLs, improving error handling across authentication, authorization, S3 access, and downstream processing to accelerate troubleshooting.

##### Software Engineer I | Aug 2020 – Jan 2023
- Developed backend features for legacy on-premises applications using Java, Spring, and Oracle SQL, with Control-M for job scheduling, supporting high-volume transaction data processing.
- Extended new reporting capabilities to existing merchants on the legacy platform by integrating APIs with the modern platform and implementing cursor-based pagination for efficient data retrieval.
- Built an automated SIT reconciliation workflow using AWS Step Functions, Glue, Lambda, and EMR to replicate the production data flow and enable end-to-end validation without modifying the existing pipeline.

---

### Projects

#### PrepAI – Local-First AI Interview Coach (FastAPI, ChromaDB, Ollama, RAG)
- Built a local-first RAG pipeline using semantic chunking, hybrid BM25 + dense retrieval, RRF fusion, and cross-encoder reranking, achieving a 93% Hit Rate.
- Developed an interview engine with 6 LLM personas, conversational query rewriting, session persistence, and confidence-gated source citations.

#### Enterprise AI Search & Mobility Chatbot (Python, AWS, Hugging Face, Rasa)
- Built an enterprise RAG search engine using Hugging Face embeddings to index and query unstructured Confluence knowledge.
- Developed a Rasa-based mobility chatbot with intent classification during an internal hackathon.

#### AWS DeepRacer Championship (Reinforcement Learning, Python, AWS)
- Secured 2nd Runner-Up at the JPMorgan Chase Global DeepRacer Championship and competed in the AWS DeepRacer Global Finals (2021).

---

### Education

Bachelor of Engineering, Computer Science – University of Mumbai | 2016 – 2020 | 9.25 CGPI

---

### Certifications

- AWS Certified Solutions Architect
- HashiCorp Terraform Associate
- Neural Networks and Deep Learning

---

<p align="center">
  <i>Building reliable backend systems, solving complex engineering problems, and driving measurable platform improvements.</i>
</p>
