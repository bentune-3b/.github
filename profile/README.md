<p align="center">
  <img src="bentune.png" alt="BenTune Logo" width="500"/>
</p>

<p align="center">An instruction-tuned LLaMA-3.2B assistant developed at Arizona State University</p>

---

## Overview

BenTune-3B is a lightweight, fine-tuned version of Meta’s LLaMA-3.2B model, optimized for general-purpose instruction following. Developed entirely on ASU’s SOL cluster, this project aims to explore low-latency inference, modular fine-tuning, and evaluation of open-weight LLMs under academic resource constraints.

The model is capable of answering diverse instruction-based prompts ranging from logical reasoning and factual queries to summarization and coding tasks.

---

## Inference Strategies

We tested three key decoding techniques during inference:

- **Forced Chain-of-Thought (CoT)**  
- **Dynamic CoT Triggering**  
- **Self-Consistency Decoding**

Performance varied based on the nature of the prompt. While some reasoning tasks benefited from CoT strategies, others did not show significant improvement. Due to time constraints, we were unable to fully explore these behaviors across all benchmark categories.

---

## UI Interface

...


---

## Example Responses

Here are some sample prompts and corresponding model outputs from BenTune-3B.

> **Prompt:** What are some ethical concerns with deploying autonomous weapons?  
> **Response:** *[Coming soon]*

> **Prompt:** Solve: A train leaves at 3:00 PM traveling at 60 mph...  
> **Response:** *[Coming soon]*

> **Prompt:** Summarize the causes of World War I in under 100 words.  
> **Response:** *[Coming soon]*

---

## ARC Evaluation 

...
---

## Team

- Jaya Adithya Pavuluri  
- Deep Goyal  
- Namita Shah  
- Evan Zhu  
- Navni Athale  

Project developed for CSE 476: Intro to NLP at Arizona State University.

---

## License

TBD
