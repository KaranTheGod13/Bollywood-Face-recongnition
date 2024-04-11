# Bollywood Celebrity Face Recognition 🎭

This project utilizes Convolutional Neural Networks (CNN) to identify Bollywood celebrities from images. It's an exciting application of machine learning and image processing, trained on a dataset of celebrity faces.

## Table of Contents

- Requirements
- Dataset
- Project Structure
- Usage
- Demo
- Disclaimer

## Requirements

Built with Python 3.7.9, the project requires the following libraries:

- Tensorflow 2.3.1
- Keras 2.3.4
- keras-vggface 0.6
- keras_applications 1.0.8
- MTCNN 0.1.0
- Streamlit
- PIL
- NumPy
- tqdm

## Dataset

The dataset comprises Bollywood celebrity images and is available on Kaggle:

- [Bollywood Celeb Localized Face Dataset](https://www.kaggle.com/datasets/sushilyadav1998/bollywood-celeb-localized-face-dataset/data)

**Important**: After downloading, rename the folder to "Bollywood_celeb_face_localized" and consolidate all images into the `data` folder.

## Project Structure

The project includes:

- `feature_extractor.ipynb`: Prepares data and trains the model, outputting a pickle file with image embeddings.
- `app.py`: A Streamlit app that uses the model to recognize celebrities in uploaded images.

## Usage

To use this project:

1. Clone the repository.
2. Download and organize the dataset into the `data` directory.
3. Execute `feature_extractor.ipynb` to train the model.
4. Start the Streamlit app with `streamlit run app.py`.
5. Upload an image and let the model identify the celebrity.

## Demo

A working video demonstration of the project is available.

## Disclaimer

Ensure you use the same Python and library versions specified to avoid compatibility issues.
