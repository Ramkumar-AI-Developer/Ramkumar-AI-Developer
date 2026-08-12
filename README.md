# Ram Kumar

**AI/ML Engineer — LLM systems in production.**

I build and run LLM infrastructure for an enterprise GRC (governance, risk & compliance)
platform at Cytrusst Intelligence in Bengaluru. Most of my work is inference serving,
small-model fine-tuning, and making language models produce output that downstream
systems can actually depend on.

### What I work on

**Self-hosted inference** — vLLM serving gpt-oss-20b (MXFP4 quantized) on A100 hardware,
fronted by LiteLLM, consumed by Django services. Migrated production workloads off a
hosted API provider.

**Small-model fine-tuning** — LoRA supervised fine-tuning on domain data curated from
production logs. Lifted a core classification task from 11.8% to 88.2% held-out accuracy
on Phi-4-mini.

**CPU-only deployment** — Phi-4-mini quantized to Q4_K_M via llama.cpp, so air-gapped
customers can run inference without a GPU.

**Structured output** — guided decoding for schema-guaranteed responses, backed by
evaluation harnesses that measure whether a prompt change actually helped instead of
assuming it did.

**Retrieval** — hybrid search over OpenSearch (BM25 + kNN) with DynamoDB-backed
session state.

### Stack

`Python` · `Django` · `PyTorch` · `Transformers` · `PEFT / LoRA` · `vLLM` · `LiteLLM` ·
`llama.cpp` · `LangGraph` · `OpenSearch` · `DynamoDB` · `AWS` · `Docker`

### About the repos here

Most of my production work is closed-source. What's public below is earlier project
work — I'm adding repositories that reflect my current stack.

### Elsewhere

[LinkedIn](https://www.linkedin.com/in/ramkumar-ai) ·
[Kaggle](https://www.kaggle.com/ramkumar4240) ·
ramkumar.ai.contact@gmail.com
