# BERT: Pre-training of Deep Bidirectional Transformers for Language Understanding

---

### Core Idea in One Sentence



---

### The Problem

*What specific problem or limitation were the authors trying to solve? What was the state of the art before this paper?*
Two current approaches for downstream tasks:
- feature-based: use task specific architecture, include pre trained representations as features
- GPT: finetune all parameters on downstream tasks

Problem of current approach:
undirectional architecture, eg GPT only attend to previous tokens.(Reason for this design is that transformer are used mainly for next token prediction)
---

### The How

*In bullet points, what are the key components of their proposed solution? Explain them simply, as if you were teaching a colleague.*
Bidirectional Encoder REpresentations from Transformers
- use masked language model, which randomly masks some tokens from input, try to predict the original vocabulary id of the masked word based on context
- 


---

### The Results & Proofs

*What are the 1-3 key graphs, tables, or results that prove their solution works? What metrics did they use? add screenshots if needed*


---

### The Questions 

*What parts are confusing? Do I agree with their assumptions? What are the limitations or potential failure modes?*



---

### The Connections

*How does this relate to other papers I've read? Does it build on, refute, or propose an alternative to a previous idea?*


---

###  The Vocabulary & Concepts

*List and define any new terms learned from this paper.*



---

### The Codes

*Are there any interesting implementation details? Can I link to an official or unofficial implementation? Can I write a small code snippet to demonstrate the core idea?*

  ```python

  ```