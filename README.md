# ChessmanPredictor
In this project a Convolution Neural Network is trained using an Image Dataset of various types of Chessmen . Later, when an image of a chessman or a chessman itself is placed in front of the camera, the type of chessman is predicted using this CNN

The source codes of two jupyter notebook script are given. 
>  Chessman_Detector.ipynb contain the code for creating a model and training it using an Image dataset downloaded from https://www.kaggle.com/niteshfre/chessman-image-dataset
    This model is then saved with the name "Chessman_Detector.h5".
>   This saved model is then reused in  "loading_model.ipynb" which is later used to classify a given Image into a Particalr Chessman.
