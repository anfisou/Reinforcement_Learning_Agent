# English Version

This project was developed for the subject 'Introdução a Sistemas Autónomos e Inteligentes' by the students [André Sousa](https://github.com/anfisou), [David Scarin](https://github.com/davidmscarin) and [Paulo Silva](https://github.com/WrekingPanda).

#### The Project

The goal is to explore how we can alter (and maybe optimize) the learning and behavior of a reinforcement learning agent by manipulating the learning algorithms, the reward system, environment and more.
We used the Mujoco Humanoid from OpenAI Gymnasium as our chosen environment and the PPO reinforcement learning algorithm from the Stable Baselines library.
We attempt a different approach to learning by dividing the training into 2 phases and adjusting the rewards accordingly. All of the work is document in jupyter notebooks.  
As the goal of the environment is for the agent to learn how to walk, we tested how would the learning process change if instaed of just learning how to walk, the agent firstly learned how to stand without falling, which should be a much simpler task, and only then try to learn how to walk. We implemented this by changing the weights of the different rewards.

#### Files

- agent_training.ipynb: describes our approach to training different agents and storing the results from training and testing their performance
- result_analysis.ipynb: Analysis of the data obtained from the previous notebook 
- agent_behavior.ipynb: Visualization of the agents interacting with the environment

#### References:

- [Stable Baselines 3 Tutorial](https://pythonprogramming.net/introduction-reinforcement-learning-stable-baselines-3-tutorial/)
- [Training in a Similar Mujoco Environment](https://gymnasium.farama.org/tutorials/training_agents/reinforce_invpend_gym_v26/#sphx-glr-tutorials-training-agents-reinforce-invpend-gym-v26-py)
- [Environment Wrappers Usage](https://gymnasium.farama.org/tutorials/gymnasium_basics/implementing_custom_wrappers/#sphx-glr-tutorials-gymnasium-basics-implementing-custom-wrappers-py)


# Versão Portuguesa

Este projeto foi desenvolvido no âmbito da unidade curricular 'Introdução a Sistemas Autónomos e Inteligentes' pelos alunos [André Sousa](https://github.com/anfisou), [David Scarin](https://github.com/davidmscarin) e [Paulo Silva](https://github.com/WrekingPanda).

#### The Project

O objetivo do porjeto é explorar como podemos alterar (e talvez otimizar) a aprendizagem e o comportamento de um agente de aprendizagem por reforço, manipulando os algoritmos de aprendizagem, o sistema de recompensas, o ambiente e mais.
Utilizamos o Humanoid do Mujoco do OpenAI Gymnasium como nosso ambiente escolhido e o algoritmo de aprendizado por reforço PPO da biblioteca Stable Baselines.
Experimentamos uma abordagem diferente de aprendizagem, dividindo o treino em 2 fases e ajustando as recompensas. Todo o trabalho está documentado em Jupyter notebooks.
Como o objetivo do ambiente é fazer com que o agente aprenda a andar, testamos como o processo de aprendizagem mudaria se, em vez de simplesmente aprender a andar, o agente primeiro aprendesse a ficar em pé sem cair, o que deveria ser uma tarefa muito mais simples, e apenas depois tentasse aprender a andar. Implementamos isso alterando os pesos das diferentes recompensas.

#### Ficheiros

- agent_training.ipynb: Implementação da mudança sugerida e treino dos diferentes agents, bem como guardar a sua performance para futura análise
- result_analysis.ipynb: Análise dos dados obtidos no notebook anterior 
- agent_behavior.ipynb: Visualização dos agentes a interagir com o ambiente

#### Referências:

- [Stable Baselines 3 Tutorial](https://pythonprogramming.net/introduction-reinforcement-learning-stable-baselines-3-tutorial/)
- [Training in a Similar Mujoco Environment](https://gymnasium.farama.org/tutorials/training_agents/reinforce_invpend_gym_v26/#sphx-glr-tutorials-training-agents-reinforce-invpend-gym-v26-py)
- [Environment Wrappers Usage](https://gymnasium.farama.org/tutorials/gymnasium_basics/implementing_custom_wrappers/#sphx-glr-tutorials-gymnasium-basics-implementing-custom-wrappers-py)
