# Data Science Internship - Assignment


### Overview
This repository contains the solutions for two tasks:
1. **Task 1**: Implemented a predictive model for future sales forecasting using Random Forest.
2. **Task 2**: Developed a maze solver using reinforcement learning with Q-tables.

The repository includes the complete source code, documentation, and results for each task.

### Table of Contents
- [Task 1: Sales Forecasting](#task-1-sales-forecasting)
- [Task 2: Maze Solver](#task-2-maze-solver)

---

### Task 1: Sales Forecasting

#### Description
The goal of Task 1 was to build a predictive model for future sales forecasting using historical sales data. The model was implemented using a **Random Forest Regressor** to predict future sales based on various features such as week, day, supermarket, and other relevant data.

#### Approach
1. **Data Preprocessing**:
   - Cleaned the dataset by handling missing values and outliers.
   - Transformed the features to improve model accuracy
     
2. **Feature Engineering**:
   - Selected features that had a significant impact on sales, including temporal data like week and day.

3. **Model Training**:
   - Split the data into training and testing sets.
   - Trained the model using a **Random Forest Regressor**.

4. **Model Evaluation**:
   - Evaluated the model's performance using metrics such as **R²**, **Mean Absolute Error (MAE)**, and **Root Mean Squared Error (RMSE)**.
   - Compared model predictions with actual sales data to assess accuracy.

#### Results
The model successfully predicted future sales with reasonable accuracy, showing potential for aiding business decisions.

---

### Task 2: Maze Solver

#### Description
Task 2 involved developing a maze solver using **reinforcement learning** with a **Q-table**. The objective was to teach an agent to navigate through a maze from a starting point to a goal while avoiding obstacles.

#### Approach
1. **Maze Environment Setup**:
   - Created a grid representation of the maze where each cell could be a wall, a free path, the start, or the goal.
   - Defined rewards for reaching the goal and penalties for hitting walls.

2. **Reinforcement Learning Using Q-Learning**:
   - Implemented the **Q-learning algorithm** to update the Q-table based on the agent's state and actions.
   - Trained the agent over multiple episodes, with an epsilon-greedy strategy for exploration.

3. **Evaluation**:
   - Tested the trained agent's ability to solve the maze and plotted the path taken from the start to the goal.

#### Results
The agent was able to navigate the maze successfully, learning an optimal path to reach the goal while avoiding obstacles.

---

