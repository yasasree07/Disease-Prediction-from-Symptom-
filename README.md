🧠 Disease Prediction from Symptoms
This project is a machine learning-based system that predicts the most likely disease based on user-input symptoms. It uses classification algorithms to analyze symptom patterns and provide a probable diagnosis.

🚀 Features
Predicts disease based on multiple symptoms.

Trained on a structured dataset containing symptoms and diseases.

Easy-to-use command-line interface.

Uses machine learning classifiers like Decision Tree, Random Forest, etc.

🧰 Requirements
Make sure the following are installed:

bash
Copy
Edit
Python 3.x
pandas
numpy
scikit-learn
You can install dependencies using:

bash
Copy
Edit
pip install -r requirements.txt
📁 Project Structure
csharp
Copy
Edit
Disease-Prediction-from-Symptoms/
│
├── disease_prediction.ipynb       # Main Jupyter Notebook
├── Training.csv                   # Dataset for training
├── Testing.csv                    # Dataset for testing
├── disease_prediction.py          # Script version of the model
├── README.md                      # Project description

▶️ How to Run
🧪 Using the Jupyter Notebook:

jupyter notebook disease_prediction.ipynb
Then follow the steps in the notebook to test predictions.

⚙️ Using the Python Script:

python disease_prediction.py
You’ll be prompted to enter symptoms in the terminal.

✅ Example Output

Enter symptoms (comma-separated): headache, nausea, vomiting

Predicted Disease: Migraine
📌 Notes
Make sure symptoms match the dataset (e.g., use lowercase, exact spelling).

The system is only for educational/demonstration purposes and not a replacement for professional medical advice.

