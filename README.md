# Bibliography

# Table of contents

* [Reinforcement Learning](#reinforcement-learning)
  * [Value-based](#value-based)
  * [Policy-based](#policy-based)
    * [Policy gradient](#policy-gradient)
    * [Actor-critic](#actor-critic)
    * [Derivative-free](#derivative-free)
  * [Temporal abstraction](#temporal-abstraction)
  * [Partial observability](#partial-observability)
  * [Safety](#safety)
  * [Multi-agent](#multi-agent)
  * [Performances and acceleration](#performances-and-acceleration)
* [Learning from Demonstrations](#learning-from-demonstrations)
  * [Imitation Learning](#imitation-learning)
    * [IL applications](#il-applications)
  * [Inverse Reinforcement Learning](#inverse-reinforcement-learning)
    * [IRL applications](#irl-applications)
* [Optimal Control](#optimal-control)
  * [Control Theory](#control-theory)
  * [Dynamic Programming](#dynamic-programming)
* [Tree Search](#tree-search)

![RL Diagram](https://rawgit.com/eleurent/phd-bibliography/master/reinforcement-learning.svg)

# Reinforcement Learning

## Value-based

* [Playing Atari with Deep Reinforcement Learning](https://www.cs.toronto.edu/~vmnih/docs/dqn.pdf), Mnih V. et al, 2013. *DQN*.
* [Deep Reinforcement Learning with Double Q-learning](https://arxiv.org/abs/1509.06461), van Hasselt H. Silver D. et al, 2015. *DDQN*.
* [Dueling Network Architectures for Deep Reinforcement Learning](https://arxiv.org/abs/1511.06581), Wang Z. et al, 2015. *DDDQN*.
* [Prioritized Experience Replay](https://arxiv.org/abs/1511.05952), Schaul T. et al, 2015. *PDDDQN*.
* [Continuous Deep Q-Learning with Model-based Acceleration](https://arxiv.org/abs/1603.00748), Gu S. et al, 2016. *NAF*.

## Policy-based

### Policy gradient

* [Simple Statistical Gradient-Following Algorithms for Connectionist Reinforcement Learning](http://www-anw.cs.umass.edu/~barto/courses/cs687/williams92simple.pdf), Williams R., 1992. *REINFORCE*.
* [End-to-End Training of Deep Visuomotor Policies](https://arxiv.org/abs/1504.00702), Levine S. et al, 2015. *GPS*.
* [Trust Region Policy Optimization](https://arxiv.org/abs/1502.05477), Schulman J. et al, 2015. *TRPO*.
* [Proximal Policy Optimization Algorithms ](https://arxiv.org/abs/1707.06347), Schulman J. et al, 2017. *PPO*.

### Actor-critic

* [Policy Gradient Methods for Reinforcement Learning with Function Approximation](https://papers.nips.cc/paper/1713-policy-gradient-methods-for-reinforcement-learning-with-function-approximation.pdf), Sutton R. et al, 1999. *AC*.
* [Natural Actor-Critic](https://homes.cs.washington.edu/~todorov/courses/amath579/reading/NaturalActorCritic.pdf), Peters J. et al, 2005. *NAC*.
* [Asynchronous Methods for Deep Reinforcement Learning](https://arxiv.org/abs/1602.01783), Mnih V. et al 2016. *A3C*.
* [Continuous Control With Deep Reinforcement Learning](https://arxiv.org/abs/1509.02971), Lillicrap T. et al, 2016. *DDPG*.

### Derivative-free

* [Learning Tetris Using the Noisy Cross-Entropy Method](http://iew3.technion.ac.il/CE/files/papers/Learning%20Tetris%20Using%20the%20Noisy%20Cross-Entropy%20Method.pdf), Szita I. Lörincz A., 2006. *CEM*.
* [Completely Derandomized Self-Adaptation in Evolution Strategies](https://dl.acm.org/citation.cfm?id=1108843), Hansen N. Ostermeier A., 2001. *CMAES*.
* [Evolving Neural Networks through Augmenting Topologies](http://nn.cs.utexas.edu/downloads/papers/stanley.ec02.pdf), Stanley K., 2002. *NEAT*.

## Temporal abstraction

* [Between MDPs and semi-MDPs: A framework for temporal abstraction in reinforcement learning](http://www-anw.cs.umass.edu/~barto/courses/cs687/Sutton-Precup-Singh-AIJ99.pdf), Sutton R. et al, 1999.
* [Intrinsically motivated learning of hierarchical collections of skills](http://www-anw.cs.umass.edu/pubs/2004/barto_sc_ICDL04.pdf), Barto A. et al, 2004.
* [Learning and Transfer of Modulated Locomotor Controllers](https://arxiv.org/abs/1610.05182), Heess N. et al, 2016.
* [FeUdal Networks for Hierarchical Reinforcement Learning](https://arxiv.org/abs/1703.01161), Vezhnevets A. et al, 2017. *FuNs*.
* [On a Formal Model of Safe and Scalable Self-driving Cars](https://arxiv.org/abs/1708.06374), Shalev-Shwartz S. et al, 2017.

## Partial observability

* [Point-based Value Iteration: An anytime algorithm for POMDPs](https://www.ri.cmu.edu/pub_files/pub4/pineau_joelle_2003_3/pineau_joelle_2003_3.pdf), Pineau J. et al, 2003.
* [Point-Based Value Iteration for Continuous POMDPs](http://www.jmlr.org/papers/volume7/porta06a/porta06a.pdf), Porta J. et al, 2006.

## Safety

* [A Comprehensive Survey on Safe Reinforcement Learning](http://jmlr.org/papers/v16/garcia15a.html), García J., Fernández F., 2015.
* [Safe, Multi-Agent, Reinforcement Learning for Autonomous Driving](https://arxiv.org/abs/1610.03295), Shalev-Shwartz S. et al, 2016.

## Multi-agent

* [MAgent: A Many-Agent Reinforcement Learning Platform for Artificial Collective Intelligence](https://arxiv.org/abs/1712.00600), Zheng L. et al, 2017.

## Performances and acceleration

* [Near-optimal Regret Bounds for Reinforcement Learning](http://www.jmlr.org/papers/volume11/jaksch10a/jaksch10a.pdf), Jaksch T., ‎2010. *UCRL2*.
* [Integrated Architectures for Learning, Planning, and Reacting Based on Approximating Dynamic Programming](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.84.6983&rep=rep1&type=pdf), Sutton R., 1990. *Dyna*.

# Tree Search

* [Mastering the game of Go with deep neural networks and tree search](https://www.nature.com/articles/nature16961), Silver D. et al, 2016.

# Learning from Demonstrations

## Imitation Learning

* [Learning from Demonstrations for Real World Reinforcement Learning](https://pdfs.semanticscholar.org/a7fb/199f85943b3fb6b5f7e9f1680b2e2a445cce.pdf), Hester T. et al, 2017. *DQfD*.
* [Value Iteration Networks](https://arxiv.org/abs/1602.02867), Tamar A. et al , 2016. *VIN*.
* [Value Prediction Network](https://arxiv.org/abs/1707.03497), Oh J. et al, 2017. *VPN*.

### IL applications

* [ALVINN, an autonomous land vehicle in a neural network](https://papers.nips.cc/paper/95-alvinn-an-autonomous-land-vehicle-in-a-neural-network), Pomerleau D., 1989.
* [End to End Learning for Self-Driving Cars](https://arxiv.org/abs/1604.07316), Bojarski M. et al (NVIDIA), 2016.
* [End-to-End Deep Learning for Steering Autonomous Vehicles Considering Temporal Dependencies](https://arxiv.org/abs/1710.03804), Eraqi H. et al, 2017.

## Inverse Reinforcement Learning

* [Apprenticeship learning via inverse reinforcement learning](http://ai.stanford.edu/~ang/papers/icml04-apprentice.pdf), Abbeel P. Ng A. 2004. *Projection*.
* [Bayesian inverse reinforcement learning](https://www.aaai.org/Papers/IJCAI/2007/IJCAI07-416.pdf), Ramachandran D. Amir E., 2007. *BIRL*.
* [Maximum Entropy Inverse Reinforcement Learning](https://www.aaai.org/Papers/AAAI/2008/AAAI08-227.pdf), Ziebart B. et al, 2008. *MEIRL*.
* [Maximum Entropy Deep Inverse Reinforcement Learning](https://arxiv.org/abs/1507.04888), Wulfmeier M., 2015. *MEDIRL*.
* [Guided Cost Learning: Deep Inverse Optimal Control via Policy Optimization](https://arxiv.org/abs/1603.00448), Finn C. et al, 2016. *GCL*.
* [Generative Adversarial Imitation Learning](https://arxiv.org/abs/1606.03476), Ho J., Ermon S., 2016. *GAIL*.
* [Bridging the Gap Between Imitation Learning and Inverse Reinforcement Learning](http://ieeexplore.ieee.org/document/7464854/), Piot B. et al, 2017.

### IRL applications

* [Apprenticeship Learning for Motion Planning, with Application to Parking Lot Navigation](http://ieeexplore.ieee.org/document/4651222/), Abbeel P. et al, 2008.
* [Planning-based Prediction for Pedestrians](http://ieeexplore.ieee.org/abstract/document/5354147/), Ziebart B. et al, 2009.
* [Watch This: Scalable Cost-Function Learning for Path Planning in Urban Environments](https://arxiv.org/abs/1607.02329), Wulfmeier M., 2016.
* [Learning Driving Styles for Autonomous Vehicles from Demonstration](http://ieeexplore.ieee.org/document/7139555/), Kuderer M. et al, 2015.

# Optimal Control

## Control theory

* (book) [Model Predictive Control](http://een.iust.ac.ir/profs/Shamaghdari/MPC/Resources/), Camacho E., 1995.
* (book) [Predictive Control With Constraints](https://books.google.fr/books/about/Predictive_Control.html?id=HV_Y58c7KiwC&redir_esc=y), Maciejowski J. M., 2002.
* (book) [Constrained Control and Estimation](http://www.springer.com/gp/book/9781852335489),  Goodwin G., 2005.
* [A Generalized Path Integral Control Approach to Reinforcement Learning](http://www.jmlr.org/papers/volume11/theodorou10a/theodorou10a.pdf), Theodorou E. et al, 2010. *PI²*
* [Path Integral Policy Improvement with Covariance Matrix Adaptation](https://arxiv.org/abs/1206.4621), Stulp F., Sigaud O., 2010. *PI²-CMA*.
* [A generalized iterative LQG method for locally-optimal feedback control of constrained nonlinear stochastic systems](http://maeresearch.ucsd.edu/skelton/publications/weiwei_ilqg_CDC43.pdf), Todorov E., 2005. *iLQG*.
* [Synthesis and stabilization of complex behaviors through online trajectory optimization](https://homes.cs.washington.edu/~todorov/papers/TassaIROS12.pdf), Tassa Y., 2012. *iLQG+*.

### Dynamic programming

* (book) [Dynamic Programming](https://press.princeton.edu/titles/9234.html), Bellman R., 1957.
* (book) [Dynamic Programming and Optimal Control, Volumes 1 and 2](http://web.mit.edu/dimitrib/www/dpchapter.html), Bertsekas D., 1995.
* (book) [Markov Decision Processes - Discrete Stochastic Dynamic Programming](http://eu.wiley.com/WileyCDA/WileyTitle/productCd-1118625870.html), Puterman M., 1995.

## Search

