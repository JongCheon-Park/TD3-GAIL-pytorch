# TD3-GAIL pytorch

PyTorch implementation of TD3-GAIL tested on the following environments:

- [Bipedal Walker v2](http://gym.openai.com/envs/BipedalWalker-v2/) 

- [Lunar Lander Continuous v2](http://gym.openai.com/envs/LunarLanderContinuous-v2/) 

- [Walker2d v1 (Roboschool)](https://github.com/openai/roboschool)

- [HalfCheetah v1 (Roboschool)](https://github.com/openai/roboschool)


TD3-GAIL is the recovered reward function based reinforcement learning that fusion of TD3 and GAIL.
TD3-GAIL shows good learning performance compared with GAIL and DDPG-GAIL.

### Usage

- To train the TD3-GAIL, run the 'train.py'
- To test the trained TD3-GAIL, run the 'test.py'

## Requirements
```
Python 3.6
PyTorch 1.5.0
NumPy 1.19.5
gym 0.15.4
Roboschool 1.0.34
Pillow 7.0.0
```
## References

[1] [Official TD3 Code] (https://github.com/sfujim/TD3)  
[2] [DGAIL] (https://github.com/nikhilbarhate99/Deterministic-GAIL-PyTorch)  
