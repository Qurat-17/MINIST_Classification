# # MNIST Handwritten Digit Classification using Keras

## Project Overview

This project demonstrates a simple neural network built with Keras and TensorFlow to classify handwritten digits from the MNIST dataset. The goal is to train a model that can accurately identify digits (0-9) from grayscale images.

## Features

-   **Data Loading:** Efficiently loads the MNIST dataset using `keras.datasets`.
-   **Data Preprocessing:** Normalizes image pixel values to a range of 0-1.
-   **Model Architecture:** Implements a feed-forward neural network with `Flatten` and `Dense` layers.
-   **Model Training:** Trains the model on the preprocessed training data with a specified number of epochs and validation split.
-   **Model Evaluation:** Predicts on the test set and calculates accuracy.
-   **Visualization:** Plots training history (loss and accuracy) and visualizes sample predictions.

## Setup and Installation

To run this notebook, you'll need a Python environment with TensorFlow and Keras installed. Google Colab is an ideal environment as it comes pre-installed with most necessary libraries.

1.  **Clone the Repository (if applicable):**
    ```bash
    git clone (https://github.com/Qurat-17/MINIST_Classification
    cd<MINIST_Classification
    ```

2.  **Install Dependencies:**
    If running locally, ensure you have the following packages:
    ```bash
    pip install tensorflow keras matplotlib scikit-learn
    ```
    
    *(In Google Colab, these are typically pre-installed.)*

## Usage

1.  **Open the Notebook:** Load the `.ipynb` file into Google Colab or your preferred Jupyter environment.
2.  **Run All Cells:** Execute all cells sequentially. The notebook will:
    -   Load and preprocess the MNIST data.
    -   Define and compile the neural network model.
    -   Train the model.
    -   Evaluate the model's performance.
    -   Generate plots for training history and sample predictions.

## Results and Visualizations

The trained model achieves a good accuracy on the test set. Below are some visualizations from the training process and a sample prediction.

### Training Loss vs. Validation Loss

This plot shows how the model's loss decreased over epochs for both the training and validation datasets.

![Loss Plot](./loss_plot.png)

### Training Accuracy vs. Validation Accuracy

This plot illustrates the improvement in accuracy over epochs for both training and validation sets.

![Accuracy Plot](./accuracy_plot.png)

### Sample Prediction

Here's an example of a test image along with its true label and the model's predicted label.

![Sample Prediction]([./sample_prediction.png](https://github.com/Qurat-17/MINIST_Classification/blob/31b5eaa2370fdbc3ae4cefb21c39e39389f6c338/prediction_vs%20actual.png))

*(Note: To generate these images for your repository, make sure to save the plots from the executed notebook cells as `loss_plot.png`, `accuracy_plot.png`, and `sample_prediction.png` in your repository's root directory.)*

## Contributing

Contributions are welcome! Please feel free to open issues or submit pull requests.

## License

This project is licensed under the MIT License - see the `LICENSE` file for details. (If you have a `LICENSE` file, otherwise consider adding one.)
