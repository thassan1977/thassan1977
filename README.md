# 👋 Hi, I'm Thair Hasan

## Senior Backend Engineer | Software Architect | AI Engineer

I am a Dubai-based software engineer and architect with 15+ years of experience building reliable backend systems, distributed services, data platforms, and production APIs.

My current focus is AI engineering: building RAG systems that retrieve the right evidence, measure retrieval quality, and improve safely through automated evaluation. I bring strong backend engineering principles to AI systems, including clear interfaces, deterministic behavior, idempotency, concurrency control, observability, and performance thinking.

## 🤖 AI Engineering

I am building a practical RAG retrieval and evaluation system from the ground up.

- Implemented BM25 lexical retrieval with term frequency, document frequency, IDF, and document-length normalization.
- Implemented semantic retrieval using Sentence Transformers, document chunking, embeddings, and cosine similarity.
- Combined lexical and semantic results with Reciprocal Rank Fusion (RRF).
- Built evaluation for Recall@k, Precision@k, Reciprocal Rank@k, and NDCG@k.
- Added baseline-versus-candidate comparison with per-query improvements and regressions.
- Added regression gates for mean score drops and individual query drops.
- Handled graded relevance judgments for NDCG instead of using only binary relevance.
- Added floating-point tolerance so mathematically equal thresholds are not rejected because of precision noise.
- Designed the pipeline to be deterministic, inspectable, and easy to extend with rerankers and vector databases.

On a controlled evaluation dataset, the hybrid retriever improved:

| Metric | BM25 baseline | Hybrid result |
|---|---:|---:|
| Recall@5 | 0.5731 | 0.6848 |
| Precision@5 | 0.6600 | 0.7800 |
| Reciprocal Rank@5 | 0.9500 | 1.0000 |
| NDCG@5 | 0.7245 | 0.9086 |

The next areas I am working on are cross-encoder reranking, pgvector storage, retrieval latency measurement, real-world relevance datasets, and agentic workflows that use retrieved context to perform safe business operations.

## 💼 What I Do

- Architect microservices and high-throughput distributed systems.
- Build backend APIs with Java, Spring Boot, Kafka, RabbitMQ, and PostgreSQL.
- Design reliable workflows with idempotency, concurrency protection, retries, and transactional boundaries.
- Build data pipelines and search systems using Spark, HDFS, Hive, Elasticsearch, and vector retrieval.
- Integrate secure OAuth2 and authentication flows with Google and Facebook.
- Design CI/CD pipelines and cloud deployments using GitHub Actions, GitLab CI, Azure, AWS, Docker, and Kubernetes.
- Lead technical discussions, conduct interviews, and mentor engineers.

## 🛠️ Tech Stack

- **Languages:** Java, Python, PHP, Node.js, PL/SQL
- **Backend:** Spring Boot, Spring Security, Hibernate, Express.js
- **AI/RAG:** BM25, semantic search, Sentence Transformers, embeddings, cosine similarity, RRF, reranking, Recall, Precision, RR, NDCG
- **Databases:** PostgreSQL, pgvector, MongoDB, Oracle, Redis
- **Messaging:** Apache Kafka, RabbitMQ
- **Data:** Spark, HDFS, Hive, Elasticsearch, ETL pipelines
- **DevOps:** Docker, Kubernetes, Helm, GitHub Actions, GitLab CI
- **Cloud:** Azure, AWS, ECR, EC2
- **Observability:** ELK Stack, Prometheus, structured logging, tracing

## 📈 Career Highlights

- Led development of real-time CDR processing systems for telecom-grade Huawei and Ericsson environments.
- Built custom SFTP connectors for Kafka Connect supporting XML, ASN.1, JSON, and other data formats.
- Migrated Firebase-backed functionality to PostgreSQL and implemented secure payment flows with Checkout.com.
- Designed scalable backend services with attention to throughput, failure handling, data consistency, and operational visibility.
- Conducted technical interviews and mentored cross-functional teams to improve engineering quality.
- Built this RAG learning project to demonstrate practical AI engineering rather than only model usage.

## 🎓 Education & Certifications

- **MSc in Information and Decision Support Systems** — HIAST, Syria
- Google Foundations: Data Everywhere
- IBM Tools for Data Science
- Data Science Orientation — Coursera
- Building Cloud Services with Java Spring — Coursera

## 🌐 Languages

- English — Fluent
- Arabic — Native

## 📫 Contact Me

- 📍 Dubai, UAE
- 📧 [thairhassan.eng@gmail.com](mailto:thairhassan.eng@gmail.com)
- 📧 [thairhasanuae@gmail.com](mailto:thairhasanuae@gmail.com)
- 📱 +971 58 508 5116

Thanks for visiting my profile.
