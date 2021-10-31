# Data Center Load Prediction

Machine Learning models have been successfully applied to predict Energy Utilization in different areas. In Data centres, this can be applied to reduce power utilization by dynamically controlling servers (power off and on). However, this has been limited in data centres as if any wrong prediction may result in latency and may not meet SLA.

In this project, the main aim is to predict the load for next 5 seconds as output considering past 30 seconds as input. These predictions can help to dynamically turn on servers if there is more load. The load on servers depends on make and model of servers. Random Forest Regressor and LSTM Model have been applied to predict the load.
