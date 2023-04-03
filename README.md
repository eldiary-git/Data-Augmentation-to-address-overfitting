# Data-Augmentation-to-address-overfitting
the project target is to prevent overfitting by increasing Data with different forms of the same data 

what is Data Augmentation?
Data augmentation is a technique used in machine learning and deep learning to increase the size of the training dataset by applying various transformations to the existing data. The goal is to improve the performance of the model by providing it with more diverse examples to learn from, while also reducing the risk of overfitting. Some common data augmentation techniques include flipping, rotation, cropping, zooming, and color adjustments. By incorporating data augmentation into the training pipeline, the model can learn to generalize better and perform more accurately on new, unseen data.

#some highlights, small steps in this project

- convert images to numpy array then resizing it.
- doing ( train, test split ), scale the images 
- building the CNN on the scaled images then train it 
* then we found that the test set accuracy is low So we use ( Data Augmentation ) to improve the accuracy, now we have too many shapes of every image in the dataset.

- training the model with ( Data Augmentation, drop out layer)

Now, the accuracy of the test set data increased 


# installing steps:
1- Clone the repository to your local machine using the command git clone <repository URL>.
2- Navigate to the project directory using the cd command.
3- 


