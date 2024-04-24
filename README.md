# NLGraph - Can Language Models Solve Graph Problems in Natural Language?  
This project and implementation is based on the following NeurIPS 2023 paper:
- Wang, Heng, et al. Can Language Models Solve Graph Problems in Natural Language? arXiv:2305.10037, arXiv, 5 Jan. 2023. arXiv.org, http://arxiv.org/abs/2305.10037.
- https://neurips.cc/virtual/2023/poster/71520#:~:text=LLMs%20do%20possess%20preliminary%20graph,%2C%20cycle%2C%20and%20shortest%20path.


## Abstract  
This repository explores the potential of Large Language Models (LLMs) to solve graph-based problems in natural language, implmenting Wang et al.'s study "Can Language Models Solve Graph Problems in Natural Language?". Our work utilizes the NLGraph benchmark, which offers a diverse set of graph reasoning tasks across varying complexity levels. We implement advanced prompting techniques, such as Build-a-Graph Prompting and Algorithmic Prompting, to enhance LLMs' problem-solving capabilities. This project aims to demonstrate the practicality and limitations of LLMs in graph-theoretical problem-solving. This repository includes our code, results, and an in-depth analysis of LLM performance on the NLGraph benchmark.

## Report  
The NLGraph_Report.ipynb file contains the paper review along with more detailed implementation details.  

## Setup to Reproduce Implementation  

First install all the necessary libraries & dependencies needed to run the project.  
```
!conda env create -n NLGraph -f environment.yml 
```

Set your openai key `OEPNAI_API_KEY`:
```
$env:OPENAI_API_KEY="your openai key" # for Windows powershell
export OPENAI_API_KEY="your openai key" # for Linux
```

























### Citation
```
@inproceedings{
wang2023can,
title={Can Language Models Solve Graph Problems in Natural Language?},
author={Heng Wang and Shangbin Feng and Tianxing He and Zhaoxuan Tan and Xiaochuang Han and Yulia Tsvetkov},
booktitle={Thirty-seventh Conference on Neural Information Processing Systems},
year={2023},
url={https://openreview.net/forum?id=UDqHhbqYJV}
}
```
