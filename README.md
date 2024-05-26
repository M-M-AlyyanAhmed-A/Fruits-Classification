# Fruits-Classification
This project utilizes a VGG16 convolutional neural network to classify images of fruits as ripe or unripe. The dataset consists of images categorized into 22 different fruit classes, stored in a Google Drive directory.

# Key Features
**1. Data Preparation:**
Load and preprocess images from the specified Google Drive directory.
Apply transformations including resizing and normalization.

**2. Model Training:**
Use a pre-trained VGG16 model, modifying the final layer to classify 22 classes.
Train the model using the Adam optimizer and CrossEntropyLoss.
Perform training over 10 epochs with training and validation splits.

**3. Evaluation:**
Evaluate the model's accuracy on the validation set.
Display training loss and accuracy metrics.

**4. Model Saving:**
Save the trained model to a file using the pickle library.

**5. Flask Integration:**
Set up a basic Flask server to potentially serve the trained model.

# Requirements
* Python 3.7+
* PyTorch
* Torchvision
* OpenCV
* Matplotlib
* Flask
