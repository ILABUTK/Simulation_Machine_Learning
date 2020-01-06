# Power of Simulation + Machine Learning and their applications

Simulation + Machine Learning Demos: https://ilabutk.github.io/Simulation_Machine_Learning/

The runnable models are hosted on the Cloud. Detailed documentations and source codes to be added.

<hr />

* Demo of "Capture the Flag" using Reinforcement Learning within a simulation model built using AnyLogic
> 1. A basic "capture the flag" or "find a treasure box" model in which a "hidden" flag is placed on a `m*n` grid. The player has to capture the flag. When he/she does, a big reward is given; otherwise, a negative reward is imposed.
> 2. One can play "manually". Or enable Q-learning - remember you may increase the simulation speed at the bottom. Say, `x5` or `x10` or `x100` or `x1000`. Q-learning with stop at episode 2000. You may reduce to `x1` after a few hundreds of episode as you may see the `agent` will play decently after some learning. 
> 3. Note the model is on AnyLogic Cloud (https://cloud.anylogic.com/model/3c7a6c87-e23b-4e47-add1-f22bd6a8064b?mode=SETTINGS)
> 4. RL will work for a grid, e.g., `12*12`, without much delay, while it won't work for a grid like `100*100` without a lengthy computation. (Recall 4^(10,000) is HUGE.) What can we do then? DQN! (Actually there are a few things that we can try. E.g., adding a MAX_STEP inside each episode seems to work well.)

[![RL Demo](https://ilabutk.github.io/Simulation_Machine_Learning/images/cover.png)](https://youtu.be/wUTTcUBYZYk)

* Demo of flocks of battling boids
```
Original Boids, developed by Craig Reynolds, is an artificial life program, simulating the flocking behavior of
birds. As with most artificial life simulations, Boids is an example of emergent behavior; that is, the complexity of Boids
arises from the interaction of individual agents adhering to a set of simple rules, like separation (steer to avoid
crowding), alignment (steer towards the average heading of local flockmates), cohesion (steer to move toward the
average position of local flockmates). This AnyLogic model adds diversity of boids (there are four different colors) and
attacking/retreating behavior. The model features fascinating animation of battle boids and capability to inject
boids at runtime.
```

* Demo of an air defense system (agent-based modeling)
```
A model of an air defense system protecting a number of assets being attacked by aircrafts, made by AnyLogic. The assets 
are located nearby the seashore and are protected by three radars. Bomber aircrafts are trying to destroy the assets. Each aircraft is assigned a particular asset when launched. Radar has a limited coverage zone and can concurrently control only a
limited number of missiles. You can interactively control several parameters of the model, including the aircraft speed,
radar properties, etc. This agent based model features continuous time behavior (differential equations) inside the agents.
```

* Demo of an ED department
```
This is a simulation of a Level II Trauma Center, based on AnyLogic model. The center receives over 40,000 patient
visits per year. The hospital facilities include a specialized Express Care unit and Emergency Department area. EC area
has its own staff adjacent to the Emergency Department. The model was developed to help analyze several improvement
options such as, staff levels and schedules, Express Care hours of operation. Experiments also include changing and
designing new management function, adding bedside registration process.
```

* Demo of a call center
```
A model of a call center with two types of agents with different skills and two types of incoming calls. The model
focuses of call routing. The calls arrive at certain rates and are placed in queues (one queue for each call type). 
Some callers abandon from the queue after a certain waiting time. There are two agent groups, each trained to handle a particular call type. However the agents are also cross-trained so that they can handle calls of different type, 
yet less efficiently. The logic for call routing is the following: a call is routed to the “native” agent, if there is 
oneavailable; otherwise, the call is routed to the “alien” agent, again if the latter is idle. The output metrics in
this model are the queue lengths and “service levels” for both call types. All parameters can be changed on-the-fly,
including the routing options. Built by AnyLogic.
```

* Demo of a aircraft fleet planning optimization
```
The model of management of aircraft fleet. Built by AnyLogic. The fleet consists of 20 aircrafts that need regular 
maintenance. There are two types of maintenance: week-based maintenance, which is scheduled according to the amount 
of weeks the aircraft is operated, and Hours-based maintenance is scheduled according to the amount of hours the 
aircraft has flown since last maintenance. The entire fleet has weekly planned rate of effort (in hours). 
If the fleet did not manage to operate this amount of time, the remaining hours (hours to catch up) are added to the 
next week's plan. You can play with individual rates of effort to minimize the amount of time to catch up. Alternatively, 
you can use the built-in OptQuest optimizer.
```

* Demo of deep Q-learning network (DQN). A simulation model interacts with DQN built using Python. 
```
Using PyTorch DNN. To come ...
```

