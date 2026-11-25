sindhi-cross-script-rag

Roman-script query to Arabic-script Sindhi document retrieval and question answering.

What is in this repo
A Sindhi Wikipedia corpus and a 303-question test set (Arabic and Roman versions of each question).
Skeleton-BM25: a simple rule-based method that lets BM25 match Roman queries to Arabic-script text.
A RAG study with Qwen2.5-3B-Instruct: hallucination, abstention, verifier, error analysis.

Main result (Recall@5, Roman queries): BM25 0.143, multilingual-e5-base 0.269, Skeleton-BM25 0.902.

Seeds: 42 for the data split, 0, 1, 2 for prompts and noise.

Data

Text from Sindhi Wikipedia (CC BY-SA). Questions and labels by the author; faithfulness labels by two native Sindhi speakers (Cohen's kappa 0.78).

