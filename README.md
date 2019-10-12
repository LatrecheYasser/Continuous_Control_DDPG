# Continuous_Control_DDPG

in the 2nd project of the **DRLND** from udacity we will try to train the double-jointed arm agent to move to target locations.

<p align="center">
  <img src="https://video.udacity-data.com/topher/2018/June/5b1ea778_reacher/reacher.gif"/>
</p>

 A reward of +0.1 is provided for each step that the agent's hand is in the goal location. Thus, the goal of the agent is to maintain its position at the target location for as many time steps as possible.

The observation space consists of 33 variables corresponding to position, rotation, velocity, and angular velocities of the arm. Each action is a vector with four numbers, corresponding to torque applicable to two joints. Every entry in the action vector should be a number between -1 and 1.

---
so how to run this project ?

the depepandencies that you need to install inorder to run this project are:

  - numpy
  - matplotlib
  - pytorch
  - pandas
  - jupyter
  - and the Unity ML-Agents (you find below the link to how install it page ) 

or you can install them in defrent ways, by derectly run the folowing scripit in the terminal ` pip install -r requirements.txt `

or you have to create a vertual python env and  install the dependencies . or you can simply follow the instractions below
 - 1 - clone this project 
 - 2 - move to it's folder and open the terminal there 
 - 3 - run `  conda env create -f Continuous_Control_DDPG.yml ` this will create an envirenment and install the needed depandecies automaticly <br/


 and finaly now you will have to install the Unity ML-Agent, inorder to do that just [follow this link](https://github.com/Unity-Technologies/ml-agents/blob/master/docs/Installation.md) <br/>

now if u did all this correctly you are able to run the code. in the same folder run this ` source activate Continuous_Control_DDPG ` than `jupyter notebook`. and yfrom the notebook home page you can open `Continuous_Control_DDPG.jpynb`.

