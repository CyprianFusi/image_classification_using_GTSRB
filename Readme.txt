Lack of sufficient training data is the number cause of overfitting during training of machine learning models. Therefore getting sufficient training data is also the number 
one way to combat overfitting. Data augmentation is generating artificial data using the dataset at hand. Keras provides ImageDataGenerator function which can be used to 
generate more images for an image recognition or classification problem. This is what has been used in this simulation example to generate more training sample images.
Note that data augmentation is not used during validation and testing - it's only for training.
Please see the Jupyter Nootbook for the workflow and results.
The training and validation results look good but the final testing is lower than the validation score by more than 10%. 
The final testing data is provided by the authors and I would like to believe that this testing data is from the same distribution as
both training and validation data. A very import characteristic of training, validation and testing data is that they should be 
independent but identically distributed (IID). If this does not hold then it would be hard to tweak the model for to achieve any 
significant improvement. 

I made use of knowledge from the following sources:

Deep Learning with Python by Francois Chollet
Deep Learning for Dummies by by John Paul Mueller and Luca Massaron

Thanks to Institut für NeuroInformatik at Ruhr-Universität Bochum in Germany for the dataset.

PS: I am doing data science and machine learning as a hobby but I wish to make it my life career!

