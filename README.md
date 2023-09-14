## CelebA Gender Classification with B-cos ResNet-18
This project demonstrates gender classification on the CelebA dataset using a B-cos ResNet-18 model. 
The goal is to classify images of celebrities as either "Male" or "Female" based on facial features. 
What sets this project apart is that the B-cos ResNet-18 model used for gender classification was custom-built for this dataset.

#### Model Architecture
The core of this project is the B-cos ResNet-18 model, a modified version of the ResNet architecture. 
This model has been built specifically for gender classification on the CelebA dataset, making it a unique and tailored solution.

#### Training
The model is trained using the training split of the CelebA dataset. The training loop includes dynamic learning rate scheduling to improve training efficiency and convergence. 
The model has achieved an impressive training accuracy of 97%. 

#### Evaluation
Model performance is evaluated using a validation dataset, and key metrics such as accuracy and per-class accuracy are recorded. 
The project also includes a test dataset for final evaluation.

#### Prediction and Explanation
You can use the trained model to make predictions on individual images. 
The project provides options to visualize predictions and explanations for model decisions.

#### What's New in B-cos ResNet

The B-cos ResNet is a novel direction for increasing the interpretability of deep neural networks (DNNs). It introduces the B-cos transform, a replacement for the linear transforms in DNNs, which induces alignment pressure on the weights during optimization. This alignment results in highly interpretable linear transforms that align with task-relevant features.

#### Key Features:
- The B-cos transform promotes weight-input alignment during training.
- A sequence of B-cos transforms induces a single linear transform summarizing the entire model's computations.
- Produces high-quality visual explanations for model predictions.
- Performs well under quantitative metrics for interpretability.

#### How it Works:
- The B-cos transform replaces traditional linear units in DNNs.
- It introduces alignment pressure on weights, aligning them with task-relevant input patterns.
- Compatible with binary cross-entropy (BCE) loss for training.

This project adapts and trains the B-cos ResNet model for gender classification on the CelebA dataset, providing accurate results and interpretable model explanations.

#### References
For more details, refer to the [paper](https://arxiv.org/pdf/2205.10268.pdf) on the B-cos transform.








