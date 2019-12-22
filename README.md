# Simulation_Machine_Learning

Simulation + Machine Learning Demos: https://ilabutk.github.io/Simulation_Machine_Learning/

<hr />

* Demo of Reinforcement Learning within a simulation model built using AnyLogic
> 1. A basic "capture a flag" or "find a treasure box" model in which a "hidden" flag is placed on a `m*n` grid. The player has to capture the flag. When he/she does, a big reward is given; otherwise, a negative reward is imposed.
> 2. One can play "manually". Or enable Q-learning - remember you may increase the simulation speed at the bottom. Say, `x5` or `x10` or `x100` or `x1000`. Q-learning with stop at episode 2000. You may reduce to `x1` after a few hundreds of episode as you may see the `agent` will play decently after some learning. 
> 3. Note the model is on AnyLogic Cloud (https://cloud.anylogic.com/model/3c7a6c87-e23b-4e47-add1-f22bd6a8064b?mode=SETTINGS)
> 4. RL will work for a grid less than about `12*12` without much delay, while it won't work for a grid like `20*20`, nor `100*100` for sure. (Recall 4^(10,000) is HUGE.) What can we do then?? DQN! 

[![RL Demo](https://ilabutk.github.io/Simulation_Machine_Learning/images/cover.png)](https://youtu.be/wUTTcUBYZYk)


* Demo of deep Q-learning network (DQN). A simulation model interacts with DQN built using Python. (to come ...)
