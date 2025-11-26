# Developing a Neural Network Classification Model

## AIM
To develop a neural network classification model for the given dataset.

## THEORY
The Iris dataset consists of 150 samples from three species of iris flowers (Iris setosa, Iris versicolor, and Iris virginica). Each sample has four features: sepal length, sepal width, petal length, and petal width. The goal is to build a neural network model that can classify a given iris flower into one of these three species based on the provided features.

## Neural Network Model
Include the neural network model diagram.

## DESIGN STEPS
### STEP 1: 

Load the Iris dataset using a suitable library.

### STEP 2: 

Preprocess the data by handling missing values and normalizing features.

### STEP 3: 

Split the dataset into training and testing sets.

### STEP 4: 

Train a classification model using the training data.

### STEP 5: 

Evaluate the model on the test data and calculate accuracy.

### STEP 6: 

Display the test accuracy, confusion matrix, and classification report.



## PROGRAM

### Name: Saranya V

### Register Number: 212223040188

```python
class IrisClassifier(nn.Module):
    def __init__(self, input_size):
        super(IrisClassifier, self).__init__()
        #Include your code here

    def forward(self, x):
        #Include your code here



# Initialize the Model, Loss Function, and Optimizer

def train_model(model, train_loader, criterion, optimizer, epochs):
    #Include your code here

```

### OUTPUT

## Dateset Information
<img width="817" height="577" alt="image" src="https://github.com/user-attachments/assets/5547b4f1-33a4-47a7-bfd0-57475509f0c4" />


## Confusion Matrix
<img width="574" height="529" alt="image" src="https://github.com/user-attachments/assets/d80b3a0e-1689-48ae-8009-36c005809970" />


## Classification Report
<img width="817" height="577" alt="image" src="https://github.com/user-attachments/assets/1affc019-87fa-471d-935b-d157a237e176" />


### New Sample Data Prediction
<img width="511" height="95" alt="image" src="https://github.com/user-attachments/assets/80ffe85f-adce-45b4-b2da-12addf129220" />


## RESULT
The program is executed successfully.
