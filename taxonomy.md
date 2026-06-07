# LLM Vulnerability Taxonomy

| Vulnerability | Stage | Intent | Root Cause | Impact | Mitigation |
|---|---|---|---|---|---|
| Data Poisoning | Training/Fine-tuning | Malicious | Corrupted training data | Backdoors / biased behavior | Data auditing and cleaning |
| Jailbreaking | Inference | Malicious | Weak safety filters | Forbidden content generation | RLHF and red teaming |
| Prompt Injection | Inference | Malicious | No boundary between data and instructions | Unauthorized actions / data leaks | Input filtering and instruction hierarchy |
| Hallucination | Training + Inference | Usually unintentional | Probabilistic generation / weak grounding | Misinformation / loss of reliability | RAG and decoding strategies |
