<!-- ==============================================================
     NEURAL INTERFACE v5.0 - SAAD SALMAN
     llm systems / slm optimization / local inference
     ============================================================== -->

<div align="center">

<img src="assets/hero.svg" width="100%" alt="Saad Salman - Machine Learning and Deep Learning Systems Engineer"/>

<img src="assets/boot.svg" width="740" alt="system boot sequence"/>

<img src="assets/divider.svg" width="70%" alt=""/>

</div>

I build **language-model systems that run where the users are** - from frontier LLMs
reasoning over private data to quantized SLMs running silently on a laptop. The design
principle never changes: **keep intelligence local, and spend cloud tokens only when
they earn their price.**

## 01 // DOMAINS

| DOMAIN | FOCUS |
| :--- | :--- |
| **LLM SYSTEMS** | Agentic pipelines / RAG at scale / fine-tuning (LoRA, QLoRA, DPO) / evaluation harnesses / open-weight deployment |
| **SLM + EDGE** | Quantization (GGUF, AWQ, GPTQ) / knowledge distillation / pruning / 1B-8B models on consumer and mobile silicon |
| **LOCAL INFERENCE** | Ollama / llama.cpp / vLLM / ONNX Runtime / TensorRT - on-prem, on-device, air-gapped |
| **TOKEN ECONOMY** | SLM-first routing with LLM escalation / semantic caching / context compression / 90%+ cost reduction |
| **PRODUCTION AI** | FastAPI services / Docker + Kubernetes / model CI/CD / observability / autoscaling inference |
| **OPEN SOURCE** | Building in public / reproducible artifacts / permissive licensing / upstream-first mindset |

## 02 // ARCHITECTURE

<div align="center">

<img src="assets/mesh.svg" width="100%" alt="local-first inference mesh"/>

</div>

**The mesh in one line:** every request enters through one smart router - a local SLM
fleet answers the majority, and the frontier model is billed only as the exception.

- **Route small, escalate smart** - local SLMs absorb the bulk of traffic; the cloud LLM is a fallback, not a default
- **Quantize ruthlessly** - 4-bit checkpoints keep near-full quality at a fraction of the memory footprint
- **Cache semantically** - identical intents are answered once, then served forever
- **Meter every token** - cost becomes a first-class metric, measured on every hop

## 03 // STACK

**`NEURAL CORE`**

<img src="https://img.shields.io/badge/PYTHON-0A0E16?style=flat-square&logo=python&logoColor=00E5FF" alt="python"/>
<img src="https://img.shields.io/badge/PYTORCH-0A0E16?style=flat-square&logo=pytorch&logoColor=00E5FF" alt="pytorch"/>
<img src="https://img.shields.io/badge/TENSORFLOW-0A0E16?style=flat-square&logo=tensorflow&logoColor=00E5FF" alt="tensorflow"/>
<img src="https://img.shields.io/badge/HUGGING%20FACE-0A0E16?style=flat-square&logo=huggingface&logoColor=00E5FF" alt="huggingface"/>
<img src="https://img.shields.io/badge/CUDA-0A0E16?style=flat-square&logo=nvidia&logoColor=00E5FF" alt="cuda"/>
<img src="https://img.shields.io/badge/NUMPY-0A0E16?style=flat-square&logo=numpy&logoColor=00E5FF" alt="numpy"/>

**`INFERENCE ENGINE ROOM`**

<img src="https://img.shields.io/badge/OLLAMA-0A0E16?style=flat-square&logo=ollama&logoColor=3DFFA2" alt="ollama"/>
<img src="https://img.shields.io/badge/LLAMA.CPP-0A0E16?style=flat-square&logo=cplusplus&logoColor=3DFFA2" alt="llama.cpp"/>
<img src="https://img.shields.io/badge/VLLM-0A0E16?style=flat-square" alt="vllm"/>
<img src="https://img.shields.io/badge/GGUF%204--BIT-0A0E16?style=flat-square" alt="gguf"/>
<img src="https://img.shields.io/badge/ONNX-0A0E16?style=flat-square&logo=onnx&logoColor=3DFFA2" alt="onnx"/>
<img src="https://img.shields.io/badge/TENSORRT-0A0E16?style=flat-square&logo=nvidia&logoColor=3DFFA2" alt="tensorrt"/>

**`AGENT ORCHESTRATION`**

<img src="https://img.shields.io/badge/LANGCHAIN-0A0E16?style=flat-square&logo=langchain&logoColor=8A7CFF" alt="langchain"/>
<img src="https://img.shields.io/badge/LANGGRAPH-0A0E16?style=flat-square" alt="langgraph"/>
<img src="https://img.shields.io/badge/LLAMAINDEX-0A0E16?style=flat-square&logo=llamaindex&logoColor=8A7CFF" alt="llamaindex"/>
<img src="https://img.shields.io/badge/TRANSFORMERS-0A0E16?style=flat-square&logo=huggingface&logoColor=8A7CFF" alt="transformers"/>

**`SHIP IT DECK`**

<img src="https://img.shields.io/badge/DOCKER-0A0E16?style=flat-square&logo=docker&logoColor=E6F1FF" alt="docker"/>
<img src="https://img.shields.io/badge/KUBERNETES-0A0E16?style=flat-square&logo=kubernetes&logoColor=E6F1FF" alt="kubernetes"/>
<img src="https://img.shields.io/badge/FASTAPI-0A0E16?style=flat-square&logo=fastapi&logoColor=E6F1FF" alt="fastapi"/>
<img src="https://img.shields.io/badge/RUST-0A0E16?style=flat-square&logo=rust&logoColor=E6F1FF" alt="rust"/>
<img src="https://img.shields.io/badge/TYPESCRIPT-0A0E16?style=flat-square&logo=typescript&logoColor=E6F1FF" alt="typescript"/>
<img src="https://img.shields.io/badge/GIT-0A0E16?style=flat-square&logo=git&logoColor=E6F1FF" alt="git"/>
<img src="https://img.shields.io/badge/GITHUB%20ACTIONS-0A0E16?style=flat-square&logo=githubactions&logoColor=E6F1FF" alt="github actions"/>

## 04 // TELEMETRY

<div align="center">

<img height="160em" src="https://github-readme-stats.vercel.app/api?username=saadxsalman&show_icons=true&hide_border=true&bg_color=05070B&title_color=00E5FF&icon_color=8A7CFF&text_color=E6F1FF" alt="github stats"/>
<img height="160em" src="https://streak-stats.demolab.com?user=saadxsalman&hide_border=true&background=05070B&ring=00E5FF&fire=8A7CFF&currStreakNum=E6F1FF&sideNums=E6F1FF&currStreakLabel=00E5FF&sideLabels=7D8CA3&dates=5A6B85" alt="streak stats"/>

<img height="145em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=saadxsalman&layout=compact&hide_border=true&bg_color=05070B&title_color=00E5FF&text_color=E6F1FF&langs_count=8" alt="top languages"/>

</div>

## 05 // OPEN SOURCE

> Good infrastructure outlives its authors. Every inference config, quantization
> recipe and evaluation harness I build gets upstreamed - in public, under
> permissive licenses, with the docs that make it reusable.

<div align="center">

<img src="https://img.shields.io/badge/PRS%20WELCOME-0A0E16?style=flat-square&logo=github&logoColor=3DFFA2" alt="prs welcome"/>
<img src="https://img.shields.io/badge/OPEN%20SOURCE%20FOREVER-0A0E16?style=flat-square&logo=github&logoColor=00E5FF" alt="open source"/>
<img src="https://img.shields.io/badge/MIT%20%2F%20APACHE--2.0-0A0E16?style=flat-square&logo=github&logoColor=8A7CFF" alt="license"/>

<!-- contribution snake - generated by .github/workflows/snake.yml into the output branch -->
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/SaadxSalman/saadxsalman/output/github-contribution-grid-snake-dark.svg"/>
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/SaadxSalman/saadxsalman/output/github-contribution-grid-snake.svg"/>
  <img alt="contribution snake" src="https://raw.githubusercontent.com/SaadxSalman/saadxsalman/output/github-contribution-grid-snake.svg" width="100%"/>
</picture>

</div>

---

<!-- SIGNALS - uncomment and fill in your handles to activate
<div align="center">

<a href="https://linkedin.com/in/YOUR-HANDLE"><img src="https://img.shields.io/badge/LINKEDIN-0A0E16?style=flat-square&logo=linkedin&logoColor=00E5FF" alt="linkedin"/></a>
<a href="https://x.com/YOUR-HANDLE"><img src="https://img.shields.io/badge/X-0A0E16?style=flat-square&logo=x&logoColor=E6F1FF" alt="x"/></a>
<a href="https://huggingface.co/YOUR-HANDLE"><img src="https://img.shields.io/badge/HUGGING%20FACE-0A0E16?style=flat-square&logo=huggingface&logoColor=FFD21E" alt="huggingface"/>
<a href="mailto:you@example.com"><img src="https://img.shields.io/badge/EMAIL-0A0E16?style=flat-square&logo=gmail&logoColor=3DFFA2" alt="email"/></a>

</div>
-->

<div align="center">

<img src="assets/divider.svg" width="45%" alt=""/>

<img src="https://komarev.com/ghpvc/?username=saadxsalman&style=flat-square&label=VISITORS&color=00E5FF" alt="visitors"/>

<br/>

<sub>LOCAL-FIRST INTELLIGENCE - SHIPPED IN THE OPEN</sub>

</div>
