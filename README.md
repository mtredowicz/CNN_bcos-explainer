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

#### References

- Paper Title: [B-cos NN](https://arxiv.org/pdf/2205.10268.pdf)
  - Description: This project is based on the B-cos ResNet-18 model architecture introduced in this paper. The model was adapted and trained for gender classification on the CelebA dataset as described in the paper.


