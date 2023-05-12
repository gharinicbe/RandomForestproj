CIFAR-10 Image Classification with Random Forest
This project aims to classify images from the CIFAR-10 dataset using machine learning models, specifically the Random Forest algorithm. The dataset consists of 60,000 32x32 color images in 10 classes, with 6,000 images per class. The 10 classes are: airplane, automobile, bird, cat, deer, dog, frog, horse, ship, and truck.

The dataset is downloaded using the Keras library, which provides a simple interface to access various datasets.

The project is implemented in Python using the following libraries:

Keras (for downloading the dataset)
Scikit-learn (for building and evaluating the Random Forest model)
Matplotlib (for visualizing the images)
Preprocessing
The images are flattened and normalized by dividing the pixel values by 255, so that they range between 0 and 1. This helps the model converge faster during training.

Random Forest Model
A Random Forest model is built using Scikit-learn to classify the images. The model consists of 100 decision trees with a maximum depth of 20.

The performance of the model is evaluated using cross-validation with 5 folds. The mean accuracy score is reported as the evaluation metric. Among the several machine learning models tried, Random Forest Model gave the highest accuracy score.

At the end of the training process, a random image from the internet is chosen and the Random Forest model predicts its class label.

Conclusion
In conclusion, this project shows that the Random Forest algorithm can be an effective method for image classification, even for a dataset as complex as CIFAR-10. The model achieved a high accuracy score and was able to correctly predict the class label of a randomly chosen image from the internet. However, it should be noted that deep learning models like CNNs generally achieve even higher accuracy for image classification tasks.
