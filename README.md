# Dog Breed Classifier

### Project Overview

The goal of this project was to create a dog breed classifier that fit the following algorithmic requirements:

Write an algorithm that accepts a file path to an image and first determines whether the image contains a human, a dog, or neither. Then,
1. if a dog is detected in the image, return the predicted breed.
2. if a human is detected in the image, return the resembling dog breed.
3. if neither is detected in the image, provide an output that indicates an error.

### Code and Package Requirements

The project requires **Python 2.7** and the following Python libraries:

- [NumPy](http://www.numpy.org/)
- [keras](https://keras.io/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [matplotlib](http://matplotlib.org/)

#### Model Results: 
The main model used for the project was based on InceptionV3 bottleneck features using transfer learning. The performance was:
- Training Accuracy: 99.49%
- Test Accuracy: 78.11%
