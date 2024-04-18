This is the code repository for NAACL paper: 
<!--[Unveiling Divergent Inductive Biases of LLMs on Temporal Data](https://openreview.net/pdf?id=i9zND2j9se2) .
-->
If you use this code for your work, please cite
<!--
```
@article{skishore2024temporalbias,
  title={Unveiling Divergent Inductive Biases of LLMs on Temporal Data},
  author={Kishore, Sindhu and He, Hangfeng},
  journal={},
  year={2024}
}
```
-->
## Installing dependencies
Use virtual environment tools (e.g miniconda) to install packages and run experiments.

python==3.7.10

pip install -r requirements.txt


## Code Organization
The code is organized as follows:
DataPrep_Prompt: It consists of code for data preparation and GPT prompts for both Implicit and Explicit Events in both Question Answering and Textual Entailment format.
Analysis: This shows the results and analysis conducted on the results obtained from the model.



## Export OPENAI API KEY
You need to export your own OpenAI API key before running experiments with [OpenAI API](https://openai.com/product), i.e., export OPENAI_API_KEY=$YOUR_OPENAI_API_KEY

## Dataset
 For our experimentation, we employed datasets such as TimeBank (Pustejovskyet al., 2003), Tempeval (Verhagen et al., 2010),AQUAINT, and TRACIE (Zhou et al., 2021). More details regarding dataset and  preprocessing is available in the paper and the code.

 ![alt text](https://github.com/SindhuKRao/LLM_temporal_Bias/blob/main/image.jpg?raw=true)

