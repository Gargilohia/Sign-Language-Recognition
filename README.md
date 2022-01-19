# Sign-Language-Recognition

Sign language is a visual communication technique that uses hand gestures, facial expressions and body language to convey messages and emotions. Signing is primarily used by the deaf and also those who have a disability or condition that makes them unable to physically speak. Contrary to popular belief, sign language isn’t universal. There exist different sign languages too.

This project aims to address issues that tend to isolate people with disabilities. A model that takes hand gestures of sign language as input and returns the corresponding character as output, has a wide range of applications. It can help inculcate a sense of belonging and helps the deaf and hard of hearing to converse with people who don’t sign.


The project is divided into 3 Modules as follows:

1. Capturing the sign language gestures of various alphabets for dataset creation:                  

   For the purpose of demonstration, we have created the test and train sets with some of the most commonly used vowels and consonants. It can easily be extended to all alphabets    and numbers.

2. Training a CNN on this dataset:

   Loading the captured images and designing a CNN. The model will be trained and tested by comparing two optimization algorithms - SGD (Stochastic Gradient Descent) and Adam        (Adagrad + RMSProp) to find which gives better accuracy.

3. Program to predict the gesture:

   Load the trained model and give it a new live input gesture.
   Here we follow the same steps used to capture the dataset (detecting background, segmenting the foreground from background) in order to detect the required hand gesture in the    live ROI. This becomes the new input for the saved detection model, which then predicts the accurately translated alphabet.
