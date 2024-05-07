## Transfer Learning with Convolutional Neural Networks For Age Prediction

### Overview

This project aims to predict the age of individuals using deep neural networks and transfer learning techniques. The project utilizes PyTorch and Computer Vision Learning Studio (CV Studio) to train a convolutional neural network (CNN) on image data. 

### Project Details

#### Training Run: Age Prediction

In this project, we trained a deep neural network using transfer learning. The image dataset was automatically downloaded from the CV Studio account. We experimented with various hyperparameters to optimize the model's performance. 

CV Studio is used for dataset management, model training, and evaluation. The dataset consists of images labeled with the corresponding age groups of the individuals. The CNN model, implemented using PyTorch, is trained on this dataset to learn age-related features from the images.

#### Technology Stack
1. Python
2. PyTorch
3. Convolutional Neural Networks (CNN)
4. CV Studio

### Results

- Number of Epochs: 10
- Batch Size: 32
- Learning Rate: 0.000001
- Momentum: 0.9
- Learning Rate Scheduler: Enabled
  - Base Learning Rate: 0.001
  - Max Learning Rate: 0.01
- Percentage of Data Used for Training: 90%

### Conclusion

The trained model achieved a maximum validation accuracy of 40% after 3 epochs. However, there seems to be room for improvement in terms of model performance. Further experimentation with hyperparameters and potentially acquiring more training data could lead to better results.
