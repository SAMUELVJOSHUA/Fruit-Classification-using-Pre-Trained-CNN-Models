# Fruit-Classification-using-Pre-Trained-CNN-Models
Usage of 2 pre-trained CNN models to classify fruits as per associated classes

We make use of ResNet10 and VGG16.

After building our CNN model, we set our model for training and iterate through batches to generate predictions and calculate the loss associated with them as well. 

We define our optimizer as well.

The optimizer is required to manually update weights and learning rates during training. 

The learning rate is updated, which determines how quickly our model is able to adapt to the problem. Upon successful training, we obtain testing and training loss associated with our model and we plot a graph with values of them for analysis.

Through this we are able to obtain fruits belonging to their corresponding classes.

