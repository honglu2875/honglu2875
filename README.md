I used to work with [poolside](https://poolside.ai) on a variety of stuff. In the free time, I also do some hobby projects.

============

For what it is worth, here are some toy projects and open-source research projects that I am able to share:

## Aria
[https://github.com/EleutherAI/aria](https://github.com/EleutherAI/aria)
Wanna make some music?
We have a much better music generation model now but some older samples can be listened to here: [https://honglu.fan/files/](https://honglu.fan/files/)

## some code for TPU inference
[https://github.com/honglu2875/mistral_jax](https://github.com/honglu2875/jaxml)
This is something a person would attempt when you are only given a few TPUs and you don't like the current TPU inferencing library ;)

## YaRN, a context length extension of RoPE
Together with Bowen, Jeff and Enrico, we posted a [preprint](https://arxiv.org/abs/2309.00071) regarding how to extend the context window of models using RoPE embedding (such as Llama families). Enrico trained a few amazing models such as this [Llama-2 128k-context](https://huggingface.co/conceptofmind/Yarn-Llama-2-7b-128k). I tried to feed it with the whole Pride and Prejudice and did manual Q&A of the novel. Bowen tried Sherlock Holmes. It wasn't perfect but it did great on those novels! 

## Thing
https://github.com/honglu2875/thing
An attempt to build a tool that catches your tensors quietly in your running codes and send them to another python console for inspection.

## Reinforcement learning of Hironaka's polyhedra game 
https://github.com/honglu2875/hironaka

Human intuition favors spaces that are locally modelled by products of coordinate lines (locally $\mathbb R^n$). They are called smooth spaces, manifolds, locally Euclidean spaces, etc. depending on your math background. But there are many other spaces that cannot be described like that, and we call them **singularities**. A common way to handle them is to convert singularities back to the smooth points: resolution of singularities. The existence of resolution of singularites in characteristic $0$ was a Fields medal result by Hironaka, as this process has been deeply weaved into algebraic geometry and influenced other branches of geometry.

An old but overlooked angle about this is that: Resolving singularities can be a Markov Decision Process. With the rise of modern deep reinforcement learning, we present the repo that implements multiple deep RL methods (gym+stablebaseline3; DQN with PyTorch DDP + MAP-Elites; AlphaZero using JAX) applied on resolution of singularities.
