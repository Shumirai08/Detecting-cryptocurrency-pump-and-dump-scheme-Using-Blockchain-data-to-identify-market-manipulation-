This research describes an extensive machine learning based framework for the 
detection of pump-and-dump schemes in the cryptocurrency market with BTC/USD 
blockchain-originated data. The project is focused on one of the growing concerns in 
decentralised financial environments: market manipulation, where sensibly the 
regulations don't follow. The fraud detection system has a hybrid detection pipeline 
incorporating both unsupervised and supervised learning techniques to improve 
reliability and scalability. 
To identify the unusual patterns in features like price volatility, percentage price 
change, and trading volume, Isolation Forest and K-Means algorithms are used by the 
anomaly detection component. After classifying these anomalies using Random 
Forest and XGBoost, two powerful supervised models that are notably robust and 
perform extremely well on imbalanced datasets, these anomalies could then be sorted. 
And the evaluation concluded with Isolation Forest having perfect metrics for 
classification, with Random Forest and XGBoost having accuracy greater than 99%. 
While having a good baseline, K-Means was not powerful enough to find fraudulent 
instances. 
Challenges such as computational demands, most notably model tuning and 
evaluation, and real-time implementation complexity are also highlighted in the project. 
However, it lays down a good groundwork for the building of large, intelligent fraud 
detection systems that can protect investor trust in volatile markets. The interpretability 
of the models is supported with visual outputs such as ROC curves, confusion 
matrices, and time series anomaly plots. 
To add to that, this work demonstrates the authenticity of utilizing AI based approaches 
meant to detect financial exploitation in blockchains and sets the basis for real time 
applications and entrepreneurial solutions to be introduced in regulatory and trading 
infrastructure.
