# 🌸 Flower Classification (Iris Dataset)

This project implements **flower classification** using the famous **Iris dataset**.  
It explores different machine learning approaches and includes a trained **Support Vector Machine (SVM)** model for prediction.

---

## 📂 Project Structure

```
flower-classification/
├── Iris Classification - DataFlair.ipynb   # Reference notebook
├── Iris Classification - DataFlair.py      # Python script
├── main.ipynb                              # Main project notebook
├── iris.data                               # Iris dataset (features)
├── iris.names                              # Dataset description
├── SVM.pickle                              # Pre-trained SVM model
├── main.pdf                                # Project report
├── requirments.txt                         # Dependencies (typo: should be requirements.txt)
└── README.md                               # Project documentation
```

---

## 📊 Dataset

- **Dataset:** [Iris Dataset](https://archive.ics.uci.edu/ml/datasets/iris)  
- **Classes:**  
  - Iris Setosa  
  - Iris Versicolour  
  - Iris Virginica  
- **Features:**  
  - Sepal length  
  - Sepal width  
  - Petal length  
  - Petal width  

---

## ⚙️ Installation

Clone the repository and install dependencies:

```bash
git clone https://github.com/your-username/flower-classification.git
cd flower-classification
pip install -r requirements.txt
```

---

## 🚀 Usage

### 1. Run the Notebook
Open the main Jupyter notebook:
```bash
jupyter notebook main.ipynb
```

### 2. Run the Python Script
You can also execute the script directly:
```bash
python "Iris Classification - DataFlair.py"
```

### 3. Load Pre-trained Model
The `SVM.pickle` file contains a trained model:
```python
import pickle

with open("SVM.pickle", "rb") as f:
    model = pickle.load(f)

sample = [[5.1, 3.5, 1.4, 0.2]]  # Example input
prediction = model.predict(sample)
print("Predicted class:", prediction)
```

---

## 📈 Results

- Model: **Support Vector Machine (SVM)**  
- Accuracy: ~**97%** on test data (Iris dataset)  

---

## 📝 References

- [Iris Dataset - UCI ML Repository](https://archive.ics.uci.edu/ml/datasets/iris)  
- DataFlair tutorial on Iris Classification  

---

## 🤝 Contributing

Feel free to open issues or submit pull requests if you’d like to improve this project.

---

## 📄 License

This project is licensed under the MIT License.
