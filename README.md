# CNN Image Classification on MNIST Dataset
- This project demonstrates the building, training, and evaluation of a Convolutional Neural Network (CNN) model for classifying images from the MNIST dataset. 

# The project includes:
- Model Building Notebook: A Jupyter Notebook to construct, train, and evaluate the CNN model.
- Test Images Folder (test_images/): A folder containing unseen MNIST test images to evaluate the performance of the model.
- Saved Trained Model (model_state.pt): The saved weights and architecture of the trained CNN model, which can be used for inference on new data.

# Requirements
To run this project, make sure you have the following dependencies installed:

- Python 3.x
- Pytorch
- Numpy
- Pandas
- OpenCV 
- Pillow 

# Model Building 
We build a Convolutional Neural Network (CNN) for image classification using the following steps:
- Data Preprocessing: Load the MNIST dataset, normalize the images, and perform any necessary preprocessing.
- Model Architecture: Define the CNN architecture with layers such as Convolutional and Fully Connected layers.
- Model Compilation: Compile the model using an optimizer (e.g., Adam) and a loss function (e.g., Sparse Categorical Crossentropy).
- Training: Train the model using the training data and validate it using the validation set.
- Evaluation: Evaluate the model performance on the test set.
- Model Saving: Save the trained model to a .pt file for later inference.

# Testing the Model on Unseen Data
- The test_images/ folder contains test images that the model has not seen during training. 
- These images can be used to evaluate the model's generalization performance.

# License
This project is licensed under the MIT License. See the LICENSE file for more details.
