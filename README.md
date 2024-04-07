# Investigating the performance of Retrieval-Augmented Generation and fine-tuning for the development of AI-driven knowledge-based systems

## Abstract

The development of generative large language models (G-LLM) opened up new opportunities for the development of new types of knowledge-based systems similar to ChatGPT, Bing, or Gemini. Fine-tuning (FN) and Retrieval-Augmented Generation (RAG) are the techniques that can be used to implement domain adaptation for the development of G-LLM-based knowledge systems. In our study, using ROUGE, BLEU, METEOR scores, and cosine similarity, we compare and examine the performance of RAG and FN for the GPT-J-6B, OPT-6.7B, LlaMA, LlaMA-2 language models. Based on measurements shown on different datasets, we demonstrate that RAG-based constructions are more efficient than models produced with FN. We point out that connecting RAG and FN is not trivial, because connecting FN models with RAG can cause a decrease in performance. Furthermore, we outline a simple RAG-based architecture which, on average, outperforms the FN models by 16\% in terms of the ROGUE score, 15\% in the case of the BLEU score, and 53\% based on the cosine similarity. This shows the significant advantage of RAG over FN in terms of hallucination, which is not offset by the fact that the average 8\% better METEOR score of FN models indicates greater creativity compared to RAG.

## Folders

- /corn: Measurement results on the corn data
- /covid: Train and test data and measurement results on COVID-19 test data. In addition, source codes for RAG and fine-tuning.
- /ub: Measurement results on the urban monitoring data

## How to cite

```bibtex
@misc{lakatos2024investigating,
  title={Investigating the performance of Retrieval-Augmented Generation and fine-tuning for the development of AI-driven knowledge-based systems},
  author={Lakatos, Robert and Pollner, Peter and Hajdu, Andras and Joo, Tamas},
  journal={arXiv preprint arXiv:2403.09727},
  year={2024}
}
```
