# DNN_forPrecipitationPrediction

**Problem** - 
Spatiotemporal forecasting. 

**Applications -** 
1. Traffic and transportation.
2. Climate resilience
3. Neuroscience

**Important Experimental Observation**
I have built models using tensorflow in one notebook and using pytorch in another for the same problem. The tensorflow model had more number of neurons in the second hidden layer than the model built in pytorch but I have observed that the same computation power was sufficient to train the tensorflow model for 2 epochs but wasn't sufficient for even 1 epoch training of the pytorch model. Also note that the size of the dataset taken was same for both the models.


**An intriguing point on this topic**

In this implementation, we build predictive model taking the numerical data i.e the features, latitude and longitude as input to obtain the precipitation predictions. 

What if instead, we treat this as a computer vision problem and train the models on the geographical heat maps on each time step. 

Which approach would perform better?
