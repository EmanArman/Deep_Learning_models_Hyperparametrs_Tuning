# Deep_Learning_models_Hyperparametrs_Tuning

In this project feature selection criteria are set to shape different scenarios according to their correlation with the Target GHI(Global Horizontal Irradiation), the Thresholds are (0,0.1,0.25,0.5), then the dataset eas split into training and testing sets by 80% and 20% respectively.

In order to forecast day-ahead GHI 6 ML models are employed namely (MLP,RNN,LSTM,BiLSTM,GRU,BiGRU) AND statistical model MLR.

To optimize the ML models the hyperparameters of each model are hypertuned using KERAS Tuner, and the most optimized model for each Scenario are evaluated using several metrics such as (R2, MAPE,nMAE,nRMSE).

The dataset used in this project belongs to the energy and weather dataset of Turkish city (Adana), and the models are employed using Python, both the dataset and Pythin file are available in the repository.
