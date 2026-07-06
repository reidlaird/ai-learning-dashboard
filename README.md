# 🧠 AI Knowledge Library

**Live library → https://reidlaird.github.io/ai-learning-dashboard/**

A digital library of curated AI knowledge — distilled notes, visual explainers, and hand-picked resources, growing from machine learning fundamentals out across the AI umbrella.

## What's inside

| Shelf | Contents |
|---|---|
| ML Fundamentals | Distilled notes from [Introduction to machine learning concepts](https://learn.microsoft.com/en-us/training/modules/fundamentals-machine-learning/) (Microsoft Learn) — models, training vs inference, regression, classification, clustering, overfitting & validation |
| Deep Learning | Classical ML vs DL pipelines, neural net anatomy, activation functions, animated gradient descent, key architectures |
| Computer Vision | Images as numbers (pixel grid), animated convolution filter, vision tasks side-by-side, transformers & multimodal models |
| NLP & LLMs | Where LLMs sit in the AI umbrella (territory-map diagram), the AI-you-don't-see iceberg, tokenization→embedding pipeline, tokens up close (text vs code vs numbers), the animated token-by-token inference loop, attention visual, context windows, hallucination & grounding |
| Speech & Docs | Speech recognition & synthesis pipelines (animated), prosody, OCR, information extraction from documents |
| Agents & RAG | Animated agent loop, full RAG pipeline diagram, how coding agents spend tokens (context-budget visual), embeddings & vector search, the prompt→RAG→fine-tune sequence |
| Prompting & Fine-tuning | Prompt anatomy diagram, temperature & sampling visual, LoRA & distillation |
| Reinforcement Learning | The agent↔environment loop (animated), key algorithms, RLHF |
| Responsible AI & MLOps | Six responsible AI principles; ML lifecycle loop with drift-retrain cycle |
| Open & Local Models | Open weights vs closed, SLMs, Ollama, Foundry Local, quantization memory chart |
| AI History | 75-year timeline from Turing to agents |
| Glossary | 61 terms, A–Z, filterable |
| Flashcards | 40-card spaced-repetition deck covering every shelf |

## Design

2026-refresh: Pantone Cloud Dancer light theme with a warm dark mode (default) — toggle via the ☀️/🌙 button, remembered per browser. Single self-contained HTML file, no dependencies; all 31 diagrams are inline SVG, several CSS-animated (gradient descent, sliding convolution, agent loop, flowing pipelines). Animations respect the OS reduced-motion setting. To update: edit `index.html` and commit. `ai-learning-dashboard.html` is now just a redirect to `index.html`.
