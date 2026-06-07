# Security Taxonomy of Large Language Model Vulnerabilities

## Overview
This project presents a structured survey and taxonomy of major security vulnerabilities in Large Language Models (LLMs). We organize the threat landscape into four categories: jailbreaking, prompt injection, data poisoning, and hallucination, and analyze how these vulnerabilities differ and interact across the LLM lifecycle.

## Motivation
LLMs are increasingly used in critical applications, but their vulnerabilities are often studied separately. This project aims to consolidate scattered research into a unified, student-friendly framework for understanding LLM security risks.

## Vulnerability Categories
1. Jailbreaking — inference-time attacks that bypass safety filters.
2. Prompt Injection — attacks where user-controlled text is treated as instructions.
3. Data Poisoning — training-time manipulation of data to embed harmful behavior.
4. Hallucination — confident but false or ungrounded model outputs.

## Unified Framework
We compare vulnerabilities based on:
- Lifecycle stage: training vs inference
- Actor intent: adversarial vs systemic
- Root cause: data integrity, instruction confusion, safety filter weakness, or probabilistic generation
- Primary impact
- Common mitigation strategies

## Key Takeaways
- Jailbreaking and prompt injection both exploit weak separation between trusted instructions and user input.
- Data poisoning can create persistent vulnerabilities before deployment.
- Hallucination weakens reliability even without an adversarial user.
- LLM security needs defense-in-depth across data curation, alignment, input filtering, and factual grounding.

## Deliverables
- Final project report
- Final presentation slides
- Categorized bibliography of reviewed literature

## Authors
Ketki Kulkarni  
Lalitha Sravanti Dasu

## Course Context
Final project for an LLM course, Fall 2025.
