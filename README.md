# Image Classification

This project focuses on image classification using deep learning techniques, specifically on the `Imagenette` dataset. It explores various convolutional neural network (CNN) architectures, including basic CNNs, all convolutional networks, and models with added regularization and transfer learning techniques. The project is implemented using [PyTorch Lightning](http://www.pytorchlightning.ai), facilitating the training and evaluation process.

## Getting Started

To get started with this project, clone the repository and install the required dependencies using [Poetry](https://python-poetry.org/).

### Prerequisites

- Python 3.11
- Poetry for dependency management

### Installation

1. Clone the repository:

   ```sh
   git clone https://github.com/your-username/image_classification.git
   ```

2. Change the directory:

   ```sh
    cd image_classification
    ```

3. Install the dependencies using Poetry:

   ```sh
    poetry install
    ```

## Usage

To train and evaluate the models, you can use the Jupyter notebooks provided in the `CNN_notebooks` directory. These notebooks can be ran in [Google Colab](https://colab.research.google.com/) for free CPU and possible GPU time.

### CNN Models

- **Basic CNN**: A simple CNN architecture with convolutional layers followed by fully connected layers.

- **All Convolutional Net**: A model consisting entirely of convolutional layers, as described in the [original paper](https://arxiv.org/abs/1412.6806).

- **Regularization**: Implementation of data augmentation or dropout to improve model performance.

- **Transfer Learning**: Utilizing pre-trained models to enhance the learning process on the `Imagenette` dataset.
