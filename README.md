# Diagnosing-Parkinson-s-Disease-using-voice-sample-data-analysis
A descriptive analytics approach to find salient features to distinguish PD and Non-PD.

In the dataset, there is total 26 features of Jitter, Shimmmer, Pulse, Pitch etc.

As the data, follows normal distribution. We extract mean and standard deviation.

Then we feed the mean and std_dev into t-test to choose saliant features which p-value is less that 0.05

We also tried to explore correlation between different features using scatter plot, histogram using pyplot and SNS library.
