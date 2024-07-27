# Number Recognition with MNIST

This repository contains a Jupyter Notebook for training a neural network to recognize handwritten digits using the MNIST dataset. The notebook demonstrates the steps for building, training, and evaluating a simple neural network model using PyTorch.

## Files

- `number-recognize.ipynb`: The main Jupyter Notebook containing the code for loading the dataset, defining the model, training, and evaluating it.

## Getting Started

### Prerequisites

Make sure you have the following libraries installed:

- `torch`
- `torchvision`
- `numpy`
- `matplotlib`
- `jupyter`

You can install the required libraries using pip:

```bash
pip install torch torchvision numpy matplotlib jupyter
```

### Running the Notebook

To run the notebook, open it with Jupyter Notebook:

```bash
jupyter notebook number-recognize.ipynb
```

## Notebook Overview

1. **Importing Libraries**: Import necessary libraries such as PyTorch, torchvision, numpy, and matplotlib.
2. **Loading Data**: Download and load the MNIST dataset using torchvision's datasets module.
3. **Data Preprocessing**: Apply necessary transformations to the dataset.
4. **Defining the Model**: Create a simple neural network using PyTorch's `nn.Module`.
5. **Training the Model**: Define the loss function and optimizer, and train the model for a specified number of epochs.
6. **Evaluating the Model**: Evaluate the model's performance on the test set and print the accuracy.

## Example Output

The notebook will output the training progress and the final accuracy of the model on the test set.

## Contributing

If you want to contribute to this project, feel free to open a pull request or submit issues.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
```
