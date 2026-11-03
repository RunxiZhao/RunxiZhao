## Hi, I'm Audrey Zhao

Software Engineer at DTCC in New York, working on backend and real-time risk systems.

At DTCC I built a Python risk-limits API used by 4 internal risk services (1,500 requests/sec at 15ms p99, Redis caching with pub/sub invalidation cutting database reads by 95%), and a self-healing ServiceNow alert remediation service that auto-resolves about 30% of 500 recurring incidents per month.

Most of my professional work at DTCC is proprietary, so it isn't on GitHub. This profile highlights my side and academic work:

- **[On-Device LLM Quantization](https://github.com/RunxiZhao/on-device-llm-quantization)** — Quantized SmolLM2-135M from BF16 to Q4_K_M (W4A16) with llama.cpp and measured the tradeoff myself: 270.89 MB → 105.45 MB (2.57x smaller) for +0.61 perplexity on wikitext-2 (13.88 → 14.49), with generation speed and time-to-first-token measured on the same machine for every variant. Includes a from-scratch group-wise W4 reference implementation and a one-command benchmark harness.
- **[Text Analytics / CATME](https://github.com/RunxiZhao/catme-text-analytics)** — Led a 4-person team building an NLP system for CATME peer evaluation, adopted at 10+ universities. SVM classifier benchmarked against TensorFlow/Keras baselines. That repo is a system write-up, not a code release — the original code belongs to the project.
- **Messaging & Observability Platform** — AI-powered ticket system processing 5,000+ Discord messages/day, extracting structured commands with the Claude API and executing them against Google Tasks, with end-to-end latency under 2 seconds. Deployed on GCP Cloud Run.
- **[MLProject](https://github.com/RunxiZhao/MLProject)** — Machine learning coursework and experiments: SVM and logistic regression notebooks.

**Stack:** Python, Java, C/C++, JavaScript, SQL · FastAPI, PostgreSQL, Redis, Kafka, Docker, GCP · Claude API

NYU Tandon, BS Computer Science (Minor in Management), May 2026.

[LinkedIn](https://linkedin.com/in/audrey-zhao-nyu/)
