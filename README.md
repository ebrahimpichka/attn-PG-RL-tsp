# Attention-based Policy Gradient RL for learning to solve Travelling Salesperson Problem


A PyTorch implementation of the attention-based Policy Gradient RL for learning to solve Travelling Salesperson Problem based on the paper https://doi.org/10.1007/978-3-319-93031-2_12 


This project is the PyTorch implementation of the attention-based policy gradient for solving TSP based on the paper [Learning Heuristics for the TSP by Policy Gradient](https://link.springer.com/chapter/10.1007/978-3-319-93031-2_12) [[PDF here]](https://hanalog.ca/wp-content/uploads/2018/11/cpaior-learning-heuristics-6.pdf)

The paper also incorporates a 2-opt heuristic to the RL algorithm, which we did not include here. Please refer to the paper for a more detailed explanation of the methodology.

---

## Architecture

### Neural (transformer) Encoder of the Policy Net
![Fig. 1. Neural (transformer) Encoder of the Policy Net](https://media.springernature.com/lw685/springer-static/image/chp%3A10.1007%2F978-3-319-93031-2_12/MediaObjects/469276_1_En_12_Fig1_HTML.gif?as=webp)

### Neural (pointer) Decoder of the Policy Net
![Fig. 2. Neural (pointer) Decoder of the Policy Net](https://media.springernature.com/lw685/springer-static/image/chp%3A10.1007%2F978-3-319-93031-2_12/MediaObjects/469276_1_En_12_Fig2_HTML.gif?as=webp)

---

## Training

The agent is trained using the REINFORCE (policy gradient) algorithm. refer to the [REINFORCE original paper](https://proceedings.neurips.cc/paper/1999/file/464d828b85b0bed98e80ade0a5c43b0f-Paper.pdf).
