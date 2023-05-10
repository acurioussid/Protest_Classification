# Protest_Classification
Classification of Protest Images into Violent or Non-Violent Protests using Deep Learning 

# Process:
- Data Collection and Sorting: Collect a diverse set of protest images and sort them into two categories: violent and non-violent protests.
- Data Cleaning: Remove images in vector format and those with a file size less than 10KB.
- Data Preprocessing: Prepare the dataset for training by performing the following steps:
  - Resize all images to a standard size of 256x256 to ensure uniformity.
  - Scale all pixel values between 0 and 1 to facilitate convergence during training.
  - Split the dataset into training, validation, and testing sets.
- Model Architecture: Design a deep learning model using Convolutional Neural Networks (CNN) to classify the images.
- Model Training: Train the model using the prepared dataset, and optimize the model's parameters using backpropagation and Adam optimizer.
- Model Evaluation: Evaluate the model's performance on the validation set and tune the hyperparameters to improve performance.
- Model Testing: Test the model's accuracy on new, previously unseen images of protests.
