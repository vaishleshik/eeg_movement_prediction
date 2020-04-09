# eeg_movement_prediction
Predict movement from EEG recordings

The motor cortex of the brain maps the human body within its small surface, a 'homonculus' ('little man')

![Motor homonculus](https://upload.wikimedia.org/wikipedia/commons/thumb/c/c4/1421_Sensory_Homunculus.jpg/800px-1421_Sensory_Homunculus.jpg)

There is evidence that the very __thought__ of movements elicits electroencephalographic changes in these regions. [https://sccn.ucsd.edu/~scott/pdf/Wang_MovementPrediction_HCI09.pdf]. If this is the case, minor differences between, say, __thinking of__ moving my left versus right hand should refelect in EEG. At present, the differences are not sufficiently distinct to be picked by humans.

## Objective of this project

1. to compile available EEG data in an appropriate format fir for machine learning libraries; one open source dataset is here: https://www.physionet.org/content/eegmmidb/1.0.0/
2. to make predictions from this data, as regards to what kind of movement the person was __thinking of__ when the ECG was recorded.

Writing in a train. Still trying to gather how the data is formatted (? EDF files) and how to read them in python.
