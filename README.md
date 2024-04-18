## Abstract

Unraveling the intricate details of events in natural language necessitates a subtle understanding of temporal dynamics. Despite the adeptness of Large Language Models (LLMs) in discerning patterns and relationships from data, their inherent comprehension of temporal dynamics remains a formidable challenge. This research meticulously explores these intrinsic challenges within LLMs, with a specific emphasis on evaluating the performance of GPT-3.5 and GPT-4 models in the analysis of temporal data. Employing two distinct prompt types, namely Question Answering (QA) format and Textual Entailment (TE) format, our analysis probes into both implicit and explicit events. The findings underscore noteworthy trends, revealing disparities in the performance of GPT-3.5 and GPT-4. Notably, biases toward specific temporal relationships come to light, with GPT-3.5 demonstrating a preference for "AFTER'' in the QA format for both implicit and explicit events, while GPT-4 leans towards "BEFORE''. Furthermore, a consistent pattern surfaces wherein GPT-3.5 tends towards "TRUE'', and GPT-4 exhibits a preference for "FALSE'' in the TE format for both implicit and explicit events. This persistent discrepancy between GPT-3.5 and GPT-4 in handling temporal data highlights the intricate nature of inductive bias in LLMs, suggesting that the evolution of these models may not merely mitigate bias but may introduce new layers of complexity.

<p align="center" width="100%">
    <img  src="https://github.com/SindhuKRao/LLM_temporal_Bias/blob/main/LLM_Temporal_Bias.png?raw=true)"> 
</p>

This is the code repository for arXiv paper: 
[Unveiling Divergent Inductive Biases of LLMs on Temporal Data](https://arxiv.org/abs/2404.01453) . If you use this code for your work, please cite

```
@article{kishore2024unveiling,
  title={Unveiling Divergent Inductive Biases of LLMs on Temporal Data},
  author={Kishore, Sindhu and He, Hangfeng},
  journal={arXiv preprint arXiv:2404.01453},
  year={2024}
}
```

## Installing dependencies
Use virtual environment tools (e.g miniconda) to install packages and run experiments.

python==3.7.10

pip install -r requirements.txt


## Code Organization
The code is organized as follows:
<li>DataPrep_Prompt: It consists of code for data preparation and GPT prompts for both Implicit and Explicit Events in both Question Answering and Textual Entailment format.</li>
<li>Analysis: This shows the results and analysis conducted on the results obtained from the model.</li>



## Export OPENAI API KEY
You need to export your own OpenAI API key before running experiments with [OpenAI API](https://openai.com/product), i.e., export OPENAI_API_KEY=$YOUR_OPENAI_API_KEY

## Dataset
 For our experimentation, we employed datasets such as TimeBank (Pustejovskyet al., 2003), Tempeval (Verhagen et al., 2010),AQUAINT, and TRACIE (Zhou et al., 2021). More details regarding dataset and  preprocessing is available in the paper and the code.



