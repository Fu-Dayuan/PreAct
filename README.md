
## PreAct: Prediction Enhances Agent's Planning Ability</h2>

<p>
📃 <a href="https://arxiv.org/abs/2402.11534">ArXiv Paper</a>
</p>


<!-- ⭐ **We will release the templates, and codes after blind review. Thanks for your attention!** -->

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
  title={PreAct: Predicting Future in ReAct Enhances Agent's Planning Ability},
  author={Fu, Dayuan and Huang, Jianzhao and Lu, Siyuan and Dong, Guanting and Wang, Yejie and He, Keqing and Xu, Weiran},
  journal={arXiv preprint arXiv:2402.11534},
  year={2024}
}
```
