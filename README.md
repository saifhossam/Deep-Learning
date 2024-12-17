# Deep-Learning & Neural Networks
# Deep Learning Architectures: ResNet, Xception, and DenseNet

## Project Overview
This repository explores 3 deep learning architectures for classification tasks:
1. **ResNet**: Implemented from scratch.
2. **Xception**: Transfer learning with fine-tuning.
3. **DenseNet**: Transfer learning with fine-tuning.

The project evaluates and compares the performance of these models on a custom dataset.

---

## Architectures Overview

### ResNet (Residual Networks)
- Introduced in *"Deep Residual Learning for Image Recognition"* by He et al. (2015).
- Key Idea: Skip connections to combat vanishing gradients.
- Implemented from scratch in this project.

### Xception
- Presented in *"Xception: Deep Learning with Depthwise Separable Convolutions"* by Chollet (2017).
- Focuses on depthwise separable convolutions to reduce computation.

### DenseNet (Densely Connected Networks)
- Proposed in *"Densely Connected Convolutional Networks"* by Huang et al. (2017).
- Ensures feature reuse by connecting each layer to all others.

---

## Evaluation Metrics
1. **Accuracy**: Measures the percentage of correctly classified samples.
2. **Confusion Matrix**: Visualized to analyze true/false positives and negatives.
3. **Recall, Precision, F1-Score**: Highlights the model's performance balance.
4. **ROC and AUC**: Visualizes the trade-off between sensitivity and specificity.

---

## References
1. **ResNet**: *He et al., 2015* [Deep Residual Learning for Image Recognition](https://arxiv.org/abs/1512.03385)
2. **Xception**: *Chollet, 2017* [Xception: Deep Learning with Depthwise Separable Convolutions](https://arxiv.org/abs/1610.02357)
3. **DenseNet**: *Huang et al., 2017* [Densely Connected Convolutional Networks](https://arxiv.org/abs/1608.06993)
