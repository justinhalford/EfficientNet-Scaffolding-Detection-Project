# EfficientNet Scaffolding Detection Project

## Overview

This repository contains the core technology for a scaffolding detection system based on EfficientNet models. It is designed to classify images based on the presence or absence of scaffolding, leveraging deep learning techniques. This technology has the potential to be integrated into future projects involving object detection through dashcams or similar devices.

## Directory Structure

- `cv_dataset/`: This directory is crucial for training and validating the models. It includes two subdirectories:
  - `yes_scaffolding/`: Contains approximately 200 images where scaffolding is present in the scene.
  - `no_scaffolding/`: Contains approximately 200 images with no scaffolding in the scene.

- `models/`: This folder hosts five fine-tuned EfficientNet models for scaffolding detection. Each of these models has achieved an accuracy of 95% or higher on the `cv_dataset` training set.

- `Model_Training_Colab.ipynb`: A Jupyter Notebook that includes code to train additional models. This notebook is compatible with Google Colab and can be used alongside the `cv_dataset` directory to train models capable of detecting scaffolding in various shots.

## Usage

To fine-tune new models, follow these steps:

1. Clone this repository to your local machine or Google Colab environment.
2. Ensure that the `cv_dataset` directory is properly set up with the two subdirectories (`yes_scaffolding` and `no_scaffolding`).
3. Run `Model_Training_Colab.ipynb` to train new models or to retrain the existing ones with additional data. Ensure that the Colab environment is GPU-enabled for efficient training runs.

## Future Integration

The technology developed here is not only limited to scaffolding detection but also opens avenues for detecting other objects that might be captured by dashcams or similar devices. It provides a foundation for developing more advanced object detection systems in various applications.

## Contributing

Contributions to this project are welcome. If you have suggestions or improvements, please open an issue or submit a pull request.

## License

[MIT License](LICENSE.md)

---
For more information, please contact the repository maintainers.
