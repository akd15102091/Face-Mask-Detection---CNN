# Face-Mask-Detection---CNN

**Dataset Link** :  https://www.kaggle.com/omkargurav/face-mask-dataset

In this project,  We **predict the Face Mask** using **CNN deep learning technique** and **Opencv** .

data/with_mask => there are 2 folders containing around total 3700 images

data/without_mask => there are 2 folders containing around total 3800 images

["with_mask","without_mask"] - 2 types of emotions (2 folders)

The model has been trained over these images.

Libraries used in this project :

    1) OS, Numpy, Random, Matplotlib

    2) Tensorflow (keras)
    
    3) Opencv-python


Approach to solve task :

    1) Import the required python libraries
    
    2) Create a function that takes directory name as a argument and return the dataset. This function reads the images from directory, convert them into array and assigned a label.

    3) Create train dataset and test dataset using function which is made for this task.

    4) Convert those dataset in X_train, X_test, y_train, y_test

    5) Convert list(X_train,X_test, y_train, y_test) into numpy-arrays , normalise them.

    6) Applied the CNN model .
    7) Save the model into h5 file .

    8) Using Opencv, implement model at run time. When camera captures the frame, our model will predict the face mask and if there is no faces in front of camera then "NO FACES" detected.
    
    
    ................................................END........................................................................
