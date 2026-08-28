# CNN from Scratch

This project implements a convolutional neural network from scratch for a 16-class audio classification task using multi-view spectrogram inputs. The work is contained in the notebook `CNNfromScratch.ipynb` and explores custom CNN building blocks, data augmentation, training, and evaluation without relying on high-level deep learning abstractions.

## Project Overview

The notebook is designed for a music classification challenge where each sample is represented by three grayscale spectrogram images. The model learns to predict one of 16 classes from these complementary time-frequency views.

Key aspects of the project include:

- Custom CNN components implemented manually, including convolution, pooling, activation, and linear layers
- Multi-input processing using three spectrogram views per sample
- Data augmentation for spectrogram images, including masking and gamma adjustment
- Training with PyTorch and evaluation using classification metrics
- Reproducible experiments through fixed random seeds and explicit configuration

## Team

- Amitesh Patra
- Aryan Arora
- Darshana Baruah
- Gaurav Singh Bora
- K Yashwant Rao
- Manas Dhaketa
- Om Mallick

## Repository Contents

- `CNNfromScratch.ipynb` — main notebook with data loading, preprocessing, model implementation, training loop, and evaluation
- `README.md` — project overview and usage instructions

## Requirements

Install the dependencies required by the notebook:

- Python 3.9+
- PyTorch
- OpenCV (`cv2`)
- NumPy
- Pandas
- scikit-learn
- Jupyter Notebook or VS Code notebook support

## Setup

1. Open the workspace in VS Code or Jupyter.
2. Install the required Python packages.
3. Open `CNNfromScratch.ipynb`.
4. Make sure the dataset path matches your environment.

The notebook includes a configuration section with dataset and training settings such as:

- `BASE_PATH`
- `TRAIN_META`
- `SAVE_PATH`
- `BATCH_SIZE`
- `EPOCHS`
- learning rate and device settings

If you are running the project outside a Kaggle environment, update these paths to match your local machine or dataset location.

## How to Run

Open the notebook and run the cells in order:

1. Imports and setup
2. Configuration
3. Dataset definition and data loading
4. Model implementation
5. Training
6. Validation and evaluation

## Notes

This project is intended as an academic deep learning assignment and demonstrates a from-scratch implementation of a CNN pipeline for spectrogram-based classification. It focuses on understanding the underlying mechanics of model building and training rather than using a plug-and-play high-level library workflow.

## License

This project is provided for educational and research use within the assignment context.
