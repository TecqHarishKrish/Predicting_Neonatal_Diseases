# Predicting_Neonatal_Diseases

🔬 Overview
This project aims to develop an AI-powered model for early detection of neonatal diseases using physiological and clinical data. Leveraging deep learning techniques like CNN and CNN-LSTM, the model helps identify health complications in newborns for faster intervention and improved healthcare outcomes.

📁 Project Structure
File	Description
bidmc_final_merged.csv	Final merged dataset containing neonatal patient health records.
CNN Model.ipynb	Jupyter Notebook to build and train a CNN-based classifier.
Model Testing.ipynb	Notebook for evaluating the trained model on new or test data.
cnn_lstm_model.h5	Saved Keras model with CNN-LSTM architecture.
scaler.pkl	Pre-trained scaler object used for data normalization.

⚙️ Technologies Used
Python

Pandas, NumPy – Data preprocessing and manipulation

Matplotlib, Seaborn – Data visualization

Scikit-learn – Data scaling, metrics, and model evaluation

Keras / TensorFlow – Deep learning model implementation

CNN & LSTM – For learning temporal patterns in neonatal health data

Pickle – For saving and loading the scaler

🚀 How to Run
Clone the Repository

bash
Copy
Edit
git clone https://github.com/yourusername/predicting-neonatal-diseases.git
cd predicting-neonatal-diseases
Install Required Packages

bash
Copy
Edit
pip install -r requirements.txt
Run the Notebooks

Open CNN Model.ipynb to train the model.

Open Model Testing.ipynb to evaluate performance.

Dataset

Ensure bidmc_final_merged.csv is available in the working directory for both notebooks.

📊 Model Highlights
📌 Architecture: CNN and CNN-LSTM hybrid

🎯 Goal: Classify critical neonatal conditions using clinical input features

🧪 Output: Disease predictions with accuracy, confusion matrix, and classification report

⚖️ Preprocessing: Data normalized using scaler.pkl

💡 Future Improvements
Expand the dataset with more real-time hospital data

Implement alert systems for high-risk conditions

Deploy as a web dashboard for neonatal ICUs
