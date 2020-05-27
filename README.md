## Introduction
This is a full world training model, to achieve the goal of training an AI to learn car racing game using reinforcement learning.
It's is inspired by the [World Models](https://worldmodels.github.io/) by David Ha, Jürgen Schmidhuber.


## Installation
```
conda create -n masterai python=3.6
conda activate masterai
conda install -c conda-forge tensorflow==1.10.0
python -m pip install cma==2.6.0
conda install -c intel mpi4py
conda install -c conda-forge pybox2d
pip install pillow==5.4.1
pip install gym==0.9.4
pip install -r requirement.txt
```

## Run the model 
```
conda activate masterai
cd .\Inference\
python .\full_world_model.py
```
![IMAGE](https://nikeshthapa.tech/car1.png)