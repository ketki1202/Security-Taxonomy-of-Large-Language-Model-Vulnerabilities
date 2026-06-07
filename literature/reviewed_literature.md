# Reviewed Literature

This file lists the key papers reviewed for the project **Security Taxonomy of Large Language Model Vulnerabilities**. The literature is organized around four major categories: jailbreaking, prompt injection, data poisoning, and hallucination.

## 1. Jailbreaking

- Zou, A., Wang, Z., Kolter, J. Z., & Fredrikson, M. (2023). *Universal and Transferable Adversarial Attacks on Aligned Language Models*.
- Perez, E., et al. (2022). *Red Teaming Language Models with Language Models*. EMNLP.
- Chao, P., et al. (2023). *Jailbreaking Black Box Large Language Models in Twenty Queries*. NeurIPS.
- Mehrotra, A., et al. (2023). *Tree of Attacks: Jailbreaking Black-Box LLMs Automatically*.
- Liu, X., et al. (2024). *AutoDAN: Interpretable Gradient-Based Adversarial Attacks on Large Language Models*. USENIX Security Symposium.
- Yuan, Y., et al. (2023). *GPT-4 Is Too Smart To Be Safe: Stealthy Chat with LLMs via Cipher*.
- Lv, H., et al. (2024). *CodeChameleon: Personalized Encryption Framework for Jailbreaking Large Language Models*.
- Zhao, X., et al. (2024). *Weak-to-Strong Jailbreaking on Large Language Models*.
- Shen, X., et al. (2024). *Do Anything Now: Characterizing and Evaluating In-The-Wild Jailbreak Prompts*. ACM CCS.
- Chao, P., et al. (2024). *JailbreakBench: An Open Robustness Benchmark for Jailbreaking Large Language Models*.
- Deng, G., et al. (2023). *Jailbreaking ChatGPT via Prompt Engineering: An Empirical Study*. EMNLP.
- Zeng, Y., et al. (2024). *How Johnny Can Persuade LLMs to Jailbreak Them: Rethinking Persuasion to Challenge AI Safety*. NAACL.
- Wang, X., et al. (2025). *SelfDefend: LLMs Can Defend Themselves against Jailbreaking in a Practical Manner*. USENIX Security Symposium.

## 2. Prompt Injection

- Greshake, K., et al. (2023). *Not What You’ve Signed Up For: Compromising Real-World LLM-Integrated Applications with Indirect Prompt Injection*.
- Wang, et al. (2025). *Compromising Safety via Direct Injection*. USENIX Security Symposium.
- Chen, Y., et al. (2025). *TopicAttack: An Indirect Prompt Injection Attack via Topic Transition*. EMNLP.
- ICLR Conference Paper. (2025). *Can LLMs Separate Instructions From Data?*

## 3. Data Poisoning

- Che, Z., et al. (2024). *Data Poisoning in LLMs: Jailbreak-Tuning and Scaling Laws*.
- Zhang, Y., et al. (2025). *Persistent Pre-Training Poisoning of LLMs*. ICLR.
- Xu, et al. *Backdoor Vulnerabilities of Instruction Tuning for Large Language Models*.
- Cai, et al. *BadPrompt: Backdoor Attacks on Continuous Prompts*.

## 4. Hallucination

- Lin, S., et al. (2022). *TruthfulQA: Measuring How Models Mimic Human Falsehoods*. ACL.
- Manakul, P., et al. (2023). *SelfCheckGPT: Zero-Resource Black-Box Hallucination Detection*. EMNLP.
- Wang, Y., et al. (2024). *Factuality of Large Language Models: A Survey*. EMNLP.
- Lyu, et al. *Faithful Chain-of-Thought Reasoning*.
- Huang, et al. *Understanding and Mitigating Hallucination in LLMs and LVLMs*.

## Summary

The reviewed literature shows that LLM vulnerabilities are not isolated problems. Jailbreaking and prompt injection mainly exploit weaknesses during inference, data poisoning affects the training pipeline, and hallucination reflects deeper reliability and grounding issues. Together, these works motivate the need for a defense-in-depth approach to LLM security.
