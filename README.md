# Mobile-Price-Range-Prediction
Objective:
Predict the price range of mobile phones based on features like battery life, RAM, storage, and more.

Steps:

Data Collection:
Collected pre-existing dataset containing mobile phone specifications and their corresponding price ranges.

Data Preprocessing:
Clean Data: Remove invalid entries and duplicates.
Handle Missing Values: Use imputation techniques for any missing features.
Normalize Data: Standardize features like RAM, storage, etc., for uniformity.

Feature Engineering:
Extract or create relevant features such as battery capacity, processor speed, or display size.

Model Building:
Build a Sequential model with dense layers.

Used activation functions like:
ReLU: For hidden layers to introduce non-linearity.
Softmax: For the output layer to predict multiple price ranges.

Model Compilation:
Compile the model with a loss function (e.g., categorical_crossentropy for multi-class classification), optimizer (e.g., Adam), and evaluation metrics (e.g., Accuracy).

Model Training:
Train the model on the dataset while monitoring validation loss and accuracy.

Model Evaluation:
Evaluate on test data and analyze predictions using a Classification Report and Confusion Matrix.
