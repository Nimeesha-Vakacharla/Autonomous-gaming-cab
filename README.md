# Reinforcement Learning for Self-Driving Cab - User Documentation Manual
## Introduction
Welcome to the "Reinforcement Learning for Self-Driving Cab" project! This documentation serves as your comprehensive guide to understanding and implementing an innovative approach to creating a self-driving cab using reinforcement learning techniques. We've employed advanced methods, including Q-learning, to enable the autonomous functioning of a self-driving cab.
## Table of Contents
1. **Overview**
2. **Getting Started**
   - Prerequisites
   - Installation
3. **Project Components**
   - ```env.py```
   - ```agent.py```
   - ```train.py```
4. **Algorithms and How It Works**
   - Reinforcement Learning
   - Q-learning
5. **Using the Project**
   - Training the Self-Driving Cab
   - Running the Trained Agent
6. **Conclusion**
7. **References**
8. **Contributors**
## 1. **Overview**
This project focuses on developing a self-driving cab using reinforcement learning techniques. The cab is trained to efficiently navigate its environment, pick up passengers, and drop them off at designated locations. The primary learning algorithm employed is Q-learning, allowing the cab to make informed decisions based on past experiences.
## 2. **Getting Started**
### Prerequisites
No prerequisites are required to run this project.
### Installation
Clone the repository:
  ```
git clone https://github.com/your-username/self-driving-cab-rl.git
```
Navigate to the project directory:
```
cd self-driving-cab-rl
```
## 3.**Project Components**
### ```env.py```
The ```env.py``` file contains the environment representation for the self-driving cab. It defines the state space, action space, and reward mechanisms.
### ```agent.py```
The ```agent.py``` file implements the reinforcement learning agent, executing iterations of Q-learning. It learns from the environment, updating Q-values to optimize decision-making.
### ```train.py```
The ```train.py``` file provides functionality to train the self-driving cab using the implemented Q-learning algorithm.
## 4. Algorithms and How It Works
### Reinforcement Learning
Reinforcement learning involves the agent learning from its environment through positive and negative reinforcements. In our case, the self-driving cab learns to navigate the environment by receiving rewards for correct actions.

### Q-learning
Q-learning is an off-policy learning algorithm where the agent learns a policy to maximize the expected rewards. Q-values are updated based on the reward received, influencing the agent's future decisions.
## 5. Using the Project
### Training the Self-Driving Cab
To train the self-driving cab, execute the following command:
```
python train.py
```
### Running the Trained Agent
After training, observe the self-driving cab in action by running:
```
python agent.py
```
## 6. Conclusion
Congratulations! You've completed the "Reinforcement Learning for Self-Driving Cab" project. The self-driving cab is now capable of autonomously navigating its environment.
## 7. References
1. Sutton, R. S., & Barto, A. G. (2018). Reinforcement Learning: An Introduction. MIT Press.

2. Mnih, V., et al. (2015). Human-level control through deep reinforcement learning. Nature, 518(7540), 529-533.

3. OpenAI Gym. (https://gym.openai.com/)

4. Kaelbling, L. P., Littman, M. L., & Cassandra, A. R. (1996). Planning and acting in partially observable stochastic domains. Artificial Intelligence, 101(1-2), 99-134.
## 8. Contributors
Created by: Nimeesha Vakacharla & Ifra Mohammed 
