# Optical-Character-Recognition

This is an Optical Character Recognition program which recognizes sentences presented in images. Unlike traditional OCR systems, this system has a strong language model. It can resolve ambuigities in recognition by using statistical constraints of English. These constraints are incorporated using a Hidden Markov Model.

The model uses a training text file, which contains all the training letters, and a training image, which contains the respective image representations of the images in the training text file.
For each test image, the model takes into consideration the initial probabilites of all the training letters, the emission probabilites (probability of observing the letter in the image given the training letter) and the transition probabilites (probability of transitioning from letter 1 to letter 2 in the training set, for each set of training letters) to identify the sentence.

## Technology
#### Python
