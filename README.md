# Predicting_mkt_condition_markov_chains
This notebook contains the S&P500 market predictions using markov chains as a machine learning model.
Used daily data with starting from Jan 2010
Created a daily series of 3 events given by the parameters 'Close Gap', 'Volume_Gap', 'Daily_change'.
Formed the transition matrix from the set of unique event
Used markov chains on the series of events and the accuracy is found out to be 40.09%
