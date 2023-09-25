# Task 
- These days it's very easy to generate a Fake image using one of the already available GAN models. 
- The purpose of this project is to identify if a given image is real or fake (developed through some artificial means). 

## Usage guidelines
- In order to run the prediction, you need to provide one of your own image in the ``to_test`` folder. 
- Open the notebook in VS code, and run all cells. In the last cell, the output would be the image and at the bottom of the image, we'd have the output if the given image is real or fake. 

## Future Modifications 
- I intend on adding a Flask API very soon, using which the user would be able to simply provide an image and get prediction rather than having to run the entire notebook. 
- I also intend on deploying this on AWS so that anyone with a link could use this. 
- Also, for accuracy I couldn't do much data augmentation to improve accuracy. I intend on doing that to see how the accuracy is affected. 
- One another thing that I want to do is to see if I could somehow put the ``metadata.csv`` file along with the images and then train the model on both these data simultaneously. 

### Dataset
The data used here has been taken from a kaggle. 
[Link To Data](https://www.kaggle.com/datasets/ciplab/real-and-fake-face-detection)