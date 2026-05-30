# Day 1 - LLM Fundamentals

## Overview
Today I studied the fundamentals of Large Language Models (LLMs), which are the foundation of Agentic AI systems. The goal was to understand how LLMs work internally and what their limitations are.

---

## Topics Covered

### 1. Large Language Models (LLMs)
- LLMs are models that generate text by predicting the next token in a sequence.
- They do not “think” or “understand” like humans.
- They work probabilistically based on training data.

---

### 2. How LLMs Work
Flow:
Input Text → Tokenization → Embeddings → Transformer Layers → Output Tokens

---

### 3. Tokens and Tokenization
- Text is broken into smaller units called tokens.
- Tokens can be words or parts of words.
- All LLM operations are based on tokens.

Example:
"Artificial Intelligence" → multiple tokens

---

### 4. Context Window
- The maximum number of tokens an LLM can process at once.
- If exceeded, older information is removed.
- This acts as the model’s short-term memory.

---

### 5. Embeddings
- Text is converted into numerical vectors.
- These vectors represent semantic meaning.
- Similar meanings have closer vector representations.

---

### 6. Prompt Engineering
- The way we instruct LLMs using text.
- Different prompt styles affect output quality.
Types:
- Zero-shot prompting
- Few-shot prompting
- Structured prompting

---

### 7. Fine-tuning vs RAG

| Fine-tuning | RAG |
|------------|-----|
| Model retraining | External knowledge retrieval |
| Expensive | Efficient |
| Static updates | Dynamic updates |

---

### 8. Hallucinations
- LLMs can generate incorrect or made-up information.
- This happens because they predict text, not truth.

---

## Key Concepts Learned

- LLMs are token prediction systems
- Attention helps models focus on important context
- Embeddings represent meaning mathematically
- Context window limits memory
- RAG is preferred for knowledge updates

---

## Practical Observations

- Longer prompts consume more tokens
- Small changes in prompt structure affect output
- LLMs may confidently produce incorrect answers

---

## Conclusion

Day 1 helped me build a strong foundation in understanding how LLMs work internally. This knowledge is essential before moving into Agentic AI systems, where tools, memory, and reasoning are added on top of LLMs.

---

## Status
Day 1 Completed ✅
