MNIST Handwritten Digit Classifier 🖋️🔢

A deep learning model built with TensorFlow/Keras to recognize handwritten digits (0–9) from the MNIST dataset.
This project uses a custom data generator with preprocessing, data augmentation, and training optimizations.

🚀 Features

Custom MNISTDataGenerator class for efficient data loading and preprocessing

Image augmentation using ImageDataGenerator

Multi-layer perceptron (MLP) architecture

Callbacks: Early Stopping, ReduceLROnPlateau, Model Checkpoint

Detailed classification report and accuracy metrics

📂 Dataset

Source: MNIST Dataset

Training and test CSVs are expected in:

/kaggle/input/mnist-hw/train.csv
/kaggle/input/mnist-hw/test.csv

📌 Usage

Run the notebook on Kaggle or locally:

jupyter notebook mnist-handwritten.ipynb

📊 Results

Accuracy: ~XX% on the test set

Confusion matrix and sample predictions included in the notebook.

🖼 Example Predictions
Input Image	Predicted	True Label

	1	1

	7	7
📜 License

This project is licensed under the MIT License.
