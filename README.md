# In-Network Fusion for High Interference Signal Detection within CBRS Band
This codebase facilitates the fusion of multiple signal modalities, enabling enhanced detection and classification in environments with interference from various signal sources.
## Introduction
This repository provides a robust framework for signal detection in environments with multiple signal sources, such as radar pulses and 5G signals. The code leverages an in-network fusion approach to combine data from different modalities, improving detection performance even in high-interference scenarios. Designed to be adaptable, this framework supports various signal types and detection models, making it suitable for applications in shared spectrum environments. With the ability to handle complex interference, the code facilitates reliable signal detection, classification, and coexistence of different technologies. This code can be easily extended to work with different signal detection tasks and interference conditions.
## Setup and Prerequisites
## Prerequisites

Before running the signal detection code, make sure you have the following installed:

- **Python 3.8 or higher**  
  Download from the official [Python website](https://www.python.org/downloads/).

- **Jupyter Kernel**  
  Install Jupyter by following the instructions on the [Jupyter website](https://jupyter.org/install).

- **TensorFlow 2.6 or higher**  
  Install TensorFlow via pip by following the instructions on the [TensorFlow website](https://www.tensorflow.org/install).

Additionally, make sure to install any other dependencies as mentioned in the project.
## Getting Started

To get started with the project, you have two options for using the model:

#### Option 1: Train the Model from Scratch
1. **Prepare your data**: Make sure your data is properly preprocessed and formatted.
2. **Train the Model**: Train the individual model from scratch using your data. This will involve setting up the architecture and running the training process.
3. **Save the Model**: Once the training is complete, save the trained model to a directory for future use.
4. **Load the Model**: When you're ready to use the model, load it from the saved directory for further evaluation or inference.

#### Option 2: Use a Pretrained Model and Fine-Tune It
1. **Access the Pretrained Models**: Navigate to the "Pretrained Models" folder in the project directory, where you will find models that have already been trained on a general dataset.
2. **Fine-Tune the Model**: Adapt the pretrained model to your specific dataset by fine-tuning it. This will help the model better fit the characteristics of your data.
3. **Run the Script**: Once you’ve fine-tuned the model, you can run the script to evaluate or make predictions using the Jupyter notebook (`.ipynb` file).

### Running the Script
- After completing either of the two options above, you can run the Python script using the provided Jupyter notebook. This allows you to interact with the model, make predictions, or evaluate its performance on new data.

By following these steps, you can either build a model from scratch or take advantage of pretrained models for faster results, depending on your specific needs.


## Cite

If you find this fusion approach useful in your research, please cite our work:

```Shafi Ullah Khan, Michel Kulhandjian, and Debashri Roy, “In-Network Fusion for High Interference Signal Detection within CBRS Band,” In IEEE International Conference on Computer Communications (INFOCOM), May 2025. [Accepted]```
