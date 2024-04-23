# FloraSight

FloraSight is an AI-powered plant classification system designed for the Brisbane Flora and Fauna Society (BFFS) to aid in the scalable and accurate identification of native plant species and invasive weeds. The project implements a semi-supervised machine learning model using a Student-Teacher framework to enhance model accuracy and adaptability to new, unlabeled data.

## Technologies Used:
Python
PyTorch
ResNet18
Weights & Biases (wandb)

## Key Features:
Dual model architecture (Teacher and Student models) for enhanced learning from labeled and pseudo-labeled data.
Implementation of data augmentation techniques such as RandomHorizontalFlip, RandomVerticalFlip, and RandomRotation to improve model robustness.
High accuracy in classifying 10 different plant species, split evenly between healthy plants and weeds.

### Challenges Faced:
Managing the semi-supervised learning process to effectively use both labeled and unlabeled data.
Tuning the neural network to prevent overfitting while maintaining high validation accuracy.

### Outcome/Results:
The project achieved impressive classification accuracies, with the teacher model serving as a robust classifier and the student model maintaining high performance with less complexity.
Demonstrated potential for real-world application in aiding conservation efforts through enhanced plant species identification.
