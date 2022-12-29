Some things I have written or participated in:

## OpenELM (Evolution through Large Models)
https://github.com/CarperAI/OpenELM

This is a work in progress with Carper AI to replicate the paper [Evolution through Large Models](https://arxiv.org/abs/2206.08896) in open-source domain.

ELM makes use of LLM's capacity for code generations and mutations to perform evolution methods such as MAP-Elites. In turn, it uses the generated data and RL finetuning to further align LLM with the given task. We have implemented the evolution and LM pipelines except for the RL finetuning components. We use models finetuned on Github commits, and we will also gradually release them.

## Architext
https://github.com/CarperAI/ArchitextRL

Helping with the integration of Architext with ELM.

Architext is a Carper AI project that makes use of Language models to generate presentations of architecture designs. 


## Reinforcement learning of Hironaka's polyhedra game 
https://github.com/honglu2875/hironaka

Our commonsense favors spaces that can be locally parametrized as products of coordinate lines. They are called smooth points, manifolds, locally Euclidean spaces, etc. depending on where you come from.  But there are many other spaces that cannot be described like that, and we call them singularities. A common way to handle them is to convert singularities back to the smooth points: resolution of singularities. The existence of resolution of singularites in characteristic $0$ was a Fields medal result by Hironaka, as this process has been deeply weaved into algebraic geometry and influenced other branches of geometry.

An old but overlooked angle about this is that: Resolving singularities can be a Markov Decision Process. With the rise of modern deep reinforcement learning, we present the repo that implements multiple deep RL methods (gym+stablebaseline3; DQN with PyTorch DDP + MAP-Elites; AlphaZero using JAX) applied on resolution of singularities.


## some side projects
https://github.com/honglu2875/fmlang_env
https://github.com/honglu2875/Bookit-proof-of-concept.git
https://github.com/honglu2875/weirdonetworks.git (really old)
