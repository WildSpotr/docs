# evaluate_model.py Documentation

## Introduction

`evaluate_model.py` is a Python script used for evaluating the performance of a trained CNN model for a wildlife spotting application. It loads the trained model, evaluates it on a test dataset, and calculates the accuracy of the model.

## Usage

To evaluate the trained model, run the following command:

```bash
python evaluate_model.py
```

## Dependencies

- TensorFlow
- scikit-learn

Install dependencies using pip:

```bash
pip install tensorflow scikit-learn
```

## Input

The script expects a test dataset consisting of images and corresponding labels. Ensure that the test dataset is preprocessed similarly to the training dataset.

## Output

The script prints the accuracy of the trained model on the test dataset.

## Example

```bash
python evaluate_model.py
```

This command will load the trained model, evaluate it on the provided test dataset, and print the accuracy of the model.
