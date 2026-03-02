# CS 370: Current and Emerging Trends in Computer Science - Course Journal

## Project Reflection: Pirate Intelligent Agent for Treasure Hunt Game
In Project Two, I developed a deep Q-learning agent to navigate a pirate through a maze to find treasure, avoiding obstacles and optimizing paths. 
The starter code provided included two Python classes: `TreasureMaze.py` for the environment (maze grid, states, actions, rewards) and `GameExperience.py` for experience replay (storing and sampling episodes). 
The Jupyter notebook had helper functions like `build_model` (neural network), `completion_check`, `play_game`, and a skeleton for the `qtrain` function. 
I created the core logic in `qtrain`: implementing epsilon-greedy action selection for exploration-exploitation balance, storing episodes in replay memory, sampling mini-batches for training the model with Q-targets
(using the Bellman equation), decaying epsilon over epochs, and periodically updating a target network for stability. 
This allowed the agent to achieve a 100% win rate, demonstrating reinforcement learning in pathfinding.

Throughout CS 370, I connected these concepts to the broader field of computer science, where professionals design algorithms and systems to process information, solve complex problems, and drive innovation—from AI in healthcare to cybersecurity. 
This matters because CS underpins modern society, enabling efficient data handling, automation, and ethical tech that improves lives while mitigating risks like bias or privacy breaches. 
As a computer scientist, I approach problems systematically: define the state space and goals (e.g., maze navigation), break them into components (e.g., Q-value approximation via neural nets), iterate with testing (e.g., epsilon decay tuning), and evaluate outcomes (e.g., win rates). 
Ethically, I have responsibilities to end users—ensuring transparency in AI decisions (like explainable Q-values) and fairness (diverse training data to avoid biased paths)—and to organizations, by prioritizing secure, sustainable solutions that align with regulations like GDPR and promote societal good over profit alone.
