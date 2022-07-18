# Multi-step-Deductive-Reasoning-over-Natural-Language
This repository contains the code for the paper "Multi-Step Deductive Reasoning Over Natural Language: An Empirical Study on Out-of-Distribution Generalisation". This paper is the extention work from the poster [From Symbolic Logic Reasoning to Soft Reasoning: A Neural-Symbolic Paradigm](https://www.researchgate.net/publication/356695884_From_Symbolic_Logic_Reasoning_to_Soft_Reasoning_A_Neural-Symbolic_Paradigm). We add details for building the large-scale deeper multi-step reasoning dataset PARARULE-Plus and more experiments by adding the PARARULE-Plus in training. The goal is to build up an end-to-end neural based reasoning engine. The existing neural based models lack a reasoning engine, and they are not end-to-end training process. The repository also incorporates extra code for research as part of future work.

## Dataset
All the current work data is using the [PARARULE](https://allenai.org/data/ruletaker) from Allen AI institute. The dataset has been published on [Transformers as Soft Reasoners over Language](https://arxiv.org/abs/2002.05867), [CONCEPTRULES V1](https://drive.google.com/file/d/1lxoAvtcvqVCYiO8e3tENnrTQ1NNVtpjs/view?usp=sharing) and [CONCEPTRULES V2](https://drive.google.com/file/d/1lOCbW8bfZxj1RIzKDxn8xKg99XyYNj7z/view?usp=sharing) from [Tim Hartill](https://github.com/timhartill) and [PARARULE-Plus](https://github.com/Strong-AI-Lab/PARARULE-Plus).

 ## Citation
```
@InProceedings{
  title={Multi-Step Deductive Reasoning Over Natural Language: An Empirical Study on Out-of-Distribution Generalisation},
  author={Qiming Bao, Alex Peng, Tim Hartill, Neset Tan, Zhenyun Deng, Michael Witbrock, Jiamou Liu},
  year={2022},
  publisher={The 2nd International Joint Conference on Learning & Reasoning and 16th International Workshop on Neural-Symbolic Learning and Reasoning (IJCLR-NeSy 2022)}
}
```
