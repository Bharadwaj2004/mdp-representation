# MDP REPRESENTATION

## AIM:
Write your aim here

## PROBLEM STATEMENT:
To develop an environment in which a person is cycling Parachuting. The goal is to reach the ground.
### Problem Description
The agent has to reach the goal state(ground) by taking the correct route towards the goal without drifting away from the path. After reaching the goal the agent will be rewarded if not then no reward will be provided.

### State Space
{0,1,2}

### Sample State
0->Hole State(sitting in plane) 1->starting state(jump from plane) 2->Goal state(Reaching ground)

### Action Space
{1,2}

### Sample Action
0->Moving down 1->Moving up

### Reward Function
Reward: +1 if the agent reaches goal state. 0 if the agent reaches the hole state.

### Graphical Representation
![output](![WhatsApp Image 2024-03-05 at 15 13 08_f189157e](https://github.com/Bharadwaj2004/mdp-representation/assets/119560345/1525fa2d-8009-4ecc-9d9b-a1ea1b9952db)
)

## PYTHON REPRESENTATION:
```python
Name: Venkata Bharadwaj B
Reg No: 212222240020
```
```python

import gym
import gym_walk
P={0: {0: [(1.0, 0, 0.0, True)],
       1: [(1.0, 0, 0.0, True)]},
   1: {0: [(0.57, 0, 0.0, True),(0.43,2,1,True)],
       1: [(0.57, 2, 1.0, True),(0.43,0,0,True)]},
   2: {0: [(1.0, 2, 0.0, True)],
       1: [(1.0, 2, 0.0, True)]}
  }
```

## OUTPUT:
![output](![Screenshot (73)](https://github.com/Bharadwaj2004/mdp-representation/assets/119560345/f650292d-fd3c-4ffe-8ab1-ecb43f0d5b00)
)

## RESULT:
Thus the given real world problem is successfully represented in a MDP form .

