# CodeGRU: Context-aware Deep Learning with Gated Recurrent Unit for Source Code Modeling

This repository contains the replication pack for our work "CodeGRU: Context-aware Deep Learning with Gated Recurrent Unit for Source Code Modeling"

## Prerequisites
Make sure your system meets the followings requirements
* [Python 3.6+](https://www.python.org/)
* [Tensorflow 1.13.1+](www.tensorflow.org)
* [Keras 2.2.2+](https://keras.io/)


## Reproduction
Download the following files for reproduction.
* [Vectors](https://pan.baidu.com/s/1i6_ITX9EJseW_o7JunCb5g): Project vectors to replicate the results.
* [SavedModels](https://pan.baidu.com/s/1e0wct-SzL3uij5yVv-Mlsw): Trained models to replicate the results.

## Note: 

* Use the *Encoded* (fixed size context) vectores to evaluate GRU models, use *Encoded-VSCL* (Variable size context) to evalute CodeGRU models. Both, *Vectors* and *Saved Models* can be downloaded here ([Vectors](https://pan.baidu.com/s/1i6_ITX9EJseW_o7JunCb5g),[SavedModels](https://pan.baidu.com/s/1e0wct-SzL3uij5yVv-Mlsw)).


## Citation
if you use CodeGRU in academic works, please use the following citation:
```
@article{Hussain2020CodeGRU,
author    = {Yasir Hussain and
            Zhiqiu Huang and
            Yu Zhou and
            Senzhang Wang
            },
title     = {CodeGRU: Context-aware Deep Learning with Gated Recurrent Unit for
            Source Code Modeling},
journal   = {Information and Software Technology},
volume    = {Volume 125, September 2020, 106309},
year      = {2020},
url       = {https://doi.org/10.1016/j.infsof.2020.106309},
eprint    = {http://arxiv.org/abs/1903.00884}
}
```


