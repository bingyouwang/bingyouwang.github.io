---
title: "A Pipeline for Optimizing F1-Measure in Multi-Label Text Classification"
collection: publications
permalink: /publication/pipeline
excerpt: 'A pipeline, with carefully regularizing both features during training and label structure during prediction, was proposed to optimize the F1-measure in the text multi-label classification.'
date: 2018-11-19
venue: '17th IEEE International Conference on Machine Learning and Applications, Orlando, FL, USA'
paperurl: 'https://bingyouwang.github.io/files/pipeline.pdf'
---
Bingyu Wang, Cheng Li, Virgil Pavlu, Javed Aslam


Abstract
------
Multi-label text classification is the machine learning task wherein each document is tagged with multiple labels, and this task is uniquely challenging due to high dimensional features and correlated labels. Such text classifiers need to be regularized to prevent severe over-fitting in the high dimensional space, and they also need to take into account label dependencies in order to make accurate predictions under uncertainty. Many classic multi-label learning algorithms focus on incorporating label dependencies in the model training phase and optimize for the strict set-accuracy measure. We propose a new pipeline which takes such algorithms and improves their F1-performance with careful training regularization and a new prediction strategy based on support inference, calibration and GFM, to the point that classic multi-label models are able to outperform recent sophisticated methods (PDsparse, SPEN) and models (LSF, CFT, CLEMS) designed specifically to be multi-label F-optimal. Beyond performance and practical contributions, we further demonstrate that support inference acts as a strong regularizer on the label prediction structure.

Advisor
------
Professor [Javed Aslam](http://www.ccs.neu.edu/home/jaa/)

Advisor's Statement
------
[TODO]

## Acceptance Rate:
* Regular Papers: 31%  
* Short Papers:   14%  
Accepted as a short paper, with 6 pages.   

## Download
------
[[pdf](http://bingyouwang.github.io/files/pipeline.pdf)]

<!-- Recommended citation: Your Name, You. (2015). "Paper Title Number 3." <i>Journal 1</i>. 1(3). -->