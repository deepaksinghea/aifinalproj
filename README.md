# AI Class Final Project 

# Project Topic : Stock Price Prediction using RL

![alt text](https://www.stockmarketeye.com/blog/wp-content/uploads/2015/04/end-of-day-stock-prices.png)


# Team Members : Deepak Singh 

# Slides and Code is provided in this repository.

# Youtube Walkthrough : 

https://www.youtube.com/watch?v=I_56t9jEJss 

# Motivation 
1. Stock price prediction is a classic problem, with successful model for
prediction we can obtain market insights and trends.
2. With the increased computational power, we can harness reinforcement
learning to solve the problem.
3. Our project is different from any other open-source project as we introduce
custom signals to our RL agent.

# RL Agent Used 

For the implementation, we are using MLP LSTM policy. This policy uses Long Short Term Memory with Multi-Layer Perceptron feature
extraction.

# Dependencies for the project 

TensorFlow 
Gym
Gym Any Trading
Yahoo Finance API
Fin TA (Financial Technical Analysis)

# Methodologies

1. We are using any-trading with custom signals to improve RL agent
performance compared to vanilla RL agent.
2. We will calculating RSI, OBV and SMA using Fin TA package.
3. After integrating custom signals, we will re-train and test our new model.
4. We will perform evaluation on the new model.
5. We will visualize the result !!

# Future Scope 

1. We can try out different RL agents with varying timestamps.
2. We can also deploy it as a web app for end users using services and packages like AWS, Streamlit etc.

# Thank you!!
