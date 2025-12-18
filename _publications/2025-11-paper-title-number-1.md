---
title: "Fine-tuning LLMs with Cross-Attention-based Weight Decay for Bias Mitigation"
collection: publications
category: manuscripts
permalink: /publication/2025-11-paper-title-number-1
excerpt: 'Large Language Models (LLMs) excel in Natural Language Processing (NLP) tasks but often propagate societal biases from their training data, leading to discriminatory outputs. These biases are amplified by the models’ selfattention mechanisms, which disproportionately emphasize biased correlations with sensitive tokens, like" he" or" she", reflecting the sensitive attributes such as gender and race. To address this issue, we propose a novel finetuning method, called Cross-Attention-based Weight Decay (CrAWD), which modifies the LLM architecture to mitigate bias. CrAWD introduces a cross-attention mechanism between an input sequence and a sensitive token sequence, enabling the model to identify and selectively decay the attention weights of tokens associated with sensitive tokens. This reduces the influence of biased association on the model’s generation while maintaining task performance. Evaluations on real-world datasets demonstrate the effectiveness of our proposed CrAWD method. Notably, our method can handle multiple sensitive attributes by adjusting the sensitive token sequence, and it does not require full knowledge of sensitive tokens presented in the dataset, underscoring CrAWD’s versatility in promoting fair LLMs across various applications.'
date: 2025-11-04
venue: 'Findings of the Conference on Empirical Methods in Natural Language Processing'
slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'http://academicpages.github.io/files/paper1.pdf'
bibtexurl: 'http://academicpages.github.io/files/bibtex1.bib'
citation: 'Farsheed, H., Fu, Z., Xu, D., Yuan, S., and Niu, X. (2025). &quot;Fine-tuning LLMs with Cross-Attention-based Weight Decay for Bias Mitigation.&quot; In <i> Findings of the 2025 Conference on Empirical Methods in Natural Language Processing </i>. 15785-15798. November 4-9, 2025, Suzhou, China.'
---
The contents above will be part of a list of publications, if the user clicks the link for the publication than the contents of section will be rendered as a full page, allowing you to provide more information about the paper for the reader. When publications are displayed as a single page, the contents of the above "citation" field will automatically be included below this section in a smaller font.
