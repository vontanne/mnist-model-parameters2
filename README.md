# MNIST Model Parameters

This repository provides pre-extracted weights and biases from a model trained on the MNIST dataset, specifically designed for handwritten digit recognition. The parameters are formatted in JavaScript (JS) to facilitate seamless integration into web applications or any JavaScript-based project.

## Overview

The MNIST ("Modified National Institute of Standards and Technology") dataset is a cornerstone in the field of machine learning, providing a large set of handwritten digits for training image processing systems. This repository leverages a Convolutional Neural Network (CNN), trained on the MNIST dataset using PyTorch, to offer a ready-to-use set of model parameters.

## Features

- **Pre-Extracted Parameters**: Includes weights and biases for three layers of the CNN, stored in separate JS files for ease of use.
- **JavaScript Compatibility**: Parameters are provided in a JavaScript-friendly format, enabling straightforward integration with web technologies.
- **High Performance**: The model architecture and training have been optimized to achieve high accuracy on digit recognition tasks.

## Repository Structure

- `/weights`: Contains JS files (`weightsLayer1.js`, `weightsLayer2.js`, `weightsLayer3.js`) with the model's layer-specific weights.
- `/biases`: Includes JS files (`biasesLayer1.js`, `biasesLayer2.js`, `biasesLayer3.js`) with the biases for each corresponding model layer.
- `LICENSE`: The MIT License file detailing the terms under which the repository's contents can be used.

## Getting Started

To integrate the MNIST model parameters into your project, simply include the relevant JS files from the `/weights` and `/biases` directories in your application. Detailed instructions and examples of how to use these parameters within your projects are forthcoming in future updates to this repository.

## Performance Metrics

The model achieves an accuracy of 98.7% on the MNIST test set, making it highly reliable for digit recognition tasks. Additional metrics such as precision, recall, and F1 score are also indicative of the model's robust performance.

## License

This project is released under the MIT License, which provides extensive freedom for reuse within your own projects, subject to the original copyright notice and license agreement. See the [LICENSE](./LICENSE) file for full details.

Stay tuned for further updates and enhancements to this repository!
