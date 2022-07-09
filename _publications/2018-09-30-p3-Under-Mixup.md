---
title: "3 Understanding mixup training methods"
collection: publications
permalink: /publication/2018-09-30-p3-Under-Mixup
# excerpt: '---.'
#date: 2018-09-30
venue: 'Journal 3'
paperurl: 'http://liangdaojun.github.io/files/p3-Under-Mixup.pdf'
citation: 'Liang, Daojun, et al. "Understanding mixup training methods." IEEE Access 6 (2018): 58774-58783.'

---

[Download](http://liangdaojun.github.io/files/p3-Under-Mixup.pdf)
[Code](https://github.com/liangdaojun/spatial-mixup)
[Citation](http://liangdaojun.github.io/files/c3-Under-Mixup.bib)

**Abstract**
Mixup is a neural network training method that generates new samples by linear interpolation of multiple samples and their labels. The mixup training method has better generalization ability than the traditional empirical risk minimization method (ERM). But there is a lack of a more intuitive understanding of why mixup will perform better. In this paper, several different sample mixing methods are used to test how neural networks learn and infer from mixed samples to illustrate how mixups work as a data augmentation method and how it regularizes neural networks. Then, a method of weighting noise perturbation was designed to visualize the loss functions of mixup and ERM training methods to analyze the properties of their high-dimensional decision surfaces. Finally, by analyzing the mixture of samples and their labels, a spatial mixup approach was proposed that achieved the state-of-the-art performance on the CIFAR and ImageNet data sets. This method also enables the generative adversarial nets to have more stable training process and more diverse sample generation ability.