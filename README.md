# Siamese Network for License Plate Similarity Check

This project demonstrates the implementation of a Siamese Neural Network using PyTorch. The goal of the network is to determine the similarity between pairs of license plate images from different angles. It can be particularly useful in applications such as face recognition, duplicate image detection, or any scenario where measuring the similarity between images is required.

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

Before running the project, ensure you have the following softwares/libraries installed on your system:

- Python 3.8 or higher
- PyTorch
- torchvision
- matplotlib
- PIL (Python Imaging Library)
- numpy

You can install the necessary Python packages and set up the environment using the following command:

```bash
conda create -n simlp python=3.8
conda activate simlp
pip install torch torchvision matplotlib Pillow numpy
```

### Dataset Structure

Your dataset should be organized into subdirectories within a main `dataset_name/` directory. Each subdirectory represents a class, containing images that belong to that class. Here's an example structure:

```
dataset_name/
    class1/
        img1.jpg
        img2.jpg
        ...
    class2/
        img1.jpg
        img2.jpg
        ...
    ...
```

## Contributing

Contributions to improve the project are welcome. Feel free to fork the repository and submit pull requests.
