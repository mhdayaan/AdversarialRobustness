# Adversarial Robustness Project

This repository contains code and documentation for the project on adversarial robustness, specifically focusing on solving the inner maximization part. Adversarial robustness is a crucial aspect of machine learning, aiming to make models resistant to adversarial attacks.

## Overview

Adversarial examples are inputs to machine learning models that an attacker has intentionally designed to cause the model to make a mistake. This project addresses the inner maximization problem, which is a key component in creating and defending against adversarial examples.

### Inner Maximization

The inner maximization problem is about finding the worst-case perturbation for a given input that maximizes the model's loss. This is critical for both creating robust models and generating adversarial examples for testing model robustness.

## Getting Started


### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/mhdayaan/AdversarialRobustness
   cd AdversarialRobustness
   ```
   
### Usage

1. Navigate to the `notebooks/` directory and open the main notebook to explore the experiments and code implementations:
   ```bash
   jupyter notebook
   ```

2. Run the notebook cells to execute the code and observe the results.

### Example
Refer to the [Adversarial Examples Tutorial](https://adversarial-ml-tutorial.org/adversarial_examples/) for a comprehensive understanding and additional context.

## Methods Implemented

- **FGSM (Fast Gradient Sign Method)**
- **PGD (Projected Gradient Descent)**
- **CW (Carlini & Wagner) Attack**
- **DeepFool**
- **Boundary Attack**

## Results

The results of the experiments, including the performance of various models against adversarial attacks and the effectiveness of different defense mechanisms can be found in the notebook.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request with your changes.

## Acknowledgments

- The authors of the [Adversarial Examples Tutorial](https://adversarial-ml-tutorial.org/) for their comprehensive guide and resources.
- All contributors and researchers working on improving the robustness of machine learning models.
