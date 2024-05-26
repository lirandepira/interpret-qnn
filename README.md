# interpret-qnn

**On the Interpretability of Quantum Neural Networks**

*Lirandë Pira & Chris Ferrie*

## Overview
This code designs and implements a local model-agnostic interpreter for a quantum neural network (QNN). Consequently, in this simulation we define the so-called *region of indecision* which is evident when interpreting different data samples with a quantum classifier. This implies that there is a region in the classifier, in which corresponding data points will not have an interpretation, due to the random nature of quantum effects.

The repository includes example notebooks that demonstrate how to use the local interpreters on QNNs. These examples cover:
* Training a QNN on a sample dataset.
* Applying local interpretation methods to understand the QNN's predictions.
* Highlighting the region of indecision and visualizing the results of the interpretations.

## Main Steps
The notebook is structured around the following four main steps:

### Data Preparation
Load the Iris dataset to be used for training the QNN.
Preprocess the data to ensure it is in the correct format for the quantum circuits and QNN training process.

### Classical Model Training
Define a classical neural network model for baseline comparison.
Compile, train and test the classical model using the prepared dataset.

### QNN Model Training
Define the QNN architecture, including the quantum circuit and any classical layers.
Compile and train the QNN model using the prepared dataset.
Monitor the training process and evaluate the performance of the model on a validation set.

### Interpretation and Visualization of the Region of Indecision
Apply local interpretation techniques such as LIME to understand how the QNN makes decisions on individual data points.
Visualize the results of these interpretations to gain insights into the model's behavior.
Analyze the effectiveness of the interpretation methods in explaining the QNN's predictions, via the framework of the region of indecision.

## Installation

To get started with this project, you'll need to clone the repository and install the required dependencies.

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Required Python packages (in the ipynb file)

### Clone the Repository

```bash
git clone https://github.com/lirandepira/interpret-qnn.git
cd interpret-qnn
