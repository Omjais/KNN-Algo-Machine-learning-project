KNN Classification
This repository contains a Jupyter notebook implementing a K-Nearest Neighbors (KNN) classifier to predict underweight status based on features from a dataset.

📂 Project Structure
Copy
Edit
📦 KNN_Classification/
 ┣ 📄 KNN_Classifiacton(Irisflower).ipynb
 ┗ 📄 README.md
📈 Overview
Dataset: The notebook uses data from
https://www.kaggle.com/datasets/saurabh00007/iriscsv

Features: The first two columns are used as predictors (features).

Target: The last column represents the class label (underweight status).

🚀 Steps Performed
✅ Data loading using Pandas
✅ Feature extraction (x) and target extraction (y)
✅ Model creation with KNeighborsClassifier (n_neighbors=15)
✅ Model training
✅ Prediction on training data
✅ Evaluation using accuracy score and confusion matrix

🛠 Requirements
Install dependencies using:

bash
Copy
Edit
pip install pandas scikit-learn
💻 How to Run
1️⃣ Clone this repository:

bash
Copy
Edit
git clone https://github.com/your-username/your-repo-name.git
2️⃣ Navigate to the project directory:

bash
Copy
Edit
cd your-repo-name
3️⃣ Run the notebook:

bash
Copy
Edit
jupyter notebook KNN_Classifiacton(Irisflower).ipynb
📊 Results
Accuracy: The model computes the accuracy on the training data.

Confusion Matrix: The confusion matrix is generated to evaluate performance.

👉 Note: The current implementation predicts on the same data used for training. For realistic evaluation, consider splitting the dataset (e.g., using train_test_split).

✍️ Author
Om Jaiswal
https://github.com/Omjais
