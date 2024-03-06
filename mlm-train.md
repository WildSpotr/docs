# Train.py Documentation

## Introduction

`train.py` is a Python script used for training a Convolutional Neural Network (CNN) model for a wildlife spotting application. It loads a dataset, preprocesses it, defines a CNN architecture, compiles and trains the model, and finally saves the trained model for later use.

## Usage

To train the model, run the following command:

```bash
python train.py
```

## Dependencies

- TensorFlow
- scikit-learn

Install dependencies using pip:

```bash
pip install tensorflow scikit-learn
```

## Input

The script expects a dataset consisting of images of wildlife and non-wildlife scenes, along with corresponding labels indicating whether each image contains wildlife or not.

## Output

After training, the script saves the trained model in HDF5 format as `wildlife_spotting_model.h5`.

## Example

```bash
python train.py
```

This command will train the CNN model using the provided dataset and save the trained model as `wildlife_spotting_model.h5`.
