# FrozenLake-played-by-Reinforcement-Q-Learning-Agent
A simple program where the 'Agent' plays the Frozen Lake game environment. The 'Agent' tries to maximize it's rewards using Q Learning.


## Agent-Environment:

![Agent_Environment](/pic/0.png)

## Discounted Rewards:
For continuous 'Actions' we use a Discounted reward system, so that the Agent prioritizes the present reward rather than some future reward.

![Discount](/pic/5.png)

where γ(gamma) is the discounted value

## Bellman Equation for Optimality:

We use the Bellman equation to find the optimal 'q' value

![Bellman](/pic/6.png) 

## Updating Q value:

![Qnew](/pic/2.png) 

![QnewCode](/pic/1.png) 

## Exponential decay for Exploration vs Exploitation:
We use the ε-Greedy algorithm to determine whether the 'Agent' would Explore the environment or Exploit the past information of the environment, gathered overtime. We then we Exponential Decay to reduce the Exploration rate so that at some later timestep, the 'Agent' would select to Exploit rather than Exploring the Environment.

![ExponentialDecay](/pic/n.png)
 
![Edecay](/pic/.png) 


  

  
