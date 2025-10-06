# Length-aware dynamic Sampling for Policy Optimization

Our code is based on verl[https://github.com/volcengine/verl], specifically, the implementation in DAPO.

# Installation

Please follow the official installation guide of verl. Specifically, you need to additionally install math_verify to match the exact performance as our reported results (very important!).

# Reimplement Results

## Preparing Data

We have provide the exact data we use in ```data/```. 

However, you can also re-prepare the data following the GRESO repo as we use the exact same prompt and training data[https://github.com/Infini-AI-Lab/GRESO/]. 


## Running Experiments

We have provided one example bash script to showcase how to run each variant of the algorithm. You can find the script in ```recipes/dapo/```.

Specifically, currently the code is ran on one node with 4 GPUs. You can change according to your need.