# Deep AUC Maximization  [![pdf](https://img.shields.io/badge/Arxiv-pdf-orange.svg?style=flat)](https://arxiv.org/abs/1908.10831)

This is the implementation of paper "**Stochastic AUC Maximization with Deep Neural Networks**" published on **ICLR2020**. 

## Installation
```
Python=3.5
Numpy=1.18.5 
Scipy=1.2.1
Scikit-Learn=0.20.3
Pillow=5.0.0
Tensorflow>=1.10.0
```

### Run
```
python PPD_SG.py --dataset=10 --train_batch_size=128 --use_L2=False --split_index=4 --lr=0.01 --keep_index=0.1 --t0=200
```
or 
```
python PPD_AdaGrad.py --dataset=10 --train_batch_size=128 --use_L2=False --split_index=4 --lr=0.01 --keep_index=0.1 --t0=200

```

## Bibtex 
If you use this repository  in your work, please cite our paper:

```
@inproceedings{
Liu2020Stochastic,
title={Stochastic AUC Maximization with Deep Neural Networks},
author={Mingrui Liu and Zhuoning Yuan and Yiming Ying and Tianbao Yang},
booktitle={International Conference on Learning Representations},
year={2020},
url={https://openreview.net/forum?id=HJepXaVYDr}
}
```

## Explanation for the Forked File:
This forked repository contains files modified from the original repository to be compatible with running Tensorflow 2.0. The modification is reserved by pkan2. 

