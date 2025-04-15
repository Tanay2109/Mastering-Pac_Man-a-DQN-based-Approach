# Mastering Pac-Man a DQN-based Approach
A Deep Q-Network (DQN) implementation trained to play MsPacman using OpenAI Gym’s Atari environment. This project demonstrates reinforcement learning in action using convolutional neural networks and includes live training visualization. 

In Deep RL, neural networks are used to approximate policies or value functions. This is especially helpful in complex environments (like video games) where the state space (e.g., pixels of a screen) is too large for traditional tabular methods. DQN is a DRL algorithm developed by DeepMind, which combines Q-learning with deep neural networks. It learns the optimal Q-value function that estimates the expected return (reward) for each action in a given state.

Key elements of DQN:

- Q-Network: A neural network approximates the Q-value function.

- Experience Replay: Stores past experiences in a buffer and samples random mini-batches for training to break correlation between consecutive data.

- Target Network: A separate copy of the Q-network updated at intervals to stabilize training.

- Epsilon-Greedy Policy: Balances exploration and exploitation by choosing random actions with probability ε and best-known actions otherwise.

This project implements DQN to let an agent learn how to play MsPacman by observing the game's screen and learning which actions yield high scores.

📌 Features

🎮 Trains an agent to play MsPacman from pixel input

🧠 Deep Q-Network (DQN) with experience replay and target network

📈 Real-time training progress plots 

🎥 Option to record and watch trained agent’s gameplay

🧪 Epsilon-greedy exploration with decay

# Output

The following output gameplay was received after training the agent for 200 episodes with gamma=0.99, batch_size=32, buffer_limit=10000 and learning_rate=1e-4

https://github.com/user-attachments/assets/23bc73a3-430e-4afe-9cc2-3f5946f4dce1


