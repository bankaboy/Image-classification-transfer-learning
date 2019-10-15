## A Custom Image Classifier using Transfer Learning on Google Inception V3

This is a step by step guide of transfer learning by adapting an existing image classifier (Inception V3) to a custom task.

1. Create a folder for the dataset.
2. Inside the dataset folder create separate folders for each class.
3. Inside each class folder, put the images to train the classifier on for that class.
4. Run script retrain.py as <b><i>retrain.py --imag_dir dataset</i></b>, where dataset is the folder with all the images of different classes.
