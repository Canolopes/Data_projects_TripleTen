# Computer Vision Project

This is the final graded version of my computer vision project for TripleTen. I was tasked with helping a business use computer vision to help verify customer ages and adhere to alcohol laws.

## The Process

I begin with my due diligence on the project data by observing the distrbution of ages and also opening some of the images to train the model. I used a ResNet50 model to train and validate the model, and mean absolute error was used as the grading metric. Since this kind of testing requires increased computational resoures, it was trained on a GPU platform, and the results of the epochs were put into the notebook. The results stabilized with an MAE around 7, which was more than enough for our target. I used several libraries and modules, such as ImageDataGenerator, ResNet50, and other neural network modules from TensorFlow. 

The Jupyter Notebook will demonstrate how I was able to achieve my results.
