# NLGraph - Can Language Models Solve Graph Problems in Natural Language?  
This project and implementation is based on the following paper:
- Wang, Heng, et al. Can Language Models Solve Graph Problems in Natural Language? arXiv:2305.10037, arXiv, 5 Jan. 2023. arXiv.org, [http://arxiv.org/abs/2305.10037.](https://arxiv.org/abs/2305.10037)

## Report  
The NLGraph_Report.ipynb file contains the paper review along with more detailed implementation details.  

## Steps to Reproduce Implementation  

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
