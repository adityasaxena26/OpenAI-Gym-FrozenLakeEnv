# Udacity Deep Learning Nanodegree
## Dynamic Programming
## Reinforcement Learning using OpenAI Gym
### Project: Frozen Lake Environment

In the FrozenLake environment, the agent navigates a 4x4 gridworld.
![Frozen Lake](http://eskipaper.com/images/frozen-lake-6.jpg)

### The Dynamic Programming Setting
Environments in OpenAI Gym are designed with the reinforcement learning setting in mind. For this reason, OpenAI Gym does not allow easy access to the underlying one-step dynamics of the Markov decision process (MDP).

In order to use the FrozenLake environment for the dynamic programming setting, first clone the repository and navigate to the downloaded folder.
```
https://github.com/adityasaxena26/openAI-frozen-lake.git
cd OpenAI-Gym-FrozenLakeEnv
run frozen_lake.py
```
Open Jupyter Noteook
```
open notebook 'frozenlake_dynamic_programming.ipynb'
```
### Softwares Prerequisites:
* Python 3.5+
* Jupyter Notebook

While Jupyter runs code in many programming languages, Python is a requirement (Python 3.3 or greater) for installing the Jupyter Notebook.

For new users, installing Anaconda is highly recommended. Anaconda conveniently installs Python, the Jupyter Notebook, and other commonly used packages for scientific computing and data science.
As an existing Python user, you may wish to install Jupyter using Python’s package manager, ```pip```, instead of Anaconda.

First, ensure that you have the latest pip; older versions may have trouble with some dependencies: ```pip3 install --upgrade pip```

Then install the Jupyter Notebook using:
```pip3 install jupyter```

To run the notebook:
``` jupyter notebook```
* OpenAI Gym
To get started, you’ll need to have Python 3.5+ installed. Simply install gym using pip:

```pip install gym```

The following packages (libraries) need to be installed. You can install these packages via conda or pip.
* NumPy
* Matplotlib
