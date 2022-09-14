# Colab for the Generative Models tutorial at M2L 2022

**Authors**: **[Fabio Viola](https://scholar.google.co.uk/citations?user=-cCry1cAAAAJ&hl=en)** and **[Nemanja Rakicevic](https://nemanja-rakicevic.github.io/)**.


### Introduction

In this tutorial you will learn how to implement Variational AutoEncoders. We will focus on several approaches to modelling the posterior distribution function, as well as approaches to optimisation that are used to train the models.

We will investigate the reconstruction quality, latent space coverage and the losses, in order to gain intuition about the different properties of the studied models and optimisation procedures.


### Outline

The tutorial is structured as follows:
- Setup
	- Download and install packages
	- Imports
- Dataset
	- Import data
	- Helper functions
- Amortized Variational Inference
	- Posterior function modelling
	- Losses
	- Training VAEs using constraint optimization (GECO)
- Practical Excercise
	- Model Implementations
	- Tasks and Conclusion


### Useful links

+ Tutorial: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/m2lschool/tutorials2022/blob/main/3_generative/VAE_Tutorial.ipynb)
+ Solved Tutorial: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/m2lschool/tutorials2022/blob/main/3_generative/VAE_Tutorial_Solutions.ipynb)


### Libraries and Frameworks

All exercises will be implemented using [JAX](https://github.com/google/jax) for low level operations and [haiku](https://github.com/deepmind/dm-haiku) to model neural network modules, and [optax](https://github.com/deepmind/optax) for training optimization. In addition, we will use [datasets](https://github.com/huggingface/datasets) and [distrax](https://github.com/deepmind/distrax) for probability distribution modelling.


### Credits

This tutorial is adapted from the [EEML 2019](https://github.com/eemlcommunity/PracticalSessions2019/tree/master/unsupervised) and [EEML 2020](https://github.com/eemlcommunity/PracticalSessions2020/tree/master/unsup) Unsupervised Learning tutorials authored by Mihaela Rosca, David Szepesvari and Stanislaw Jastrzebski.


### License

Designed for education purposes. Please do not distribute without permission. Write at organizers@m2lschool.org if you have any question.

You are welcome to reuse this material in other courses or schools, but please reach out to organizers@m2lschool.org if you plan to do so. We would appreciate it if you could acknowledge that the materials come from M2L 20202 and give credits to the authors. Also please keep a link in your materials to the original repo, in case updates occur.

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
