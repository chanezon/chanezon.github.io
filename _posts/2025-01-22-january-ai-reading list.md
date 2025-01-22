---
layout: post
title:  "A few papers and posts I found interesting to read in December"
---

During the holidays I've read a few AI blog posts and papers. The following are worth a read:
* [Introducing Phi-4: Microsoft’s Newest Small Language Model Specializing in Complex Reasoning](https://techcommunity.microsoft.com/blog/aiplatformblog/introducing-phi-4-microsoft%E2%80%99s-newest-small-language-model-specializing-in-comple/4357090) Details about the Phi4 small language model, that runs on your dev machine and is good at reasoning and logic.
* [OpenAI o3 Breakthrough High Score on ARC-AGI-Pub](https://arcprize.org/blog/oai-o3-pub-breakthrough) Francois Chollet's analysis of OpenAI o3 model results of 87.5% on ARC-AGI benchmark in high compute mode. 
> "o3's core mechanism appears to be natural language program search and execution within token space – at test time, the model searches over the space of possible Chains of Thought (CoTs) describing the steps required to solve the task, in a fashion perhaps not too dissimilar to AlphaZero-style Monte-Carlo tree search."
LLM do program synthesis in natural language with these Chains of Thoughts and take time to evaluate them at inference time before answering. Exciting insight!
* [ARC Prize 2024: Technical Report](https://arcprize.org/media/arc-prize-2024-technical-report.pdf) a paper about the design of the ARC-AGI benchmark.
* [Deliberative Alignment: Reasoning Enables Safer Language Models](https://arxiv.org/abs/2412.16339) The OpenAI paper on Deliberative alignment, an approach used on o1, leveraging the model's reasoning capabilities to make it reason on prompts, answers and the text of it's safety specifications, resulting in higher resitance ot jailbreaks while lowering overrefusal rates.
* [The Unbearable Slowness of Being: Why do we live at 10 bits/s?](https://arxiv.org/abs/2408.10234) a fascinating reflection on the limitations of human brains, where our senses gather data at 10^9 bits/s, but our overall information throughput is only 10 bits/s. Very relevant for the design of human computer interfaces, and as a background for thinking about how humans and AI will interact.
* [Things we learned about LLMs in 2024](https://simonwillison.net/2024/Dec/31/llms-in-2024/) Simon Willison's end of the year summary of what we learned about LLms in 2024, always insightful.



