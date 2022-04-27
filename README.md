# DnnAttack: One pixel attack
One pixel attack for a Deep Neural Network

* Paper
   * [One pixel attack for fooling deep neural networks](https://arxiv.org/abs/1710.08864)
   * **Abstract**: Recent research has revealed that the output of Deep Neural Networks (DNN) can be easily altered by adding relatively small perturbations to the input vector. In this paper, we analyze an attack in an extremely limited scenario where only one pixel can be modified. For that we propose a novel method for generating one-pixel adversarial perturbations based on differential evolution (DE). It requires less adversarial information (a black-box attack) and can fool more types of networks due to the inherent features of DE. The results show that 67.97% of the natural images in Kaggle CIFAR-10 test dataset and 16.04% of the ImageNet (ILSVRC 2012) test images can be perturbed to at least one target class by modifying just one pixel with 74.03% and 22.91% confidence on average. We also show the same vulnerability on the original CIFAR-10 dataset. Thus, the proposed attack explores a different take on adversarial machine learning in an extreme limited scenario, showing that current DNNs are also vulnerable to such low dimension attacks. Besides, we also illustrate an important application of DE (or broadly speaking, evolutionary computation) in the domain of adversarial machine learning: creating tools that can effectively generate low-cost adversarial attacks against neural networks for evaluating robustness.
   * [Understanding the One-Pixel Attack: Propagation Maps and Locality Analysis](https://www.researchgate.net/publication/331008411_Understanding_the_One-Pixel_Attack_Propagation_Maps_and_Locality_Analysis)


* Youtube
   * [One Pixel Attack | Lecture 24 (Part 2) | Applied Deep Learning](https://www.youtube.com/watch?v=1-wKbWH5wCc)
   * [One Pixel Attack Defeats Neural Networks | Two Minute Papers, Simple Explanation](https://www.youtube.com/watch?v=SA4YEAWVpbk)
   * [One Pixel Attack by Big Data Analytics and Management Lab at UT Dallas](https://www.youtube.com/watch?v=40F0QYygj74)
   * [Adversarial Examples for Deep Neural Networks](https://www.youtube.com/watch?v=kxyacmVSGlI)
      * From Northeastern University's CS 7150 Summer 2020 class on Deep Learning, taught by Paul Hand.
   * [J. Z. Kolter and A. Madry: Adversarial Robustness - Theory and Practice (NeurIPS 2018 Tutorial)](https://www.youtube.com/watch?v=TwP-gKBQyic)
   * [A New Perspective on Adversarial Perturbations](https://www.youtube.com/watch?v=mUt7w4UoYqM)
      * Aleksander Madry (MIT), https://simons.berkeley.edu/talks/tbd-57, Frontiers of Deep Learning
   * [한국어: [Paper Review] Toward Deep Learning Models Resistant to Adversarial Attack](https://www.youtube.com/watch?v=SePQlKQd5xY)
   * [Lec 12 : Differential Evolution](https://www.youtube.com/watch?v=xwR7WbKtylg)
   * [Working Example of Differential Evolution (DE) Algorithm](https://www.youtube.com/watch?v=xQT5YjxgiZE)

* Source
   * [Keras Version](https://github.com/Hyperparticle/one-pixel-attack-keras)
   * [Pytorch Version](https://github.com/DebangLi/one-pixel-attack-pytorch)
   * [Pytorch Attack LIBRARY](https://adversarial-attacks-pytorch.readthedocs.io/en/latest/index.html)


* A tutorial on Differential Evolution with Python
   * https://pablormier.github.io/2017/09/05/a-tutorial-on-differential-evolution-with-python/

>최근에 인공지능, 빅데이터, 사물인터넷 등 많은 하이테크 기술들이 빠른 발전을 하고 있고, 많은 이들이 이러한 기술들을 습득하고자 노력하고 있습니다. 특히 최신 기술에 관심을 가지고 열심히 공부하는 우리 학생들의 모습이 아주 보기 좋습니다. ^^
>
>최신 기술에 대한 이와 같은 관심과 함께 이러한 최신 기술들을 가능하게 만들었던 핵심 알고리즘, 자료구조, 그리고 시스템 내부 등에도 우리 학생들이 관심을 가지고 컴퓨터 과학/공학에 튼튼한 기초를 다지는 것이 매우 중요하다고 생각합니다. 
>
>특히, 알고리즘은 전공지식뿐 아니라 사고의 폭과 깊이도 함께 향상시킬수 있다는 점에서 여러모로 도움이 되는 분야라고 생각해요.
>
>이러한 관점에서 알고리즘 스터디를 진행하는 우리 씨애랑 알고리즘 스터디 화이팅!!!~
