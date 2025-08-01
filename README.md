# Wekeza LLM v4 – Constitutional Alignment

This repository contains the code, dataset, and workflow for aligning the Wekeza LLM (v4) with a set of principled, Kenya-specific financial rules using methods inspired by the paper **[Constitutional AI: Harmlessness from AI Feedback](https://arxiv.org/pdf/2212.08073.pdf)** by Bai et al., 2022.

Wekeza LLM is a domain-specific language model built to serve as a responsible financial assistant for the Kenyan market. This version (v4) builds on the base model `distilgpt2-wekeza-finetuned_v3_lora` and applies **self-critique and self-revision techniques** using a hand-crafted **Kenyan finance constitution**.

---

## 📌 Key Features

- 📜 **Kenyan Financial Constitution:** Rules to ensure safe and accurate investment advice (e.g., avoid unregulated funds, warn about risks, etc.)
- 🔁 **Self-Improving Dataset:** Automatically generated critiques and revised outputs using the base LLM and constitution prompts
- 🧠 **Constitutional Fine-Tuning:** Model is fine-tuned on the curated revised outputs to encourage safe, transparent, and accurate responses
- 🧪 **Ready for RLAIF:** Structured to allow follow-up training with Reinforcement Learning from AI Feedback

---
