# Q-learning Jupyter Notebook
This Jupyter Notebook contains an implementation of the Q-learning algorithm for the FrozenLake-v1 environment provided by the OpenAI Gym. The implementation allows the user to train the agent with the algorithm and evaluate its performance by generating a GIF of its behavior.

# Dependencies
To run this Jupyter Notebook, the following dependencies are required:

- gym
- matplotlib
- numpy
- random
- imageio
- Usage
To use this notebook, simply run all the cells in order. The Q-learning algorithm will be trained on the FrozenLake-v1 environment, and then evaluated to generate a GIF of the agent's behavior. The GIF will be saved in the current working directory under the name FrozenLake-v1(4x4).gif.

# Parameters
The following parameters can be adjusted in the code:

- lr: The learning rate used in the Q-learning algorithm.
- gamma: The discount factor used in the Q-learning algorithm.
- max_epsilon: The maximum value of the exploration rate used in the Q-learning algorithm.
- min_epsilon: The minimum value of the exploration rate used in the Q-learning algorithm.
- decay: The decay rate of the exploration rate used in the Q-learning algorithm.
- n_train_episodes: The number of episodes used to train the agent.
- n_eval_episodes: The number of episodes used to evaluate the agent.
- max_steps: The maximum number of steps allowed per episode.

# References 
This implemenetation was made possible by this article [Introduction to Q-learning with OpenAI Gym](https://medium.com/swlh/introduction-to-q-learning-with-openai-gym-2d794da10f3d)
