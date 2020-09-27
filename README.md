# Dog-Breeds-Classification-Kaggle

The following code repository consists of an ongoing project based on Dogs Breeds Classification.

1. Dataset : 

          ->  ! kaggle competitions download -c dog-breed-identification

2. Implementation Steps : 

-> Creating separate directories for 120 Dog breeds

-> Labeling the data previously present in the format of id.jpg inside the train and test directories and labels.csv in the format of (id,breed)

-> Use of Image Data Generator of Keras to carry out Data Augmentation in order to prevent the model from overfitting and feeding the data to the model without causing the System resource exhaustion

-> Model Foramtion with 491,640 trainable parameters

Note : The project is work in progress as the model is still taking a long time to complete training and I am trying to use a better combination of hyperparameters so that the model performs well without getting overfitted.
