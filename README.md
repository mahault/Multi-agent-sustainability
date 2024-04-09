# Multi-agent-sustainability

A multi-agent reinforcement learning task.
A very simple environment:
9 grid squares, 2 agents. 
There is water on a grid square, food on another grid square.
water and food deplete after an unknown number of acquisition by the agents. The water and food can return after an unknown number of timesteps.
The agents can communicate that they found water or food (and the location on the grid of the food or water), and they can communicate their beliefs about the number of times the food or water can be acquired, as well as their beliefs about the repleting rate (1food/xtimestep  - 1water/xtimestep)
The agents must consume food and water. If they have not consumed food every 7 timesteps, they die (they terminate). If they have not consumed water every 3 timesteps, they die.
They must both consume water and food. they must ensure the environment is never depleted, and they should ideally both survive. 

The goal of the agents is to do reinforcement learning to figure out to optimal way to forage food and water, and do so by communicating. 
