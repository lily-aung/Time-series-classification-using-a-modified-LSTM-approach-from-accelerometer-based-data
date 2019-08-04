# Time-series-classification-using-a-modified-LSTM-approach-from-accelerometer-based-data
A comparative study for gait cycle detection

# Background: 
Gait event detection (GED) is an important aspect in identifying and interpretation a user’s gait to assess gait abnormalities and design intelligent assistive devices.

# Research Question: 
There is a need to develop robust GED models that can accurately detect various gait instances in different scenarios and environments. 

# Methods: 
This paper presents a novel method of detecting heel strikes (HS) and toe offs (TO) during the user’s gait cycle using a modified Long Short-Term Memory (LSTM) networks approach. The method was tested on a database from Movement Analysis in Real-world Environments using Accelerometers (MAREA) (n=20 healthy subjects) that consisted of walking and running in indoor and outdoor environments with accelerometers positioned on waist, wrist and both ankles. Modifications include oversampling, composite accelerations and optimizing the LSTM network architecture were made. 

# Results: 
Performance of our modified model was found to be better than six state-of-the-art GED algorithms, with a median F1 score of 0.98 for Heel Strikes and 0.98 for Toe Offs in the scenario of steady walking in an indoor environment, and a median F1 score of 0.94 for Heel Strikes and 0.68 for Toe-offs in the scenario of walking and running in an outdoor environment. 
Significance: This paper highlights the potential of the single proposed model to be an alternative to the six GED models in gait detection under various conditions.

# Acknowledgment:
We would like to thank Siddhartha Khandelwal of Halmstad University for sharing the MAREA gait database that is used in our experiments.
