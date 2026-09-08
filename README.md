# Collins Nyagaka

AI and machine-learning engineer focused on reliable application boundaries, evaluation, and data systems. My public repositories are working references: they show code, tests, trade-offs, and known limitations rather than claiming live production deployments.

[LinkedIn](https://linkedin.com/in/collinsnyagaka001) · [Portfolio](https://collins-nyagaka-portfolio.vercel.app/) · [Email](mailto:cnyagakan@gmail.com)

## Selected work

### [Production AI Reference Template](https://github.com/CollinsNyatundo/production-ai-template)

FastAPI and Streamlit reference implementation for authenticated LLM application boundaries, tenant-scoped state, a bounded agent/tool loop, circuit breakers, evaluation utilities, and optional NVIDIA NIM/OpenKB adapters.

What to inspect: the request boundary in `app/main.py`, orchestration in `app/services/rag_pipeline.py`, security controls in `app/security/`, and CI/tests. The README distinguishes implemented behavior from local prototypes and missing deployment controls.

### [Customer Churn ML System](https://github.com/CollinsNyatundo/customer-churn-ml-system)

Tabular-ML workflow covering validation-based model selection, threshold tuning, experiment tracking, API serving, monitoring examples, and reproducible synthetic demo data.

What to inspect: the training/evaluation split, model tests and benchmarks, dependency isolation, and deployment examples. It is a reference implementation, not a hosted service.

### [Machine Learning Systems Reference Plugin](https://github.com/CollinsNyatundo/machine-learning-systems-plugin)

Searchable Markdown study/reference package adapted from Vijay Janapa Reddi's *Machine Learning Systems* material, with a read-only FastMCP interface.

What to inspect: attribution and provenance, the CC BY-NC-SA 4.0 licensing terms, chapter/resource indexing, and MCP containment tests. This is an adapted reference collection, not an original textbook or an MLOps execution platform.

## Current engineering interests

- Reliable agent execution and evaluation
- Retrieval and memory boundaries
- ML experimentation without train/test leakage
- API security, tenant isolation, and observability
- Reproducible local development and CI

## Working style

I prefer evidence that can be inspected: deterministic tests, explicit limitations, small reproducible examples, and architecture claims tied to code. Private work is discussed directly when relevant rather than advertised here without public proof.
