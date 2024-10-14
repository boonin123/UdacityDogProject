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

#### Summary of Results and Findings: 
I explored three different models as a solution for the classification problem, including one CNN from scratch and two using transfer learning. 

The final model used for the project was based on InceptionV3 bottleneck features using transfer learning. The performance was as follows:
- Training Accuracy: 99.49%
- Test Accuracy: 78.11%

After that, I built my final algorithm using the above requirements and the InceptionV3 model. I found that it worked well on all 6 of the images I fed it to test! It correctly identified humans and dogs separately, was accurate in the dog breed classification, and did not get fooled by the final two images of cats.

#### Acknowledgements
Thank you to Udacity for providing all the materials and the starter code for this project. Below are the data and code citations relevant to this project.
- The Dog Images data can be downloaded [here](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip)
- The InceptionV3 bottleneck features can be downloaded [here](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/DogInceptionV3Data.npz)
- You can find the links to the necessary Python packages above in the code requirements section.
