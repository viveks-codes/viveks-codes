<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1a3a5c,100:2563eb&height=200&section=header&text=Vivek%20Patel&fontSize=60&fontColor=ffffff&fontAlignY=38&desc=Generative%20AI%20Engineer%20%7C%20NLP%20Researcher%20%7C%20PyTorch%20Contributor&descAlignY=58&descSize=16&descColor=93c5fd" />

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vivek-patel-0553731a5/)
[![HuggingFace](https://img.shields.io/badge/🤗%20HuggingFace-FFD21E?style=for-the-badge&logoColor=black)](https://huggingface.co/Vivekdas)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://bento.me/vivek-patel)
[![Dev.to](https://img.shields.io/badge/Dev.to-0A0A0A?style=for-the-badge&logo=devdotto&logoColor=white)](https://dev.to/vivekcodes)
[![PyPI](https://img.shields.io/badge/PyPI-3775A9?style=for-the-badge&logo=pypi&logoColor=white)](https://pypi.org/project/honeypotllm/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vivek.patel@tihiitb.org)

![Profile Views](https://komarev.com/ghpvc/?username=viveks-codes&label=Profile%20Views&color=2563eb&style=flat-square)
![GitHub followers](https://img.shields.io/github/followers/viveks-codes?style=flat-square&color=2563eb)

</div>

---

## 🧠 About Me

I'm a **Generative AI Engineer** with **2.6+ years** building production LLM systems — from continued pre-training on 125 GB corpora to vLLM-based serving and inference benchmarking. Currently a **Senior GenAI & NLP Engineer** at [BharatGen](https://bharatgen.india.gov.in) (IIT Bombay × IIM Indore), India's Sovereign AI Initiative, where I lead the training of **AyurParam 2**, a 17B Mixture-of-Experts model running on a 6-node, 48-GPU NVIDIA A6000 cluster.

I've contributed code to Meta's **[pytorch/examples](https://github.com/pytorch/examples)** (22k ⭐), co-authored **3 arXiv papers** evaluating 20+ frontier models across Indic languages, and published **[honeypotllm](https://pypi.org/project/honeypotllm/)** — an open-source LLM security SDK — on PyPI.

```python
vivek = {
    "role"       : "Senior GenAI & NLP Engineer @ BharatGen (IIT Bombay × IIM Indore)",
    "research"   : ["IndicParam", "ParamBench", "SectEval"],  # 3 arXiv papers
    "training"   : "AyurParam 2 — 17B MoE on 48× NVIDIA A6000",
    "open_source": ["honeypotllm (PyPI)", "pytorch/examples (Meta AI)"],
    "location"   : "Mumbai / Bengaluru / Remote",
    "languages"  : ["Python", "Hindi", "Gujarati", "English"],
}
```

---

## 🔬 arXiv Research

> Co-authored 3 papers at BharatGen benchmarking frontier models on Indic languages and AI safety.

| Paper | Description | Link |
|-------|-------------|------|
| **IndicParam** | LLM benchmark for 11 low-resource Indic languages — 13k+ MCQs, 20 models evaluated (GPT-5, Gemini 2.5, DeepSeek) | [![arXiv](https://img.shields.io/badge/arXiv-2512.00333-b31b1b?style=flat-square)](https://arxiv.org/abs/2512.00333) [![HF](https://img.shields.io/badge/🤗-Dataset-FFD21E?style=flat-square)](https://huggingface.co/datasets/bharatgenai/IndicParam) |
| **ParamBench** | Graduate-level Hindi benchmark — 17k questions across 21 culturally grounded Indian subjects | [![arXiv](https://img.shields.io/badge/arXiv-2508.16185-b31b1b?style=flat-square)](https://arxiv.org/abs/2508.16185) [![HF](https://img.shields.io/badge/🤗-Dataset-FFD21E?style=flat-square)](https://huggingface.co/datasets/bharatgenai/ParamBench) |
| **SectEval** | First study on latent sectarian bias in LLMs — 88 bilingual questions, 15 models including GPT-4o and Claude 3.5 | [![arXiv](https://img.shields.io/badge/arXiv-2603.12768-b31b1b?style=flat-square)](https://arxiv.org/abs/2603.12768) |

---

## 🚀 Highlight Projects

### 🤗 [VaidhLlama — Deployed Ayurvedic LLM (3B)](https://huggingface.co/Vivekdas/VaidhLLaMA-3.2-3B-Instruct)
Fine-tuned LLaMA-3.2-3B on 130k curated Ayurvedic QA pairs using QLoRA + Unsloth. Achieved **41.91% on BhashaBench-Ayur** (+1.17% over base). Deployed via **vLLM** with full TTFT and throughput benchmarking.

### 🔐 [honeypotllm](https://pypi.org/project/honeypotllm/) — `pip install honeypotllm`
Open-source Python SDK that defends LLM APIs from model extraction and data theft by embedding forensic watermarks — making stolen training data the verifiable evidence of an attack.

### 🧬 [Param2-Clinical-17B-MoE](https://github.com/viveks-codes/Param2-Clinical-17B-MoE) — CPT Training Stack
Custom multi-GPU CPT pipeline for a **17B MoE model** trained on a **125 GB Ayurvedic and clinical corpus**. Full stack: DeepSpeed ZeRO-2, Flash Attention 2, NUMA-tuned torchrun launch scripts, and a fault-tolerant distributed checkpoint manager.

### 🗣️ Ayurvedic Domain Tokenizer
Domain-specific BPE tokenizer trained on 125 GB of Sanskrit and clinical text. Achieves **40%+ fertility improvement** over LLaMA-3 tokenizer on Ayurvedic terminology, reducing inference cost and improving model comprehension of classical medical terms.

### 👁️ Multimodal Government Document Extraction
End-to-end VLM pipeline using **Qwen-VL** to extract structured records (name, religion, address, voter ID) from scanned government PDFs. LLM post-correction layer resolves OCR errors and name normalisation at scale.

### ⚡ [PyTorch Forward-Forward Algorithm](https://github.com/pytorch/examples) — Merged to `pytorch/examples`
Implemented Hinton's Forward-Forward Algorithm in Meta AI's official **pytorch/examples** repository (22k ⭐). Collaborated directly with **Soumith Chintala** (PyTorch founder) on GPU optimisation and test coverage.

---

## 🛠️ Tech Stack

### LLM Training & Alignment
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/🤗%20Transformers-FFD21E?style=flat-square)
![DeepSpeed](https://img.shields.io/badge/DeepSpeed-00ADD8?style=flat-square)
![LoRA](https://img.shields.io/badge/LoRA%20%2F%20QLoRA-8B5CF6?style=flat-square)
![Unsloth](https://img.shields.io/badge/Unsloth-F97316?style=flat-square)
![Axolotl](https://img.shields.io/badge/Axolotl-10B981?style=flat-square)
![LLaMA-Factory](https://img.shields.io/badge/LLaMA--Factory-6366F1?style=flat-square)
![NVIDIA NeMo](https://img.shields.io/badge/NVIDIA%20NeMo-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Flash Attention](https://img.shields.io/badge/Flash%20Attention%202-EC4899?style=flat-square)

**Training paradigms:** CPT · SFT · Instruction Tuning · RLHF · DPO / ORPO · MoE Architecture

### Inference & Serving
![vLLM](https://img.shields.io/badge/vLLM-1D4ED8?style=flat-square)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![FAISS](https://img.shields.io/badge/FAISS-0052CC?style=flat-square)

**Techniques:** Speculative Decoding · Quantization (GPTQ / AWQ / BnB) · TTFT & Throughput Benchmarking · RAG · Knowledge Graphs

### Multimodal
![Qwen-VL](https://img.shields.io/badge/Qwen--VL-7C3AED?style=flat-square)
**Vision Language Models · Document Understanding · OCR · Structured Extraction**

### MLOps & Infrastructure
![Slurm](https://img.shields.io/badge/Slurm-003366?style=flat-square)
![NVIDIA](https://img.shields.io/badge/NVIDIA%20A6000%20%2F%20H100-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Weights & Biases](https://img.shields.io/badge/W%26B-FFBE00?style=flat-square&logo=weightsandbiases&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)

**DeepSpeed ZeRO-2/3 · torchrun · NUMA Topology Tuning · CI/CD · DVC**

---

## 📊 GitHub Stats

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=viveks-codes&show_icons=true&count_private=true&include_all_commits=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=2563eb&icon_color=2563eb&text_color=c9d1d9" />
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=viveks-codes&exclude_repo=KNN-Image-Classification&show_icons=true&hide_border=true&layout=compact&langs_count=8&theme=github_dark&bg_color=0d1117&title_color=2563eb&text_color=c9d1d9" />

<img height="180em" src="https://github-readme-streak-stats.herokuapp.com/?user=viveks-codes&hide_border=true&theme=github-dark-blue&background=0d1117&ring=2563eb&fire=2563eb&currStreakLabel=2563eb" />

</div>

---

## ✍️ Technical Writing

- **[Under the Hood: VaidhLlama Architecture & Training Pipeline](https://dev.to/vivek_patel_022db0e176cf2/under-the-hood-vaidhllama-architecture-training-pipeline-1ho1)** — Deep dive into fine-tuning a 3B Ayurvedic LLM
- **[From a Dumb Student to a PyTorch Contributor](https://dev.to/vivekcodes/from-a-dumb-student-to-a-pytorch-contributor-the-impact-of-teachers-on-my-life-4me4)** — How great teachers changed my trajectory
- Python & Data Science tutorials on [dev.to/vivekcodes](https://dev.to/vivekcodes)

---

## 🌐 Experience Timeline

```
2021 ─── B.Tech AI & Data Science, Uka Tarsadia University (First Class with Distinction)
2023 ─── Research Intern @ Goa Institute of Management (Big Data Analytics)
2023 ─── PyTorch Contributor — pytorch/examples merged (Meta AI, 22k ⭐)
2023 ─── Backend Intern @ Axelor, Surat
2024 ─── SDE-I NLP & ML @ NowFloats by Reliance Industries, Hyderabad (130k+ daily users)
2025 ─── Senior GenAI & NLP Engineer @ BharatGen (IIT Bombay × IIM Indore)
         ↳ AyurParam 2: 17B MoE CPT on 48-GPU A6000 cluster
         ↳ 3 arXiv papers: IndicParam · ParamBench · SectEval
         ↳ honeypotllm on PyPI
         ↳ 8 years on GitHub and still shipping 🚀
```

---

<div align="center">

**Building the future of Indic AI — one token at a time.**

*Open to collaborations on Indic NLP, LLM safety, and domain-specific foundation models.*

[![LinkedIn](https://img.shields.io/badge/Let's%20Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/vivek-patel-0553731a5/)
[![Email](https://img.shields.io/badge/Drop%20a%20Mail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:vivek.patel@tihiitb.org)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2563eb,100:0d1117&height=100&section=footer" />

</div>
