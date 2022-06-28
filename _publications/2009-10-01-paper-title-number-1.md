---
title: "Chaotic continual learning"
collection: publications
date: 2020-06-14
venue: 'ICML workshop of life long learning'
paperurl: 'https://openreview.net/pdf?id=dRQRGjf2L3-'
---

'Training a deep neural network requires the model to go over training data for several epochs and update network parameters. In continual learning, this process results in catastrophic forgetting which is one of the core issues of this domain. Most proposed approaches for this issue try to compensate for the effects of parameter updates in the batch incremental setup in which the training model visits a lot of samples for several epochs. However, it is not realistic to expect training data will always be fed to model in a batch incremental setup. This paper proposes a chaotic stream learner that mimics the chaotic behavior of biological neurons and does not updates network parameters. In addition, it can work with fewer samples compared to deep learning models on stream learning setup. Our experiments on MNIST, CIFAR10, and Omniglot show that the chaotic stream learner has less catastrophic forgetting by its nature in comparison to a CNN model in continual learning.'
