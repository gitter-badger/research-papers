# research-papers

[![Join the chat at https://gitter.im/deep-learning-ai-research/research-papers](https://badges.gitter.im/deep-learning-ai-research/research-papers.svg)](https://gitter.im/deep-learning-ai-research/research-papers?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
List of curated research papers on A.I. and Deep Learning

Grid Long Short-Term Memory, DeepMind
https://arxiv.org/abs/1507.01526

This paper introduces Grid Long Short-Term Memory, a network of LSTM cells arranged in a multidimensional grid that can be applied to vectors, sequences or higher dimensional data such as images. The network differs from existing deep LSTM architectures in that the cells are connected between network layers as well as along the spatiotemporal dimensions of the data. The network provides a unified way of using LSTM for both deep and sequential computation. We apply the model to algorithmic tasks such as 15-digit integer addition and sequence memorization, where it is able to significantly outperform the standard LSTM. We then give results for two empirical tasks. We find that 2D Grid LSTM achieves 1.47 bits per character on the Wikipedia character prediction benchmark, which is state-of-the-art among neural approaches. In addition, we use the Grid LSTM to define a novel two-dimensional translation model, the Reencoder, and show that it outperforms a phrase-based reference system on a Chinese-to-English translation task.

--------------------------------------------------------

Deep Attention Recurrent Q-Network
https://arxiv.org/abs/1512.01693

A deep learning approach to reinforcement learning led to a general learner able to train on visual input to play a variety of arcade games at the human and superhuman levels. Its creators at the Google DeepMind's team called the approach: Deep Q-Network (DQN). We present an extension of DQN by "soft" and "hard" attention mechanisms. Tests of the proposed Deep Attention Recurrent Q-Network (DARQN) algorithm on multiple Atari 2600 games show level of performance superior to that of DQN. Moreover, built-in attention mechanisms allow a direct online monitoring of the training process by highlighting the regions of the game screen the agent is focusing on when making decisions.


--------------------------------------------------------


Reinforced Decision Trees
https://arxiv.org/abs/1505.00908

In order to speed-up classification models when facing a large number of categories, one usual approach consists in organizing the categories in a particular structure, this structure being then used as a way to speed-up the prediction computation. This is for example the case when using error-correcting codes or even hierarchies of categories. But in the majority of approaches, this structure is chosen \textit{by hand}, or during a preliminary step, and not integrated in the learning process. We propose a new model called Reinforced Decision Tree which simultaneously learns how to organize categories in a tree structure and how to classify any input based on this structure. This approach keeps the advantages of existing techniques (low inference complexity) but allows one to build efficient classifiers in one learning step. The learning algorithm is inspired by reinforcement learning and policy-gradient techniques which allows us to integrate the two steps (building the tree, and learning the classifier) in one single algorithm.








