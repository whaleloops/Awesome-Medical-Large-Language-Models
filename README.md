# Awesome-Medical-Large-Language-Models [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of popular Foundation Models in Healthcare. Please submit a pull request to contribute :-)
<!-- used non-break hyphen &#x2011; in the last entry of the tables so dates don't break into different lines: https://stackoverflow.com/questions/30308032/markdown-no-break-nobr -->
<!-- for meditron entry, both HF and Github is shown. There is no <br> between Github and Stars as having <br> breaks the HuggingFace entry into separate line and currently seems hard to have nonbreaking property: https://stackoverflow.com/a/44555965/5276428 -->

# Table of Contents
- [Large Language Models](#llms)
- [Large Vision Models](#lvms)
- [Survey Papers + Clinical Studies](#survey-studies)
- [Articles](#articles)

## Large Language Models <a name="llms"></a>
| Title | Institute | Date | Code
| :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------: | :-----------: | :-------------: |
whaleloops/ClinicalMamba
| [ClinicalMamba](https://arxiv.org/abs/2403.05795): A Generative Clinical Language Model on Longitudinal Clinical Notes | University of Massachusetts | 2024-03 | [Github](https://github.com/whaleloops/ClinicalMamba) <br> ![Star](https://img.shields.io/github/stars/whaleloops/ClinicalMamba?style=social&label=Stars)
| [BioMistral](https://arxiv.org/pdf/2402.10373.pdf): A Collection of Open-Source Pretrained Large Language Models for Medical Domains | LIA - Avignon Université, <br> Nantes Université ![citations](https://img.shields.io/badge/dynamic/json?url=https://api.semanticscholar.org/graph/v1/paper/CorpusID:267740180?fields=citationCount&query=%24.citationCount&label=citations) | 2024-02 | [HuggingFace](https://huggingface.co/BioMistral/BioMistral-7B) <br> ![Likes](https://img.shields.io/badge/dynamic/json?url=https://huggingface.co/api/models/BioMistral/BioMistral-7B&query=%24.likes&label=🤗+Likes)
| [AMIE](https://arxiv.org/pdf/2401.05654.pdf): Towards Conversational Diagnostic AI | Google Research, DeepMind <br> ![citations](https://img.shields.io/badge/dynamic/json?url=https://api.semanticscholar.org/graph/v1/paper/CorpusID:266933212?fields=citationCount&query=%24.citationCount&label=citations) | 2024-01 | -
| [MEDITRON-70B](https://arxiv.org/pdf/2311.16079.pdf): Scaling Medical Pretraining for Large Language Models | EPFL Lausanne <br> ![citations](https://img.shields.io/badge/dynamic/json?url=https://api.semanticscholar.org/graph/v1/paper/CorpusID:265456229?fields=citationCount&query=%24.citationCount&label=citations) | 2023-11 | [Hugging🤗](https://huggingface.co/epfl-llm/meditron-70b) <br> [Github](https://github.com/epfLLM/meditron) ![Star](https://img.shields.io/github/stars/epfLLM/meditron?style=social&label=Stars)
| [Radiology-Llama2](https://arxiv.org/pdf/2309.06419.pdf): Best-in-Class Large Language Model for Radiology | University of Georgia <br> ![citations](https://img.shields.io/badge/dynamic/json?url=https://api.semanticscholar.org/graph/v1/paper/CorpusID:261696494?fields=citationCount&query=%24.citationCount&label=citations) | 2023-08 | -
| [CoDoC](https://www.nature.com/articles/s41591-023-02437-x): Enhancing the reliability and accuracy of AI-enabled diagnosis via complementarity-driven deferral to clinicians | DeepMind, Google <br> ![citations](https://img.shields.io/badge/dynamic/json?url=https://api.semanticscholar.org/graph/v1/paper/CorpusID:259939727?fields=citationCount&query=%24.citationCount&label=citations) | 2023-07 | [Github](https://github.com/deepmind/codoc/tree/main) <br> ![Star](https://img.shields.io/github/stars/deepmind/codoc?style=social&label=Stars)
| [Med-PaLM 2](https://arxiv.org/pdf/2305.09617.pdf): Towards Expert-Level Medical Question Answering with Large Language Models | Google <br> ![citations](https://img.shields.io/badge/dynamic/json?url=https://api.semanticscholar.org/graph/v1/paper/CorpusID:258715226?fields=citationCount&query=%24.citationCount&label=citations) | 2023-05 | -
| [Clinical Camel](https://arxiv.org/pdf/2305.12031.pdf): An Open-Source Expert-Level Medical Language Model with Dialogue-Based Knowledge Encoding | Vector Institute, <br> University of Toronto <br> ![citations](https://img.shields.io/badge/dynamic/json?url=https://api.semanticscholar.org/graph/v1/paper/CorpusID:258832351?fields=citationCount&query=%24.citationCount&label=citations) | 2023-05 | [Hugging🤗](https://huggingface.co/wanglab/ClinicalCamel-70B) <br> [Github](https://github.com/bowang-lab/clinical-camel) ![Star](https://img.shields.io/github/stars/bowang-lab/clinical-camel?style=social&label=Stars)
| [MEDALPACA](https://arxiv.org/pdf/2304.08247.pdf) - AN OPEN-SOURCE COLLECTION OF MEDICAL CONVERSATIONAL AI MODELS AND TRAINING DATA | University Hospital Aachen <br> ![citations](https://img.shields.io/badge/dynamic/json?url=https://api.semanticscholar.org/graph/v1/paper/CorpusID:258180068?fields=citationCount&query=%24.citationCount&label=citations) | 2023-04 | [Hugging🤗](https://huggingface.co/medalpaca/medalpaca-7b) <br> [Github](https://github.com/kbressem/medAlpaca) ![Star](https://img.shields.io/github/stars/kbressem/medAlpaca?style=social&label=Stars)
| [PMC-LLaMA](https://arxiv.org/pdf/2304.14454.pdf): Towards Building Open-source Language Models for Medicine | CMIC, Shanghai Jiao Tong University <br> Shanghai AI Laboratory ![citations](https://img.shields.io/badge/dynamic/json?url=https://api.semanticscholar.org/graph/v1/paper/CorpusID:263888272?fields=citationCount&query=%24.citationCount&label=citations) | 2023-04 | [Hugging🤗](https://huggingface.co/chaoyi-wu/PMC_LLAMA_7B) <br> [Github](https://github.com/chaoyi-wu/PMC-LLaMA) ![Star](https://img.shields.io/github/stars/chaoyi-wu/PMC-LLaMA?style=social&label=Stars)
| [ChatDoctor](https://arxiv.org/ftp/arxiv/papers/2303/2303.14070.pdf): A Medical Chat Model Fine-Tuned on a Large Language Model Meta-AI (LLaMA) Using Medical Domain Knowledge |  University of Texas <br> ![citations](https://img.shields.io/badge/dynamic/json?url=https://api.semanticscholar.org/graph/v1/paper/CorpusID:257756992?fields=citationCount&query=%24.citationCount&label=citations) | 2023-03 | [Github](https://github.com/Kent0n-Li/ChatDoctor) ![Star](https://img.shields.io/github/stars/Kent0n-Li/ChatDoctor?style=social&label=Stars)
| [BioMedLM-PubMedGPT](https://crfm.stanford.edu/2022/12/15/biomedlm.html): A purpose-built AI model trained to interpret biomedical language | Stanford CRFM, MosaicML | 2022-12 | [HuggingFace](https://huggingface.co/stanford-crfm/BioMedLM) <br> ![Likes](https://img.shields.io/badge/dynamic/json?url=https://huggingface.co/api/models/stanford-crfm/BioMedLM&query=%24.likes&label=🤗+Likes)
| [Med-PaLM](https://arxiv.org/pdf/2212.13138.pdf): Large Language Models Encode Clinical Knowledge | Google <br> ![citations](https://img.shields.io/badge/dynamic/json?url=https://api.semanticscholar.org/graph/v1/paper/CorpusID:255124952?fields=citationCount&query=%24.citationCount&label=citations) | 2022-12 | [Github](https://github.com/conceptofmind/PaLM) <br> ![Star](https://img.shields.io/github/stars/conceptofmind/PaLM?style=social&label=Stars)
| [ClinicalT5](https://aclanthology.org/2022.findings-emnlp.398.pdf): A Generative Language Model for Clinical Text | University of Oregon, Baidu <br> ![citations](https://img.shields.io/badge/dynamic/json?url=https://api.semanticscholar.org/graph/v1/paper/CorpusID:256631112?fields=citationCount&query=%24.citationCount&label=citations) | 2022-12 | [HuggingFace](https://huggingface.co/luqh/ClinicalT5-large) <br> ![Likes](https://img.shields.io/badge/dynamic/json?url=https://huggingface.co/api/models/luqh/ClinicalT5-large&query=%24.likes&label=🤗+Likes)
| [GatorTron](https://www.nature.com/articles/s41746-022-00742-2): A large language model for electronic health records | University of Florida, NVIDIA <br> ![citations](https://img.shields.io/badge/dynamic/json?url=https://api.semanticscholar.org/graph/v1/paper/CorpusID:255175535?fields=citationCount&query=%24.citationCount&label=citations) | 2022-12 | [HuggingFace](https://huggingface.co/UFNLP/gatortron-base) <br> ![Likes](https://img.shields.io/badge/dynamic/json?url=https://huggingface.co/api/models/UFNLP/gatortron-base&query=%24.likes&label=🤗+Likes)
| [BioGPT](https://aclanthology.org/2020.clinicalnlp-1.17/): Generative Pre-trained Transformer for Biomedical Text Generation and Mining | Microsoft Research <br> ![citations](https://img.shields.io/badge/dynamic/json?url=https://api.semanticscholar.org/graph/v1/paper/CorpusID:252542956?fields=citationCount&query=%24.citationCount&label=citations) | 2022-09 | [HuggingFace](https://huggingface.co/microsoft/biogpt) <br> ![Likes](https://img.shields.io/badge/dynamic/json?url=https://huggingface.co/api/models/microsoft/biogpt&query=%24.likes&label=🤗+Likes)
| [BioBART](https://arxiv.org/pdf/2204.03905.pdf): Pretraining and Evaluation of A Biomedical Generative Language Model | Tsinghua University <br> ![citations](https://img.shields.io/badge/dynamic/json?url=https://api.semanticscholar.org/graph/v1/paper/CorpusID:248069469?fields=citationCount&query=%24.citationCount&label=citations) | 2022-04 | [HuggingFace](https://huggingface.co/GanjinZero/biobart-v2-base) <br> ![Likes](https://img.shields.io/badge/dynamic/json?url=https://huggingface.co/api/models/GanjinZero/biobart-v2-base&query=%24.likes&label=🤗+Likes)
| [KeBioLM](https://aclanthology.org/2021.bionlp-1.20.pdf): Improving Biomedical Pretrained Language Models with Knowledge | Tsinghua, Alibaba <br> ![citations](https://img.shields.io/badge/dynamic/json?url=https://api.semanticscholar.org/graph/v1/paper/CorpusID:233324564?fields=citationCount&query=%24.citationCount&label=citations) | 2021-04 | [Github](https://github.com/GanjinZero/KeBioLM) <br> ![Star](https://img.shields.io/github/stars/GanjinZero/KeBioLM?style=social&label=Stars)
| [Pretrained Language Models for Biomedical and Clinical Tasks: Understanding and Extending the State-of-the-Art](https://aclanthology.org/2020.clinicalnlp-1.17/) | Meta <br> ![citations](https://img.shields.io/badge/dynamic/json?url=https://api.semanticscholar.org/graph/v1/paper/CorpusID:226283910?fields=citationCount&query=%24.citationCount&label=citations) | 2020-11 | [Github](https://github.com/facebookresearch/bio-lm) <br> ![Star](https://img.shields.io/github/stars/facebookresearch/bio-lm?style=social&label=Stars)
| [BioMegatron](https://aclanthology.org/2020.emnlp-main.379.pdf): Larger Biomedical Domain Language Model | NVIDIA <br> ![citations](https://img.shields.io/badge/dynamic/json?url=https://api.semanticscholar.org/graph/v1/paper/CorpusID:222310618?fields=citationCount&query=%24.citationCount&label=citations) | 2020-10 | [HuggingFace](https://huggingface.co/EMBO/BioMegatron345mUncased) <br> ![Likes](https://img.shields.io/badge/dynamic/json?url=https://huggingface.co/api/models/EMBO/BioMegatron345mUncased&query=%24.likes&label=🤗+Likes)
| [PubMedBERT](https://arxiv.org/pdf/2007.15779.pdf): Domain-Specific Language Model Pretraining for Biomedical Natural Language Processing | Microsoft Research <br> ![citations](https://img.shields.io/badge/dynamic/json?url=https://api.semanticscholar.org/graph/v1/paper/CorpusID:220919723?fields=citationCount&query=%24.citationCount&label=citations) | 2020-07 | [HuggingFace](https://huggingface.co/microsoft/BiomedNLP-PubMedBERT-base-uncased-abstract-fulltext) <br> ![Likes](https://img.shields.io/badge/dynamic/json?url=https://huggingface.co/api/models/microsoft/BiomedNLP-PubMedBERT-base-uncased-abstract-fulltext&query=%24.likes&label=🤗+Likes)
| [Publicly Available Clinical BERT Embeddings](https://arxiv.org/pdf/1904.03323.pdf) | MIT CSAIL <br> ![citations](https://img.shields.io/badge/dynamic/json?url=https://api.semanticscholar.org/graph/v1/paper/CorpusID:102352093?fields=citationCount&query=%24.citationCount&label=citations) | 2019-04 | [HuggingFace](https://huggingface.co/emilyalsentzer/Bio_ClinicalBERT) <br> ![Likes](https://img.shields.io/badge/dynamic/json?url=https://huggingface.co/api/models/emilyalsentzer/Bio_ClinicalBERT&query=%24.likes&label=🤗+Likes)
| [ClinicalBERT](https://arxiv.org/pdf/1904.05342.pdf): Modeling Clinical Notes and Predicting Hospital Readmission | Harvard, Princeton, NYU <br> ![citations](https://img.shields.io/badge/dynamic/json?url=https://api.semanticscholar.org/graph/v1/paper/CorpusID:119308351?fields=citationCount&query=%24.citationCount&label=citations) | 2019-04 | [Github](https://github.com/kexinhuang12345/clinicalBERT) <br> ![Star](https://img.shields.io/github/stars/kexinhuang12345/clinicalBERT?style=social&label=Stars)
| [BioBERT](https://arxiv.org/pdf/1901.08746): a pre-trained biomedical language representation model for biomedical text mining | Korea University <br> ![citations](https://img.shields.io/badge/dynamic/json?url=https://api.semanticscholar.org/graph/v1/paper/CorpusID:59291975?fields=citationCount&query=%24.citationCount&label=citations) | 2019&#x2011;01 | [Github](https://github.com/dmis-lab/biobert) <br> ![Star](https://img.shields.io/github/stars/dmis-lab/biobert?style=social&label=Stars)
<!--
| [Paper Name](arxiv link) | Institute Name <br> ![citations](https://img.shields.io/badge/dynamic/json?url=https://api.semanticscholar.org/graph/v1/paper/CorpusID:12345678?fields=citationCount&query=%24.citationCount&label=citations) | 20xx-xx | [HuggingFace](https://github.com) <br> ![Likes](https://img.shields.io/badge/dynamic/json?url=https://huggingface.co/api/models/&query=%24.likes&label=🤗+Likes)
-->
## Large Vision Models <a name="lvms"></a>
| Title | Institute | Date | Code
| :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------: | :-----------: | :---------: |
| [Segment anything model for medical image analysis: An experimental study](https://arxiv.org/pdf/2304.10517) | Duke University <br> ![citations](https://img.shields.io/badge/dynamic/json?url=https://api.semanticscholar.org/graph/v1/paper/CorpusID:258236547?fields=citationCount&query=%24.citationCount&label=citations) | 2023-04 | [Github](https://github.com/mazurowski-lab/segment-anything-medical-evaluation) <br> ![Star](https://img.shields.io/github/stars/mazurowski-lab/segment-anything-medical-evaluation?style=social&label=Stars)
## Survey Papers + Clinical Studies <a name="survey-studies"></a>
| Title | Institute | Date
| :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------: | :-----------: |
| [Opportunities and challenges for ChatGPT and large language models in biomedicine and health](https://academic.oup.com/bib/article/25/1/bbad493/7505071) | NIH <br> ![citations](https://img.shields.io/badge/dynamic/json?url=https://api.semanticscholar.org/graph/v1/paper/CorpusID:259203988?fields=citationCount&query=%24.citationCount&label=citations) | 2024-01
| [Evaluating the Medical Knowledge of Open LLMs - Part 1](https://www.medarc.ai/blog/medarc-llms-eval-part-1) | MedARC <br> ![citations](https://img.shields.io/badge/dynamic/json?url=https://api.semanticscholar.org/graph/v1/paper/CorpusID:12345678?fields=citationCount&query=%24.citationCount&label=citations) | 2024-01
| [A Survey of Large Language Models in Medicine: Principles, Applications, and Challenges](https://arxiv.org/pdf/2311.05112.pdf) | University of Oxford <br> ![citations](https://img.shields.io/badge/dynamic/json?url=https://api.semanticscholar.org/graph/v1/paper/CorpusID:266163487?fields=citationCount&query=%24.citationCount&label=citations) | 2023-11
| [Exploring the Boundaries of GPT-4 in Radiology](https://arxiv.org/pdf/2310.14573.pdf) | Microsoft, Harvard University <br> ![citations](https://img.shields.io/badge/dynamic/json?url=https://api.semanticscholar.org/graph/v1/paper/CorpusID:264425949?fields=citationCount&query=%24.citationCount&label=citations) | 2023-10
| [A Survey of Large Language Models for Healthcare: from Data, Technology, and Applications to Accountability and Ethics](https://arxiv.org/pdf/2310.05694.pdf) | IEEE members <br> ![citations](https://img.shields.io/badge/dynamic/json?url=https://api.semanticscholar.org/graph/v1/paper/CorpusID:263829396?fields=citationCount&query=%24.citationCount&label=citations) | 2023-10
| [Capabilities of GPT-4 on Medical Challenge Problems](https://arxiv.org/pdf/2303.13375.pdf) | Microsoft, OpenAI <br> ![citations](https://img.shields.io/badge/dynamic/json?url=https://api.semanticscholar.org/graph/v1/paper/CorpusID:257687695?fields=citationCount&query=%24.citationCount&label=citations) | 2023-03
| [Do We Still Need Clinical Language Models?](https://arxiv.org/pdf/2302.08091) | MIT, Xyla <br> ![citations](https://img.shields.io/badge/dynamic/json?url=https://api.semanticscholar.org/graph/v1/paper/CorpusID:256900662?fields=citationCount&query=%24.citationCount&label=citations) | 2023-02
## Articles <a name="articles"></a>
| Title | Institute | Date
| :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :------------------: | :-----------: |
| [The future landscape of large language models in medicine](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10564921/) | TUD Dresden <br> ![citations](https://img.shields.io/badge/dynamic/json?url=https://api.semanticscholar.org/graph/v1/paper/CorpusID:263827375?fields=citationCount&query=%24.citationCount&label=citations) | 2023-10
<!--
| [Paper Name](arxiv link) | Institute Name <br> ![citations](https://img.shields.io/badge/dynamic/json?url=https://api.semanticscholar.org/graph/v1/paper/CorpusID:12345678?fields=citationCount&query=%24.citationCount&label=citations) | 20xx-xx
-->
