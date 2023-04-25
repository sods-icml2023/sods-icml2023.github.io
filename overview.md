---
layout: post
title: Overview
permalink: /overview/
---

<!-- **Date and time:** May 7, time 8:45am-5:00pm PDT (see [schedule](https://simdl.github.io/schedule/)) <br>
The workshop will be held **virtually** at [https://iclr.cc/virtual/2021/workshop/2141](https://iclr.cc/virtual/2021/workshop/2141). The full recorded workshop will be open to general public some time later after the ICLR conference. If you would like to participate, you need to [register the ICLR ticket](https://iclr.cc/Conferences/2021) first. -->

Sampling and optimization in discrete space are classical and important problems that arise in many applications, including physics, combinatorial optimization, compiler optimization, and many modern machine learning models like large language models and protein models. Examples include searching device placement strategies for distributed neural network training, or sampling from language model posteriors with arbitrary conditioning.

### Challenges
However, discrete space sampling/optimization is hard in general compared to continuous space. Although some independence structures can be leveraged for some special problems, in general discrete space sampling/optimization is slow. 
Recently, there have been new research trends in efficient discrete sampling and optimization via
- *Leveraging the gradient information of objectives:* the gradient based MCMC algorithms generalize the Langevin dynamics to discrete space.
- *Embedding into a continuous space:* The embedding methods first map the discrete space to continuous space, then apply an efficient sampling algorithm in continuous space, then map the new sample back into discrete space.
- *Other effective proposal strategies in discrete space:* for example the Stein variational method and GFlowNet.
These methods have improved efficiency in many domains. With simulated annealing, they can also serve as optimization algorithms and demonstrate superior performance on many combinatorial optimization problems compared to existing learning-based methods. However, they might still be limited when applied to black-box objectives, or problems involving long-range and high-order correlations like in modern language models. 

### Scope and Topics
Given this new direction of research and potential applications, we are organizing this workshop with the goals including, but not limited to:
- Syncing up on the latest research progress in discrete sampling and optimization.
- Discussing limitations of the current methods and brainstorm the new algorithm paradigms.
- Connecting to applications in domains such as language/protein modeling, physics simulation, and bio/chemical engineering, where improved sampling/optimization in discrete space would help, and explore the current gap between the application requirements and the capability of existing methods.

We hope this workshop will be a great opportunity for presenting and discussing new algorithms and applications with researchers and practitioners within or outside the domain of discrete sampling/optimization. 


Should you have any questions, please reach out to us via email:<br>
[sods-icml2023@googlegroups.com
](mailto:sods-icml2023@googlegroups.com)



<!-- ### Sponsorship
*NeurIPS 2022 GLFrontiers Workshop is generously sponsored by Google.*
<img src="https://github.com/glfrontiers/glfrontiers.github.io/blob/master/images/google.png?raw=true" alt="Google sponsorship" width="250" height="85"> -->
