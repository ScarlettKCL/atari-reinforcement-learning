# atari-reinforcement-learning
## A model built using reinforcement learning algorithms to train an agent to succesfully perform in games from Atari environments from the OpenAI Gymnasium library.
Can be run in a notebook or any environment that supports Python.
### About
This project was carried out to improve my understanding of how to succesfully implement reinforcement learning algorithms, by building and training a Deep-Q Network (DQN) agent to perform in games from Atari environments found in the OpenAI Gymnasium Library, with the example environment shown in this code being the SpaceInvaders environment.
### Evaluation
Reward and Epsilon values in each training episode:
```
Episode 0/5, Total Reward: 0.0, Epsilon: 0.98
Episode 1/5, Total Reward: 30.0, Epsilon: 0.9603999
Episode 2/5, Total Reward: 5.0, Epsilon: 0.9411919
Episode 3/5, Total Reward: 30.0, Epsilon: 0.9223682
Episode 4/5, Total Reward: 35.0, Epsilon: 0.9039208
```
Testing Reward:
```
Average Reward over 5 episodes: 28.0
```
The values of the total reward given in each of the epsisodes used to train the DQN agent show that overtime, the performance of the agent improved, reaching a total reward of 35.0 by the final episode. By increasing the value of epsilon with each episode, the randomness of the model decreased, allowing the algorithm to gradually converge to achieve more accuracy. For the testing phase of the project, Epsilon was set to a value of 0.01 so that the agent mostly used its learning policy to act rather than just choosing random actions, allowing for a more effective validation of the model. The average reward over the 5 episodes of the testing phase was 28.0, showing that the average reward for a lower value of epsilon was greater than for a higher epsilon value, so the trainer agent had a more effective performance in the environment than if the agent randomly took actions, proving the success of the model.
