## Customizing OpenAI Gym Humanoid Environment and Implementing Reinforcement Learning Agents with Stable Baselines

#### The Project

This project was developed for Introdução aos Sistemas Inteligentes e Autónomos. The goal is to explore how we can optimize and alter the learning and behavior of a reinforcement learning agent by manipulating the learning algorithms, the reward system, environment and more.
We used the Mujoco Humanoid from Gymnasium as our chosen environment and the PPO reinforcement learning algorithm from the Stable Baselines library.
We attempt a different approach to learning by dividing the training into 2 phases and adjusting the rewards accordingly. All of the work is document in jupyter notebooks.  

#### Files

- agent_training.ipynb: describes our approach to training different agents and storing the results from training and testing their performance
- result_analysis.ipynb: Analysis of the data obtained from the previous notebook 
- agent_behavior.ipynb: Visualization of the agents interacting with the environment
- agents, logs, rewards: different folders storing data from agent training and testing

#### References:

- [Stable Baselines 3 Tutorial](https://pythonprogramming.net/introduction-reinforcement-learning-stable-baselines-3-tutorial/)
- [Training in a Similar Mujoco Environment](https://gymnasium.farama.org/tutorials/training_agents/reinforce_invpend_gym_v26/#sphx-glr-tutorials-training-agents-reinforce-invpend-gym-v26-py)
- [Environment Wrappers Usage](https://gymnasium.farama.org/tutorials/gymnasium_basics/implementing_custom_wrappers/#sphx-glr-tutorials-gymnasium-basics-implementing-custom-wrappers-py)
