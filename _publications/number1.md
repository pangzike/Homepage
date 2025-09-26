---
title: "Generic dependency modeling for multi-party conversation"
collection: publications
permalink: /publication/number1
excerpt: "Weizhou Shen, Xiaojun Quan, **Ke Yang** <br/><img src='/images/research1.png' style=\"width: 500px; height: auto;\" >"
date: 2023/6
venue: 'ICASSP 2023-2023 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)'
paperurl: 'https://ieeexplore.ieee.org/abstract/document/10096003'
---
[paper link](https://ieeexplore.ieee.org/abstract/document/10096003)

<img src="/images/research1.png" style="zoom:50%;" />

To model the dependencies between utterances in multi-party conversations, we propose a simple and generic framework based on the dependency parsing results of utterances. Particularly, we present an approach to encoding the dependencies in the form of relative dependency encoding (ReDE) and illustrate how to implement it in Transformers by modifying the computation of self-attention. Experimental results on four multi-party conversation benchmarks show that this framework successfully boosts the general performance of two Transformer-based language models and leads to comparable or even superior performance compared to the state-of-the-art methods. The code is available at https://github.com/shenwzh3/ReDE.