# engine-degradation-kalman-filter
A script that implements extended kalman filtering to estimate the state of an aircraft engine based on varying numbers of points.

This was a simple project done for a machine learning and process controls class intended to give experience in working with some principles of state estimation and signal processing. Given two different types of engine data (one exhibiting gradual faults, the other exhibiting abrupt faults) and state evolution models/process and noise variance, I implemented an extended kalman filter to predict the progression of the engine faults based on the first 60 and 100 data samples of an arbitrary sensor.
