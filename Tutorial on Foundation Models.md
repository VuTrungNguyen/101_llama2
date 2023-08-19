---
title: Foudation model
author: Bob
source: All citations for this article can be fetched here https://www.youtube.com/watch?v=YzyBSDn3OQU
---

# Foundation models definition
> Models trained on broad data (generally using self-supervision at scale) that can be adapted to a wide range of downstream tasks[^1]
# Training
Using:
1. Self-supervises learning
2. Scale
# Unifying tasks
- Question answering
- Sentiment classification
- Translation
- Coreference resolution
- Parsing
# Potential Harms
- Generate offensive content
- Generate untruthful content
- Enable disinformation/malicious
# Use of foundation models
- Linear probing
  > :notebook:
  > Simple and efficient, model must be very good
- (Full)Fine-tuning
  > :notebook:
  > Best method when we have lots of data, lots of memory
- Prefix-Tuning/Prompt-Tuning (consume less memory than Fine-tuning)
  > :notebook:
  > Good for mid-sized datasets, memory-efficient
- Zero-shot Prompting
  > :notebook:
  > Open ended task (no dataset collection), need to engineer prompts, accuracy can be low
- In-context Learning
  > :notebook:
  > Open ended task (minimal dataset collection), accuracy can be lower than tuning methods
- Chain-of-Thought
# Foundation models
1. BERT
2. RoBERTa
3. GPT-2
4. T5
5. Turing NLG
6. GPT-3

| Organization | Models |
|---|---|
| OpenAI | GPT-3, Codex, DALL-E, CLIP |
| Meta | OPT |
| AI21labs | Jurassic |
| HuggingFace + BigSciece | BLOOM |
| Nvidia + Microsoft | MT-NLG |
| Stability.ai | Stable diffusion |
| BAAI | Wu Dao 2.0 |
| EleutherAI | GPT-NeoX |
| DeepMind | Gopher, Chinchilla |
| Huawei | PanGu-Alpha |
| Naver | HyperCL, OVA |
| Google | PaLM, MUM |
[^1]: ["Introducing the Center for Research on Foundation Models (CRFM)"](https://hai.stanford.edu/news/introducing-center-research-foundation-models-crfm) Stanford HAI. Retrieved 11 June 2022.
