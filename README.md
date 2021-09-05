# Open-Domain-Table-to-text-generation

* Generation of meaningful inference from highlighted cells. 
* Used the Google Totto Dataset for training and testing.
* The model used was T5-Base
* Special tokens were added for seperation between the different cells and rows so that the model too could understand the positions of the input text
* Model was trained for 7 epochs on GPU and later on 12 rpochs on TPU

File Information
* File for data preprocessing -> converting table data into model input format
* GPU Training -> training model on GPU
* TPU Training -> Training model on TPU using Pytorch XLA
