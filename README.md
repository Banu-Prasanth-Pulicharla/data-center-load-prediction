# Data Center Load Prediction

## Introduction
Machine Learning models have been successfully applied to predict Energy Utilization in different areas. In Data centres, this can be applied to reduce power utilization by dynamically controlling servers (power off and on). However, this has been limited in data centres as if any wrong prediction may result in latency and may not meet SLA.

In this project, the main aim is to predict the load for next 5 seconds as output considering past 30 seconds as input. These predictions can help to dynamically turn on servers if there is more load. The load on servers depends on make and model of servers. Random Forest Regressor and LSTM Model have been applied to predict the load.

## Dataset
The dataset used has 19 features. The statistics are collected at a frequency of 1 second. Considered “group [0].csv” for training the model.

### Features
1. Time (sec)
2. Group Power Factor (%)
3. Load of Online Machines(%)
4. Average CPU Core Temp. (°c)
5. Lowest Load(%)
6. Hottest CPU Core Temp. (°c)
7. Highest Load(%)
8. WC  Average CPU Core Temp (°c)
9. Number of Requests
10. WC Hottest CPU Core Temp (°c)
11. Powered BED Count
12.Capacity Used(%)
13. Group Power(w)
14. I/O Load of Online Machines(%)
15. Active BED Count
16. I/O Capacity Used(%)
17. S3 Powered Count
18. Number of Batch Jobs
19. Online BED Count