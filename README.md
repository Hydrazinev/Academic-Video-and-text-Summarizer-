🧠 GAI for Education: Smarter Summaries for Smarter Students
🚀 TL;DR
i built an AI-powered system that synthesizes concise, high-quality summaries of video lectures and associated reading materials using LLMs + Retrieval-Augmented Generation (RAG). Why? Because students shouldn’t have to waste hours on content they could understand in minutes.

💡 The Problem
There's too much content, and students have too little time (or patience). Educational videos and materials are great—but the sheer volume overwhelms learners. Existing summarizers mostly suck at coherence, context, or combining sources.

🔍 What Makes it Different?
Unlike traditional methods that summarize each content type separately, we:

Use reading material as a contextual knowledge base

Summarize video content in context of the readings

Leverage RAG + LLMs to refine and enrich summaries

🧪 Tech Stack
🧠 LLMs: GPT-3.5, GPT-4, LLaMA-2

🧩 Framework: RAG (Retrieval-Augmented Generation)

📚 Dataset: EDUVSUM (98 educational videos w/ subtitles & annotations)

🧪 Evaluation: Human surveys, G-Eval, BERTScore, ROUGE

📈 Results & Findings
🥇 Pegasus led early benchmarks in ROUGE/BERTScore.

✅ GPT-3.5 + Reading Context > GPT-3.5 alone

🔥 RAG + Few-Shot LLM > Zero-Shot methods

⚖️ G-Eval shows promise but is sensitive to prompt design
