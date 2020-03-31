[//]: # (Image References)

[image1]: https://user-images.githubusercontent.com/10624937/42135619-d90f2f28-7d12-11e8-8823-82b970a54d7e.gif "Trained Agent"

# Project 1: Navigation

### Introduction

For this project, you will train an agent to navigate (and collect bananas!) in a large, square world.  

![Trained Agent][image1]

A reward of +1 is provided for collecting a yellow banana, and a reward of -1 is provided for collecting a blue banana.  Thus, the goal of your agent is to collect as many yellow bananas as possible while avoiding blue bananas.  

The state space has 37 dimensions and contains the agent's velocity, along with ray-based perception of objects around agent's forward direction.  Given this information, the agent has to learn how to best select actions.  Four discrete actions are available, corresponding to:
- **`0`** - move forward.
- **`1`** - move backward.
- **`2`** - turn left.
- **`3`** - turn right.

The task is episodic, and in order to solve the environment, your agent must get an average score of +13 over 100 consecutive episodes.

### Requirements
* Conda
* jupyter-notebook

### Getting Started

1. Create (and activate) a new environment with Python 3.6.

	- __Linux__ or __Mac__: 
	```bash
	conda create --name drlnd python=3.6
	source activate drlnd
	```
	- __Windows__: 
	```bash
	conda create --name drlnd python=3.6 
	activate drlnd
	```
	
2. Clone the drl repository ( https://github.com/udacity/deep-reinforcement-learning). 
```bash
git clone https://github.com/udacity/deep-reinforcement-learning.git

```

3. Clone this repository, replace requirements.txt in dlr repository file with requirements.txt file from this repository. (To fix Dependency issues for Tensorflow, Torch, ...)
Then install dependencies.
```bash
git clone https://github.com/Python35/drl_p1_navigation.git
cp drl_p1_navigation/requirements.txt deep-reinforcement-learning/python/requirements.txt 
cd deep-reinforcement-learning/python/
pip install .
```

4. Create an [IPython kernel](http://ipython.readthedocs.io/en/stable/install/kernel_install.html) for the `drlnd` environment and then change directory o this repository.  
```bash
python -m ipykernel install --user --name drlnd --display-name "drlnd"
cd ../../drl_p1_navigation/
```

5. Download the environment from one of the links below.  You need only select the environment that matches your operating system:
    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P1/Banana/Banana_Windows_x86_64.zip)
    

6. Place the file in this GitHub repository, in the root folder, and unzip (or decompress) the file. 

5. Open Jupyter notebook
```bash
jupyter-notebook
```

6. Before running code in a notebook, change the kernel to match the `drlnd` environment by using the drop-down `Kernel` menu. 


### Instructions

Follow the instructions in `Navigation.ipynb` to train an agent.  

