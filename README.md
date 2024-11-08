
# Potato Disease Classification

### Overview
This project involves building a Convolutional Neural Network (CNN) to classify plant images using TensorFlow and Keras. The model is trained on the "plantvillage" dataset to recognize and categorize plant types, which can aid in agricultural diagnostics, specifically identifying potato plants and their health status.

### Prerequisites
 * Python 3.x
 * TensorFlow
 * Keras
 * Matplotlib
 * NumPy
 
### Dataset
 * The model uses images from the "plantvillage" dataset, which contains a variety of labeled plant images.
 * Images are processed to have a consistent size of 256x256 pixels, and the dataset is divided into batches for efficient model training.

### Project Structure
1. ### Data Loading and Preprocessing
 * Image Loading: Images are loaded and preprocessed using TensorFlow's image_dataset_from_directory function.
 * Batching: The images are organized into batches with a size of 32 for efficient processing.
 * Class Names: Plant categories are extracted and printed, allowing the model to label predictions accurately.
   
2. ### Model Architecture
 * Convolutional Layers: The model is built using a series of convolutional layers to extract features from images.
 * Pooling Layers: Max pooling layers are used to reduce spatial dimensions, making the model more efficient.
 * Dense Layers: Fully connected layers at the end provide classification predictions.

3. ### Model Compilation and Training
 * Compilation: The model is compiled with categorical cross-entropy loss and an optimizer, typically Adam.
 * Training: The model is trained on the processed dataset for a set number of epochs.
   
4. ### Evaluation and Visualization
 * Performance Evaluation: The model's accuracy and loss are evaluated to assess performance.
 * Visualization: Sample predictions and model accuracy/loss graphs are plotted to observe training effectiveness.
