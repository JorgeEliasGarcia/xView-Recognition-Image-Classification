# Image Classification on xView-Recognition using Swin Transformer


This project addresses an **image classification problem** using the **xView-recognition dataset**, a large-scale dataset designed for object and scene recognition in aerial imagery.  
A **Swin Transformer** model is employed as the core architecture, leveraging **transfer learning** to adapt a pretrained vision transformer to the target classification task.

The notebook demonstrates how transformer-based models can be effectively applied to remote sensing and overhead imagery classification problems.

---

## Project Goals
- Solve an image classification task on the **xView-recognition dataset**.
- Apply **transfer learning** with a Swin Transformer model.
- Fine-tune a pretrained vision transformer for domain-specific imagery.
- Analyze training behavior and classification performance.
---

## Dataset: xView-Recognition
The **xView-recognition dataset** is designed for classification tasks in overhead and satellite imagery.

Key characteristics:
- Images captured from an aerial perspective.
- Multiple semantic classes representing different object or scene categories.
- Challenging visual conditions due to scale variation and background complexity.

### Data Preparation
- Loading and organizing images according to class labels.
- Applying image transformations compatible with the Swin Transformer.
- Splitting data into training and validation (and/or test) sets.

---

## Model

### Swin Transformer
- A hierarchical **vision transformer** architecture.
- Uses shifted window attention to model both local and global context.
- Scales efficiently to high-resolution images.
- Well suited for image classification tasks.

### Transfer Learning Setup
- Initialization from pretrained Swin Transformer weights.
- Replacement or adaptation of the classification head.
- Fine-tuning the model on the xView-recognition dataset.
- Selective freezing/unfreezing of layers to balance stability and adaptability.

---

## Training Strategy
- Supervised learning for multi-class image classification.
- Optimization using gradient-based methods.
- Monitoring of training and validation metrics.
- Iterative adjustments to improve convergence and generalization.

---

## Evaluation
Model performance is evaluated through:
- Classification metrics (e.g. accuracy on validation/test data).
- Analysis of learning curves.
- Inspection of correct vs. incorrect predictions.

---

## Technologies Used
- Python
- Tensorflow
- NumPy
- Matplotlib

---

