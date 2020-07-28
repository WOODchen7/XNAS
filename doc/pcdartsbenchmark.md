# Benchmark

## Introduction

This file documents a collection of baselines searched neural architectures on different search spaces and datasets. On cifar10, the network is trained by using the default training set of [pt.darts](https://github.com/zhengxiawu/pytorch_cls/tree/master/pytorch-cifar-v2).

We reimplement several widely used NAS methods including:

* pcDarts

### Results on CIFAR10

| Method       | Seed | params(M) | search(hrs) | train(hrs) |  Top1  |
| ------------ | :--: | :-------: | :---------: | :--------: | :----: |
| xnas-pcdarts |  1   |     -     |    3.46     |     -      | 86.012 |
| xnas-pcdarts |  2   |     -     |    2.93     |     -      | 85.72  |
| xnas-pcdarts |  3   |     -     |    3.41     |     -      | 85.488 |
| xnas-pcdarts |  4   |     -     |    3.48     |     -      | 85.476 |
| pcdarts      |  1   |   4.052   |    3.61     |   41.28    | 85.296 |
| pcdarts      |  2   |   3.247   |     3.6     |   27.96    | 84.552 |
| pcdarts      |  3   |   4.368   |    3.63     |   38.68    | 84.792 |
| pcdarts      |  4   |   4.148   |    3.16     |   34.58    | 85.280 |
