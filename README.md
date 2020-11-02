# Data Analysis for MIL-STD-1553

- Exploration_1.ipynb

    - Explore data 
    - Data Cleaning
    - Plots to Visualize
    - decode 'data message'?
    - Count is the measure of traffic?
    - Distrubution plots
    - Group by plots
    - OneClassSVM

- Exploration_2.ipynb

    - Skewness and Kurtosis for 'Gap' (cleaning->remove large gaps) and 'Count'
    - Saperate RT to BC and BC to RC
    - Seasonal Decomposition
    - Anomaly Detection - i Forest

- Remove_gaps.ipynb

    - Removing the rows with large time gap
    - Distribution of Gap
    - Observing the anomaly is still there.  


- pattern_anomaly_for_counts.ipynb

    - LSTM Autoencoder Model 
    
- pattern_anomaly_RT_BC_grouped.ipynb
    - LSTM Autoencoder Model 


Thoughts:

- preprocessing to "gap" so that data won't be biased towards that one variable

- calculationg a confidece value to anomaly in new data. (68% sure this is different. Or 90% sure this is the same)

- Weight of variables 

- expand your data set to include new data : Re-Training

if the new data point used for testing should be included in the training set afterwards 




