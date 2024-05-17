# Master thesis
Repo for my master thesis on the topic of exploration of translation and reasoning abilities of LLMs in the low-resource Saris dialect.
The goal of this thesis is to establish first Saris dataset ever, together with evaluation of two NLP tasks - translation and common sence reasoning.
For translation we used the GPT-4 model and fine-tuned the NLLB model as well. For the CSR task, we manually translated COPA dataset to Saris and tested the GPT-4 model on it.

The current version of this thesis can be seen [here](https://github.com/vikion/kivi.github.io/blob/main/main.pdf).



## TO-DO

January
- study the papers and check other similiar datasets on Huggingface

February
- Gather the data for SarisSet -> 4000 sentences
- manually translate 500 sentences to form a golden set

March
  - Try GPT-3.5-Turbo and GPT-4 on translation
  - fine-tune NLLB model on SarisSet
  - manually evaluate the results on a sample of 100 sentences, 

April
- Translate the XCOPA to Saris and Slovak with the help of annotators
- evaluate the results
- SVK and VarDial papers

May
- presentation for Project Seminar
- Skeleton of the master thesis
- Github for MT

2024/2025
- study of the remaining papers (Bonan)
- study of the Saris dialect to be part of the final MT
- try NLLB from Saris to other languages (English, German, etc)
- NLLB to Saris from other languages basides Slovak
- more data, fine-tune more models like mT5
- different approaches of fine-tuning the model,
- complex analysis of the results,try to identify general flaws with the translation to/from dialect


## Literature
[Ebing, Benedikt, and Goran Glavaš. "To Translate or Not to Translate: A Systematic Investigation of Translation-Based Cross-Lingual Transfer to Low-Resource Languages." arXiv preprint arXiv:2311.09404 (2023).](https://arxiv.org/pdf/2311.09404)

[Tars, Maali, Andre Tättar, and Mark Fišel. "Extremely low-resource machine translation for closely related languages." arXiv preprint arXiv:2105.13065 (2021).](https://aclanthology.org/2021.nodalida-main.5.pdf)

[Min, Bonan, et al. "Recent advances in natural language processing via large pre-trained language models: A survey." ACM Computing Surveys 56.2 (2023): 1-40.](https://arxiv.org/pdf/2111.01243)

