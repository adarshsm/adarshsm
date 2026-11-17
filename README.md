# Adarsh S M

**Generative AI engineer building efficient multimodal and on-device systems.**

I work across models and the systems that ship them: diffusion transformers, LLM adaptation, retrieval, and inference optimization. My focus is making capable models faster, cheaper, and reliable enough to use outside the lab.

[Portfolio](https://adarshsm.vercel.app) · [LinkedIn](https://linkedin.com/in/adarshsm) · [Email](mailto:adarshsmwork@gmail.com) · Bengaluru, India

## Selected work

### AURA — multimodal generation

Core contributor to a ~30B-parameter foundation model that generates 2K video and synchronized stereo audio in a single forward pass. Reduced sampling from 50 steps to ≤8 using rectified flow and step distillation.

`PyTorch` `Diffusion Transformers` `Rectified Flow` `Step Distillation`

### [Sigil](https://sigilnative.com/) — private, on-device AI

Founder and builder of an AI-native mobile app that turns spoken agreements into signed, tamper-evident micro-contracts. Speech recognition and language-model inference run entirely on-device; the complete workflow works offline after setup.

Private source · `Flutter` `whisper.cpp` `On-device SLMs` `Ed25519` `SQLite`

### [SemantiCache](https://github.com/adarshsm/semanticache) — semantic LLM caching

A lightweight Python library that caches LLM responses by meaning rather than exact prompt matches, with local or OpenAI embeddings and in-memory or SQLite storage. On its included 60-query benchmark, it avoids 47% of API calls at threshold 0.85 with zero false positives.

[Benchmarks](https://github.com/adarshsm/semanticache/blob/main/BENCHMARKS.md) · `Python` `Sentence Transformers` `SQLite`

## Open source

**33 merged upstream pull requests across 12 projects**, focused on correctness, reliability, and regression-tested fixes. [View contribution history](https://github.com/pulls?q=is%3Apr+author%3Aadarshsm+is%3Amerged+-user%3Aadarshsm).

| Project | Merged PRs | Areas improved |
|:--|--:|:--|
| [BlockNote](https://github.com/TypeCellOS/BlockNote) | 11 | Editor behavior, clipboard handling, DOCX and email exports |
| [folium](https://github.com/python-visualization/folium) | 5 | GeoJSON and TopoJSON popups, grouped layer controls |
| [Feast](https://github.com/feast-dev/feast) | 4 | Redis event ordering, registry lookups, materialization reporting |
| [statsmodels](https://github.com/statsmodels/statsmodels) | 3 | SARIMAX, prediction validation, covariance scaling |
| [DVC](https://github.com/treeverse/dvc) | 2 | Run-cache hashing, mixed pull and checkout targets |
| [Hydra](https://github.com/hydra-ecosystem/hydra) | 2 | Dictionary overrides, user-facing error behavior |

Also merged in [k6](https://github.com/grafana/k6), [matplotlib](https://github.com/matplotlib/matplotlib), [Gymnasium](https://github.com/Farama-Foundation/Gymnasium), [Recharts](https://github.com/recharts/recharts), [astroid](https://github.com/pylint-dev/astroid), and [dulwich](https://github.com/jelmer/dulwich).

## Experience

- **AI Research Engineer / ML Engineer — Stealth AI startup** · 2026–present<br>Multimodal generation and inference optimization for AURA.
- **Founder — Sigil** · 2026–present<br>Privacy-first, on-device AI for spoken agreements.
- **ML Engineer & Generative AI Specialist — Fiverr** · 2024–present<br>LLM fine-tuning, retrieval pipelines, and computer vision for client systems.
- **Project Engineer — Centre for AI & Robotics, DRDO** · 2023–2026<br>Edge ML, real-time analytics, and threat detection for military IoT.
- **Senior System Engineer — Infosys** · 2021–2023<br>Production observability, telemetry analysis, and incident response.

## Technical toolkit

- **Generative AI:** PyTorch, diffusion transformers, rectified flow, latent consistency models, step distillation, cross-modal attention
- **Language systems:** LLM fine-tuning, RAG, FAISS, Pinecone, on-device SLMs
- **Engineering:** Python, TypeScript, Dart, C++, Flutter, React, Next.js
- **Cloud and edge:** Azure, AWS, IBM Cloud, MQTT, Raspberry Pi, Arduino, ESP32, observability

---

Open to collaboration on multimodal generation, inference optimization, on-device AI, and impactful open source. [Get in touch](mailto:adarshsmwork@gmail.com).
