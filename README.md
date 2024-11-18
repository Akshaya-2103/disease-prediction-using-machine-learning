#Disease Prediction Using Machine Learning
Description
This project leverages Machine Learning techniques to predict diseases based on user input symptoms. By training our system on a comprehensive medical dataset, we provide accurate disease predictions and relevant preventive measures through a user-friendly graphical interface. The aim is to improve accessibility to preliminary healthcare diagnostics using advanced AI solutions.

Model Used
The project employs an Artificial Neural Network (ANN) model, which has been trained on medical data to accurately predict possible diseases based on input symptoms. The model uses feature extraction, data preprocessing, and prediction algorithms to offer accurate and actionable healthcare insights.

How It Works
Data Preprocessing: User inputs are collected, preprocessed, and normalized to ensure compatibility with the model.
Model Training: An ANN model is trained on labeled datasets, learning associations between symptoms and diseases.
Prediction and Recommendations: The trained model takes input symptoms and predicts potential diseases, also providing preventive measures.
User Interface: The project includes a graphical user interface (GUI) built using Python's Tkinter, enabling users to input symptoms easily and view predictions seamlessly.
Steps to Follow
1. Install VS Code and Necessary Extensions
Download and install Visual Studio Code (VS Code).
Install the necessary extensions for running Jupyter Notebook files in VS Code. Recommended extensions include:
Python Extension for VS Code
Jupyter Extension for VS Code
2. Modify Dataset Paths
Change the paths of the dataset files to point to the appropriate locations on your system. Make sure to update the paths in the code to reflect where your dataset files are stored.
3. Run the Disease Prediction.ipynb File
Open and run the Disease Prediction.ipynb Jupyter Notebook file first.
This step will generate the following files:
columns.pkl: Contains serialized column information.
label_encoder.pkl: Contains the trained label encoder for encoding data.
fyp.h5: The trained model file saved in HDF5 format.
scaler.pkl: Contains the scaler object used for feature scaling.
4. Run the GUI.ipynb File
Once the above files have been created, open and run the GUI.ipynb Jupyter Notebook file to start the graphical user interface.
Enter symptoms into the GUI to predict diseases and receive preventive measures.
