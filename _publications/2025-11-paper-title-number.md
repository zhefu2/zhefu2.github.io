---
title: "Fine-tuning LLMs with Cross-Attention-based Weight Decay for Bias Mitigation"
collection: publications
category: conferences
permalink: /publication/2025-11-paper-title-number
excerpt: 'Farsheed Haque, <b>Zhe Fu</b>, Depeng Xu, Shuhan Yuan, Xi Niu'
date: 2025-11-04
venue: 'Findings of the Conference on Empirical Methods in Natural Language Processing'
paperurl: 'http://zhefu2.github.io/files/EMNLP2025.pdf'
---
Large Language Models (LLMs) excel in Natural Language Processing (NLP) tasks but often propagate societal biases from their training data, leading to discriminatory outputs. These biases are amplified by the models’ selfattention mechanisms, which disproportionately emphasize biased correlations with sensitive tokens, like" he" or" she", reflecting the sensitive attributes such as gender and race. To address this issue, we propose a novel finetuning method, called Cross-Attention-based Weight Decay (CrAWD), which modifies the LLM architecture to mitigate bias. CrAWD introduces a cross-attention mechanism between an input sequence and a sensitive token sequence, enabling the model to identify and selectively decay the attention weights of tokens associated with sensitive tokens. This reduces the influence of biased association on the model’s generation while maintaining task performance. Evaluations on real-world datasets demonstrate the effectiveness of our proposed CrAWD method. Notably, our method can handle multiple sensitive attributes by adjusting the sensitive token sequence, and it does not require full knowledge of sensitive tokens presented in the dataset, underscoring CrAWD’s versatility in promoting fair LLMs across various applications.
