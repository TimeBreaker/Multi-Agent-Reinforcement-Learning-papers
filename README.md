# Multi-Agent Reinforcement Learning papers
This is a collection of Multi-Agent Reinforcement Learning (MARL) papers. Each category is a potential start point for you to start your research. Some papers are listed more than once because they belong to multiple categories.

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
* [From Single-Agent to Multi-Agent](https://github.com/TimeBreaker/Multi-Agent-Reinforcement-Learning-papers#from-single-agent-to-multi-agent)
* [Discrete-Continuous Hybrid Action Spaces / Parameterized Action Space](https://github.com/TimeBreaker/Multi-Agent-Reinforcement-Learning-papers#discrete-continuous-hybrid-action-space--parameterized-action-space)
* [Role](https://github.com/TimeBreaker/Multi-Agent-Reinforcement-Learning-papers#role)
* [Diversity](https://github.com/TimeBreaker/Multi-Agent-Reinforcement-Learning-papers#diversity)
* [Multi-Agent Path Finding](https://github.com/TimeBreaker/Multi-Agent-Reinforcement-Learning-papers#multi-agent-path-finding)
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
* [VDN???Value-Decomposition Networks For Cooperative Multi-Agent Learning](https://arxiv.org/pdf/1706.05296)
* [QMIX: Monotonic Value Function Factorisation for Deep Multi-Agent Reinforcement Learning](http://proceedings.mlr.press/v80/rashid18a/rashid18a.pdf)
* [QTRAN: Learning to Factorize with Transformation for Cooperative Multi-Agent Reinforcement Learning](https://arxiv.org/abs/1905.05408)
* [NDQ: Learning Nearly Decomposable Value Functions Via Communication Minimization](https://arxiv.org/abs/1910.05366v1)
* [CollaQ???Multi-Agent Collaboration via Reward Attribution Decomposition](https://arxiv.org/abs/2010.08531)
* [SQDDPG???Shapley Q-Value: A Local Reward Approach to Solve Global Reward Games](https://arxiv.org/abs/1907.05707)
* [QPLEX: Duplex Dueling Multi-Agent Q-Learning](https://arxiv.org/abs/2008.01062)
* [QPD???Q-value Path Decomposition for Deep Multiagent Reinforcement Learning](http://proceedings.mlr.press/v119/yang20d/yang20d.pdf)
#### Improvements
* [Weighted QMIX: Expanding Monotonic Value Function Factorisation for Deep Multi-Agent Reinforcement Learning](https://arxiv.org/abs/2006.10800)
* [QTRAN++: Improved Value Transformation for Cooperative Multi-Agent Reinforcement Learning](https://arxiv.org/abs/2006.12010v2)

### Other Methods
* [COMA???Counterfactual Multi-Agent Policy Gradients](https://arxiv.org/abs/1705.08926)
* [LiCA???Learning Implicit Credit Assignment for Cooperative Multi-Agent Reinforcement Learning](https://arxiv.org/abs/2007.02529v2)

## Policy Gradient
* [MADDPG???Multi-Agent Actor-Critic for Mixed Cooperative-Competitive Environments](https://arxiv.org/abs/1706.02275v3)
* [COMA???Counterfactual Multi-Agent Policy Gradients](https://arxiv.org/abs/1705.08926)
* [IPPO???Is Independent Learning All You Need in the StarCraft Multi-Agent Challenge?](https://arxiv.org/abs/2011.09533)
* [MAPPO???The Surprising Effectiveness of MAPPO in Cooperative, Multi-Agent Games](https://arxiv.org/abs/2103.01955)
* [MAAC???Actor-Attention-Critic for Multi-Agent Reinforcement Learning](https://arxiv.org/abs/1810.02912)
* [DOP: Off-Policy Multi-Agent Decomposed PolicyGradients](https://arxiv.org/abs/2007.12322)
* [Robust multi-agent reinforcement learning via minimax deep deterministic policy gradient](https://ojs.aaai.org/index.php/AAAI/article/view/4327/4205)

## Communication
### Communication Without Bandwidth Constraint
* [CommNet???Learning Multiagent Communication with Backpropagation](https://arxiv.org/abs/1605.07736)
* [BiCNet???Multiagent Bidirectionally-Coordinated Nets: Emergence of Human-level Coordination in Learning to Play StarCraft Combat Games](https://arxiv.org/abs/1703.10069)
* [VAIN: Attentional Multi-agent Predictive Modeling](https://arxiv.org/abs/1706.06122)
* [IC3Net???Learning when to Communicate at Scale in Multiagent Cooperative and Competitive Tasks](https://arxiv.org/abs/1812.09755)
* [VBC???Efficient Communication in Multi-Agent Reinforcement Learning via Variance Based Control](https://arxiv.org/abs/1909.02682v1)
* [Graph Convolutional Reinforcement Learning for Multi-Agent Cooperation](https://arxiv.org/abs/1810.09202v1)
* [NDQ???Learning Nearly Decomposable Value Functions Via Communication Minimization](https://arxiv.org/abs/1910.05366v1)
* [RIAL/RIDL???Learning to Communicate with Deep Multi-Agent Reinforcement Learning](https://arxiv.org/abs/1605.06676)
* [ATOC???Learning Attentional Communication for Multi-Agent Cooperation](https://arxiv.org/abs/1805.07733)
* [Fully decentralized multi-agent reinforcement learning with networked agents](http://proceedings.mlr.press/v80/zhang18n/zhang18n.pdf)
* [TarMAC: Targeted Multi-Agent Communication](http://proceedings.mlr.press/v97/das19a/das19a.pdf)
### Communication Under Limited Bandwidth
* [SchedNet???Learning to Schedule Communication in Multi-Agent Reinforcement learning](https://arxiv.org/abs/1902.01554)
* [Learning Multi-agent Communication under Limited-bandwidth Restriction for Internet Packet Routing](https://arxiv.org/abs/1903.05561)
* [Gated-ACML???Learning Agent Communication under Limited Bandwidth by Message Pruning](https://arxiv.org/abs/1912.05304v1)
* [Learning Efficient Multi-agent Communication: An Information Bottleneck Approach](https://arxiv.org/abs/1911.06992)
* [Coordinating Multi-Agent Reinforcement Learning with Limited Communication](http://aamas.csc.liv.ac.uk/Proceedings/aamas2013/docs/p1101.pdf)

## Emergent
* [Multiagent Cooperation and Competition with Deep Reinforcement Learning](https://arxiv.org/abs/1511.08779v1)
* [Multi-agent Reinforcement Learning in Sequential Social Dilemmas](https://arxiv.org/abs/1702.03037)
* [Emergent preeminence of selfishness: an anomalous Parrondo perspective](https://kanghaocheong.files.wordpress.com/2020/02/koh-cheong2019_article_emergentpreeminenceofselfishne.pdf)
* [Emergent Coordination Through Competition](https://arxiv.org/abs/1902.07151v2)
* [Biases for Emergent Communication in Multi-agent Reinforcement Learning](https://arxiv.org/abs/1912.05676)
* [Towards Graph Representation Learning in Emergent Communication](https://arxiv.org/abs/2001.09063)
* [Emergent Tool Use From Multi-Agent Autocurricula](https://arxiv.org/abs/1909.07528)
* [On Emergent Communication in Competitive Multi-Agent Teams](https://arxiv.org/abs/2003.01848)
* [QED???Quasi-Equivalence Discovery for Zero-Shot Emergent Communication](https://arxiv.org/abs/2103.08067)
* [Incorporating Pragmatic Reasoning Communication into Emergent Language](https://arxiv.org/abs/2006.04109)

## Opponent Modeling
* [Bayesian Opponent Exploitation in Imperfect-Information Games](https://arxiv.org/abs/1603.03491v1)
* [LOLA???Learning with Opponent-Learning Awareness](https://arxiv.org/abs/1709.04326)
* [Variational Autoencoders for Opponent Modeling in Multi-Agent Systems](https://arxiv.org/abs/2001.10829)
* [Stable Opponent Shaping in Differentiable Games](https://arxiv.org/abs/1811.08469)
* [Opponent Modeling and Strategic Reasoning in the Real-time Strategy Game Starcraft](https://ntnuopen.ntnu.no/ntnu-xmlui/bitstream/handle/11250/252930/565941_FULLTEXT01.pdf?sequence=2)
* [Opponent Modeling in Deep Reinforcement Learning](https://arxiv.org/abs/1609.05559)
* [Game Theory-Based Opponent Modeling in Large Imperfect-Information Games](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.385.6032&rep=rep1&type=pdf)

## Game Theoretic
* [??-Rank: Multi-Agent Evaluation by Evolution](https://arxiv.org/abs/1903.01373)
* [??^?? -Rank: Practically Scaling ??-Rank through Stochastic Optimisation](https://arxiv.org/abs/1909.11628)
* [A Game Theoretic Framework for Model Based Reinforcement Learning](https://arxiv.org/abs/2004.07804)
* [Fictitious Self-Play in Extensive-Form Games](http://proceedings.mlr.press/v37/heinrich15.pdf)
* [An Analysis of Stochastic Game Theory for Multiagent Reinforcement Learning](https://www.cs.cmu.edu/~mmv/papers/00TR-mike.pdf)
* [Combining Deep Reinforcement Learning and Search for Imperfect-Information Games](https://arxiv.org/pdf/2007.13544)
* [Real World Games Look Like Spinning Tops](https://arxiv.org/pdf/2004.09468)
* [PSRO: A Unified Game-Theoretic Approach to Multiagent Reinforcement Learning](https://arxiv.org/pdf/1711.00832)
* [Pipeline PSRO: A Scalable Approach for Finding Approximate Nash Equilibria in Large Games](https://arxiv.org/pdf/2006.08555)
* [A Game-Theoretic Model and Best-Response Learning Method for Ad Hoc Coordination in Multiagent Systems](https://arxiv.org/pdf/1506.01170)
* [Neural Replicator Dynamics: Multiagent Learning via Hedging Policy Gradients](http://www.ifaamas.org/Proceedings/aamas2020/pdfs/p492.pdf)


## Hierarchical
* [Hierarchical multi-agent reinforcement learning](https://apps.dtic.mil/sti/pdfs/ADA440418.pdf)
* [Hierarchical Cooperative Multi-Agent Reinforcement Learning with Skill Discovery](https://arxiv.org/pdf/1912.03558)
* [Hierarchical Critics Assignment for Multi-agent Reinforcement Learning](https://arxiv.org/pdf/1902.03079)
* [Hierarchical Reinforcement Learning for Multi-agent MOBA Game](https://arxiv.org/pdf/1901.08004)
* [Hierarchical Deep Multiagent Reinforcement Learning with Temporal Abstraction](https://arxiv.org/pdf/1809.09332)
* [HAMA???Multi-Agent Actor-Critic with Hierarchical Graph Attention Network](https://ojs.aaai.org/index.php/AAAI/article/download/6214/6070)

## Ad Hoc Teamwork
* [CollaQ???Multi-Agent Collaboration via Reward Attribution Decomposition](https://arxiv.org/pdf/2010.08531)
* [A Game-Theoretic Model and Best-Response Learning Method for Ad Hoc Coordination in Multiagent Systems](https://arxiv.org/pdf/1506.01170)
* [Half Field Offense: An Environment for Multiagent Learning and Ad Hoc Teamwork](https://www.cse.iitb.ac.in/~shivaram/papers/hmsks_ala_2016.pdf)

## League Training
* [AlphaStar???Grandmaster level in StarCraft II using multi-agent reinforcement learning](https://www.gwern.net/docs/rl/2019-vinyals.pdf)

## Curriculum Learning
* [Diverse Auto-Curriculum is Critical for Successful Real-World Multiagent Learning Systems](https://arxiv.org/abs/2102.07659)
* [From Few to More: Large-Scale Dynamic Multiagent Curriculum Learning](https://arxiv.org/abs/1909.02790)
* [EPC???Evolutionary Population Curriculum for Scaling Multi-Agent Reinforcement Learning](https://arxiv.org/pdf/2003.10423)
* [Emergent Tool Use From Multi-Agent Autocurricula](https://arxiv.org/pdf/1909.07528)
* [Learning to Teach in Cooperative Multiagent Reinforcement Learning](https://ojs.aaai.org/index.php/AAAI/article/download/4570/4448)
* [StarCraft Micromanagement with Reinforcement Learning and Curriculum Transfer Learning](https://arxiv.org/pdf/1804.00810)
* [Cooperative Multi-agent Control using deep reinforcement learning](http://ala2017.it.nuigalway.ie/papers/ALA2017_Gupta.pdf)

## Mean Field
* [Mean Field Multi-Agent Reinforcement Learning](http://proceedings.mlr.press/v80/yang18d/yang18d.pdf)
* [Efficient Ridesharing Order Dispatching with Mean Field Multi-Agent Reinforcement Learning](https://arxiv.org/pdf/1901.11454)
* [Bayesian Multi-type Mean Field Multi-agent Imitation Learning](https://www.researchgate.net/profile/Wen_Dong5/publication/347240659_Bayesian_Multi-type_Mean_Field_Multi-agent_Imitation_Learning/links/5fd8c3b245851553a0bb78b1/Bayesian-Multi-type-Mean-Field-Multi-agent-Imitation-Learning.pdf)

## Transfer Learning
* [A Survey on Transfer Learning for Multiagent Reinforcement Learning Systems](https://www.jair.org/index.php/jair/article/download/11396/26482)
* [Parallel Knowledge Transfer in Multi-Agent Reinforcement Learning](https://arxiv.org/pdf/2003.13085)

## Meta Learning
* [A Policy Gradient Algorithm for Learning to Learn in Multiagent Reinforcement Learning](https://arxiv.org/pdf/2011.00382)
* [Continuous Adaptation via Meta-Learning in Nonstationary and Competitive Environments](https://arxiv.org/pdf/1710.03641.pdf?source=post_page---------------------------)

## Fairness 
* [FEN???Learning Fairness in Multi-Agent Systems](https://arxiv.org/pdf/1910.14472)
* [Fairness in Multiagent Resource Allocation  with Dynamic and Partial Observations](https://hal.archives-ouvertes.fr/hal-01808984/file/aamas-distrib-fairness-final.pdf)
* [Fairness in Multi-agent Reinforcement Learning for Stock Trading](https://arxiv.org/pdf/2001.00918)

## Exploration
* [EITI/EDTI???Influence-Based Multi-Agent Exploration](https://arxiv.org/pdf/1910.05512)
* [MAVEN???Multi-Agent Variational Exploration](https://arxiv.org/pdf/1910.07483)
* [CM3: Cooperative Multi-goal Multi-stage Multi-agent Reinforcement Learning](https://arxiv.org/pdf/1809.05188)
* [Coordinated Exploration via Intrinsic Rewards for Multi-Agent Reinforcement Learning](https://arxiv.org/pdf/1905.12127)
* [Exploration by Maximizing Renyi Entropy for Reward-Free RL Framework](https://arxiv.org/abs/2006.06193v3)
* [Exploration-Exploitation in Multi-Agent Learning: Catastrophe Theory Meets Game Theory](https://arxiv.org/abs/2012.03083v2)
* [LIIR: Learning Individual Intrinsic Reward in Multi-Agent Reinforcement Learning](http://papers.neurips.cc/paper/8691-liir-learning-individual-intrinsic-reward-in-multi-agent-reinforcement-learning.pdf)
* [Social Influence as Intrinsic Motivation  for Multi-Agent Deep Reinforcement Learning](http://proceedings.mlr.press/v97/jaques19a/jaques19a.pdf)

## Graph Neural Network 
* [Multi-Agent Game Abstraction via Graph Attention Neural Network](https://ojs.aaai.org/index.php/AAAI/article/view/6211/6067)
* [Graph Convolutional Reinforcement Learning for Multi-Agent Cooperation](https://arxiv.org/abs/1810.09202v1)
* [Multi-Agent Reinforcement Learning with Graph Clustering](https://arxiv.org/pdf/2008.08808)
* [Learning to Coordinate with Coordination Graphs in Repeated Single-Stage Multi-Agent Decision Problems](http://proceedings.mlr.press/v80/bargiacchi18a/bargiacchi18a.pdf)

## Model-based
* [Model-based Multi-Agent Reinforcement Learning with Cooperative Prioritized Sweeping](https://arxiv.org/pdf/2001.07527)

## NAS
* [MANAS: Multi-Agent Neural Architecture Search](https://arxiv.org/pdf/1909.01051)

## Safe Multi-Agent Reinforcement Learning
* [MAMPS: Safe Multi-Agent Reinforcement Learning via Model Predictive Shielding](https://arxiv.org/pdf/1910.12639)
* [Safer Deep RL with Shallow MCTS: A Case Study in Pommerman](https://arxiv.org/pdf/1904.05759)

## From Single-Agent to Multi-Agent
* [IQL???Multi-Agent Reinforcement Learning: Independent vs. Cooperative Agents](https://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.84.3701&rep=rep1&type=pdf)
* [IPPO???Is Independent Learning All You Need in the StarCraft Multi-Agent Challenge?](https://arxiv.org/pdf/2011.09533)
* [MAPPO???The Surprising Effectiveness of MAPPO in Cooperative, Multi-Agent Games](https://arxiv.org/pdf/2103.01955)
* [MADDPG???Multi-Agent Actor-Critic for Mixed Cooperative-Competitive Environments](https://arxiv.org/pdf/1706.02275.pdf&quot;&gt;Multi-Agent)

## Discrete-Continuous Hybrid Action Space / Parameterized Action Space
* [Deep Reinforcement Learning in Parameterized Action Space](https://arxiv.org/pdf/1511.04143)
* [DMAPQN: Deep Multi-Agent Reinforcement Learning with Discrete-Continuous Hybrid Action Spaces](https://arxiv.org/pdf/1903.04959)
* [H-PPO: Hybrid actor-critic reinforcement learning in parameterized action space](https://arxiv.org/pdf/1903.01344)
* [P-DQN: Parametrized Deep Q-Networks Learning: Reinforcement Learning with Discrete-Continuous Hybrid Action Space](https://arxiv.org/pdf/1810.06394)

## Role
* [ROMA: Multi-Agent Reinforcement Learning with Emergent Roles](https://openreview.net/pdf?id=RQP2wq-dbkz)
* [RODE: Learning Roles to Decompose Multi-Agent Tasks](https://arxiv.org/pdf/2010.01523)

## Diversity
* [Diverse Auto-Curriculum is Critical for Successful Real-World Multiagent Learning Systems](https://arxiv.org/pdf/2102.07659)
* [Q-DPP???Multi-Agent Determinantal Q-Learning](http://proceedings.mlr.press/v119/yang20i/yang20i.pdf)
* [Diversity is All You Need: Learning Skills without a Reward Function](https://arxiv.org/pdf/1802.06070)
* [Modelling Behavioural Diversity for Learning in Open-Ended Games](https://arxiv.org/pdf/2103.07927)
* [Diverse Agents for Ad-Hoc Cooperation in Hanabi](https://arxiv.org/pdf/1907.03840)
* [Generating Behavior-Diverse Game AIs with Evolutionary Multi-Objective Deep Reinforcement Learning](https://nos.netease.com/mg-file/mg/neteasegamecampus/art_works/20200812/202008122020238603.pdf)
* [Quantifying environment and population diversity in multi-agent reinforcement learning](https://arxiv.org/pdf/2102.08370)

## Multi-Agent Path Finding
* TODO

## TODO
* Multi-Agent Path Finding

