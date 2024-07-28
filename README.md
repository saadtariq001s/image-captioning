# Image Captioning with BLIP by Salesforce

This repository contains a Jupyter Notebook for performing image captioning using BLIP by Salesforce. The notebook demonstrates the process of loading pre-trained models, preprocessing images, generating captions, and evaluating the results.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Introduction
Image captioning is the task of generating descriptive captions for images. This notebook showcases how to use pre-trained deep learning models to automatically generate captions for given images. The model combines the power of convolutional neural networks (CNNs) for image feature extraction and recurrent neural networks (RNNs) for generating sequences of words.

## Features
- Loading pre-trained image captioning models
- Preprocessing input images
- Generating captions for images
- Visualizing the generated captions along with the images

## Installation
To run this notebook, you need to have the following dependencies installed:

- Python 3.x
- Jupyter Notebook
- NumPy
- Pandas
- Pillow
- Torch
- torchvision
- Transformers (Hugging Face)
- Matplotlib

You can install the required packages using `pip`:
```bash
pip install numpy pandas pillow torch torchvision transformers matplotlib
```

## Usage
1. Clone the repository:
```bash
git clone https://github.com/saadtariq001s/image-captioning.git
cd image-captioning
```

2. Open the Jupyter Notebook:
```bash
jupyter notebook image_captioning.ipynb
```

3. Follow the steps in the notebook to load the pre-trained model, preprocess your images, and generate captions.

## Results
The notebook provides visualizations of the input images along with their generated captions, helping you to understand the model's performance and the quality of the captions.

## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
