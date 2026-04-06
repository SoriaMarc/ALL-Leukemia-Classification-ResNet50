# Acute Lymphoblastic Leukemia Classification using ResNet50

Acute Lymphoblastic Leukemia Classifier using ResNet50 and Transfer Learning

This project focuses on the automated classification of leukemic lymphoblasts using Deep Learning. Developed as a first attempt to test the Deep Learning knowledge I aquired over the last months and to serve as a link between **Biomedical Engineering** and **Deep Learning**. This project evaluates the efficacy of Transfer Learning and fine-tuning strategies in the context of medical diagnostics.

## Abstract
The diagnosis of Acute Lymphoblastic Leukemia (ALL) traditionally relies on manual morphological assessment, a process susceptible to subjective thinking and errors caused by fatigue. This study implements a ResNet50-based convolutional neural network (CNN) to classify cells into healthy and leukemic categories. By employing a two-phase training strategy and class-weight balancing, the model achieves a precision of 85.04% and a specificity of 96.00%.

## Methodology
The technical approach is divided into three primary stages:
1. **Preprocessing:** Image normalization and data augmentation to enhance model generalization.
2. **Phase 1 Training:** Feature extraction by freezing the ResNet50 backbone and training the fully connected classification head.
3. **Phase 2 Training:** Global fine-tuning of the entire architecture with a reduced learning rate to optimize weight convergence.

## Performance Analysis
The model's performance was evaluated using standard metrics, including Accuracy (83.28%), Precision (85.04%), and Sensitivity (55.82%). 

### Confusion Matrix
![Confusion Matrix](./confusion_matrix.png)

*Figure 1: Confusion matrix illustrating the classification performance across healthy and ALL-positive samples.*

## Repository Structure
* **Acute_Lymphoblastic_Leukemia_Classifier.pdf**: Comprehensive technical report detailing the clinical background, experimental setup, and results discussion.
* **Acute_Lymphoblastic_Leukemia_Classifier.ipynb**: Documented Jupyter Notebook containing the Python implementation using TensorFlow/Keras.
* **confusion_matrix.png**: Visualization of the model evaluation results.

## Accessing the Documentation
The complete formal analysis is available in the accompanying paper:
[Link to Technical Paper (PDF)](./Acute_Lymphoblastic_Leukemia_Classifier.pdf)

## Author
**Marc Soria Ponseti** Biomedical Engineering | Deep Learning Research
