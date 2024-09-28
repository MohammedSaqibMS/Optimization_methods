# Neural Network Optimization Algorithms 🌐

## Overview 📈
This repository provides an implementation of a 3-layer neural network model that evaluates the performance of three different optimization algorithms: Gradient Descent, Momentum, and Adam. The objective is to compare their effectiveness in terms of accuracy and convergence behavior on a given dataset.

## Table of Contents 📚
- [Model Architecture](#model-architecture)
- [Training Configuration](#training-configuration)
- [Performance Results](#performance-results)
- [Key Observations](#key-observations)
- [Visualizations](#visualizations)
- [Recommendations](#recommendations)
- [Conclusion](#conclusion)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Model Architecture 🏗️
- **Structure**: 
  - Input Layer
  - Two Hidden Layers
  - Output Layer
- **Input Size**: Adapted to match the feature dimensions of the dataset.

## Training Configuration ⚙️
- **Epochs**: 10,000
- **Mini-batch Size**: 64
- **Learning Rate**: 0.0007
- **Cost Tracking**: Costs printed every 1,000 epochs and visualized for analysis.

## Performance Results 📊

| Optimization Method | Final Accuracy | Cost Behavior         |
|---------------------|----------------|------------------------|
| **Gradient Descent**| 79.7%          | Oscillatory behavior    |
| **Momentum**        | 79.7%          | Oscillatory behavior    |
| **Adam**            | 94%            | Smooth convergence      |

## Key Observations 🔍
- Both **Gradient Descent** and **Momentum** achieved similar accuracy (79.7%) but displayed oscillations in cost, indicating potential convergence issues.
- The **Adam** optimizer notably improved performance, achieving a final accuracy of 94% with a smoother cost curve, suggesting stable convergence.

## Visualizations 🖼️
Decision boundaries were plotted for each optimization method, effectively illustrating how well each model separates the classes in the training dataset.

## Recommendations 💡
- Consider experimenting with different layer configurations (e.g., varying the number of neurons in hidden layers) and hyperparameters (e.g., learning rates) to enhance model performance.
- Monitor both training and validation accuracy to prevent overfitting, especially with powerful optimizers like Adam.

## Conclusion 🎉
This structured approach to implementing and comparing optimization methods has yielded valuable insights, particularly highlighting the advantages of the Adam optimizer regarding accuracy and convergence stability. Further experimentation with variations can help refine the model's performance even more!

## License 📜
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments 🙏
- Special thanks to the [Deep Learning Specialization](https://www.deeplearning.ai/courses/deep-learning-specialization/) for providing the foundational knowledge and skills necessary for implementing this project.
- Appreciation to all contributors and libraries used in this project.
