# DeepLearningProject
## Project Title: X-ray Image Classifier Model 

(Dataset Linkhttps) [https://www.kaggle.com/datasets/pranavraikokte/covid19-image-dataset/data]

Dataset Description: 
It is a simple directory structure branched into test and train and further branched into the respective 3 classes which contains the chest X-ray images for the following:
1. covid images
2. viral pneumonia
3. normal

It contains around 137 cleaned images of COVID-19 and 317 in total containing Viral Pneumonia and Normal Chest X-Rays structured into the test and train directories.

Preprocessing for image dataset : 
1. Resizing(setting specific height and width) and Rescaling(normalizing pixel value)
2. Data Augmentation (Apply transformations like -flip,rotate,blur,etc. to make a larger training data)
3. Noise Reduction : but cannot be applied bcoz all the images are important for classificatiion into covid ,pnemonia nad normal
   Check this can be done or not?
   
