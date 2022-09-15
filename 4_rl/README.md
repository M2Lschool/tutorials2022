# Colab for the RL tutorial at M2L 2021

**Authors**: Adrià Puigdomènech Badia, Robert Lange and Bojan Vujatovic. Part 1 adapted from [EEML 2020](https://github.com/eemlcommunity/PracticalSessions2020/tree/master/rl) (authors Feryal Behbahani and Gheorghe Comanici).

**Description**: The tutorial covers a number of important reinforcement learning (RL) algorithms, including multi-armed bandits, policy iteration, Q-Learning, deep RL, policy gradient methods and meta RL.
- **Part 1**: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/m2lschool/tutorials2022/blob/main/4_rl/RL_Tutorial_Part1.ipynb) In the first part, we will guide you through the general interaction between RL agents and environments, where the agents ought to take actions in order to maximize returns (i.e. cumulative reward) in the simple multi-armed bandit setting. Next, we will implement Policy Iteration, SARSA, and Q-Learning for a simple tabular environment. The core ideas in the latter will be scaled to more complex MDPs through the use of function approximation. Lastly, we will provide a short introduction to deep reinforcement learning and the DQN algorithm.
- **Part 2**: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/m2lschool/tutorials2022/blob/main/4_rl/RL_Tutorial_Part2.ipynb) In the second part, you will learn how to implement a memory-based meta-RL agent capable of learning its own exploration algorithm in order to solve different bandit environments. This will require implementing a synchronous actor-critic algorithm using policy gradients. We will leverage JAX-based RL environments which allow for easy parallelization of data collection using multiple parallel actors. You will then reproduce parts of the results of the classic 'learning to reinforcement learn' by [Wang et al. (2016)](https://arxiv.org/abs/1611.05763?source=post_page---------------------------) and test the agent's meta-generalization capabilities.


Designed for education purposes. Please do not distribute without permission. Write at organizers@m2lschool.org if you have any question.

You are welcome to reuse this material in other courses or schools, but please reach out to organizers@m2lschool.org if you plan to do so. We would appreciate it if you could acknowledge that the materials come from M2L 2020 and give credits to the authors. Also please keep a link in your materials to the original repo, in case updates occur.

MIT License

Copyright (c) 2020 m2lschool

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
