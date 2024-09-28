# TuringQ: Evaluating the Reasoning Capabilities of Large Language Models in the Theory of Computation

![Copy of Rising Stars (26)](https://github.com/user-attachments/assets/cdae5eb0-1e95-44cb-9e8b-f835a4fefeaf)

## Abstract
We present TuringQ, to the best of our knowledge, the first effort to evaluate the reasoning capabilities of large language models (LLMs) in the theory of computation. TuringQ consists of 4,006 question-answer pairs spanning undergraduate and graduate-level problems collected from a diverse set of universities. It covers three difficulty levels and six main concepts, including a valuable subset of axioms and essential theoretical concepts. We evaluated various open-source LLMs and GPT-4 using Chain of Thought prompting and human expert assessment. Additionally, we explored an automated LLM-Judge, demonstrating its potential to compete with human precision. We show that fine-tuning an LLaMA3-8B model on TuringQ improves its reasoning ability. TuringQ serves as both a benchmark and a fine-tuning resource for enhancing LLM reasoning in this complex domain. Our comparative analysis reveals insights into LLM performance, contributing to advancements in AI comprehension of theoretical computer science.

## Introduction
The reasoning and comprehension capabilities of large language models across complex domains are crucial due to their recent vast number of applications. As LLMs grow in capability, robust benchmarks are needed to accurately assess their performance, especially in domains requiring deep understanding and logical reasoning. While efforts have introduced multi-task benchmarks across various domains, a dedicated dataset to assess LLM performance on theoretical concepts and problems in the theory of computation has been notably absent. Assessing comprehension in formal languages is particularly important to understand the depth of LLMs' reasoning abilities. This can be a significant step toward developing LLMs into effective problem solvers in complex domains.

TuringQ provides a robust platform to rigorously assess and compare the reasoning capabilities of different LLMs on complex theoretical domains, driving advancements in enhancing their skills for tackling intricate computational concepts and contributing to the development of more capable and reliable AI systems. Moreover, a strong grasp of theory of computation principles is crucial for LLMs as these foundational concepts underpin modern computing systems. Enhancing LLM comprehension in this domain can unlock their potential for reasoning about computational problems, analyzing algorithms, and potentially contributing to the development of new computational models and methodologies.

## Contributions
Our contributions are threefold:
1. **TuringQ Dataset**: We introduce a new resource of 4,006 theory of computation question-answer pairs from universities worldwide. This dataset spans undergraduate and graduate-level concepts across three difficulty levels and seven main areas, including a subset focused on theoretical essentials. It serves as a comprehensive tool for evaluating and fine-tuning LLMs in this domain.
2. **LLM-based Evaluation**: We explore the feasibility of leveraging LLMs themselves as evaluators for TuringQ. By defining an Autograde-TuringQ prompt using Llama-3-8B, we investigate the potential for automating the evaluation process, thereby reducing the time and cost associated with manual grading.
3. **Llama3-8B-ft-TuringQ Model**: We fine-tuned a large language model on the TuringQ dataset, creating Llama3-8B-ft-TuringQ, a model specialized for theory of computation reasoning. Through comprehensive evaluation using custom metrics, we provide a comparative analysis of LLM performance across different TuringQ categories, shedding light on their ability to tackle complex queries relative to human performance.
