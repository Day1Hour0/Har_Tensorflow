# Har_Tensorflow
HAR dataset model using TF

In this respository, the model.py contain the import/ preprocessing / model.
It is mean to be a basic version of the model use to train data and evaluate the model using the validation data

From my testing, the model managed to reach ~ 90 % accuracy on the validation dataset.
This is supprising considering I only use Convolution network and few Dense layer on the model. 
I will probrably update this with another version that use Bidirectional layer with LSTM

Here is the graph showing the model 's performance:

![Alt text](https://raw.githubusercontent.com/Day1Hour0/Har_Tensorflow/main/Figure_1.png)

![Alt text](https://github.com/Day1Hour0/Har_Tensorflow/blob/main/Figure_2.png)
