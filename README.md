# CS370-Current-Trends-in-CS
  
  This project focused on building an intelligent pirate agent capable of navigating a maze and reaching a treasure through reinforcement learning. Instead of hard-coding a path, the goal was to design a system that could learn effective navigation behavior over time by interacting with the environment.

  The maze environment and experience replay framework were provided. The TreasureMaze.py file defined the game world, valid actions, and state transitions, while GameExperience.py handled storing and sampling past experiences. The neural network architecture was included in the starter notebook. My work centered on implementing the Q-training logic: building the training loop, integrating epsilon-greedy exploration, performing Bellman-based updates, managing experience replay, and synchronizing the target network. I ensured the model trained without runtime errors and converged toward a stable win rate. The completed agent begins with high exploration, gradually shifts toward exploitation, and eventually learns a consistent path to the treasure based solely on reward feedback.

 Computer scientists do more than write code. They define representations, choose algorithms, and shape how systems behave under constraints. 

  Approaching the problem required breaking it into components: how the environment is represented as states, how actions are selected, how rewards are assigned, and how predictions are updated. Viewing the maze as a sequential decision problem clarified that each move affects future possibilities. From there, reinforcement learning provided the framework for optimizing long-term reward instead of immediate gain. 

  Even in a controlled game environment, reward design and exploration strategy directly shape agent behavior. Small adjustments can dramatically alter outcomes. In real-world systems, these design decisions carry greater consequences. As a computer scientist, it is important to prioritize reliability and maintainability. Code should be understandable and reproducible, and algorithmic decisions should be made thoughtfully.
