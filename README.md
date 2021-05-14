# Multi Agent Reinforcement Learning papers
This is a collection of Multi-Agent Reinforcement Learning (MARL) papers. Each category is a potential start point for you to start your research.

For MARL papers with code and MARL resources, please refer to [MARL Papers with Code](https://github.com/TimeBreaker/MARL-papers-with-code) and [MARL Resources Collection](https://github.com/TimeBreaker/MARL-resources-collection).

I will continually update this repository and I welcome suggestions. (missing important papers, missing categories, invalid links, etc.) This is only a first draft so far and I'll add more resources in the next few months.

This repository is not for commercial purposes.

My email: chenhao2019@ia.ac.cn

## Overview
* [Reviews](https://github.com/TimeBreaker/Multi-Agent-Reinforcement-Learning-papers#reviews)
* [Dealing With Credit Assignment Issue](https://github.com/TimeBreaker/Multi-Agent-Reinforcement-Learning-papers#dealing-with-credit-assignment-issue)
* [Policy Gradient](https://github.com/TimeBreaker/Multi-Agent-Reinforcement-Learning-papers#policy-gradient)
* [Communication](https://github.com/TimeBreaker/Multi-Agent-Reinforcement-Learning-papers#communication)
* [Emergent](https://github.com/TimeBreaker/Multi-Agent-Reinforcement-Learning-papers#emergent)
* [Opponent Modeling](https://github.com/TimeBreaker/Multi-Agent-Reinforcement-Learning-papers#opponent-modeling)
* [Game Theoretic](https://github.com/TimeBreaker/Multi-Agent-Reinforcement-Learning-papers#game-theoretic)
* [Hierarchical](https://github.com/TimeBreaker/Multi-Agent-Reinforcement-Learning-papers#hierarchical)
* [Ad Hoc Teamwork](https://github.com/TimeBreaker/Multi-Agent-Reinforcement-Learning-papers#ad-hoc-teamwork)
* [League Training](https://github.com/TimeBreaker/Multi-Agent-Reinforcement-Learning-papers#league-training)
* [Curriculum Learning](https://github.com/TimeBreaker/Multi-Agent-Reinforcement-Learning-papers#curriculum-learning)
* [Mean Field](https://github.com/TimeBreaker/Multi-Agent-Reinforcement-Learning-papers#mean-field)
* [Transfer Learning](https://github.com/TimeBreaker/Multi-Agent-Reinforcement-Learning-papers#transfer-learning)
* [Meta Learning](https://github.com/TimeBreaker/Multi-Agent-Reinforcement-Learning-papers#meta-learning)
* [Fairness](https://github.com/TimeBreaker/Multi-Agent-Reinforcement-Learning-papers#fairness)
* [Exploration](https://github.com/TimeBreaker/Multi-Agent-Reinforcement-Learning-papers#exploration)
* [Graph Neural Network](https://github.com/TimeBreaker/Multi-Agent-Reinforcement-Learning-papers#graph-neural-network)
* [Model-based](https://github.com/TimeBreaker/Multi-Agent-Reinforcement-Learning-papers#model-based)
* [NAS](https://github.com/TimeBreaker/Multi-Agent-Reinforcement-Learning-papers#nas)
* [Safe Multi-Agent Reinforcement Learning](https://github.com/TimeBreaker/Multi-Agent-Reinforcement-Learning-papers#safe-multi-agent-reinforcement-learning)
* [From Single-agent to Multi-agent](https://github.com/TimeBreaker/Multi-Agent-Reinforcement-Learning-papers#from-single-agent-to-multi-agent)
* [Discrete-Continuous Hybrid Action Spaces / Parameterized Action Space](https://github.com/TimeBreaker/Multi-Agent-Reinforcement-Learning-papers#discrete-continuous-hybrid-action-spaces--parameterized-action-space)
* [Multi-Agent Pathfinding](https://github.com/TimeBreaker/Multi-Agent-Reinforcement-Learning-papers#multi-agent-pathfinding)
* [TODO](https://github.com/TimeBreaker/Multi-Agent-Reinforcement-Learning-papers#todo)

## Reviews
### Recent Reviews (Since 2019)
* [A Survey and Critique of Multiagent Deep Reinforcement Learning](https://arxiv.org/pdf/1810.05587v3)
* [An Overview of Multi-Agent Reinforcement Learning from Game Theoretical Perspective](https://arxiv.org/abs/2011.00583v2)
* [Multi-Agent Reinforcement Learning: A Selective Overview of Theories and Algorithms](https://arxiv.org/abs/1911.10635v1)
* [A Review of Cooperative Multi-Agent Deep Reinforcement Learning](https://arxiv.org/abs/1908.03963)
* [Dealing with Non-Stationarity in Multi-Agent Deep Reinforcement Learning](https://arxiv.org/abs/1906.04737)
* [A Survey of Learning in Multiagent Environments: Dealing with Non-Stationarity](https://arxiv.org/abs/1707.09183v1)
* [Deep Reinforcement Learning for Multi-Agent Systems: A Review of Challenges, Solutions and Applications](https://arxiv.org/pdf/1812.11794.pdf)
* [A Survey on Transfer Learning for Multiagent Reinforcement Learning Systems](https://www.researchgate.net/publication/330752409_A_Survey_on_Transfer_Learning_for_Multiagent_Reinforcement_Learning_Systems)

### Other Reviews (Before 2019)
* [If multi-agent learning is the answer, what is the question?](https://ai.stanford.edu/people/shoham/www%20papers/LearningInMAS.pdf)
* [Multiagent learning is not the answer. It is the question](https://core.ac.uk/download/pdf/82595758.pdf)
* [Is multiagent deep reinforcement learning the answer or the question? A brief survey](https://arxiv.org/abs/1810.05587v1)   Note that [A Survey and Critique of Multiagent Deep Reinforcement Learning](https://arxiv.org/pdf/1810.05587v3) is an updated version of this paper with the same authors.
* [Evolutionary Dynamics of Multi-Agent Learning: A Survey](https://www.researchgate.net/publication/280919379_Evolutionary_Dynamics_of_Multi-Agent_Learning_A_Survey)
* (Worth reading although they're not recent reviews.)

## Dealing With Credit Assignment Issue
### Value Decomposition
* VDN：Value-Decomposition Networks For Cooperative Multi-Agent Learning
* QMIX: Monotonic Value Function Factorisation for Deep Multi-Agent Reinforcement Learning
* QTRAN: Learning to Factorize with Transformation for Cooperative Multi-Agent Reinforcement Learning
* NDQ: Learning Nearly Decomposable Value Functions Via Communication Minimization
* CollaQ：Multi-Agent Collaboration via Reward Attribution Decomposition
* Weighted QMIX: Expanding Monotonic Value Function Factorisation for Deep Multi-Agent Reinforcement Learning
* SQDDPG：Shapley Q-Value: A Local Reward Approach to Solve Global Reward Games
* QPLEX: Duplex Dueling Multi-Agent Q-Learning
* QTRAN++: Improved Value Transformation for Cooperative Multi-Agent Reinforcement Learning

### Other Methods
* COMA：Counterfactual Multi-Agent Policy Gradients
* LiCA：Learning Implicit Credit Assignment for Cooperative Multi-Agent Reinforcement Learning

## Policy Gradient
* MADDPG：Multi-Agent Actor-Critic for Mixed Cooperative-Competitive Environments
* COMA：Counterfactual Multi-Agent Policy Gradients
* IPPO：Is Independent Learning All You Need in the StarCraft Multi-Agent Challenge?
* MAPPO：The Surprising Effectiveness of MAPPO in Cooperative, Multi-Agent Games
* MAAC：Actor-Attention-Critic for Multi-Agent Reinforcement Learning
* DOP: Off-Policy Multi-Agent Decomposed PolicyGradients
* MACKRL
* Robust multi-agent reinforcement learning via minimax deep deterministic policy gradient

## Communication
* CommNet：Learning Multiagent Communication with Backpropagation
* BiCNet：Multiagent Bidirectionally-Coordinated Nets: Emergence of Human-level Coordination in Learning to Play StarCraft Combat Games
* VAIN: Attentional Multi-agent Predictive Modeling
* IC3Net：Learning when to Communicate at Scale in Multiagent Cooperative and Competitive Tasks
* VBC：Efficient Communication in Multi-Agent Reinforcement Learning via Variance Based Control
* Graph Convolutional Reinforcement Learning for Multi-Agent Cooperation
* NDQ：Learning Nearly Decomposable Value Functions Via Communication Minimization
* RIAL/RIDL：Learning to Communicate with Deep Multi-Agent Reinforcement Learning
* ATOC：Learning Attentional Communication for Multi-Agent Cooperation
* Communication under limited bandwidth
   * SchedNet：Learning to Schedule Communication in Multi-Agent Reinforcement learning
   * Learning Multi-agent Communication under Limited-bandwidth Restriction for Internet Packet Routing
   * Gated-ACML：Learning Agent Communication under Limited Bandwidth by Message Pruning
   * Learning Efficient Multi-agent Communication: An Information Bottleneck Approach
   * Coordinating Multi-Agent Reinforcement Learning with Limited Communication

## Emergent
* Multiagent Cooperation and Competition with Deep Reinforcement Learning
* Multi-agent Reinforcement Learning in Sequential Social Dilemmas
* Emergent preeminence of selfishness: an anomalous Parrondo perspective
* Emergent Coordination Through Competition
* Biases for Emergent Communication in Multi-agent Reinforcement Learning
* Towards Graph Representation Learning in Emergent Communication
* Emergent Tool Use From Multi-Agent Autocurricula  (hide and seek)
* On Emergent Communication in Competitive Multi-Agent Teams
* QED：Quasi-Equivalence Discovery for Zero-Shot Emergent Communication
* Incorporating Pragmatic Reasoning Communication into Emergent Language

## Opponent Modeling
* Bayesian Opponent Exploitation in Imperfect-Information Games
* LOLA：Learning with Opponent-Learning Awareness
* Variational Autoencoders for Opponent Modeling in Multi-Agent Systems
* Stable Opponent Shaping in Differentiable Games
* Opponent Modeling and Strategic Reasoning in the Real-time Strategy Game Starcraft
* Opponent Modeling in Deep Reinforcement Learning
* Game Theory-Based Opponent Modeling in Large Imperfect-Information Games

## Game Theoretic
* α-Rank: Multi-Agent Evaluation by Evolution
* αα -Rank: Practically Scaling α-Rank through Stochastic Optimisation
* A Game Theoretic Framework for Model Based Reinforcement Learning
* Fictitious Self-Play in Extensive-Form Games
* Nash Q-Learning for General-Sum Stochastic Games
* An Analysis of Stochastic Game Theory for Multiagent Reinforcement Learning
* Multi-Agent Reinforcement Learning in Common Interest and Fixed Sum Stochastic Games: An Experimental Study
* Combining Deep Reinforcement Learning and Search for Imperfect-Information Games
* Real World Games Look Like Spinning Tops
* Pipeline PSRO: A Scalable Approach for Finding Approximate Nash Equilibria in Large Games
* A Game-Theoretic Model and Best-Response Learning Method for Ad Hoc Coordination in Multiagent Systems
* NFSP
* PSRO: A Unified Game-Theoretic Approach to Multiagent Reinforcement Learning
* FSP

## Hierarchical
* 
* 
* 

## Ad Hoc Teamwork
* CollaQ：Multi-Agent Collaboration via Reward Attribution Decomposition
* A Game-Theoretic Model and Best-Response Learning Method for Ad Hoc Coordination in Multiagent Systems
* Half Field Offense: An Environment for Multiagent Learning and Ad Hoc Teamwork

## League Training
* AlphaStar：Grandmaster level in StarCraft II using multi-agent reinforcement learning

## Curriculum Learning
* Diverse Auto-Curriculum is Critical for Successful Real-World Multiagent Learning Systems
* From Few to More: Large-Scale Dynamic Multiagent Curriculum Learning
* EPC：Evolutionary Population Curriculum for Scaling Multi-Agent Reinforcement Learning
* Emergent Tool Use From Multi-Agent Autocurricula
* Learning to Teach in Cooperative Multiagent Reinforcement Learning
* StarCraft Micromanagement with Reinforcement Learning and Curriculum Transfer Learning

## Mean Field
* Mean Field Multi-Agent Reinforcement Learning
* Efficient Ridesharing Order Dispatching with Mean Field Multi-Agent Reinforcement Learning
* Bayesian Multi-type Mean Field Multi-agent Imitation Learning

## Transfer Learning
* A Survey on Transfer Learning for Multiagent Reinforcement Learning Systems
* Parallel Knowledge Transfer in Multi-Agent Reinforcement Learning
* 

## Meta Learning
* A Policy Gradient Algorithm for Learning to Learn in Multiagent Reinforcement Learning
* Continuous Adaptation via Meta-Learning in Nonstationary and Competitive Environment

## Fairness 
* FEN：Learning Fairness in Multi-Agent Systems
* Fairness in Multiagent Resource Allocation  with Dynamic and Partial Observations
* Fairness in Multi-agent Reinforcement Learning for Stock Trading
* Promoting Cooperation and Fairness in Self-interested Multi-Agent Systems:

## Exploration
* EITI/EDTI：Influence-Based Multi-Agent Exploration
* MAVEN：Multi-Agent Variational Exploration
* CM3: Cooperative Multi-goal Multi-stage Multi-agent Reinforcement Learning
* Coordinated Exploration via Intrinsic Rewards for Multi-Agent Reinforcement Learning
* Coordinated Multi-Agent Exploration Using Shared Goals
* Exploration by Maximizing R\'enyi Entropy for Reward-Free RL Framework
* Exploration-Exploitation in Multi-Agent Learning: Catastrophe Theory Meets Game Theory
* LIIR: Learning Individual Intrinsic Reward in Multi-Agent Reinforcement Learning
* Social Influence as Intrinsic Motivation  for Multi-Agent Deep Reinforcement Learning

## Graph Neural Network 
* Multi-Agent Game Abstraction via Graph Attention Neural Network
* Graph Convolutional Reinforcement Learning for Multi-Agent Cooperation
* Multi-Agent Reinforcement Learning with Graph Clustering
* Learning to Coordinate with Coordination Graphs in Repeated Single-Stage Multi-Agent Decision Problems

## Model-based
* Model-based Multi-Agent Reinforcement Learning with Cooperative Prioritized Sweeping

## NAS
* MANAS: Multi-Agent Neural Architecture Search

## Safe Multi-Agent Reinforcement Learning
* MAMPS: Safe Multi-Agent Reinforcement Learning via Model Predictive Shielding
* Safer Deep RL with Shallow MCTS: A Case Study in Pommerman

## From Single-agent to Multi-agent
* IQL：Multi-Agent Reinforcement Learning: Independent vs. Cooperative Agents
* IPPO：Is Independent Learning All You Need in the StarCraft Multi-Agent Challenge?
* MAPPO：The Surprising Effectiveness of MAPPO in Cooperative, Multi-Agent Games
* MADDPG：Multi-Agent Actor-Critic for Mixed Cooperative-Competitive Environments

## Discrete-Continuous Hybrid Action Spaces / Parameterized Action Space
* Deep Reinforcement Learning in Parameterized Action Space
* DMAPQN: Deep Multi-Agent Reinforcement Learning with Discrete-Continuous Hybrid Action Spaces
* H-PPO: Hybrid actor-critic reinforcement learning in parameterized action space
* P-DQN: Parametrized Deep Q-Networks Learning: Reinforcement Learning with Discrete-Continuous Hybrid Action Space

## Multi-Agent Pathfinding
* TODO

## TODO
* Multi-Agent Pathfinding




