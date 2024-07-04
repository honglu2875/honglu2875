I currently work with [poolside](https://poolside.ai) on a variety of stuff. In the free time, I also do some hobby projects.

============

Some things I have written or participated in the past:

## Aria
https://github.com/EleutherAI/aria
Wanna make some music?

## Thing
https://github.com/honglu2875/thing
Catch your tensors quietly in your running codes and send them to your python console for inspection.

## Mistral model in JAX
https://github.com/honglu2875/mistral_jax
You know what it is if you are familiar with OSS LLM ;)

## YaRN, a context length extension of RoPE
Together with Bowen, Jeff and Enrico, we posted a [preprint](https://arxiv.org/abs/2309.00071) regarding how to extend the context window of models using RoPE embedding (such as Llama families). Enrico trained a few amazing models such as this [Llama-2 128k-context](https://huggingface.co/conceptofmind/Yarn-Llama-2-7b-128k). It is quite amazing. I tried to feed it with the whole Pride and Prejudice and did manual Q&A of the novel. It did great! Bowen tried Sherlock Holmes. It wasn't perfect but it was definitely working!

Our research (i.e, hacky) implementation: [https://github.com/jquesnelle/yarn](https://github.com/jquesnelle/yarn).

## an IR that generates pytorch and JAX codes (WIP)
Tired of jumping back and forth between PyTorch and JAX? I'm making an amateur shot here by starting with an Intermediate Representation as a graph and performs codegen on PyTorch and JAX. Still a lot of things to sort out but a basic version is starting to work... **Still not usable** (will remove it once I'm happy by myself)

## LLM foundation model at Multi Tech Inc.
(models and codes are not available for now)

Trained multiple 3B-13B foundation model using various datasets totalling 1.5 trillion tokens. Focused on the ability of code synthesis and financial document generation/retrieval. Long context length (8192). FSDP with 640 A-100.

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

Human intuition favors spaces that are locally modelled by products of coordinate lines (locally $\mathbb R^n$). They are called smooth spaces, manifolds, locally Euclidean spaces, etc. depending on your math background. But there are many other spaces that cannot be described like that, and we call them **singularities**. A common way to handle them is to convert singularities back to the smooth points: resolution of singularities. The existence of resolution of singularites in characteristic $0$ was a Fields medal result by Hironaka, as this process has been deeply weaved into algebraic geometry and influenced other branches of geometry.

An old but overlooked angle about this is that: Resolving singularities can be a Markov Decision Process. With the rise of modern deep reinforcement learning, we present the repo that implements multiple deep RL methods (gym+stablebaseline3; DQN with PyTorch DDP + MAP-Elites; AlphaZero using JAX) applied on resolution of singularities.


## some side projects
https://github.com/honglu2875/fmlang_env (planned to do "RL with interpreter feedback")

https://github.com/honglu2875/Bookit-proof-of-concept.git (was learning Kotlin with a hands-on project)
