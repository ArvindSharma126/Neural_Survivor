# Neural_Survivor
Repository for the writer verification challenge.
please make sure that dataset is in the folder 'dataset' in the same dir as these notebooks.
please make sure that semi_test is in the folder 'semi_test' in the same dir as these notebooks.

# training code
The training has been done on the notebooks in four parts:

## training_1.ipynd
In this notebook the preprocessing has been done i.e.

1. resize to 500 x 50 size.
2. rename to "folder"_"file name" for easier access
3. make csv file for pairs in training set

## training_2.ipynd
In this notebook, the dataset is coverted into .npy file for easier training.

## training_3.ipynd
In this notebook torch part of the model is trained.

## training_4.ipynd
In this notebook the part(KNN) of the model is trained and final model is stored in .sav file

# inference code
In this notebook, we have load the model by pickle module.
Then we load images one by one and do the prediction.
torch part convert the images into features, and KKN is used to do the prediction.

# model_checkpoint_and_final_model.txt
It contains the google link for trained model and other intermediate stored files
