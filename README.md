
## PreAct: Prediction Enhances Agent's Planning Ability</h2>


<div align="center">
<a><img alt="Static Badge" src="https://img.shields.io/badge/made_with-Python-blue"></a>
  <a href="https://arxiv.org/pdf/2402.11534" target="_blank"><img src=https://img.shields.io/badge/arXiv-b5212f.svg?logo=arxiv></a>
  <a href="https://github.com/dongguanting/IF-RAG/blob/main/LICENSE"><img alt="License" src="https://img.shields.io/badge/LICENSE-MIT-green"></a>
</div>

## 💥 News
- [10/2024] 🔥 Our paper has been accepted by **COLING 2025**. 

- [10/2024] 🔥 We release the code for inference HotpotQA task. You can inference PreAct+TOT here. 

- [10/2024] 🔥 We released our instruction-following auto-evaluation benchmark named ***FollowRAG***. Please follow [outlines](#FollowRAG) for evaluation.

- [10/2024] 🔥 We introduced ***PreAct***. Check out the [paper](https://arxiv.org/pdf/2402.11534). 

---



## Introduction
Addressing the disparity between forecasts and actual results can enable individuals to expand their thought processes and stimulate self-reflection, thus promoting accurate planning.
In this research, we present **PreAct**, an agent framework that integrates **pre**diction, **rea**soning, and **act**ion. By utilizing the information derived from predictions, the large language model (LLM) agent can provide a wider range and more strategically focused reasoning. This leads to more efficient actions that aid the agent in accomplishing intricate tasks. Our experimental results show that PreAct surpasses the ReAct method in completing complex tasks and that PreAct's performance can be further improved when paired with other memory or selection strategy techniques. We presented the model with varying quantities of historical predictions and discovered that these predictions consistently enhance LLM planning.
The variances in single-step reasoning between PreAct and ReAct indicate that PreAct indeed has benefits in terms of diversity and strategic orientation over ReAct.

## PreAct with TOT

We use [LanguageAgentTreeSearch](https://github.com/lapisrocks/LanguageAgentTreeSearch) to run the HotpotQA task. We release the code for inference. You can inference PreAct+TOT with the following commands:

```bash 
  cd LanguageAgentTreeSearch/hotpot
  bash tot.sh
```

⭐ **We will also provide the AgentBench experiment code soon! Thanks for waiting!**

## Citation
Please kindly cite our paper if it helps your research:
```bibtex
@article{fu2024preact,
  author       = {Dayuan Fu and
                  Jianzhao Huang and
                  Siyuan Lu and
                  Guanting Dong and
                  Yejie Wang and
                  Keqing He and
                  Weiran Xu},
  title        = {PreAct: Predicting Future in ReAct Enhances Agent's Planning Ability},
  journal      = {CoRR},
  volume       = {abs/2402.11534},
  year         = {2024},
  url          = {https://doi.org/10.48550/arXiv.2402.11534},
  doi          = {10.48550/ARXIV.2402.11534},
  eprinttype    = {arXiv},
  eprint       = {2402.11534},
  timestamp    = {Wed, 19 Jun 2024 17:14:13 +0200},
  biburl       = {https://dblp.org/rec/journals/corr/abs-2402-11534.bib},
  bibsource    = {dblp computer science bibliography, https://dblp.org}
}
```
