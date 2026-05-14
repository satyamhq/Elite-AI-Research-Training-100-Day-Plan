# Elite AI Research Training: 100-Day Plan

> **7 hours/day · Intermediate → Top 1% · Structured for speed + depth**

| Metric | Value |
|--------|-------|
| Total Days | 100 |
| Total Study Hours | 700h |
| Phases | 5 |
| Portfolio Projects | 7 |
| Papers to Read | 50+ |

---

## Table of Contents

1. [Roadmap — 5 Phases](#roadmap--5-phases)
2. [Daily Schedule](#daily-schedule)
3. [Core Knowledge Stack](#core-knowledge-stack)
4. [Projects](#projects)
5. [Research Training](#research-training)
6. [Top 1% Habits](#top-1-habits)
7. [Weekly Evaluation Checkpoints](#weekly-evaluation-checkpoints)
8. [Day 100 Outcome](#day-100-outcome)

---

## Roadmap — 5 Phases

---

### Phase 1 — Mathematical Foundations
**Days 1–15**

#### Topics
- Linear Algebra
- Multivariate Calculus
- Probability Theory
- Statistics
- Information Theory
- Optimization Basics

#### Resources
| Resource | Type | Cost |
|----------|------|------|
| [3Blue1Brown — Essence of Linear Algebra](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) | YouTube Series | Free |
| [Mathematics for Machine Learning — Deisenroth, Faisal, Ong](https://mml-book.github.io/) | Book | Free PDF |
| [Khan Academy — Multivariable Calculus](https://www.khanacademy.org/math/multivariable-calculus) | Course | Free |
| [Khan Academy — Statistics & Probability](https://www.khanacademy.org/math/statistics-probability) | Course | Free |
| [Deep Learning Book Ch. 2–4 — Goodfellow, Bengio, Courville](https://www.deeplearningbook.org/) | Book | Free online |

#### Weekly Goals
- **Week 1:** Master matrix operations, eigendecomposition, SVD — implement in NumPy
- **Week 2:** Calculus (gradients, chain rule, Jacobians), probability distributions, Bayes theorem
- **Week 3 (Days 15):** Information theory basics, MLE/MAP — write derivations from scratch

#### Daily Tasks
- **1h** — Concept study (video/book)
- **1.5h** — Handwritten derivations — never skip this
- **30min** — Implement in NumPy (SVD, PCA, gradient descent by hand)
- **30min** — Anki flashcards for notation + theorems

---

### Phase 2 — Core ML: Algorithms & Theory
**Days 16–35**

#### Topics
- Supervised Learning
- Unsupervised Learning
- Bias-Variance Tradeoff
- Regularization
- SVMs
- Ensemble Methods
- PyTorch Mastery

#### Resources
| Resource | Type | Cost |
|----------|------|------|
| [Stanford CS229 — Andrew Ng (lecture notes + problem sets)](https://cs229.stanford.edu/) | Course | Free |
| [Pattern Recognition and Machine Learning — Bishop](https://www.microsoft.com/en-us/research/uploads/prod/2006/01/Bishop-Pattern-Recognition-and-Machine-Learning-2006.pdf) | Book | Free PDF |
| [fast.ai Practical Deep Learning Part 1](https://course.fast.ai/) | Course | Free |
| [PyTorch Official Tutorials](https://pytorch.org/tutorials/) | Tutorials | Free |
| [Dive into Deep Learning (d2l.ai)](https://d2l.ai/) | Book | Free online |

#### Weekly Goals
- **Week 3:** Implement linear regression, logistic regression, SVM from scratch (no sklearn)
- **Week 4:** Decision trees, random forests, gradient boosting — theory + code
- **Week 5:** PyTorch fluency — custom Dataset, DataLoader, training loops, autograd

---

### Phase 3 — Deep Learning: Architecture Mastery
**Days 36–60**

#### Topics
- CNNs
- RNNs / LSTMs
- Transformers
- Attention Mechanisms
- Normalization Techniques
- Optimizers (Adam, AdamW, etc.)
- Training Dynamics
- Scaling Laws

#### Key Papers (implement each)
| Paper | Authors | Year |
|-------|---------|------|
| [Attention Is All You Need](https://arxiv.org/abs/1706.03762) | Vaswani et al. | 2017 |
| [Deep Residual Learning for Image Recognition](https://arxiv.org/abs/1512.03385) | He et al. | 2015 |
| [Batch Normalization](https://arxiv.org/abs/1502.03167) | Ioffe & Szegedy | 2015 |
| [Dropout: A Simple Way to Prevent Neural Networks from Overfitting](https://jmlr.org/papers/v15/srivastava14a.html) | Srivastava et al. | 2014 |
| [Adam: A Method for Stochastic Optimization](https://arxiv.org/abs/1412.6980) | Kingma & Ba | 2014 |

#### Additional Resources
| Resource | Type |
|----------|------|
| [Andrej Karpathy's nanoGPT](https://github.com/karpathy/nanoGPT) | Project — Essential |
| [Andrej Karpathy's makemore series](https://www.youtube.com/playlist?list=PLAqhIrjkxbuWI23v9cThsA9GvCAUhRvKZ) | YouTube |
| [Stanford CS231n — CNNs for Visual Recognition](http://cs231n.stanford.edu/) | Course Notes |
| [Stanford CS224n — NLP with Deep Learning](https://web.stanford.edu/class/cs224n/) | Course Notes |
| [The Illustrated Transformer — Jay Alammar](https://jalammar.github.io/illustrated-transformer/) | Blog |

#### Weekly Goals
- **Week 6–7:** Build a transformer from scratch (no HuggingFace). Train on a small dataset.
- **Week 8:** BERT/GPT fine-tuning, understand pretraining objectives deeply
- **Week 9 (Days 57–60):** Scaling laws paper, training instabilities, debugging DL models

---

### Phase 4 — Specialization: Modern Research Frontier
**Days 61–85**

#### Topics
- LLMs & RLHF
- Diffusion Models
- Multimodal AI
- Efficient Fine-tuning (LoRA, QLoRA)
- AI Safety / Alignment basics
- Agents & Tool Use
- RAG Systems

#### Key Papers
| Paper | Authors | Year |
|-------|---------|------|
| [Training Language Models to Follow Instructions (InstructGPT)](https://arxiv.org/abs/2203.02155) | Ouyang et al. | 2022 |
| [LoRA: Low-Rank Adaptation of Large Language Models](https://arxiv.org/abs/2106.09685) | Hu et al. | 2021 |
| [Denoising Diffusion Probabilistic Models](https://arxiv.org/abs/2006.11239) | Ho et al. | 2020 |
| [Constitutional AI — Anthropic](https://arxiv.org/abs/2212.08073) | Bai et al. | 2022 |
| [Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks](https://arxiv.org/abs/2005.11401) | Lewis et al. | 2020 |
| [QLoRA: Efficient Finetuning of Quantized LLMs](https://arxiv.org/abs/2305.14314) | Dettmers et al. | 2023 |
| [Scaling Laws for Neural Language Models](https://arxiv.org/abs/2001.08361) | Kaplan et al. | 2020 |

#### Tools & Codebases
| Resource | Link |
|----------|------|
| HuggingFace PEFT library | [github.com/huggingface/peft](https://github.com/huggingface/peft) |
| LangChain | [github.com/langchain-ai/langchain](https://github.com/langchain-ai/langchain) |
| vLLM | [github.com/vllm-project/vllm](https://github.com/vllm-project/vllm) |
| LlamaIndex | [github.com/run-llama/llama_index](https://github.com/run-llama/llama_index) |

#### Weekly Goals
- **Week 10:** Fine-tune LLaMA/Mistral with LoRA on a task of your choice
- **Week 11:** Build a RAG pipeline from scratch, evaluate retrieval quality
- **Week 12:** Implement a minimal diffusion model, understand DDPM math
- **Week 13:** Read 10 frontier papers; write 1-page summaries of each

---

### Phase 5 — Research Mode: Create, Contribute, Publish
**Days 86–100**

#### Activities
- Original Experiments
- Ablation Studies
- Paper Writing (LaTeX)
- GitHub Portfolio Polish
- Technical Blog Posts
- Research Networking

#### Goals
- Identify a gap in 1–2 papers from Phase 4; run experiments to address it
- Write a technical blog post ([Towards Data Science](https://towardsdatascience.com/) / personal site) with novel findings
- Submit a workshop paper — [NeurIPS](https://neurips.cc/), [ICML](https://icml.cc/), [ICLR](https://iclr.cc/) workshops accept 3–4 page short papers
- Final project: full research-grade implementation with reproducibility
- Record a video walkthrough of your best project

#### Resources
| Resource | Link |
|----------|------|
| Writing Science — Joshua Schimel | [Amazon](https://www.amazon.com/Writing-Science-Papers-Proposals-Funded/dp/0199760241) |
| Papers With Code | [paperswithcode.com](https://paperswithcode.com/) |
| ArXiv | [arxiv.org](https://arxiv.org/) |
| Semantic Scholar | [semanticscholar.org](https://www.semanticscholar.org/) |
| How to Write a Great Research Paper — Simon Peyton Jones | [YouTube](https://www.youtube.com/watch?v=VK51E3gHENc) |

---

## Daily Schedule

> 7 hours/day, 6 days/week. Sunday = light review + planning (3h only).

| Time | Block | Activity | Details |
|------|-------|----------|---------|
| 6:00–7:30 AM | 90 min | **Math Deep Work** | Derivations, proofs, problem sets. No interruptions. |
| 7:30–9:30 AM | 2h | **Coding Session 1** | Implement what you studied. From scratch, always. |
| 9:30–10:00 AM | 30 min | **Break + Walk** | Think about what you built. No screens. |
| 10:00–11:30 AM | 90 min | **Paper Reading** | 1 paper/day. Annotate, question, diagram. |
| 11:30–12:30 PM | 1h | **Lunch + Rest** | Full break — protect recovery. |
| 12:30–3:30 PM | 3h | **Project Work** | Build portfolio projects. Real data, real problems. |
| 3:30–4:30 PM | 1h | **Spaced Review** | Anki deck, re-derive yesterday's key equations. |

### Sunday Protocol (3h only)
- Review the week's output: what did you build? What broke?
- Read 2 short papers or blog posts from top researchers
- Write your weekly log: key learnings, confusions, next week's focus
- Update GitHub — even failed experiments are portfolio entries

---

## Core Knowledge Stack

### Mathematics

| Topic | Key Concepts | Target Depth |
|-------|-------------|--------------|
| Linear Algebra | Eigendecomposition, SVD, matrix calculus | Implement from scratch |
| Multivariate Calculus | Gradients, Jacobians, Hessians, chain rule | Derive by hand |
| Probability & Statistics | MLE, MAP, Bayes, distributions, hypothesis testing | Prove + apply |
| Information Theory | Entropy, KL divergence, mutual information | Derive all proofs |
| Optimization | Convexity, SGD, Adam, constrained optimization | Implement + tune |

**Primary math reference:** [Mathematics for ML — Deisenroth et al.](https://mml-book.github.io/) + [Deep Learning Book Ch. 2–4](https://www.deeplearningbook.org/)

### Programming

| Tool | Depth Required |
|------|---------------|
| Python (Advanced) | Decorators, generators, profiling, async |
| [PyTorch](https://pytorch.org/) | Autograd, custom modules, distributed training |
| NumPy / [JAX](https://github.com/google/jax) | Vectorization, broadcasting, JIT compilation |
| [HuggingFace Transformers](https://huggingface.co/docs/transformers) | Fine-tuning, PEFT, custom trainers |
| [Weights & Biases](https://wandb.ai/) | Experiment tracking — use from Day 1 |

### ML/DL Concepts

| Domain | What You Must Be Able To Do |
|--------|----------------------------|
| Classical ML | Implement every algorithm from scratch — not just call it |
| Deep Learning Architectures | CNN, RNN, Transformer — math + code, no black boxes |
| Training Dynamics | Debug instabilities, tune hyperparameters systematically |
| Modern LLMs | Pretraining objectives, RLHF, fine-tuning, evaluation metrics |
| Generative Models | VAEs, GANs, Diffusion — mathematical derivations |

---

## Projects

---

### Project 1 — ML Algorithm Library from Scratch
**Days 20–35 · Difficulty: ★★★☆☆**

Implement 10+ ML algorithms (linear regression, logistic regression, SVM, k-means, PCA, decision tree, random forest, XGBoost-lite) using only NumPy. Include math derivations in a companion Jupyter notebook. Benchmark against sklearn.

**Stack:** NumPy · Python · Jupyter  
**Deliverable:** GitHub repo with README, derivations notebook, benchmark results

---

### Project 2 — GPT from Scratch: Character-level to BPE
**Days 45–60 · Difficulty: ★★★★☆**

Build a transformer language model from the ground up. Start with character-level (Karpathy style), then add BPE tokenization, multi-head attention, positional embeddings. Train on a domain-specific corpus. Analyze attention heads visually.

**Stack:** PyTorch · Transformers (from scratch) · NLP  
**Reference:** [Karpathy's nanoGPT](https://github.com/karpathy/nanoGPT) · [Let's build GPT video](https://www.youtube.com/watch?v=kCc8FmEb1nY)  
**Deliverable:** Fully working GPT + attention visualization notebook

---

### Project 3 — Multimodal Image-Text Retrieval (CLIP-like)
**Days 55–70 · Difficulty: ★★★★☆**

Implement a CLIP-like contrastive learning system from scratch. Train on a subset of COCO. Build a semantic search UI. Analyze embedding space, measure zero-shot classification accuracy. Compare to full CLIP.

**Stack:** PyTorch · Vision · Contrastive Learning  
**Reference:** [CLIP Paper](https://arxiv.org/abs/2103.00020) · [COCO Dataset](https://cocodataset.org/)  
**Deliverable:** Working retrieval system + blog post with your own visualizations

---

### Project 4 — Domain-Expert LLM via LoRA Fine-tuning
**Days 65–78 · Difficulty: ★★★★☆**

Fine-tune Mistral-7B or LLaMA-3 on a niche domain (medical notes, legal contracts, scientific papers) using QLoRA. Implement custom evaluation metrics. Compare PEFT methods. Deploy with a Gradio interface.

**Stack:** HuggingFace · LoRA/QLoRA · Gradio · GPU compute  
**Reference:** [LoRA Paper](https://arxiv.org/abs/2106.09685) · [QLoRA Paper](https://arxiv.org/abs/2305.14314) · [PEFT Docs](https://huggingface.co/docs/peft)  
**Deliverable:** Fine-tuned model + evaluation report + live Gradio demo

---

### Project 5 — Production RAG System with Rigorous Evaluation
**Days 72–82 · Difficulty: ★★★★☆**

Build an end-to-end RAG pipeline: chunking strategies, multiple embedding models (compare BM25 vs dense vs hybrid retrieval), reranking, faithfulness evaluation using RAGAS. Test on a real document corpus.

**Stack:** LangChain · Vector DB ([ChromaDB](https://www.trychroma.com/) or [Weaviate](https://weaviate.io/)) · [RAGAS](https://github.com/explodinggradients/ragas) · FastAPI  
**Reference:** [RAG Paper](https://arxiv.org/abs/2005.11401) · [RAGAS Paper](https://arxiv.org/abs/2309.15217)  
**Deliverable:** RAG system + technical report on retrieval quality vs latency trade-offs

---

### Project 6 — Diffusion Model from Scratch (DDPM + DDIM)
**Days 78–90 · Difficulty: ★★★★★**

Implement DDPM from scratch. Train on MNIST → CIFAR-10. Implement DDIM for faster sampling. Visualize the denoising process. Ablate noise schedules (linear vs cosine). Write a technical explainer with your own diagrams.

**Stack:** PyTorch · Diffusion Models · Generative AI  
**Reference:** [DDPM Paper](https://arxiv.org/abs/2006.11239) · [DDIM Paper](https://arxiv.org/abs/2010.02502) · [Annotated Diffusion](https://huggingface.co/blog/annotated-diffusion)  
**Deliverable:** Working diffusion model + technical blog post with original diagrams

---

### Project 7 — Original Research Experiment
**Days 88–100 · Difficulty: ★★★★★**

Identify a small gap or unexplored combination from papers you've read. Run experiments, collect results, perform ablations. Target: a NeurIPS / ICML / ICLR workshop submission.

**Ideas to explore:**
- A novel regularization method applied to transformers
- Empirical study of attention pattern diversity across domains
- Hybrid retrieval method for RAG outperforming existing baselines
- Ablation study that questions an assumption in a popular paper

**Reference:** [Papers With Code — Open Problems](https://paperswithcode.com/) · [NeurIPS Workshop CFPs](https://neurips.cc/)  
**Deliverable:** LaTeX paper draft (3–4 pages) + reproducible codebase + results

---

## Research Training

### How to Read a Paper — The 3-Pass Method

**Pass 1 — 15 minutes — Skim**
- Read: title, abstract, intro, section headers, conclusion
- Decision: is this worth a full read?
- Output: write 3 sentences — what problem, what solution, what result

**Pass 2 — 1 hour — Understand**
- Read fully, skip proofs on first pass
- Draw every figure yourself from scratch
- Note every equation you don't understand
- Write: what assumptions are made? What would break this paper?

**Pass 3 — 2–4 hours — Implement**
- Re-read with code editor open
- Implement the core idea — if results don't match, figure out why
- This is where real understanding happens
- Virtually no one does this. You will.

### How to Write a Research Paper

1. **Start with the results figure first** — the paper exists to explain that figure
2. **Introduction structure:** problem → why hard → why existing work fails → your insight → contributions
3. **Related work:** position yourself, don't just list papers — show contrast
4. **Method:** be precise enough that someone can reproduce it with no other information
5. **Experiments:** ablations are more convincing than cherry-picked best results
6. **Follow Simon Peyton Jones:** ["Writing a paper is how you develop the idea"](https://www.youtube.com/watch?v=VK51E3gHENc)
7. **Target venues:** start with workshops (3–4 page limit) before full conference papers

**LaTeX Resources:** [Overleaf](https://www.overleaf.com/) · [NeurIPS LaTeX template](https://neurips.cc/Conferences/2024/PaperInformation/StyleFiles)

### Thinking Like a Researcher

- Question every paper's assumptions — most breakthroughs come from questioning "obvious" constraints
- Keep an **idea journal** — write down every "what if I..." thought, even bad ones
- After every paper: write "what would I do differently and why?"
- Reproduce first, innovate second. You can't improve what you don't understand
- Follow researchers on [Twitter/X](https://twitter.com) and read their thinking, not just their papers
- Attend virtual workshops: [NeurIPS](https://neurips.cc/), [ICML](https://icml.cc/), [ICLR](https://iclr.cc/) are free to livestream

**Researchers worth following:** Andrej Karpathy · Yann LeCun · Ilya Sutskever · Yoshua Bengio · Percy Liang · Chelsea Finn

---

## Top 1% Habits

### 1. Feynman Technique — Daily
After studying any concept, explain it out loud as if teaching a beginner. Write it without notes. If you can't, you don't know it. This forces real understanding over pattern-matching.

### 2. Derivation Before Implementation
Never write code for an algorithm you haven't derived on paper first. Takes more time upfront, saves months of confusion later. Most ML engineers skip this. You won't.

### 3. Deep Work Blocks — Protected
3-hour morning sessions with phone off, notifications off. Your 3-hour protected block is worth more than 6 distracted hours.

**Tool:** [Forest App](https://www.forestapp.cc/) or [Cold Turkey Blocker](https://getcoldturkey.com/) for focus enforcement.

### 4. Weekly Research Log
Write 200–300 words every Sunday: what confused you, what clicked, what questions emerged. The best researchers are obsessive self-auditors.

### 5. Seek Confusion, Not Comfort
If you're not confused, you're not learning. Actively seek the papers and concepts that make you feel stupid. That discomfort is the signal of a productive learning boundary.

### 6. Ship Ugly Code First
Get a working prototype in 2 hours. Refactor later. Analysis paralysis kills more research careers than bad code does. The goal is experimental results, not clean abstractions.

### 7. Public Learning Accountability
Post one insight per week on [Twitter](https://twitter.com) / [LinkedIn](https://linkedin.com) / GitHub. Forces you to articulate ideas clearly and builds your network.

### 8. No Tutorial-Only Days
Every day must include original code or derivations. For every 1h of tutorial, write 2h of code.

### Mental Models for Research
- **First Principles Thinking** — strip every problem to its mathematical core before building back up
- **Inversion** — before asking "how do I make this work", ask "why would this fail?"
- **Steel-manning** — argue the strongest possible case for competing approaches before choosing one
- **Bottleneck Analysis** — always ask: what is the actual limiting factor in this system?

---

## Weekly Evaluation Checkpoints

### Week 2 Checkpoint — Day 14
- [ ] Derive backpropagation for a 3-layer MLP from scratch on paper, no references
- [ ] Implement PCA and SVD in NumPy, apply to a real dataset, visualize components
- [ ] Explain gradient descent, momentum, and Adam to a "rubber duck" on video

### Week 4 Checkpoint — Day 28
- [ ] Implement logistic regression + SVM from scratch — hit >95% accuracy on MNIST (no sklearn)
- [ ] Train a PyTorch model with a custom training loop, LR scheduler, and early stopping
- [ ] Read and write 1-page summaries of 2 classic papers (e.g., [XGBoost](https://arxiv.org/abs/1603.02754), [SVMs](https://www.cs.cornell.edu/people/tj/publications/joachims_98a.pdf))

### Week 7 Checkpoint — Day 49
- [ ] Build a transformer from scratch (no HuggingFace) — train on a text dataset
- [ ] Explain multi-head attention math and code line by line in a recorded video
- [ ] Re-implement ResNet — match paper's reported accuracy within 2%

### Week 10 Checkpoint — Day 70
- [ ] Fine-tune an LLM with LoRA — demonstrate measurable improvement over base model with eval metrics
- [ ] Build and evaluate a RAG system — report retrieval precision/recall
- [ ] Read 5 ArXiv papers this week — write a comparative analysis of their methods

### Week 13 Checkpoint — Day 91
- [ ] Implement diffusion model from scratch, generate samples, ablate noise schedules
- [ ] Have 5+ repos on GitHub with READMEs, math derivations, and results — get peer review
- [ ] Draft introduction section of your research paper or technical blog post

### Day 100 Final Assessment
- [ ] Walk through any project end-to-end (data → model → results → analysis) with no notes
- [ ] Read a brand-new paper and critique it: assumptions, limitations, what you'd do differently
- [ ] Submit or publish something: workshop paper, blog post, or reproducible technical report

---

## Day 100 Outcome

| Metric | Target |
|--------|--------|
| Portfolio projects | 7 complete, GitHub-hosted |
| Papers read | 50+ (15 implemented) |
| Deep work hours | 700h |
| Research output | 1 workshop paper draft or published blog |
| Math level | Graduate-level — derive, don't look up |
| Paper reading | Any major DL paper in 2h, including critique |

### What "Top 1%" Looks Like at Day 100

- Can read any major DL paper and critique it within 2 hours — including weaknesses the authors didn't acknowledge
- Can implement any architecture from a paper description, debug training instabilities, and explain every design choice
- Math is not a barrier — you derive, you don't just look up
- GitHub portfolio that demonstrates progression from fundamentals to frontier research
- You have a **research identity** — a topic or question you care about and are actively investigating
- You've shipped code that other people have used, starred, or cited

---

## Essential Links Summary

### Courses
- [Stanford CS229 — Machine Learning](https://cs229.stanford.edu/)
- [Stanford CS231n — CNNs for Vision](http://cs231n.stanford.edu/)
- [Stanford CS224n — NLP with Deep Learning](https://web.stanford.edu/class/cs224n/)
- [fast.ai Practical Deep Learning](https://course.fast.ai/)
- [Andrej Karpathy's Zero to Hero series](https://karpathy.ai/zero-to-hero.html)

### Books (all free)
- [Deep Learning — Goodfellow, Bengio, Courville](https://www.deeplearningbook.org/)
- [Mathematics for Machine Learning](https://mml-book.github.io/)
- [Dive into Deep Learning](https://d2l.ai/)
- [The Little Book of Deep Learning — François Fleuret](https://fleuret.org/francois/lbdl.html)
- [Pattern Recognition and Machine Learning — Bishop](https://www.microsoft.com/en-us/research/uploads/prod/2006/01/Bishop-Pattern-Recognition-and-Machine-Learning-2006.pdf)

### Research Infrastructure
- [ArXiv](https://arxiv.org/) — preprints
- [Papers With Code](https://paperswithcode.com/) — SOTA benchmarks + code
- [Semantic Scholar](https://www.semanticscholar.org/) — paper discovery
- [Weights & Biases](https://wandb.ai/) — experiment tracking
- [Overleaf](https://www.overleaf.com/) — LaTeX paper writing
- [HuggingFace Hub](https://huggingface.co/) — models + datasets

### Communities
- [r/MachineLearning](https://www.reddit.com/r/MachineLearning/)
- [EleutherAI Discord](https://discord.gg/zBGx3azzUn)
- [Alignment Forum](https://www.alignmentforum.org/)
- [ML Twitter/X](https://twitter.com/karpathy) — follow active researchers

---

*The one rule that separates top 1% from everyone else: **implement everything**. Every paper, every algorithm, every concept. People who only watch tutorials can explain ideas; people who implement them can use them.*
