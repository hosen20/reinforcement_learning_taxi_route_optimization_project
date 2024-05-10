# Taxi route optimization project using RL

![image](https://github.com/hosen20/reinforcement_learning_taxi_route_optimization_project/assets/84079430/de40debd-23a8-4028-81c6-db770a5851bd)

General steps used:
1. Initialize the Taxi-v3 environment with Gymnasium
2. Define a table to store the Q values
3. Define a function to update Q values using Q-learning: new_Q = (1 - alpha) * old_value + alpha * (reward + gamma * next_max)
4. Define a function to get the final updated policy after the training ends
5. Use the epsilon greedy method to balance exploration and exploitation
6. Train for 2000 episodes with maximum 100 actions per episode
7. Get and print the updated policy
