# Loan-Prediction
Loan prediction using CNN involves reshaping tabular data into a format suitable for 1D convolutions. The model learns patterns from applicant features like income, credit score, and loan intent to classify approval status. It offers high accuracy and is useful for automating financial risk assessments.

This project uses a Convolutional Neural Network (CNN) to predict loan approval status based on applicant data. Although CNNs are traditionally used for image data, here they are adapted to work with tabular data by reshaping input features into a format suitable for 1D convolutions.

🧠 CNN Model Architecture
Input Layer: Reshaped numerical and encoded categorical features.
Conv1D Layers: Extract patterns from sequentially arranged features.
Dropout Layers: Prevent overfitting.
Dense Layers: Fully connected layers for final classification.
Output Layer: Binary classification (Approved = 1, Rejected = 0).

📊 Dataset Features
Personal Info: Home ownership, default history.
Loan Info: Intent, grade.
Financial Info: Income, debt, credit score.
Target: Loan approval status.

⚙️ Preprocessing Steps
Handle missing values (mean/mode).
Encode categorical variables numerically.
Standardize numerical features.
Reshape data for CNN compatibility.

🧪 Training & Evaluation
Optimizer: Adam
Loss Function: Binary Crossentropy
Metrics: Accuracy, AUC
Performance: ~94.91% accuracy, ~93.37% AUC 1

✅ Outcome
The CNN model effectively captures complex relationships in applicant data, making it a powerful tool for financial risk assessment and automated loan approval systems.
