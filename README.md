AI Snake Game with Deep Reinforcement Learning
This project is an AI-powered Snake game developed using Deep Q-Network (DQN) reinforcement learning techniques. The AI agent learns to play the classic Snake game by observing the environment and taking actions that maximize cumulative reward.

Features
Deep Reinforcement Learning Agent: Trained with DQN architecture using PyTorch.

Custom Snake Environment: Grid-based Snake game with colorful, aesthetic rendering.

Enhanced Visuals: Gradient backgrounds, glowing food, and a distinct snake head with eyes for easy tracking.

Training and Evaluation: Includes training loop with epsilon-greedy policy and a playback feature to visualize game episodes.

Easily Extensible: Modular design to experiment with different RL algorithms or custom game designs.

How it Works
The environment provides the game state containing directions, food location, and danger signals. The agent learns an optimal policy through interaction by choosing actions (turn left, right, or forward) and receiving rewards (+10 for eating food, -10 for crashing, small penalty otherwise).

Usage
Install required packages:

text
pip install torch torchvision matplotlib imageio pillow numpy
Run the notebook or Python script to train the agent.

Use the playback function to render the game and save gameplay as GIF:

python
play_and_record(agent, env)
Demo and Screenshots
(Include GIF or screenshots here to showcase gameplay)

Repository Structure
RL_Project.ipynb: Main Jupyter notebook with training and evaluation code.

dqn_snake.pth: Saved model weights after training (optional).

snake_play.gif: Sample gameplay recording output.

Future Work
Implement more advanced RL methods (e.g., Double DQN, PPO).

Add difficulty levels or stochastic environments.

Create real-time gameplay UI with interactive controls.
