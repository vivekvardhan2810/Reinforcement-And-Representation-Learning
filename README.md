# Reinforcement-And-Representation-Learning
<p>Reinforcement Learning (RL) is a type of machine learning where an agent learns to make decisions by interacting with an environment. In RL, an agent learns to achieve a goal in a complex, uncertain environment by initially trying random actions and eventually learning to take actions that maximize some notion of cumulative reward. This learning process is built around the feedback loop of actions, states, and rewards.</p>
<p>For the above one python code it studies about the static environment and dynamic environment</p>
<h><b>Static vs Dynamic Environments:</b></h>
<p>In a static environment, the state of the environment does not change unless acted upon by the agent. The rules, states, and rewards remain consistent throughout the learning and execution phases.</p>
<p>In dynamic environments, the state of the environment can change independently of the agent's actions. This can be due to other agents, changes in the environment itself, or a time-evolving state.</p>
<h><b>Implement a grid world environment using reinforcement learning by training Q-learning and SARSA agents:</b></h>
<p>This grid world environment has the following configuration and rules:

1. The grid world is 5-by-5 and bounded by borders, with four possible actions (North = 1, South = 2, East = 3, West = 4).

2. The agent begins from cell [2,1] (second row, first column).

3. The agent receives a reward +10 if it reaches the terminal state at cell [5,5] (blue).

4. The environment contains a special jump from cell [2,4] to cell [4,4] with a reward of +5.

5. The agent is blocked by obstacles (black cells).

6. All other actions result in –1 reward.
</p>
<p>From the above question we observe and get the result as for Q Values for Q learning and SARSA in decimal values like matrix</p>
