# MoE-TLM: A Neuro-Symbolic Routing Architecture for Domain-Specialized Micro-Models

**Author:** Hemanth K  
**Affiliation:** Independent Researcher

---

## Overview

MoE-TLM (Mixture of Experts – Tiny Language Models) is an AI architecture that replaces a single large language model with multiple tiny, domain-specialized language models coordinated through a neuro-symbolic routing system.

This design enables:

- Sparse expert activation (1–3 experts per query)
- CPU-level deployment (no GPU or cloud required)
- Domain-deep specialization instead of generic knowledge
- Multi-expert output fusion
- Short-term conversational memory
- Modular scalability to 100+ experts

---

## Key Idea

Instead of scaling intelligence through size, MoE-TLM achieves efficiency and accuracy through specialization and intelligent routing.

---

## Architecture Highlights

- 10 domain-specific micro language models (3M–8M parameters each)
- Neural router with symbolic confidence logic
- Output fusion engine for multi-expert responses
- Sliding-window conversational memory
- Fallback and failure handling strategy

---

## Paper

Read the full paper here: [MoE-TLM_Paper.pdf](MoE-TLM_Paper.pdf)

---

## Keywords

Mixture of Experts, Tiny Language Models, Neuro-Symbolic AI, Sparse Routing, Domain-Specialized AI, Efficient LLM Architecture

---

## License

This repository contains the original research work by Hemanth K.
