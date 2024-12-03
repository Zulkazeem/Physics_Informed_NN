# Physics_Informed_NN
Pipe Burst Prediction Using Graph Neural Networks (GNNs)
Overview
This project provides a framework for training, testing, and comparing the performance of standard Graph Neural Networks (GNNs) and GNNs augmented with a physics-based loss function. Specifically, it aims to predict pipe burst events by integrating thermal expansion physics into the model. The code is built using PyTorch, and the data used for training and evaluation is generated with OpenSees.

# Features
* Graph Neural Network (GNN) Implementation: Train and evaluate a standard GNN for pipe burst prediction.
* Physics-Incorporated GNN: Enhance the GNN with a physics loss term that accounts for thermal expansion, integrating domain-specific knowledge into the training process.
* Comparison of Performance: Assess the impact of incorporating physics-based loss on the model's predictive performance.
# Dependencies
* Python 3.x
* PyTorch
* OpenSees (for data generation)
# Installation
To run this project, ensure you have the required packages installed. You can set up your environment using the following command:
pip install torch
Refer to the OpenSees documentation for guidance on installing and using OpenSees.

# Usage
* Data Generation: Use OpenSees to generate synthetic data representing the conditions that lead to pipe bursts.
* Model Training:
* Train a standard GNN model using the generated data.
* Train a physics-informed GNN by incorporating a physics-based loss that models thermal expansion effects.
* Evaluation: Evaluate the trained models on a test set and compare their performance metrics.
* Results Analysis: Analyze the impact of the physics-informed loss on the prediction accuracy and robustness.

# Key Features of the Code
* Flexible GNN Architecture: Easily modify the GNN structure to experiment with different configurations.
* Physics Loss Integration: A custom loss function that includes thermal expansion physics for more accurate modeling.
* Comparison Tools: Built-in metrics and scripts to facilitate performance comparison between models.

# Conclusion
* This code provides an end-to-end solution for comparing GNN-based models for pipe burst prediction, with and without the incorporation of physics-based losses. Leveraging * thermal expansion physics as an additional constraint can improve model performance by introducing domain-specific insights.
