---
layout: post
title: Workshop Schedule
permalink: /schedule/
---
<!-- The Workshop will be held virtually at [https://iclr.cc/virtual/2021/workshop/2141](https://iclr.cc/virtual/2021/workshop/2141), on May 7th.<br>
Time zone: PDT -->
<!-- 
8:45--9:00AM: **Opening remarks**

9:00--9:30AM: **Invited talk**: *Nils Thuerey - Differentiable Simulations as Fundamental Building Blocks for Deep Learning*

9:30--10:00AM: **Invited talk**: *Larry Zitnick - Open Catalyst Project: using AI to model and discover new catalyst to address the energy challenges posed by climate change*

10:00--10:30AM: **Invited talk**: *Shirley Ho - Learning Symbolic Equations with Deep Learning*

10:30--11:00AM: **Q&A / Discussions / Coffee break 1**

11:00--11:15AM: **Contributed talks 1**: *Alvaro Sanchez-Gonzalez, Kimberly Stachenfeld - [Learning general-purpose CNN-based simulators for astrophysical turbulence.](https://simdl.github.io/files/26.pdf)* [Poster](https://simdl.github.io/posters/26-supp_poster_upload.pdf)

11:15--11:30AM: **Break**

11:30AM--1:00PM: [**Virtual Poster Session**](/papers) (please enther via [this gather.town link](https://eventhosts.gather.town/app/gPmDp1IwP1UqHKxq/ICLR2021simDL))

1:00--1:30PM: **Invited talk**: *David Duvenaud - Latent Stochastic Differential Equations*

1:30--2:00PM: **Invited talk**: *Anima Anandkumar - AI4Science: a revolution in the making*

2:00--2:30PM: **Invited talk**: *Jesse Thaler - Deep Learning for Collider Physics Simulation*

2:30--2:45PM: **Q&A / Discussions 2**

2:45--3:00PM: **Contributed talks 2**: *Andreas Mayr - [Learning 3D Granular Flow Simulations.](https://SimDL.github.io/files/42.pdf)* [Poster](https://SimDL.github.io/posters/42-supp_poster.pdf)

3:00--3:15PM: **Contributed talks 3**: *Weihua Hu - [ForceNet: A Graph Neural Network for Large-Scale Quantum Calculations.](https://SimDL.github.io/files/62.pdf)* [Poster](https://SimDL.github.io/posters/62-supp_forcenet_iclr2021-ws-poster.pdf)

3:15--3:30PM: **Break**

3:30--4:00PM: **Invited talk**: *Ron Fedkiw - On Neural Networks for Physical Simulation* 

4:00--4:30PM: **Invited talk**: *Yunzhu Li - Learning Computational Dynamics Models for Physics Inference and Model-based Control.* 

4:30--4:45PM: **Q&A / Discussions 3**

4:45--5:00PM: **Closing remarks** -->

The Workshop will be held in person on Saturday, July 29, 2023, at the Hawaii Convention Center, as a part of the [ICML 2023 conference](https://icml.cc/Conferences/2023). The ICML homepage for our workshop is [here](https://icml.cc/Conferences/2023/Schedule?showEvent=21494). The following schedule is based on local time (HST).


9:00--9:15AM: **Opening remarks**

9:15--9:45AM: **Invited talk 1:** Yoshua Bengio
<details>
  <summary>GFlowNets for Bayesian Inference</summary>

  Generative flow networks (GFlowNets) are generative policies trained to sample proportionally to a given reward function. If the reward function is a prior distribution times a likelihood, then the GFlowNet learns to sample from the corresponding posterior. Unlike MCMC, a GFlowNet does not suffer from the problem of mixing between modes, but like RL methods, it needs an exploratory training policy in order to discover modes. This can be conveniently done without any kind of importance weighting because the training objectives for GFlowNets can all be correctly applied in an off-policy fashion without reweighting. One can view GFlowNets also as extensions of amortized variational inference with this off-policy advantage. We show how training the GFlowNet sampler also learns how to marginalize over the target distribution or part of it, at the same time as it learns to sample from it, which makes it possible to train amortized posterior predictives. Finally, we show examples of application of GFlowNets for Bayesian inference over causal graphs, discuss open problems and how scaling up such methodologies opens the door to system 2 deep learning to discover explanatory theories and form Bayesian predictors, with the approximation error asymptotically going to zero as we increase the size and training time of the neural network.
</details>


9:45--10:15AM: **Invited talk 2:** Giacomo Zanella

10:15--10:45PM: **Contributed talks 1**
* **(Outstanding)** SurCo: Learning Linear SURrogates for COmbinatorial Nonlinear Optimization Problems
* Tackling Provably Hard Representative Selection viaGraph Neural Networks
* Accelerating Diffusion-based Combinatorial Optimization Solvers by Progressive Distillation

10:45--11:15AM: **Invited talk 3:** Stefanie Jegelka  
Learning discrete optimization: Loss functions and graph neural networks

11:15--11:30PM: **Coffee Break**

11:30AM--1:00PM: [**Poster Session 1**]

1:00--1:30PM: **Invited talk 4:** Will Grathwohl
<details>
  <summary>Recent Applications of Gradients in Discrete Sampling</summary>

   Discrete sampling is a challenging and important problem. Despite much research, we still lack generic methods to sampling from discrete distribution without considerable knowledge of the structure of the target distribution. Conversely, in continuous settings much more successful generic methods exist. These methods exploit the gradients of the distribution's log-likelihood function to approximate the distribution's local structure which is used to parameterize fast-mixing markov transition kernels. A number of approaches have attempted to apply these methods to discrete problems with varying levels of success. Typically we create a related continuous distribution, sampling from this using continuous methods, and map these continuous samples back into the original discrete space. Recently, a new class of approaches has emerged which utilize gradient information in a different way. These approaches stay completely in the original discrete space but utilize gradient information to define markov transition kernels which propose discrete transitions. These approaches have shown to scale better and are widely applicable. In this talk I will discuss the development of these methods starting Gibbs-With-Gradients, further work improving or expanding upon these ideas, and new directions for further research.
</details>

1:30--2:00PM: **Invited talk 5:** Lianhui Qin
<details>
  <summary>Differentiable and structured text reasoning</summary>

  Text reasoning and generation in practice often needs to meet complex objectives, integrate diverse contextual constraints, and ground in logical structures for consistency. Current large LMs can produce fluent text and follow human instructions, but they still struggle to effectively optimize toward specific objectives. The discrete nature of text poses one of the key challenges to the optimization. In this talk, I will present our work on optimizing text reasoning and generation with continuous and discrete methods. I will first introduce COLD, a unified energy-based framework that empowers any off-the-shelf LMs to reason with any objectives in a continuous space. This approach brings forward differentiable reasoning over discrete text, thus improving efficiency. Following this, I will discuss Maieutic prompting, a method that enhances the logical consistency of neural reasoning in a discrete space by integrating with logical structures.
</details>


2:00--2:30PM: **Contributed talks 2**
* **(Outstanding)** Understanding prompt engineering does not require rethinking generalization
* Topological Neural Discrete Representation Learning à la Kohonen
* Sequential Monte Carlo Steering of Large Language Models using Probabilistic Programs

2:30--3:00PM: **Invited talk 6:** Petar Veličković 
<details>
  <summary>The Melting Pot of Neural Algorithmic Reasoning</summary>

  With the eyes of the AI world pointed at the alignment of large language models, another revolution has been more silently---yet intensely---taking place: the algorithmic alignment of neural networks. 
After briefly surveying how we got here, I'll present some of the interesting 2023 works I've had the pleasure to co-author, many of which were presented at this year's ICML.
</details>

3:00--3:15PM: **Closing remarks**

3:15--4:45PM: [**Poster Session 2**]


Should you have any questions, please reach out to us via email:<br>
[sods-icml2023@googlegroups.com
](mailto:sods-icml2023@googlegroups.com)
