# Prompt

## Articles

1. [Lilian-Weng on prompt engineering](https://lilianweng.github.io/posts/2023-03-15-prompt-engineering/) - this is a very thorough review of the topic

## Papers

### Prompt Engineering

1. [Large Language Models Are Human-Level Prompt Engineers](https://arxiv.org/abs/2211.01910) - optimizing over a set of candidate that were proposed by an LLM in order to maximize a score function. contributes to improvement of responses.
2. [Demystifying Prompts in Language Models via Perplexity](https://arxiv.org/pdf/2212.04037.pdf) - given the variability of the quality of results, how do we pick the best prompts automatically? using GPT3 and back translation to choose the lowest perplexity prompts that give the most gain in performance.
3. [SituatedQA Incorporating linguistic context into Question Answering](https://situatedqa.github.io/)

### Prompt Tuning

1. [The power of scale for parameter efficient prompt tuning](https://arxiv.org/abs/2104.08691) **-** it becomes more competitive at scale.

### Chain Of Thought

1.  [Chain Of Thought](https://arxiv.org/pdf/2201.11903.pdf) Prompting Elicits Reasoning in Large Language Models - COT is a series of intermediate reasoning steps that significantly improves the ability of large language models to perform complex reasoning, by Jason Wei Xuezhi Wang Dale Schuurmans Maarten Bosma Brian Ichter Fei Xia Ed H. Chi Quoc V. Le Denny Zhou Google Research, Brain Team.

    <figure><img src="../.gitbook/assets/image.png" alt=""><figcaption><p>COT, Google brain.</p></figcaption></figure>
2. [self consistency improve chain of though reasoning in language models](https://arxiv.org/abs/2203.11171) - "samples a diverse set of reasoning paths instead of only taking the greedy one, and then selects the most consistent answer by marginalizing out the sampled reasoning paths"
