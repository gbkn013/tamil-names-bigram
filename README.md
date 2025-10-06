# Bigram Tamil Name Generator

This project implements a bigram-based character-level neural network model in PyTorch to generate Tamil names. It uses a custom dataset of Tamil names and trains a model to predict the next character based on a context window.

## Features

- Dataset class for encoding/decoding Tamil names into tokens.
- Bigram embedding and linear layers with hidden layers.
- Model training using SGD optimizer and cross-entropy loss.
- Generates new Tamil names character-by-character.

## Requirements

- Python 3.7+
- PyTorch
- Matplotlib
- tqdm

Install dependencies using:

pip install -r requirements.txt


## Usage

- Load names dataset.
- Train the model with specified epochs and batch size.
- Generate new Tamil names from the trained model.

## Author

Alba G

---