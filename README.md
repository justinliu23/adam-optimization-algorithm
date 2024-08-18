# adam-optimization-algorithm

 ## Table of Contents

1. [Installation Instructions](#installation-instructions)
2. [Usage](#usage)
3. [Features](#features)
4. [Configuration](#configuration)
5. [Dependencies](#dependencies)

## Installation Instructions

To get started with this project, you will need to clone the repository and set up the environment on your local machine.

### Prerequisites

Before you install the dependencies, ensure that you have the following installed on your system:

- Python 3.7 or higher
- pip (Python package installer)

### Installing the Project

1. Clone the repository:

   ```bash
   git clone https://github.com/justinliu23/adam-optimization-algorithm.git
   ```

2. If you are using Jupyter Notebooks, ensure you have Jupyter installed:

   ```bash
   pip install jupyterlab
   ```

3. Start JupyterLab in the project directory:

   ```bash
   jupyter lab
   ```

## Usage

The project is built using Jupyter Notebooks, allowing for an interactive environment to run the optimization algorithms and visualize results.

### Running the Notebooks

To use the optimization methods, open the `Optimization_methods.ipynb` notebook and run each cell sequentially. You will see how different optimization techniques are applied to training a model.

For example:

1. Load the dataset using `load_dataset()`.
2. Initialize the parameters using `initialize_parameters()`.
3. Perform forward and backward propagation using `forward_propagation()` and `backward_propagation()`.
4. Use optimization techniques like Gradient Descent or Momentum to update the parameters.
5. Evaluate the performance using cost functions and prediction accuracy.

## Features

- **Momentum Optimization**: Enhances gradient descent by using an exponentially weighted moving average of gradients.
- **Adam Optimization**: Combines the advantages of RMSprop and Momentum.
- **Cost Function Evaluation**: Functions to compute the cost and evaluate model performance.

## Configuration

This project allows some configurations depending on the use case. You can adjust the learning rate, number of iterations, and batch size, among other hyperparameters, directly within the Jupyter Notebook.

You may also configure the following:

- **Dataset**: Choose different datasets for training the model.
- **Optimization Algorithm**: Select between different optimization algorithms such as Gradient Descent, Momentum, or Adam.
- **Visualization**: Configure the type and style of visualizations.

### Example Configuration

```
learning_rate = 0.01
num_iterations = 1000
batch_size = 64
```

Modify these parameters directly in the notebook cells for personal experimentation.

## Dependencies

The following Python libraries are required to run the project:

- `numpy`: Numerical computing for handling arrays and mathematical operations.
- `matplotlib`: Plotting library for visualizing data and results.
- `scipy`: Provides additional functionality for scientific computing.
- `sklearn`: For dataset loading and preprocessing.
- `opt_utils`: Custom utilities for optimization, including parameter initialization, forward and backward propagation, and cost computation.
