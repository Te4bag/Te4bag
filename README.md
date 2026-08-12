<h1 align="center">Chandrav Rajbangshi</h1>

<p align="center">
  <a href="https://github.com/Te4bag">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3500&pause=1000&color=6E56CF&center=true&vCenter=true&width=520&lines=LLMs+won't+take+over+the+world.+Don't+worry.;I+just+want+to+know+what's+happening+inside." alt="tagline">
  </a>
</p>

<p align="center">
  <a href="https://scholar.google.com/citations?user=pTThCZoAAAAJ&hl=en"><img src="https://img.shields.io/badge/Google%20Scholar-4285F4?style=for-the-badge&logo=googlescholar&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/chandrav-rajbangshi"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="mailto:chandravraj05@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <a href="https://arxiv.org/abs/2601.00231"><img src="https://img.shields.io/badge/arXiv-B31B1B?style=for-the-badge&logo=arxiv&logoColor=white"></a>
</p>

---

### `Whoami`

CS undergrad at **BIT Mesra** (2027). @**Lossfunk**, @**RAAPID Inc.**

I work on interpretability and explainability of language models — and on the unglamorous business of checking whether a result is real.

---

### The things I'll argue about

- **Chain-of-thought is an object of study, not a prompting trick.**<br>
  Whether the stated reasoning is the reasoning that happened is an empirical question.
- **An explanation you can't break isn't an explanation.**<br>
  If an interpretability claim survives no intervention, it's a story. Causal tests over correlational ones, always.
- **Mechanistic and empirical interp need each other.**<br>
  Circuits and features on one side; probes, steering vectors, activation geometry on the other. Neither camp admits how much it borrows from the other.
- **Write the kill condition first.**<br>
  What would make me abandon this project? Decided *before* the first run. Ledger, dated entries, no retroactive story-fitting.

<br>

**How that actually plays out:**

<p align="center">
  <img src="assets/pipeline.svg" alt="Hypothesis, kill condition, observational check, interventional check, or kill it and log it" width="100%">
</p>

---

### On the record

**GRIT — Geometry-Aware PEFT with K-FAC Preconditioning, Fisher-Guided Reprojection, and Dynamic Rank Adaptation**<br>
[arXiv:2601.00231](https://arxiv.org/abs/2601.00231)

> LoRA optimizes in a randomly oriented subspace and ignores local loss curvature. GRIT preconditions gradients in rank space with K-FAC, reprojects the basis onto dominant Fisher eigendirections, and adapts effective rank from the spectrum — **46% fewer trainable parameters** at LoRA/QLoRA parity, plus a curvature-modulated scaling law for forgetting drift.

---

### Built, and stress-tested

**Perception-gated interleaved reasoning** · *Lossfunk*<br>
Taught a reasoning model to interleave answers with its reasoning via SFT, trained hidden-state probes, built an online emit/continue/stop controller, and extended it to GRPO with a length-penalised reward — then ran a pre-registered control battery across two model families to test whether the probe directions survived intervention.

**[neural-observer](https://github.com/Te4bag/neural-observer)** · training diagnostics<br>
CPU-offloaded instrumentation at near-zero VRAM overhead. Crash recorder halts on gradient explosions and preserves a configurable pre-crash window. Modular hook API for ConvNets and Transformers.

**[RagShield](https://github.com/Te4bag/RagShield)** · sentence-level RAG auditing<br>
NLI-based hallucination detection with a claim-level traffic-light trust view and source attribution. ChromaDB + Groq + Streamlit.

---

### The essentials

**Languages**<br>
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**Deep learning**<br>
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/Transformers-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![PEFT](https://img.shields.io/badge/PEFT%20%2F%20TRL-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Accelerate](https://img.shields.io/badge/Accelerate-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)

**Interpretability**<br>
![TransformerLens](https://img.shields.io/badge/TransformerLens-6E56CF?style=flat-square)
![nnsight](https://img.shields.io/badge/nnsight-6E56CF?style=flat-square)
![SAELens](https://img.shields.io/badge/SAELens-6E56CF?style=flat-square)
![Captum](https://img.shields.io/badge/Captum-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)

**Serving & infra**<br>
![vLLM](https://img.shields.io/badge/vLLM-5A2CA0?style=flat-square)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

**Data & tracking**<br>
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square)
![W&B](https://img.shields.io/badge/W%26B-FFBE00?style=flat-square&logo=weightsandbiases&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6B6B?style=flat-square)

---

### Off the clock

- Space exploration, neuroscience, cognitive science. Anything where someone is trying to reverse-engineer a system that was never documented. Start with [**Life on Mars: neuroplasticity in the first Martians**](https://www.physicalcoglab.co.uk/_files/ugd/e7bc20_ac10fcf6a9ca4ba6984ec29f9166c2f1.pdf) 
- **Visca el Barça** 💙❤️
- Send me a paper I'd never find on my own. That's the whole ask.

---

<p align="center"><sub>Open to research collaborations in interpretability. Reach me at chandravraj05@gmail.com.</sub></p>
