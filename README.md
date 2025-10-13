# 👋 Hi, I'm Adrian Cisneros

### I make AI faster, smaller, and smarter.

My passion is **AI optimization** — exploring model compression, efficient architectures, and novel training techniques. I dive deep into making intelligent systems more accessible through compression research, SSM architectures, and practical deployment strategies.

**Current Focus:** State-space models, model compression, and bridging the gap between research and production-ready AI.

---

## 🏆 Featured Project

### [Itera-Lite: SSM-based Language Model with Advanced Compression](https://github.com/CisnerosCodes/Itera-Lite)

**A state-space model achieving 2.27× compression through mixed-precision optimization**

- **Architecture:** SSM (State-Space Model) + Mixture-of-Experts
- **Best Result:** 2.27× compression (6.69 MB → 2.95 MB) with quality preservation
- **Performance:** 2,740 tokens/sec on CPU, 3,308 tokens/sec baseline
- **Research:** 7 phases completed, 19 HPC job iterations, 100+ hours of optimization work

**Key Achievements:**
- Systematic compression research across INT4 quantization (4.47×), structured pruning analysis, and mixed-precision optimization
- Discovered SSM-specific architectural constraints (pruning breaks state dependencies)
- Production-ready deployment with CPU and GPU optimization paths
- Layer-wise precision allocation: INT8 for embeddings, FP16 for SSM core, FP32 for MoE

**Tech:** PyTorch • State-Space Models • Model Compression • HPC (SLURM/NVIDIA A30) • Mixed-Precision Training

---

## 🚀 Other Projects

**[Project Noēsis](https://github.com/CisnerosCodes/noesis)** - Cognitive simulation engine exploring causal reasoning  
Stage 2 complete: Latent dynamics with VAE + structural causal models (SCMs)

**[AstroBio Explorer](https://github.com/CisnerosCodes/AstroBio-Explorer)** - AI research assistant for NASA space biology (72% eval score)  
RAG pipeline with 608 papers, Gemini 2.5 + Qdrant + SerpAPI integration

**[AI Context Manager](https://github.com/CisnerosCodes/AI-Context-Manager)** - Chrome extension for AI chat workflows  
One-click context injection across ChatGPT, Claude, Gemini, Perplexity

**[Viceroy Cybersecurity Resources](https://github.com/CisnerosCodes/VICEROY)** - 4-week security workshop series  
Developed complete training materials as Viceroy Scholar at Texas A&M ([Live Site](https://cisneroscodes.github.io/VICEROY/))

**[Itera](https://github.com/CisnerosCodes/Itera)** - Thinking loop system for iterative learning  
Framework for structured reflection and meta-learning

---

## 🔧 Tech & Research Focus

**Core Expertise:**  
Model Compression • State-Space Models • Mixed-Precision Optimization • Quantization • Knowledge Distillation

**Languages & Frameworks:**  
Python • PyTorch • JAX • CUDA • C++ (learning)

**AI/ML:**  
SSMs (Mamba, S4) • Transformers • RAG Systems • Causal Inference • LangChain • Vector Databases (Qdrant)

**Infrastructure:**  
HPC (SLURM) • Docker • Git • Linux • NVIDIA GPUs (A30, H100) • ONNX Runtime

**Secondary Interest:**  
AI + Cybersecurity (threat detection, automated security workflows)

---

## 🔬 Currently Exploring

- **Model Compression Techniques:** Progressive distillation, ultra-compression (50-100K params)
- **Efficient Architectures:** State-space models vs transformers, hybrid architectures
- **Hardware Optimization:** ONNX deployment, AVX-512, custom CUDA kernels
- **Causal Reasoning:** Differentiable causal graphs, world models, planning architectures
- **AI Security Applications:** LLMs for vulnerability assessment, automated threat analysis

---

## 📊 By the Numbers

**Itera-Lite Project:**
- 19 HPC job iterations
- 2.27× compression achieved
- 3,308 tokens/sec baseline performance
- ~15,000 lines of code
- ~10,000 lines of documentation

**Other Work:**
- 608 NASA papers processed (AstroBio)
- 72% research evaluation score
- 20+ cybersecurity tools covered (Viceroy)
- Multiple production deployments

---

## 🎓 Background

**Viceroy Cybersecurity Scholar & Intern** – Texas A&M University–San Antonio (2025)  
Developed comprehensive workshop series on network security, password attacks, and web vulnerabilities

**Research Focus:**  
Efficient AI systems, model compression, state-space architectures, causal reasoning

---

> *Making AI accessible through efficiency, one optimization at a time.*
