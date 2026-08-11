# AI Engineering Roadmap

> **Goal:** Become an AI Engineer capable of understanding, building, evaluating, and deploying real-world AI systems.

This roadmap is based on the **AI Engineering from Scratch** roadmap and has been organized around our primary goal: **AI Engineering**.

We are not treating the roadmap as a requirement to complete every lesson linearly. We will prioritize the knowledge and skills that directly contribute to becoming a capable AI Engineer.

---

# 🟢 Core — Must Learn

These phases form the main learning path.

## Phase 0 — Setup & Tooling

**Priority:** 🟢 Core

Build the developer foundation required for AI engineering.

**Focus:**

* Development environment
* Git & collaboration
* GPU setup & cloud
* APIs & keys
* Jupyter
* Python environments
* Docker
* Editor setup
* Data management
* Terminal & shell
* Linux
* Debugging & profiling

**Outcome:**

Be comfortable working with the tools and environments used throughout the journey.

---

## Phase 1 — Math Foundations

**Priority:** 🟢 Core

Learn the mathematics required to understand ML and deep learning.

**Focus:**

* Linear algebra
* Vectors and matrices
* Matrix operations
* Transformations
* Eigenvalues
* Derivatives
* Gradients
* Chain rule
* Automatic differentiation
* Probability
* Statistics
* Bayes' theorem
* Optimization
* Gradient descent
* Information theory
* Tensor operations
* Numerical stability
* Norms and distances

Advanced mathematical topics will be studied when they become useful.

**Outcome:**

Understand the mathematical ideas behind machine learning and neural networks.

---

## Phase 2 — ML Fundamentals

**Priority:** 🟢 Core

Build a strong foundation in classical machine learning.

**Focus:**

* Regression
* Classification
* Decision trees
* SVM
* KNN
* Clustering
* Feature engineering
* Model evaluation
* Bias and variance
* Ensembles
* Hyperparameter tuning
* ML pipelines
* Time series
* Anomaly detection
* Imbalanced data

**Outcome:**

Understand how ML problems are formulated, trained, evaluated, and deployed.

---

## Phase 3 — Deep Learning

**Priority:** 🟢 Core

Understand neural networks from fundamentals through modern frameworks.

**Focus:**

* Perceptrons
* Forward pass
* Backpropagation
* Activation functions
* Loss functions
* Optimizers
* Regularization
* Initialization
* Learning-rate schedules
* Neural-network implementation
* PyTorch
* JAX
* Debugging

**Outcome:**

Understand what happens inside a neural network and become capable of implementing and training models.

---

## Phase 5 — NLP

**Priority:** 🟢 Core

Learn the foundations required for modern language AI.

**Focus:**

* Text processing
* Tokenization
* Representations
* Embeddings
* Sequence models
* Attention
* Semantic search
* Modern embeddings
* NLP evaluation
* Retrieval foundations

**Outcome:**

Understand how text becomes representations that modern AI systems can process.

---

## Phase 7 — Transformers

**Priority:** 🟢 Core

Deeply understand the architecture behind modern language and multimodal models.

**Focus:**

* Why Transformers
* Self-attention
* Multi-head attention
* Positional encoding
* Full Transformer architecture
* BERT
* GPT
* T5/BART
* Vision Transformers
* Audio Transformers
* Mixture of Experts
* KV cache
* Flash Attention
* Scaling laws
* Attention variants
* Speculative decoding

### Major milestone

**Build a Transformer from scratch.**

**Outcome:**

Understand Transformer architecture rather than treating it as a black box.

---

## Phase 10 — LLMs from Scratch

**Priority:** 🟢 Core

Understand how large language models are built and operated.

**Focus:**

* Tokenizers
* Building a tokenizer
* Data pipelines
* Pre-training
* Mini GPT
* Distributed training
* Supervised fine-tuning
* RLHF
* DPO
* Evaluation
* Quantization
* Inference optimization
* Complete LLM pipeline
* Open models

Advanced LLM architecture and optimization topics will be studied progressively.

### Major milestone

Build a small end-to-end language model pipeline:

**Tokenizer → Data → Training → Evaluation → Inference**

---

## Phase 11 — LLM Engineering

**Priority:** 🔥 Core

This is one of the most important phases for our AI Engineering goal.

**Focus:**

* Prompt engineering
* Structured outputs
* Embeddings
* Context engineering
* RAG
* Advanced RAG
* LoRA / QLoRA
* Function calling
* Evaluation
* Cost optimization
* Guardrails
* Production LLM applications
* MCP
* Prompt and context caching

### Major projects

* LLM application
* RAG system
* Fine-tuned model
* Tool-using LLM
* Production LLM application

**Outcome:**

Become capable of engineering useful applications around modern LLMs.

---

## Phase 13 — Tools & Protocols

**Priority:** 🔥 Core

Learn how AI systems interact with external tools and systems.

**Focus:**

* Function calling
* Tool interfaces
* Schemas
* MCP
* MCP servers
* MCP clients
* Resources
* Transports
* Authentication
* A2A
* OpenTelemetry
* Routing
* Agent SDKs

### Major milestone

Build a tool ecosystem using MCP.

**Outcome:**

Build AI systems that can reliably interact with external tools, data, and services.

---

## Phase 14 — Agent Engineering

**Priority:** 🔥 Core

Learn how to build capable AI agents.

**Focus:**

* Agent loops
* Planning
* Reflection
* Tool use
* Memory
* Skills
* Orchestration
* State
* Multi-agent patterns
* Agent SDKs
* Observability
* Failure modes
* Prompt injection
* Evaluation
* Production runtimes
* Verification
* Agent workbenches

### Major milestone

Build a production-style agent capable of completing multi-step tasks.

**Outcome:**

Understand how to design, evaluate, debug, and operate AI agents.

---

## Phase 17 — Infrastructure & Production

**Priority:** 🟢 Core — Selected Topics

Learn the production engineering required to operate AI systems.

**Focus:**

* LLM platforms
* Inference economics
* Serving engines
* Inference optimization
* Quantization
* Observability
* Caching
* Model routing
* AI gateways
* Deployment strategies
* Load testing
* Security
* Compliance
* FinOps
* Serving selection

**Outcome:**

Move from building AI applications to operating reliable AI systems in production.

---

# 🟡 Selective — Learn When Relevant

These phases are valuable but are not required to complete the initial AI Engineering core path.

---

## Phase 4 — Computer Vision

**Priority:** 🟡 Selective

Study when vision becomes relevant to our projects or specialization.

---

## Phase 6 — Speech & Audio

**Priority:** 🟡 Selective

Study when working with voice, speech recognition, audio understanding, or audio generation.

---

## Phase 8 — Generative AI

**Priority:** 🟡 Selective

Relevant topics include:

* Generative model taxonomy
* Autoencoders
* VAEs
* GANs
* Diffusion models
* Latent diffusion
* LoRA
* Conditioning
* Evaluation
* Flow matching

Study according to project requirements.

---

## Phase 9 — Reinforcement Learning

**Priority:** 🟡 Selective

Learn when reinforcement learning becomes relevant to our AI systems or when deeper understanding of model optimization and decision-making is required.

---

## Phase 12 — Multimodal AI

**Priority:** 🟡 Selective

Study after establishing strong foundations in Transformers and LLMs.

---

## Phase 16 — Multi-Agent & Swarms

**Priority:** 🟡 Selective

Study after becoming comfortable with single-agent systems in Phase 14.

---

## Phase 18 — Ethics, Safety & Alignment

**Priority:** 🟡 Selective / Important

Focus particularly on engineering-relevant areas:

* Reward hacking
* Alignment techniques
* Guardrails
* Prompt injection
* Red teaming
* Model/system cards
* Data provenance
* Moderation
* AI security
* Dual-use risks

Deeper research-oriented alignment topics can be studied later.

---

# 🔵 Later — Advanced Specialization

These areas are valuable but should not distract from the core AI Engineering path early on.

Examples include:

* Advanced distributed training
* Frontier-model architecture research
* Advanced inference research
* Autonomous systems research
* Deep alignment research
* Specialized multimodal architectures
* Advanced multi-agent research
* Research-oriented infrastructure

These topics will be revisited after we have built substantial real-world AI systems.

---

# 🛠️ Learning Method

We will not follow:

```text
Lesson → Lesson → Lesson → Lesson
```

Instead:

```text
Learn
  ↓
Understand
  ↓
Implement
  ↓
Practice
  ↓
Build
  ↓
Test
  ↓
Review
  ↓
Move Forward
```

A topic is considered genuinely learned when we can demonstrate understanding through explanation, implementation, exercises, or a project.

---

# 🏗️ Project Progression

Our projects will grow with our knowledge.

```text
Python Projects
      ↓
Machine Learning Project
      ↓
Neural Network Project
      ↓
Transformer from Scratch
      ↓
Mini GPT
      ↓
LLM Application
      ↓
RAG System
      ↓
Tool-Using LLM
      ↓
MCP System
      ↓
AI Agent
      ↓
Production AI System
      ↓
Final Capstone
```

---

# 📊 Progress Philosophy

We will measure progress by capability, not lesson count.

The important questions are:

* Can I explain it?
* Can I implement it?
* Can I debug it?
* Can I use it?
* Can I evaluate it?
* Can I build with it?
* Can I deploy it?

---

# 🎯 Current Position

**Goal:** AI Engineer

**Current Stage:** Setup

**Current Phase:** Phase 0 — Setup & Tooling

**Current Lesson:** Not started

**Start Date:** 2026-08-12

**Status:** 🟡 Preparing to Start

---

# 🚀 Long-Term Goal

> **Go from zero to an AI Engineer capable of building, evaluating, and deploying real-world AI systems.**

