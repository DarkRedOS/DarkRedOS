<h1 align="center">Hi, I'm Om Shegokar 👋</h1>
<h3 align="center">ML Engineer @ Juspay — LLM Infra, Evaluation & Payments</h3>

<p align="center">
  I build the systems that let teams trust their AI: eval pipelines, inference infra, and agentic dev tools — <br/>
  alongside production payment orchestration for 125+ D2C brands.
</p>

<p align="center">
  <a href="https://linkedin.com/in/omshegokar/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat-square&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:omshegokar1513@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-D14836?style=flat-square&logo=gmail&logoColor=white" /></a>
  <a href="https://drive.google.com/file/d/1ueGL0jFV2S_8OahVMnfZK9aCoTTYhIWr/view?usp=sharing"><img src="https://img.shields.io/badge/Resume-View_PDF-4285F4?style=flat-square&logo=googledrive&logoColor=white" /></a>
</p>

---

## What I'm working on

At **Juspay**, I sit on the **Xyne Team**, building the AI/ML infra layer for the company:

- **LLM Evaluation Platform** — a GCP Batch pipeline (job queue in Postgres, Dockerized workers, spot-preemption-resilient) feeding a 4-service eval dashboard (frontend / backend / DB / eval runner) with live log streaming across SWE-Bench, Tau2-Bench, Polyglot, and more.
- **Model Leaderboards** — TPS/latency leaderboards on models like GLM-5, Minimax M2.5, and Kimi K2.5 that directly drive production model-selection calls.
- **Xyne-CLI & Xyne Code** — a TUI coding agent (Xyne-CLI, opencode-style) and a VS Code copilot-style extension (Xyne Code) built on top of it, both serving models via vLLM on rented GPUs (H200 / B300) through OpenAI-compatible endpoints. I built the `/commands` layer wired into the CLI engine.
- **LATAM Fintech News Agent** — pulls context from internal Juspay repos to surface relevant LATAM fintech news automatically.

Before this, I spent ~1.5 years as a **Product Solution Engineer** owning checkout integrations for 125+ D2C merchants — the impact numbers below are from that work.

---

## Impact so far

| Metric | What it means |
|---|---|
| **125+** brands | Checkout integrations across Shopify, Magento & WooCommerce |
| **10%** conversion lift | vs. native Shopify checkout, via A/B tested routing |
| **95%** payment success rate | Sustained through dynamic multi-gateway routing |
| **35%** faster MTTR | Kibana + automated API-level debugging |

---

## Stack

**LLM Inference & Serving**
`vLLM` `SGLang` — plus working knowledge of flash attention, paged attention, continuous batching, and KV cache internals. Hands-on hosting models on rented **H200 / B300** GPUs.

**Languages & Data**
`Python` `Java` `Bash` `SQL (Postgres/MySQL)` `Shopify Liquid`

**ML / AI**
`PyTorch` `TensorFlow Lite` `Hugging Face` `Pandas` — model quantization, fine-tuning, agentic benchmarking

**Infra & Cloud**
`GCP (Compute, Batch)` `Docker` `Kubernetes (k9s)` `tmux` + SSH for parallel eval orchestration across VM/CPU fleets

---

## Featured projects

**🔍 LLM Evaluation & Benchmarking Pipeline** — *Xyne Team*
Production eval infra spanning a GCP Batch job pipeline, a 4-microservice dashboard, and TPS/latency leaderboards used for real model-selection decisions. Also built tmux + SSH tooling to fan out evals across multiple machines in parallel.

**🤖 Xyne-CLI + Xyne Code** — *Xyne Team*
Coding-agent tooling: a terminal agent (Xyne-CLI) and a VS Code extension (Xyne Code) on top of it, serving vLLM-hosted models on rented GPUs. Built the `/commands` interface wired into the CLI engine.

**🛍️ Breeze Checkout & Breeze Automatic** — *Juspay*
Payment orchestration for 125+ D2C brands, plus an LLM tool-calling layer (Breeze Automatic) letting merchants configure checkout in natural language.

**✋ Sign Signify** — *Personal project*
Android app translating sign language in real time via CNN (palm detection) + RNN (gesture recognition), with model quantization for edge inference.

**📱 Manas App** — *Personal project*
Offline-first Android mental wellness app with custom conflict-resolution sync logic. 1K+ Play Store downloads.

---

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=darkredos&label=Profile%20views&color=0e75b6&style=flat" alt="Profile views" />
</p>
