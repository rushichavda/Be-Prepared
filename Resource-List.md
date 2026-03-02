You're 100% right, and I appreciate the pushback. Here's the **genuinely comprehensive, multi-source** guide — blogs, Substacks, personal sites, free courses, PDFs, newsletters, academic course pages, and more. "Open source" broadly = **free to access and learn from**.

---

# 🧠 The Complete Free Resource Stack for LLM/NLP Interview Prep

---

## 🏆 CATEGORY 1: Personal Blogs (The Gold Standard for Deep Dives)

### [GOOD] 1. 🔵 **Lil'Log by Lilian Weng** — `lilianweng.github.io`
*(Ex-OpenAI Head of Safety Research — arguably the most cited AI blog in existence)*

Must-read posts for interviews:
- **The Transformer Family v2.0** — deep dive into all attention variants
- **LLM Powered Autonomous Agents** — the definitive agentic AI reference
- **Prompt Engineering** — comprehensive guide
- **Extrinsic Hallucinations in LLMs** — grounded factuality
- **Large Transformer Model Inference Optimization** — KV cache, distillation
- **Reward Hacking in RL** — key for RLHF understanding
- **Contrastive Representation Learning** — embeddings deep dive
- **How to Train Really Large Models on Many GPUs** — distributed training
- **Reducing Toxicity in Language Models** — alignment
- **Controllable Neural Text Generation**

**Why it's great:** Research-grade depth, every post is interview-goldmine level, regularly cited in papers.

---

### [GOOD]2. 🟡 **Jay Alammar's Blog** — `jalammar.github.io`
*(The king of visual explanations)*

Must-read posts:
- **The Illustrated Transformer** — THE best visual breakdown of attention
- **The Illustrated BERT, ELMo, and co.** — encoder models explained
- **The Illustrated GPT-2** — decoder model internals
- **Visualizing A Neural Machine Translation Model** — seq2seq + attention
- **The Illustrated Word2Vec** — embedding fundamentals
- **A Visual Guide to Prompt Engineering**
- **Semantic Search, Fine-tuning Representation Models** (via Cohere)

**Why it's great:** When an interviewer asks "explain self-attention," you'll have a visual mental model. Nothing beats this for Transformer internals.

---

### [SOSO] 3. 🟢 **Sebastian Raschka's Blog** — `sebastianraschka.com/blog`
*(ML researcher, author of "Build an LLM from Scratch")*

Top posts for interviews:
- **Understanding Parameter-Efficient Finetuning: From Prefix Tuning to LLaMA-Adapters**
- **Parameter-Efficient LLM Finetuning With LoRA**
- **Improving LoRA: DoRA from Scratch**
- **New LLM Pre-training and Post-training Paradigms**
- **State of RL for LLM Reasoning (GRPO)**
- **Understanding Multimodal LLMs**
- **Understanding the 4 Main Approaches to LLM Evaluation**
- **KV Cache in LLMs from Scratch**
- **Big LLM Architecture Comparison** (DeepSeek-V3 to Kimi K2)
- **Categories of Inference-Time Scaling**
- **Optimizing Memory Usage for Training LLMs in PyTorch**
- **Mixed-Precision Techniques** (FP16, BF16)

**Why it's great:** Code-first, extremely thorough on PEFT/fine-tuning, covers everything from LoRA math to modern training paradigms.

---

### 4.[SOSO] 🟠 **Eugene Yan's Blog** — `eugeneyan.com/writing`
*(Applied science at Amazon — production LLM systems)*

Filtered LLM posts:
- **Product Evals in Three Simple Steps**
- **Evaluating Long-Context Q&A Systems**
- **LLM-as-Judge**
- **Prompting Fundamentals**
- **What I learned from building with LLMs**
- **Task-Specific LLM Evals**
- **AlignEval, LLM Evaluators**

**Why it's great:** Production/applied perspective — what interviewers at Big Tech actually care about when building real LLM systems.

---

### [Excellent]5. 🔴 **Chip Huyen's Blog** — `huyenchip.com/blog`
*(Author of "Designing ML Systems" — AI systems & strategy)*

Top posts:
- **Agents** — comprehensive agentic systems breakdown
- **Building A Generative AI Platform** — production system design
- **RLHF: Reinforcement Learning from Human Feedback**
- **Multimodality and Large Multimodal Models (LMMs)**
- **Open challenges in LLM research**
- **Building LLM applications for production**
- **Generation configs: temperature, top-k, top-p**
- **Common pitfalls when building generative AI applications**

**Why it's great:** System design interviews + RLHF + production thinking. If you're going into ML Engineering/Applied Science, this is essential.

---

### [SOSO]6. 🟣 **Hamel Husain's Blog** — `hamel.dev`
*(ML engineer, 20+ years experience, worked with OpenAI/GitHub)*

Key posts:
- **LLM Evals: Everything You Need to Know**
- **What We've Learned From A Year of Building with LLMs**
- **Is Fine-Tuning Still Valuable?**
- **Your AI Product Needs Evals**
- **Using LLM-as-a-Judge For Evaluation: A Complete Guide**
- **Stop Saying RAG Is Dead**
- **Tools for curating LLM Data**
- **Tokenization Gotchas**

**Why it's great:** Extremely practical, evals-focused, and covers the "when and why" decisions that senior engineers get asked about.

---

### [Excellent] 7. ⭐ **Aman Chadha's AI Journal** — `aman.ai/primers/ai/`
*(Probably the most comprehensive single-person NLP/LLM primer site on the internet)*

This site has **organized written primers on literally every topic** you'd ever be asked about:
- Transformers, Attention, Tokenization
- BERT, GPT, T5, CLIP, LLaMA, Gemini, DeepSeek, Claude
- PEFT, LoRA, Prefix Tuning, Hypernetworks
- RAG, Factuality, Hallucination Detection
- RLHF, Preference Optimization, Reinforcement Fine-Tuning
- Reasoning in LLMs, LLM Context Length Extension
- Speculative Decoding, Flash Attention, Model Acceleration
- Agentic RL, Agents, LLM-as-a-Judge
- Mixture of Experts, State Space Models
- LLMOps, MLOps, On-Device AI, Federated Learning
- **Direct Interview Questions section at the bottom!**

**Why it's great:** This is your one-stop encyclopedia. Every topic organized, concise primers, covers even recent models like o1, DeepSeek R1, Gemma, Qwen.

---

## 📬 [Good Substacks and NL] CATEGORY 2: Substack Newsletters (Weekly Deep Dives)

### 8. **Deep (Learning) Focus by Cameron R. Wolfe, PhD** — `cameronrwolfe.substack.com`
*64,000+ subscribers*

Recent posts covering: GRPO++, Continual Learning with RL, LLM pretraining, RAG internals, RLHF vs DPO, LoRA variants, long-context models, MoE architectures. **Every post is a research paper distillation** with full conceptual explanation. Perfect for staying current and understanding the "why" behind techniques.

---

### 9. **Exploring Language Models by Maarten Grootendorst** — `newsletter.maartengrootendorst.com`
*28,000+ subscribers, Author of "Hands-On Large Language Models"*

Archive posts: Visual Guide to LLM Agents, Visual Guide to Reasoning LLMs, Visual Guide to Mixture of Experts, Visual Guide to Quantization (GPTQ vs GGUF vs AWQ), Visual Guide to Mamba/SSMs, 3 Ways to Improve Your LLM, Topic Modeling with LLaMA. **Best visual explainers on Substack for LLM internals.**

---

### 10. **Interconnects AI by Nathan Lambert** — `interconnects.ai`
*61,000+ subscribers, alignment researcher*

Deep dives on: RLHF, DPO, GRPO, preference learning, reward models, open LLM landscape, frontier model comparisons. **Best resource for deep alignment/RLHF/preference tuning interview prep.**

---

### 11. **The AiEdge Newsletter by Damien Benveniste** — `newsletter.theaiedge.io`
Covers: Agentic RAG systems, LLM fine-tuning, production AI, prompt optimization. Has a structured **LLM Book** section covering topics systematically.

---

### 12. **Ahead of AI by Sebastian Raschka** — `magazine.sebastianraschka.com`
Monthly deep dives on LLM research papers, training techniques, LoRA experiments, DPO vs PPO comparison — complementary to his blog.

---

## 🎓 [Good Courses] CATEGORY 3: Free Academic Courses & University Materials

### 13. **Stanford CS324 — Large Language Models** — `stanford-cs324.github.io/winter2022/`
Full lecture notes from Stanford covering: LLM foundations, capabilities, harms, efficiency, adaptation (fine-tuning, prompting), alignment, emerging architectures. **Graduate-level depth, fully free.**

### 14. **Full Stack Deep Learning LLM Bootcamp** — `fullstackdeeplearning.com/llm-bootcamp/spring-2023/`
Free lectures covering: Prompt Engineering, LLMOps, Augmented Language Models (RAG), Agents (Harrison Chase of LangChain), LLM Foundations (Transformer architecture, datasets). **Extremely practical and hands-on.**

### 15. **DeepLearning.AI Short Courses** — `deeplearning.ai/short-courses/`
Free short courses by domain experts: RAG, Fine-tuning, RLHF, Prompt Engineering, LLM Evaluation, Agentic AI, Multimodal. Andrew Ng + practitioners from Cohere, OpenAI, LangChain, HuggingFace.

### 16. **Princeton NLP — Understanding Large Language Models** — `princeton-nlp.github.io`
Academic lecture slides & notes on LLM theory — training objectives, scaling laws, in-context learning theory, emergent abilities.

---

## 🛠️ CATEGORY 4: Industry Blogs & Practice-Oriented Resources

### 17. [Blogs, Tuts, Good] **HuggingFace Blog** — `huggingface.co/blog`
Deep technical posts: PEFT library internals, LoRA math, RLHF with TRL, DPO tutorial, GPTQ/AWQ quantization, RAG pipelines, Flash Attention, evaluation methodologies, fine-tuning best practices. **Written by the people who build the tools.**

### 19. [Courses, Good] **Parlance Labs Educational Resources** — `parlance-labs.com/education/`
Video talks from practitioners on: Evals (when/how), RAG (basics to advanced), Fine-tuning (should you? when? how?), Deployment, Advanced fine-tuning topics (FSDP, DeepSpeed, Axolotl, function calling). **Talk-format learning from engineers who've shipped LLM products.**

### 20.[Courses, SOSO] **Weights & Biases Fully Connected** — `wandb.ai/fully-connected`
Articles + reports on: LLM training experiments, evaluation methods, LoRA experiments, RAG evaluation, prompt management, monitoring LLMs in production. Also has free LLM-Engineering course.

### 21.[Blogs, SOSO]**The Gradient** — `thegradient.pub`
Research-level explainer articles on NLP/LLM concepts, debates in the field (fine-tuning vs prompting, scaling laws, emergent abilities). Academic quality but accessible writing.

---

## 📊 CATEGORY 5: Topic-Specific Deep Resources

| Topic | Best Free Resource |
|---|---|
| **Transformer internals, self-attention math** | Jay Alammar (`jalammar.github.io`) |
| **Pre-training (data, objectives, scaling)** | Lilian Weng + Sebastian Raschka + Stanford CS324 |
| **LoRA / PEFT deep dive** | Sebastian Raschka's blog + HuggingFace Blog |
| **RLHF / DPO / PPO / GRPO** | Chip Huyen blog + Lilian Weng + Interconnects AI (Nathan Lambert) |
| **RAG (basic to advanced)** | Lil'Log + mlabonne llm-course + applied-llms.org + Parlance Labs |
| **Quantization (GPTQ, AWQ, GGUF)** | Maarten Grootendorst Newsletter + mlabonne/llm-course |
| **Agentic AI & Multi-Agent Systems** | Lilian Weng (LLM Agents post) + Chip Huyen (Agents) + mlabonne |
| **LLM Evaluation & Evals** | Eugene Yan + Hamel Husain + HuggingFace Blog |
| **Inference Optimization** | Lilian Weng (Inference post) + Sebastian Raschka (KV Cache) |
| **Classical NLP foundations** | Jay Alammar + aman.ai/primers/ai/ |
| **Mixture of Experts (MoE)** | Maarten Grootendorst + Cameron Wolfe Newsletter |
| **Reasoning LLMs / Test-Time Compute** | Sebastian Raschka + Maarten Grootendorst |
| **Production system design** | Chip Huyen + Eugene Yan + applied-llms.org |
| **Everything, organized** | **aman.ai/primers/ai/** ← bookmark this |

---

## 🗺️ Suggested Study Order

**Week 1-2: Foundations**
→ Jay Alammar (Transformers, BERT, GPT visuals) → Lilian Weng (Transformer Family v2) → aman.ai architecture section

**Week 3-4: Training Pipeline**
→ Sebastian Raschka (Pre-training + PEFT + LoRA) → Lilian Weng (RLHF + Reward Hacking) → Interconnects AI (DPO/GRPO) → Chip Huyen (RLHF)

**Week 5-6: RAG & Agents**
→ Lilian Weng (LLM Agents) → applied-llms.org → Chip Huyen (Agents + GenAI Platform) → Parlance Labs (RAG talks)

**Week 7-8: Production & Evals**
→ Hamel Husain (Evals) → Eugene Yan → HuggingFace Blog → Maarten Grootendorst (Quantization)

**Ongoing:** Cameron Wolfe Newsletter (weekly paper digests), Interconnects AI (alignment news), Sebastian Raschka (architecture comparisons)

---

The key insight: **no single resource covers everything**, but together these free blogs, Substacks, and course pages form a complete curriculum that goes far deeper than any GitHub Q&A repo — and they're what the *interviewers themselves* read.
