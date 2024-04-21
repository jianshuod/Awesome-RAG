<div align="center">
    <h1>Awesome RAG</h1>
    <a href="https://awesome.re"><img src="https://awesome.re/badge.svg"/></a>
</div>

A curated list of must-be-read papers concerning Retrieval-Augmented Generation

# Contents

- [Contents](#contents)
  - [Papers](#papers)
    - [Survey](#survey)
    - [Architecture](#architecture)
    - [Lifespan](#lifespan)
      - [Iterative Retrieval](#iterative-retrieval)
    - [Applications and Datastores](#applications-and-datastores)
      - [Applications](#applications)
    - [Others](#others)

## Papers

### Survey


### Architecture

- **Improving Language Models by Retrieving from Trillions of Tokens**  \
*Sebastian Borgeaud, Arthur Mensch, Jordan Hoffmann, Trevor Cai, Eliza Rutherford, Katie Millican, George van den Driessche, Jean-Baptiste Lespiau, Bogdan Damoc, Aidan Clark, Diego de Las Casas, Aurelia Guy, Jacob Menick, Roman Ring, Tom Hennigan, Saffron Huang, Loren Maggiore, Chris Jones, Albin Cassirer, Andy Brock, Michela Paganini, Geoffrey Irving, Oriol Vinyals, Simon Osindero, Karen Simonyan, Jack W. Rae, Erich Elsen, Laurent Sifre* (DeepMind) \
ICML 2022 – Dec 2021 [[paper](https://arxiv.org/abs/2112.04426)] \
Tag: Intermediate Fusion

### Lifespan

#### Iterative Retrieval

- **Self-RAG: Learning to Retrieve, Generate, and Critique through Self-Reflection** \
*Akari Asai, Zeqiu Wu, Yizhong Wang, Avirup Sil, Hannaneh Hajishirzi* (†University of Washington §Allen Institute for AI ‡
IBM Research AI) \
ICLR 2024, Oral - Oct 2023 [[paper](https://arxiv.org/abs/2310.11511), [code](https://github.com/AkariAsai/self-rag), [website](https://selfrag.github.io/)] \
Tag: RLHF (whether to continue retrieval)

### Applications

#### Applications

- **LeanDojo: Theorem Proving with Retrieval-Augmented Language Models** \
*Kaiyu Yang1
, Aidan M. Swope2
, Alex Gu3
, Rahul Chalamala1
, Peiyang Song4
,
Shixing Yu5
, Saad Godil∗
, Ryan Prenger2
, Anima Anandkumar1,2* (1Caltech, 2NVIDIA, 3MIT, 4UC Santa Barbara, 5UT Austin) \
NeurIPS 2023 (Datasets and Benchmarks Track) - Jun 2023 [[paper](https://arxiv.org/abs/2306.15626), [code](https://github.com/lean-dojo), [website](https://leandojo.org/)] \
Tag: Retrieval-Augmented LLMs for Theorem Proving

- **TOOLLLM: FACILITATING LARGE LANGUAGE MODELS TO MASTER 16000+ REAL-WORLD APIS** \
*Yujia Qin1∗
, Shihao Liang1∗
, Yining Ye1
, Kunlun Zhu1
, Lan Yan1
, Yaxi Lu1
, Yankai Lin3†
,
Xin Cong1
, Xiangru Tang4
, Bill Qian4
, Sihan Zhao1
, Lauren Hong1
, Runchu Tian1
,
Ruobing Xie5
, Jie Zhou5
, Mark Gerstein4
, Dahai Li2,6
, Zhiyuan Liu1†
, Maosong Sun1†* (1Tsinghua University 2ModelBest Inc. 3Renmin University of China
4Yale University 5WeChat AI, Tencent Inc. 6Zhihu Inc.) \
ArXiv - Jul 2023 [[paper](https://arxiv.org/abs/2307.16789), [code](https://github.com/OpenBMB/ToolBench)] \
Tag: Tool Retrieval


### Others