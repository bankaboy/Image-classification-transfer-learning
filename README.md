## A Custom Image Classifier using Transfer Learning on Google Inception V3

This is a step by step guide of transfer learning by adapting an existing image classifier (Inception V3) to a custom task.

1. Create a folder for the dataset.
2. Inside the dataset folder create separate folders for each class.
3. Inside each class folder, put the images to train the classifier on for that class.
4. Run script retrain.py as <b><i>retrain.py --imag_dir dataset</i></b>, where dataset is the folder with all the images of different classes.
5. After training, weights and labels files will appear in file:///tmp for linux and C://tmp for windows.
6. Put these weights file in a folder inside the classifier directory.
7. In label_image_test.py -
        a. Change path of model and label file to correct paths.
        b. Provide path of image to test on.
8. Run the script , output will be label:prediction.
