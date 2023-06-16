# FrozenLake DQN
A research project with the aim of exploring deep q-learning as a tool to navigate dynamic maps. I utilized [FrozenLake](https://gymnasium.farama.org/environments/toy_text/frozen_lake/) environment as a research platform, developed a data pipeline to extract states as images, and generated optimal policy using a two-part neural network.

### Project Status
This project is an ongoing effort. The goal is to incorporate randomness in map layout and slipperiness to increase complexity and evaluate the performance of a deep Q-learning approach.

Currently, the map is static. The layout of holes and the goal is not changed throughout training or testing. After training for about 6 hours, the model achieved around 80% accuracy.

### Future Goals
- Deal with truncations by forcing model to train with a smaller step size
- Include randomness
- Include slipperiness (non-deterministic action outcome)
