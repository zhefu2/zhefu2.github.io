---
title: "The Art of Asking: Prompting Large Language Models for Serendipity Recommendations"
collection: publications
category: conferences
permalink: /publication/2024-08-paper-title-number
excerpt: '<b>Zhe Fu</b>, Xi Niu'
date: 2024-08-02
venue: 'Proceedings of the ACM SIGIR International Conference on Theory of Information Retrieval'
paperurl: 'http://zhefu2.github.io.github.io/files/ICTIR2024.pdf'
---
Serendipity means an unexpected but valuable discovery. Its elusive nature makes it susceptible to modeling. In this paper, we address the challenge of modeling serendipity in recommender systems using Large Language Models (LLMs), a recent breakthrough in AI technologies. We leveraged LLMs' prompting mechanisms to convert a problem of serendipity recommendations into a problem of formulating a prompt to elicit serendipity recommendations. The formulated prompt is called SerenPrompt. We designed three types of SerenPrompt: discrete with natural words, continuous with trainable tokens, and hybrid that combines the previous two types. In the meanwhile, for each type of SerenPrompt, we also designed two styles: direct and indirect, to investigate whether it is feasible to directly ask an LLM a question on whether an item is a serendipity, or we should breakdown the question into several sub-questions. Extensive experiments have demonstrated the effectiveness of SerenPrompt in generating serendipity recommendations, compared to the state-of-the-art models. The combination of the hybrid type and the indirect style achieves the best performance, with relatively low sacrifice to computational efficiency. The results demonstrate that natural words and virtual tokens, as building blocks of LLM prompts, each have their own advantages. The better performance of the indirect style speaks to the effectiveness of decomposing the direct question on serendipity.
